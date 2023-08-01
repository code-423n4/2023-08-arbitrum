# Arbitrum Security Council Elections Contest Details
- Total Prize Pool: $90,500 USDC 
  - HM awards: $61,875 USDC 
  - Analysis awards: $3,750 USDC 
  - QA awards: $1,875 USDC 
  - Bot Race awards: $5,625 USDC 
  - Gas awards: $1,875 USDC
  - Judge awards: $9,000 USDC 
  - Lookout awards: $6,000 USDC
  - Scout awards: $500 USDC 
- Join [C4 Discord](https://discord.gg/code4rena) to register
- Submit findings [using the C4 form](https://code4rena.com/contests/2023-08-arbitrum-foundation/submit)
- [Read our guidelines for more details](https://docs.code4rena.com/roles/wardens)
- Starts August 3, 2023 20:00 UTC
- Ends August 10, 2023 20:00 UTC
  
**IMPORTANT NOTE:** Prior to receiving payment from this audit you MUST become a [Certified Warden](https://code4rena.com/certified-contributor-application/)  (successfully complete KYC). This also applies to bot crews.  You do not have to complete this process before competing or submitting bugs. You must have started this process within 48 hours after the audit ends, i.e. **by August 12, 2023 at 20:00 UTC in order to receive payment.**

For the Gas award pool the only concern is for gas usage related to voting, this does not include executing the proposal and the rest of its lifecycle since these are one-off operations.

## Automated Findings / Publicly Known Issues

Automated findings output for the audit can be found [here](bot-report.md) within 24 hours of audit opening.

*Note for C4 wardens: Anything included in the automated findings output is considered a publicly known issue and is ineligible for awards.*

# Overview

Arbitrum is a suite of scaling solutions providing environments with high-throughput, low-cost smart contracts, backed by industry-leading proving technology rooted in Ethereum.
The [Arbitrum DAO](https://docs.arbitrum.foundation/concepts/arbitrum-dao) governs the Arbitrum One and Nova chains.
The [Security Council](https://docs.arbitrum.foundation/concepts/security-council) is responsible for making emergency response decisions when the community needs to address a critical security risks to the protocol. They are a 12 member council from independent organisations that hold the ability to conduct emergency actions to the Arbitrum chains. The 12 member council is separated into 2 cohorts which are elected alternatively every 6 months.

The codebase includes the subsystem of Arbitrum Governance that allows these cohorts to be managed and elected through an on-chain suite of smart contracts written in Solidity.

A summary of the statement of project can be found in the [Arbitrum Governance forums](https://forum.arbitrum.foundation/t/proposal-security-council-elections-proposed-implementation-spec/15425).

As explained in the post, the [Arbitrum Constitution](https://docs.arbitrum.foundation/dao-constitution) already specifies the behaviour of the elections, it should be considered a bug if the implementation deviates from the Constitution in a way not documented in the forum statement above.

The elections share the same timelocks as the [core governance flow](https://github.com/ArbitrumFoundation/governance/blob/main/docs/overview.md). 

They also use the [Governance Action Contracts](https://github.com/ArbitrumFoundation/governance/blob/main/src/gov-action-contracts/README.md) both in activation and in the ongoing flow.

Throughout the codebase, language of “contenders”, “nominees” and “members” is used:

- “contender” - someone who can receive votes in the nominee selection stage but who has received less than 0.2% of votable tokens
- “nominee” - someone who has received 0.2% of votable tokens in the nominee selection stage
    - “compliant” / “noncompliant” indicates whether they’ve been excluded by the nominee vetter
- “member” - a member of the security council

In-depth documentation on the system can also be found in [Security Council Manager as a source of truth
](https://github.com/ArbitrumFoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/docs/security-council-manager.md), [Security Council Election and Membership Management
](https://github.com/ArbitrumFoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/docs/security-council-mgmt.md) and [Nominee vetting guidelines](https://github.com/ArbitrumFoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/docs/security-council-nominee-vetting.md).

A [technical deep dive session](https://twitter.com/i/spaces/1yoKMZwjVODGQ) will be hosted on Twitter Spaces on Friday August 4th.

You can also join [Arbitrum's discord server](https://discord.gg/arbitrum) to learn more and join the on-going discussions.

## Areas of concern

- Ensure that the implementation does not deviate from the constitution in any way that’s not documented in the forum post
- Ensure that existing Governance security is not affected in any way by the new elections
- Ensure that the elections contracts do not allow any new parties to gain governance power (power to call the upgrade executors in arbitrary ways) in the system - other than the security council and the dao which already have governance power
- Ensure the power to upgrade any of the election contracts is held only by the DAO and the Security councils
- Ensure that elections can be created and progressed by any party, inline with the correct schedule
- Ensure only the DAO or Security Council can change the election process in any way
- Ensure that votes are not double counted in the governors, and conform to the weighting schedule specified in the Constitution


## Known risks

- It’s possible for Core Governance and the elections to schedule the same operation in timelocks, and therefore block each other. However the DAO would need to do this on purpose, and against their Constitution. If the DAO is willing to make proposals against their Constitution then they can arbitrarily change all the contracts, so a clashing operation is not considered an issue.
- The Security Council can create updates in the SecurityCouncilManager that could cause an election execution to fail. They are expected to take care when making these kinds of updates not to cause that issue. Since the Security Council can technically change all the contracts, a Council that is causing disruption can already do so in much wider ways.
- An additional method “rotateMember” is provided that does the same as “replaceMember”. Although this method has the same functionality as “replaceMember” it has a different semantic meaning as it should be used to change the key of an existing member, rather than replace a member of with a different one.


# Scope

*List all files in scope in the table below (along with hyperlinks) -- and feel free to add notes here to emphasize areas of focus.*

*For line of code counts, we recommend using [cloc](https://github.com/AlDanial/cloc).* 

All referenced code is frozen at commit hash [c18de53820c505fc459f766c1b224810eaeaabc5](https://github.com/arbitrumfoundation/governance/tree/c18de53820c505fc459f766c1b224810eaeaabc5).

| Contract | SLOC | Purpose |  
| ----------- | ----------- | ----------- | 
| [SecurityCouncilManager.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol) | 326 |  The source of true for the current state of all security councils. Initiates updates across chains, looks to the UpgradeExecRouteBuilder to build the payload for it. |
| [SecurityCouncilNomineeElectionGovernor.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol) | 298 |  Delegates vote to select a short list of nominees from a long list of contenders. Introduces a vetting period to allow a trusted party to exclude/include contenders |
| [SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol) | 110 | counting module for the nominee governor |
| [SecurityCouncilNomineeElectionGovernorTiming.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol) | 67 | Timing functionality for the nominee election governor |
| [SecurityCouncilMemberElectionGovernor.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol) | 153 | Delegates vote for 6 candidates from the short list |
| [SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol) | 186 | counting module for the member election governor |
| [SecurityCouncilMemberRemovalGovernor.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol) | 193 | Delegates vote to remove a candidate from the existing security council |
| [ArbitrumGovernorVotesQuorumFractionUpgradeable.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol) | 27 | Base functionality for counting only “votable” tokens |
| [ElectionGovernor.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol) | 34 | Shared functionality for election governors |
| [UpgradeExecRouteBuilder.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol) | 131 | Builds routes to target the upgrade executors on each chain |
| [SecurityCouncilMemberSyncAction.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol) | 95 | Action contract to update the members of the gnosis safe |
| [SecurityCouncilMgmtUtils.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol) | 30 | Shared array utils |
| [Common.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/Common.sol) | 13 | Shared common data structures |
| [L2SecurityCouncilMgmtFactory.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol) | 197 | Deploys election contracts |
| [GovernanceChainSCMgmtActivationAction.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol) | 118 | Activates elections on Arbitrum One |
| [L1SCMgmtActivationAction.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol) | 52 | Activates elections on L1 Ethereum |
| [NonGovernanceChainSCMgmtActivationAction.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol) | 37 | Activates elections on Arbitrum Nova |
| [SecurityCouncilMgmtUpgradeLib.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol) | 79 | Shared utilities |
| [KeyValueStore.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol) | 19 | Stores values against a key (useful for external storage to avoid Actions from using state) |
| [ActionExecutionRecord.sol](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol) | 19 | Stores a record that the action executed. |


## Out of scope

There are multiple other contracts in the repo that correspond to the rest of Arbitrum's governance system. Those contracts are out of scope for the competition but are eligible for the [Immunify bug bounty program](https://immunefi.com/bounty/arbitrum/).


## Scoping Details 
```
- If you have a public code repo, please share it here: https://github.com/ArbitrumFoundation/governance
- How many contracts are in scope?: 20
- Total SLoC for these contracts?: 2184 
- How many external imports are there?: 16
- How many separate interfaces and struct definitions are there for the contracts within scope?: 13 
- Does most of your code generally use composition or inheritance?: Inheritance
- How many external calls?: 8
- What is the overall line coverage percentage provided by your tests?: 94%
- Is this an upgrade of an existing system?: No
- Check all that apply (e.g. timelock, NFT, AMM, ERC20, rollups, etc.): Timelock function, Use rollups, Multi-Chain, ERC-20 Token
- Is there a need to understand a separate part of the codebase / get context in order to audit this part of the protocol?: Yes. 
- Please describe required context: They must understand the governance lifecycle flow of Arbitrum. They dont need in-depth knowledge, but a high level understanding.  
- Does it use an oracle?:  No
- Describe any novel or unique curve logic or mathematical models your code uses: None
- Is this either a fork of or an alternate implementation of another project?:  No 
- Does it use a side-chain?: No
- Describe any specific areas you would like addressed: Read "Areas of concern" above
```

# Tests

To run the Security Council Election tests

```bash
git clone https://github.com/code-423n4/2023-08-arbitrum
git submodule update --init --recursive
cd governance
foundryup
make install
make build
make sc-election-test
```

To run code coverage

```bash
make coverage
```

To run gas benchmarks

```bash
make gas
```
