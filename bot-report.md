**Note:** There is a section for disputed findings below the usual findings sections

## Summary

### Medium Risk Issues

| |Issue|Instances|
|-|:-|:-:|
| [[M&#x2011;01](#m01-the-owner-is-a-single-point-of-failure-and-a-centralization-risk)] | The `owner` is a single point of failure and a centralization risk | 5 | 

Total: 5 instances over 1 issues

### Low Risk Issues

| |Issue|Instances|
|-|:-|:-:|
| [[L&#x2011;01](#l01-unsafe-downcast)] | Unsafe downcast | 1 | 
| [[L&#x2011;02](#l02-loss-of-precision)] | Loss of precision | 2 | 
| [[L&#x2011;03](#l03-upgradeable-contract-not-initialized)] | Upgradeable contract not initialized | 6 | 
| [[L&#x2011;04](#l04-use-ownable2step-rather-than-ownable)] | Use `Ownable2Step` rather than `Ownable` | 4 | 
| [[L&#x2011;05](#l05-upgradeable-contract-is-missing-a-__gap50-storage-variable-to-allow-for-new-storage-variables-in-later-versions)] | Upgradeable contract is missing a `__gap[50]` storage variable to allow for new storage variables in later versions | 4 | 
| [[L&#x2011;06](#l06-external-calls-in-an-un-bounded-for-loop-may-result-in-a-dos)] | External calls in an un-bounded `for-`loop may result in a DOS | 3 | 
| [[L&#x2011;07](#l07-initialization-can-be-front-run)] | Initialization can be front-run | 1 | 
| [[L&#x2011;08](#l08-missing-checks-for-address0x0-when-updating-address-state-variables)] | Missing checks for `address(0x0)` when updating `address` state variables | 3 | 
| [[L&#x2011;09](#l09-missing-checks-for-address0x0-in-the-constructor)] | Missing checks for `address(0x0)` in the constructor | 14 | 
| [[L&#x2011;10](#l10-upgradeable-contract-uses-non-upgradeable-version-of-the-openzeppelin-librariescontracts)] | Upgradeable contract uses non-upgradeable version of the OpenZeppelin libraries/contracts | 1 | 
| [[L&#x2011;11](#l11-use-of-a-single-step-ownership-transfer)] | Use of a single-step ownership transfer | 3 | 
| [[L&#x2011;12](#l12-consider-implementing-two-step-procedure-for-updating-protocol-addresses)] | Consider implementing two-step procedure for updating protocol addresses | 2 | 

Total: 44 instances over 12 issues

### Non-critical Issues

| |Issue|Instances|
|-|:-|:-:|
| [[N&#x2011;01](#n01-public-functions-not-called-by-the-contract-should-be-declared-external-instead)] | `public` functions not called by the contract should be declared `external` instead | 34 | 
| [[N&#x2011;02](#n02-constants-should-be-defined-rather-than-using-magic-numbers)] | `constant`s should be defined rather than using magic numbers | 12 | 
| [[N&#x2011;03](#n03-event-is-not-properly-indexed)] | Event is not properly `indexed` | 4 | 
| [[N&#x2011;04](#n04-common-functions-should-be-refactored-to-a-common-base-contract)] | Common functions should be refactored to a common base contract | 9 | 
| [[N&#x2011;05](#n05-vulnerable-versions-of-packages-are-being-used)] | Vulnerable versions of packages are being used | 1 | 
| [[N&#x2011;06](#n06-import-declarations-should-import-specific-identifiers-rather-than-the-whole-file)] | Import declarations should import specific identifiers, rather than the whole file | 82 | 
| [[N&#x2011;07](#n07-large-multiples-of-ten-should-use-scientific-notation-eg-1e6-rather-than-decimal-literals-eg-1000000-for-readability)] | Large multiples of ten should use scientific notation (e.g. `1e6`) rather than decimal literals (e.g. `1000000`), for readability | 2 | 
| [[N&#x2011;08](#n08-events-that-mark-critical-parameter-changes-should-contain-both-the-old-and-the-new-value)] | Events that mark critical parameter changes should contain both the old and the new value | 1 | 
| [[N&#x2011;09](#n09-constant-redefined-elsewhere)] | Constant redefined elsewhere | 5 | 
| [[N&#x2011;10](#n10-use-inheritdoc-rather-than-using-a-non-standard-annotation)] | Use `@inheritdoc` rather than using a non-standard annotation | 3 | 
| [[N&#x2011;11](#n11-lines-are-too-long)] | Lines are too long | 28 | 
| [[N&#x2011;12](#n12-long-functions-should-be-refactored-into-multiple-smaller-functions)] | Long functions should be refactored into multiple, smaller, functions | 4 | 
| [[N&#x2011;13](#n13-variable-names-that-consist-of-all-capital-letters-should-be-reserved-for-constantimmutable-variables)] | Variable names that consist of all capital letters should be reserved for `constant`/`immutable` variables | 6 | 
| [[N&#x2011;14](#n14-typos)] | Typos | 13 | 
| [[N&#x2011;15](#n15-file-is-missing-natspec)] | File is missing NatSpec | 5 | 
| [[N&#x2011;16](#n16-natspec-param-is-missing)] | NatSpec `@param` is missing | 116 | 
| [[N&#x2011;17](#n17-natspec-return-argument-is-missing)] | NatSpec `@return` argument is missing | 59 | 
| [[N&#x2011;18](#n18-function-ordering-does-not-follow-the-solidity-style-guide)] | Function ordering does not follow the Solidity style guide | 26 | 
| [[N&#x2011;19](#n19-contract-does-not-follow-the-solidity-style-guides-suggested-layout-ordering)] | Contract does not follow the Solidity style guide's suggested layout ordering | 10 | 
| [[N&#x2011;20](#n20-interfaces-should-be-indicated-with-an-i-prefix-in-the-contract-name)] | Interfaces should be indicated with an `I` prefix in the contract name | 1 | 
| [[N&#x2011;21](#n21-control-structures-do-not-follow-the-solidity-style-guide)] | Control structures do not follow the Solidity Style Guide | 32 | 
| [[N&#x2011;22](#n22-top-level-declarations-should-be-separated-by-at-least-two-lines)] | Top-level declarations should be separated by at least two lines | 26 | 
| [[N&#x2011;23](#n23-consider-using-delete-rather-than-assigning-zerofalse-to-clear-values)] | Consider using `delete` rather than assigning zero/false to clear values | 1 | 
| [[N&#x2011;24](#n24-contracts-should-have-full-test-coverage)] | Contracts should have full test coverage | 1 | 
| [[N&#x2011;25](#n25-large-or-complicated-code-bases-should-implement-invariant-tests)] | Large or complicated code bases should implement invariant tests | 1 | 
| [[N&#x2011;26](#n26-enable-ir-based-code-generation)] | Enable IR-based code generation | 1 | 
| [[N&#x2011;27](#n27-custom-errors-should-be-used-rather-than-revertrequire)] | Custom errors should be used rather than `revert()`/`require()` | 22 | 
| [[N&#x2011;28](#n28-array-indicies-should-be-referenced-via-enums-rather-than-via-numeric-literals)] | Array indicies should be referenced via `enum`s rather than via numeric literals | 13 | 
| [[N&#x2011;29](#n29-variable-names-for-constants-dont-follow-the-solidity-style-guide)] | Variable names for constants don't follow the Solidity style guide | 1 | 
| [[N&#x2011;30](#n30-contracts-containing-only-utility-functions-should-be-made-into-libraries)] | Contracts containing only utility functions should be made into libraries | 1 | 
| [[N&#x2011;31](#n31-events-are-missing-sender-information)] | Events are missing sender information | 19 | 
| [[N&#x2011;32](#n32-internal-functions-not-called-by-the-contract-should-be-removed)] | `internal` functions not called by the contract should be removed | 9 | 
| [[N&#x2011;33](#n33-addresss-shouldnt-be-hard-coded)] | `address`s shouldn't be hard-coded | 4 | 
| [[N&#x2011;34](#n34-variables-need-not-be-initialized-to-zero)] | Variables need not be initialized to zero | 59 | 
| [[N&#x2011;35](#n35-consider-using-named-mappings)] | Consider using named mappings | 13 | 
| [[N&#x2011;36](#n36-consider-adding-a-blockdeny-list)] | Consider adding a block/deny-list | 7 | 
| [[N&#x2011;37](#n37-non-externalpublic-variable-and-function-names-should-begin-with-an-underscore)] | Non-`external`/`public` variable and function names should begin with an underscore | 1 | 
| [[N&#x2011;38](#n38-non-externalpublic-variable-names-should-begin-with-an-underscore)] | Non-`external`/`public` variable names should begin with an underscore | 2 | 
| [[N&#x2011;39](#n39-use-of-override-is-unnecessary)] | Use of `override` is unnecessary | 40 | 
| [[N&#x2011;40](#n40-array-is-pushed-but-not-poped)] | Array is `push()`ed but not `pop()`ed | 3 | 
| [[N&#x2011;41](#n41-redundant-inheritance-specifier)] | Redundant inheritance specifier | 8 | 
| [[N&#x2011;42](#n42-use-abiencodecall-instead-of-abiencodewithsignatureabiencodewithselector)] | Use `abi.encodeCall()` instead of `abi.encodeWithSignature()`/`abi.encodeWithSelector()` | 7 | 
| [[N&#x2011;43](#n43-consider-using-descriptive-constants-when-passing-zero-as-a-function-argument)] | Consider using descriptive `constant`s when passing zero as a function argument | 9 | 
| [[N&#x2011;44](#n44-constants-in-comparisons-should-appear-on-the-left-side)] | Constants in comparisons should appear on the left side | 14 | 
| [[N&#x2011;45](#n45-expressions-for-constant-values-should-use-immutable-rather-than-constant)] | Expressions for constant values should use `immutable` rather than `constant` | 9 | 
| [[N&#x2011;46](#n46-consider-disabling-renounceownership)] | Consider disabling `renounceOwnership()` | 1 | 
| [[N&#x2011;47](#n47-custom-error-has-no-error-details)] | Custom error has no error details | 8 | 
| [[N&#x2011;48](#n48-consider-bounding-input-array-length)] | Consider bounding input array length | 9 | 
| [[N&#x2011;49](#n49-interfaces-should-be-defined-in-separate-files-from-their-usage)] | Interfaces should be defined in separate files from their usage | 1 | 
| [[N&#x2011;50](#n50-contract-declarations-should-have-natspec-descriptions)] | Contract declarations should have NatSpec descriptions | 6 | 
| [[N&#x2011;51](#n51-contract-declarations-should-have-natspec-title-annotations)] | Contract declarations should have NatSpec `@title` annotations | 20 | 
| [[N&#x2011;52](#n52-contract-declarations-should-have-natspec-title-annotations)] | Contract declarations should have NatSpec `@title` annotations | 11 | 
| [[N&#x2011;53](#n53-function-declarations-should-have-natspec-descriptions)] | Function declarations should have NatSpec descriptions | 18 | 
| [[N&#x2011;54](#n54-setters-should-prevent-re-setting-of-the-same-value)] | Setters should prevent re-setting of the same value | 4 | 
| [[N&#x2011;55](#n55-named-imports-of-parent-contracts-are-missing)] | Named imports of parent contracts are missing | 40 | 
| [[N&#x2011;56](#n56-polymorphic-functions-make-security-audits-more-time-consuming-and-error-prone)] | Polymorphic functions make security audits more time-consuming and error-prone | 1 | 
| [[N&#x2011;57](#n57-use-the-latest-solidity-prior-to-0820-if-on-l2s-for-deployment)] | Use the latest solidity (prior to 0.8.20 if on L2s) for deployment | 17 | 
| [[N&#x2011;58](#n58-public-variable-declarations-should-have-natspec-descriptions)] | Public variable declarations should have NatSpec descriptions | 27 | 

Total: 887 instances over 58 issues

### Gas Optimizations

| |Issue|Instances|Total Gas Saved|
|-|:-|:-:|:-:|
| [[G&#x2011;01](#g01-structs-can-be-packed-into-fewer-storage-slots)] | Structs can be packed into fewer storage slots | 1 |  2000 |
| [[G&#x2011;02](#g02-structs-can-be-packed-into-fewer-storage-slots-by-truncating-timestamp-bytes)] | Structs can be packed into fewer storage slots by truncating timestamp bytes | 2 |  4000 |
| [[G&#x2011;03](#g03-using-storage-instead-of-memory-for-structsarrays-saves-gas)] | Using `storage` instead of `memory` for structs/arrays saves gas | 1 |  4200 |
| [[G&#x2011;04](#g04-state-variables-should-be-cached-in-stack-variables-rather-than-re-reading-them-from-storage)] | State variables should be cached in stack variables rather than re-reading them from storage | 34 |  3298 |
| [[G&#x2011;05](#g05-multiple-accesses-of-a-mappingarray-should-use-a-local-variable-cache)] | Multiple accesses of a mapping/array should use a local variable cache | 1 |  42 |
| [[G&#x2011;06](#g06-internal-functions-only-called-once-can-be-inlined-to-save-gas)] | `internal` functions only called once can be inlined to save gas | 6 |  120 |
| [[G&#x2011;07](#g07-arraylength-should-not-be-looked-up-in-every-loop-of-a-for-looparray)] | `<array>.length` should not be looked up in every loop of a `for`-loop | 25 |  75 |
| [[G&#x2011;08](#g08-ii-should-be-uncheckediuncheckedi-when-it-is-not-possible-for-them-to-overflow-as-is-the-case-when-used-in-for--and-while-loops)] | `++i`/`i++` should be `unchecked{++i}`/`unchecked{i++}` when it is not possible for them to overflow, as is the case when used in `for`- and `while`-loops | 28 |  1680 |
| [[G&#x2011;09](#g09-requirerevert-strings-longer-than-32-bytes-cost-extra-gas)] | `require()`/`revert()` strings longer than 32 bytes cost extra gas | 22 |  66 |
| [[G&#x2011;10](#g10-optimize-names-to-save-gas)] | Optimize names to save gas | 11 |  242 |
| [[G&#x2011;11](#g11-it-costs-more-gas-to-initialize-non-constantnon-immutable-state-variables-to-zero-than-to-let-the-default-of-zero-be-applied)] | It costs more gas to initialize non-`constant`/non-`immutable` state variables to zero than to let the default of zero be applied | 1 |  - |
| [[G&#x2011;12](#g12-i-costs-less-gas-than-i-especially-when-its-used-in-for-loops---ii---too)] | `++i` costs less gas than `i++`, especially when it's used in `for`-loops (`--i`/`i--` too) | 32 |  160 |
| [[G&#x2011;13](#g13-using-private-rather-than-public-for-constants-saves-gas)] | Using `private` rather than `public` for constants, saves gas | 16 |  - |
| [[G&#x2011;14](#g14-stack-variable-used-as-a-cheaper-cache-for-a-state-variable-is-only-used-once)] | Stack variable used as a cheaper cache for a state variable is only used once | 1 |  3 |
| [[G&#x2011;15](#g15-use-custom-errors-rather-than-revertrequire-strings-to-save-gas)] | Use custom errors rather than `revert()`/`require()` strings to save gas | 22 |  - |
| [[G&#x2011;16](#g16-functions-guaranteed-to-revert-when-called-by-normal-users-can-be-marked-payable)] | Functions guaranteed to revert when called by normal users can be marked `payable` | 22 |  462 |
| [[G&#x2011;17](#g17-constructors-can-be-marked-payable)] | Constructors can be marked `payable` | 10 |  210 |
| [[G&#x2011;18](#g18-not-using-the-named-return-variables-anywhere-in-the-function-is-confusing)] | Not using the named return variables anywhere in the function is confusing | 1 |  - |
| [[G&#x2011;19](#g19-use-assembly-to-emit-events-in-order-to-save-gas)] | Use assembly to emit events, in order to save gas | 13 |  494 |
| [[G&#x2011;20](#g20-use-assembly-for-small-keccak256-hashes-in-order-to-save-gas)] | Use assembly for small keccak256 hashes, in order to save gas | 3 |  240 |
| [[G&#x2011;21](#g21-events-should-be-emitted-outside-of-loops)] | Events should be emitted outside of loops | 1 |  375 |
| [[G&#x2011;22](#g22-internal-functions-not-called-by-the-contract-should-be-removed-to-save-deployment-gas)] | `internal` functions not called by the contract should be removed to save deployment gas | 9 |  - |
| [[G&#x2011;23](#g23-reduce-gas-usage-by-moving-to-solidity-0819-or-later)] | Reduce gas usage by moving to Solidity 0.8.19 or later | 20 |  - |
| [[G&#x2011;24](#g24-add-unchecked--for-subtractions-where-the-operands-cannot-underflow-because-of-a-previous-require-or-if-statement)] | Add `unchecked {}` for subtractions where the operands cannot underflow because of a previous `require()` or `if`-statement | 1 |  20 |
| [[G&#x2011;25](#g25-avoid-updating-storage-when-the-value-hasnt-changed)] | Avoid updating storage when the value hasn't changed | 4 |  3200 |
| [[G&#x2011;26](#g26-state-variable-read-in-a-loop)] | State variable read in a loop | 11 |  1067 |
| [[G&#x2011;27](#g27-using-this-to-access-functions-results-in-an-external-call-wasting-gas)] | Using `this` to access functions results in an external call, wasting gas | 3 |  300 |
| [[G&#x2011;28](#g28-unchecked---can-be-used-on-the-division-of-two-uints-in-order-to-save-gas)] | `unchecked {}`  can be used on the division of two `uint`s in order to save gas | 3 |  60 |
| [[G&#x2011;29](#g29-simple-checks-for-zero-can-be-done-using-assembly-to-save-gas)] | Simple checks for zero can be done using assembly to save gas | 10 |  60 |

Total: 314 instances over 29 issues with **22374 gas** saved

Gas totals are estimates based on data from the Ethereum Yellowpaper. The estimates use the lower bounds of ranges and count two iterations of each `for`-loop. All values above are runtime, not deployment, values; deployment values are listed in the individual issue descriptions. The table above as well as its gas numbers do not include any of the excluded findings.

### Disputed Issues

The issues below may be reported by other bots/wardens, but can be penalized/ignored since either the rule or the specified instances are invalid

| |Issue|Instances|
|-|:-|:-:|
| [[D&#x2011;01](#d01-abiencodepacked-should-not-be-used-with-dynamic-types-when-passing-the-result-to-a-hash-function-such-as-keccak256)] | ~~`abi.encodePacked()` should not be used with dynamic types when passing the result to a hash function such as `keccak256()`~~ | 1 | 
| [[D&#x2011;02](#d02-spdx-identifier-should-be-the-in-the-first-line-of-a-solidity-file)] | ~~SPDX identifier should be the in the first line of a solidity file~~ | 20 | 
| [[D&#x2011;03](#d03-inconsistent-comment-spacing)] | ~~Inconsistent comment spacing~~ | 1 | 
| [[D&#x2011;04](#d04-overly-complicated-arithmetic)] | ~~Overly complicated arithmetic~~ | 6 | 
| [[D&#x2011;05](#d05-public-functions-not-used-internally-can-be-marked-as-external-to-save-gas)] | ~~Public functions not used internally can be marked as external to save gas~~ | 34 | 
| [[D&#x2011;06](#d06-shorten-the-array-rather-than-copying-to-a-new-one)] | ~~Shorten the array rather than copying to a new one~~ | 11 | 
| [[D&#x2011;07](#d07-require--revert-statements-should-have-descriptive-reason-strings)] | ~~`require()` / `revert()` statements should have descriptive reason strings~~ | 92 | 
| [[D&#x2011;08](#d08-use-delete-instead-of-setting-mappingstate-variable-to-zero-to-save-gas)] | ~~Use delete instead of setting mapping/state variable to zero, to save gas~~ | 1 | 
| [[D&#x2011;09](#d09-events-that-mark-critical-parameter-changes-should-contain-both-the-old-and-the-new-value)] | ~~Events that mark critical parameter changes should contain both the old and the new value~~ | 16 | 
| [[D&#x2011;10](#d10-empty-function-body)] | ~~Empty function body~~ | 1 | 
| [[D&#x2011;11](#d11-cast-to-bytes-or-bytes32-for-clearer-semantic-meaning)] | ~~Cast to `bytes` or `bytes32` for clearer semantic meaning~~ | 1 | 
| [[D&#x2011;12](#d12-abiencode-is-less-efficient-than-abiencodepacked)] | ~~`abi.encode()` is less efficient than `abi.encodepacked()`~~ | 2 | 
| [[D&#x2011;13](#d13-event-names-should-use-camelcase)] | ~~Event names should use CamelCase~~ | 19 | 
| [[D&#x2011;14](#d14-internal-functions-not-called-by-the-contract-should-be-removed)] | ~~`internal` functions not called by the contract should be removed~~ | 11 | 
| [[D&#x2011;15](#d15-change-public-to-external-for-functions-that-are-not-called-internally)] | ~~Change `public` to `external` for functions that are not called internally~~ | 1 | 
| [[D&#x2011;16](#d16-initialization-can-be-front-run)] | ~~Initialization can be front-run~~ | 3 | 
| [[D&#x2011;17](#d17-use-multiple-require-and-if-statements-instead-of-)] | ~~Use multiple `require()` and `if` statements instead of `&&`~~ | 3 | 
| [[D&#x2011;18](#d18-use-inheritdoc-rather-than-using-a-non-standard-annotation)] | ~~Use `@inheritdoc` rather than using a non-standard annotation~~ | 27 | 
| [[D&#x2011;19](#d19-functions-which-are-either-private-or-internal-should-have-a-preceding-_-in-their-name)] | ~~Functions which are either private or internal should have a preceding _ in their name~~ | 4 | 
| [[D&#x2011;20](#d20-contracts-are-not-using-their-oz-upgradeable-counterparts)] | ~~Contracts are not using their OZ Upgradeable counterparts~~ | 4 | 
| [[D&#x2011;21](#d21-all-interfaces-used-within-a-project-should-be-imported)] | ~~All interfaces used within a project should be imported~~ | 10 | 
| [[D&#x2011;22](#d22-change-public-function-visibility-to-external-to-save-gas)] | ~~Change `public` function visibility to `external` to save gas~~ | 22 | 
| [[D&#x2011;23](#d23-re-org-attack)] | ~~Re-org attack~~ | 2 | 
| [[D&#x2011;24](#d24-a-function-which-defines-named-returns-in-its-declaration-doesnt-need-to-use-return)] | ~~A function which defines named returns in it's declaration doesn't need to use return~~ | 1 | 
| [[D&#x2011;25](#d25-state-variable-read-in-a-loop)] | ~~State variable read in a loop~~ | 13 | 
| [[D&#x2011;26](#d26-do-not-use-underscore-at-the-end-of-variable-name)] | ~~Do not use underscore at the end of variable name~~ | 4 | 
| [[D&#x2011;27](#d27-save-gas-with-the-use-of-specific-import-statements)] | ~~Save gas with the use of specific import statements~~ | 82 | 
| [[D&#x2011;28](#d28-unused-error-definition)] | ~~Unused `error` definition~~ | 2 | 
| [[D&#x2011;29](#d29-unused-struct-definition)] | ~~Unused `struct` definition~~ | 5 | 

Total: 399 instances over 29 issues




## Medium Risk Issues


### [M&#x2011;01] The `owner` is a single point of failure and a centralization risk
Having a single EOA as the only owner of contracts is a large centralization risk and a single point of failure. A single private key may be taken in a hack, or the sole holder of the key may become unable to retrieve the key when necessary, or the single owner can become malicious and perform a rug-pull. Consider changing to a multi-signature setup, and or having a role-based authorization model.

*There are 5 instances of this issue:*

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

81       function deploy(DeployParams memory dp, ContractImplementations memory impls)
82           external
83           onlyOwner
84           returns (DeployedContracts memory)
85:      {

```
*GitHub*: [81](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L81-L85)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

103      function relay(address target, uint256 value, bytes calldata data)
104          external
105          virtual
106          override
107          onlyOwner
108:     {

```
*GitHub*: [103](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L103-L108)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

178:     function setVoteSuccessNumerator(uint256 _voteSuccessNumerator) public onlyOwner {

203      function relay(address target, uint256 value, bytes calldata data)
204          external
205          virtual
206          override
207          onlyOwner
208:     {

```
*GitHub*: [178](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L178-L178), [203](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L203-L208)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

254      function relay(address target, uint256 value, bytes calldata data)
255          external
256          virtual
257          override
258          onlyOwner
259:     {

```
*GitHub*: [254](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L254-L259)

## Low Risk Issues


### [L&#x2011;01] Unsafe downcast
When a type is downcast to a smaller type, the higher order bits are truncated, effectively applying a modulo to the original value. Without any other checks, this wrapping will lead to unexpected behavior and bugs

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

/// @audit uint256 x -> uint240
263:          return uint240(x);

```
*GitHub*: [263](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L263)


### [L&#x2011;02] Loss of precision
Division by large numbers may result in the result being zero, due to solidity not supporting fractions. Consider requiring a minimum amount for the numerator to ensure that it is always larger than the denominator

*There are 2 instances of this issue:*

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

39            return (getPastCirculatingSupply(blockNumber) * quorumNumerator(blockNumber))
40:               / quorumDenominator();

```
*GitHub*: [39](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L39-L40)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

253:              votes * (blockNumber - fullWeightVotingDeadline_) / decreasingWeightDuration;

```
*GitHub*: [253](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L253)


### [L&#x2011;03] Upgradeable contract not initialized
Upgradeable contracts are initialized via an initializer function rather than by a constructor. Leaving such a contract uninitialized may lead to it being taken over by a malicious user

*There are 6 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

/// @audit missing __AccessControl_init()
28:   contract SecurityCouncilManager is

```
*GitHub*: [28](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L28)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

/// @audit missing __Ownable_init()
17:   contract SecurityCouncilMemberElectionGovernor is

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L17)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

/// @audit missing __Governor_init()
/// @audit missing __ArbitrumGovernorProposalExpiration_init()
/// @audit missing __Ownable_init()
17:   contract SecurityCouncilMemberRemovalGovernor is

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L17), [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L17), [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L17)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

/// @audit missing __Ownable_init()
16:   contract SecurityCouncilNomineeElectionGovernor is

```
*GitHub*: [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L16)


### [L&#x2011;04] Use `Ownable2Step` rather than `Ownable`
[`Ownable2Step`](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/3d7a93876a2e5e1d7fe29b5a0e96e222afdc4cfa/contracts/access/Ownable2Step.sol#L31-L56) and [`Ownable2StepUpgradeable`](https://github.com/OpenZeppelin/openzeppelin-contracts-upgradeable/blob/25aabd286e002a1526c345c8db259d57bdf0ad28/contracts/access/Ownable2StepUpgradeable.sol#L47-L63) prevent the contract ownership from mistakenly being transferred to an address that cannot handle it (e.g. due to a typo in the address), by requiring that the recipient of the owner permissions actively accept via a contract call of its own.

*There are 4 instances of this issue:*

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

55:   contract L2SecurityCouncilMgmtFactory is Ownable {

```
*GitHub*: [55](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L55)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

17    contract SecurityCouncilMemberElectionGovernor is
18        Initializable,
19        GovernorUpgradeable,
20        GovernorVotesUpgradeable,
21        SecurityCouncilMemberElectionGovernorCountingUpgradeable,
22        GovernorSettingsUpgradeable,
23        OwnableUpgradeable,
24        ElectionGovernor,
25        ISecurityCouncilMemberElectionGovernor
26    {
27:       /// @notice The SecurityCouncilNomineeElectionGovernor that creates proposals for this governor and contains the list of compliant nominees

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L17-L27)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

17    contract SecurityCouncilMemberRemovalGovernor is
18        Initializable,
19        GovernorUpgradeable,
20        GovernorVotesUpgradeable,
21        GovernorPreventLateQuorumUpgradeable,
22        GovernorCountingSimpleUpgradeable,
23        ArbitrumGovernorVotesQuorumFractionUpgradeable,
24        GovernorSettingsUpgradeable,
25        ArbitrumGovernorProposalExpirationUpgradeable,
26        OwnableUpgradeable
27:   {

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L17-L27)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

16    contract SecurityCouncilNomineeElectionGovernor is
17        Initializable,
18        GovernorUpgradeable,
19        GovernorVotesUpgradeable,
20        SecurityCouncilNomineeElectionGovernorCountingUpgradeable,
21        ArbitrumGovernorVotesQuorumFractionUpgradeable,
22        GovernorSettingsUpgradeable,
23        OwnableUpgradeable,
24        SecurityCouncilNomineeElectionGovernorTiming,
25        ElectionGovernor,
26        ISecurityCouncilNomineeElectionGovernor
27    {
28        /// @notice parameters for `initialize`
29        /// @param firstNominationStartDate First election start date
30        /// @param nomineeVettingDuration Duration of the nominee vetting period (expressed in blocks)
31        /// @param nomineeVetter Address of the nominee vetter
32        /// @param securityCouncilManager Security council manager contract
33        /// @param token Token used for voting
34        /// @param owner Owner of the governor (the Arbitrum DAO)
35        /// @param quorumNumeratorValue Numerator of the quorum fraction (0.2% = 20)
36        /// @param votingPeriod Duration of the voting period (expressed in blocks)
37        ///                     Note that the voting period + nominee vetting duration must be << than 6 months to ensure elections dont overlap
38        struct InitParams {
39            Date firstNominationStartDate;
40            uint256 nomineeVettingDuration;
41            address nomineeVetter;
42            ISecurityCouncilManager securityCouncilManager;
43            ISecurityCouncilMemberElectionGovernor securityCouncilMemberElectionGovernor;
44            IVotesUpgradeable token;
45            address owner;
46            uint256 quorumNumeratorValue;
47:           uint256 votingPeriod;

```
*GitHub*: [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L16-L47)


### [L&#x2011;05] Upgradeable contract is missing a `__gap[50]` storage variable to allow for new storage variables in later versions
See [this](https://docs.openzeppelin.com/contracts/4.x/upgradeable#storage_gaps) link for a description of this storage variable. While some contracts may not currently be sub-classed, adding the variable now protects against forgetting to add it in the future.

*There are 4 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

28    contract SecurityCouncilManager is
29        Initializable,
30        AccessControlUpgradeable,
31:       ISecurityCouncilManager

```
*GitHub*: [28](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L28-L31)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

17    contract SecurityCouncilMemberElectionGovernor is
18        Initializable,
19        GovernorUpgradeable,
20        GovernorVotesUpgradeable,
21        SecurityCouncilMemberElectionGovernorCountingUpgradeable,
22        GovernorSettingsUpgradeable,
23        OwnableUpgradeable,
24        ElectionGovernor,
25:       ISecurityCouncilMemberElectionGovernor

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L17-L25)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

17    contract SecurityCouncilMemberRemovalGovernor is
18        Initializable,
19        GovernorUpgradeable,
20        GovernorVotesUpgradeable,
21        GovernorPreventLateQuorumUpgradeable,
22        GovernorCountingSimpleUpgradeable,
23        ArbitrumGovernorVotesQuorumFractionUpgradeable,
24        GovernorSettingsUpgradeable,
25        ArbitrumGovernorProposalExpirationUpgradeable,
26:       OwnableUpgradeable

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L17-L26)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

16    contract SecurityCouncilNomineeElectionGovernor is
17        Initializable,
18        GovernorUpgradeable,
19        GovernorVotesUpgradeable,
20        SecurityCouncilNomineeElectionGovernorCountingUpgradeable,
21        ArbitrumGovernorVotesQuorumFractionUpgradeable,
22        GovernorSettingsUpgradeable,
23        OwnableUpgradeable,
24        SecurityCouncilNomineeElectionGovernorTiming,
25        ElectionGovernor,
26:       ISecurityCouncilNomineeElectionGovernor

```
*GitHub*: [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L16-L26)


### [L&#x2011;06] External calls in an un-bounded `for-`loop may result in a DOS
Consider limiting the number of iterations in `for-`loops that make external calls

*There are 3 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

62:              if (!securityCouncil.isOwner(member)) {

```
*GitHub*: [62](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L62-L62)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

112:             if (!govChainEmergencySCSafe.isOwner(dp.firstCohort[i])) {

118:             if (!govChainEmergencySCSafe.isOwner(dp.secondCohort[i])) {

```
*GitHub*: [112](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L112-L112), [118](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L118-L118)


### [L&#x2011;07] Initialization can be front-run
The `initialize()` functions below are not called by another contract atomically after the contract is deployed, so it's possible for a malicious user to call `initialize()` which, if it's noticed in time, would require the project to re-deploy the contract in order to properly initialize. Consider creating a factory contract, which will `new` and `initialize()` each contract atomically.

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

89       function initialize(
90           address[] memory _firstCohort,
91           address[] memory _secondCohort,
92           SecurityCouncilData[] memory _securityCouncils,
93           SecurityCouncilManagerRoles memory _roles,
94           address payable _l2CoreGovTimelock,
95           UpgradeExecRouteBuilder _router
96:      ) external initializer {

```
*GitHub*: [89](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L89-L96)


### [L&#x2011;08] Missing checks for `address(0x0)` when updating `address` state variables


*There are 3 instances of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

114:         nomineeVetter = params.nomineeVetter;

248:         nomineeVetter = _nomineeVetter;

```
*GitHub*: [114](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L114-L114), [248](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L248-L248)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

216:             topNomineesAddresses[i] = nominees[uint16(topNomineesPacked[i])];

```
*GitHub*: [216](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L216-L216)


### [L&#x2011;09] Missing checks for `address(0x0)` in the constructor


*There are 14 instances of this issue:*

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

35:          newEmergencySecurityCouncil = _newEmergencySecurityCouncil;

36:          newNonEmergencySecurityCouncil = _newNonEmergencySecurityCouncil;

38:          prevEmergencySecurityCouncil = _prevEmergencySecurityCouncil;

39:          prevNonEmergencySecurityCouncil = _prevNonEmergencySecurityCouncil;

44:          securityCouncilManager = _securityCouncilManager;

45:          l2AddressRegistry = _l2AddressRegistry;

```
*GitHub*: [35](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L35-L35), [36](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L36-L36), [38](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L38-L38), [39](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L39-L39), [44](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L44-L44), [45](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L45-L45)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

23:          newEmergencySecurityCouncil = _newEmergencySecurityCouncil;

24:          prevEmergencySecurityCouncil = _prevEmergencySecurityCouncil;

26:          l1UpgradeExecutor = _l1UpgradeExecutor;

27:          l1Timelock = _l1Timelock;

```
*GitHub*: [23](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L23-L23), [24](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L24-L24), [26](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L26-L26), [27](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L27-L27)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

19:          newEmergencySecurityCouncil = _newEmergencySecurityCouncil;

20:          prevEmergencySecurityCouncil = _prevEmergencySecurityCouncil;

22:          upgradeExecutor = _upgradeExecutor;

```
*GitHub*: [19](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L19-L19), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L20-L20), [22](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L22-L22)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

19:          store = _store;

```
*GitHub*: [19](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L19-L19)


### [L&#x2011;10] Upgradeable contract uses non-upgradeable version of the OpenZeppelin libraries/contracts
OpenZeppelin has an [Upgradeable](https://github.com/OpenZeppelin/openzeppelin-contracts-upgradeable/tree/master/contracts/utils) variants of each of its libraries and contracts, and upgradeable contracts should use those variants.

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

12:  import "@openzeppelin/contracts/utils/Address.sol";

```
*GitHub*: [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L12-L12)


### [L&#x2011;11] Use of a single-step ownership transfer
The existing `transferOwnership` function immediately transfers ownership to the new addres. Consider implementing a two-step variant, where the 'acceptor' of the ownership must call a separate function in order for the transfer to take effect. This can help to prevent mistakes where the wrong address is used, and ownership is irrecoverably lost.

*There are 3 instances of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

48       function initialize(
49           ISecurityCouncilNomineeElectionGovernor _nomineeElectionGovernor,
50           ISecurityCouncilManager _securityCouncilManager,
51           IVotesUpgradeable _token,
52           address _owner,
53           uint256 _votingPeriod,
54           uint256 _fullWeightDuration
55       ) public initializer {
56           if (_fullWeightDuration > _votingPeriod) {
57               revert InvalidDurations(_fullWeightDuration, _votingPeriod);
58           }
59   
60           __Governor_init("SecurityCouncilMemberElectionGovernor");
61           __GovernorVotes_init(_token);
62           __SecurityCouncilMemberElectionGovernorCounting_init({
63               initialFullWeightDuration: _fullWeightDuration
64           });
65           __GovernorSettings_init(0, _votingPeriod, 0);
66           _transferOwnership(_owner);
67   
68           if (!Address.isContract(address(_nomineeElectionGovernor))) {
69               revert NotAContract(address(_nomineeElectionGovernor));
70           }
71           nomineeElectionGovernor = _nomineeElectionGovernor;
72           if (!Address.isContract(address(_securityCouncilManager))) {
73               revert NotAContract(address(_securityCouncilManager));
74           }
75           securityCouncilManager = _securityCouncilManager;
76:      }

```
*GitHub*: [48](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L48-L76)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

58       function initialize(
59           uint256 _voteSuccessNumerator,
60           ISecurityCouncilManager _securityCouncilManager,
61           IVotesUpgradeable _token,
62           address _owner,
63           uint256 _votingDelay,
64           uint256 _votingPeriod,
65           uint256 _quorumNumerator,
66           uint256 _proposalThreshold,
67           uint64 _minPeriodAfterQuorum,
68           uint256 _proposalExpirationBlocks
69       ) public initializer {
70           __GovernorSettings_init(_votingDelay, _votingPeriod, _proposalThreshold);
71           __GovernorCountingSimple_init();
72           __GovernorVotes_init(_token);
73           __ArbitrumGovernorVotesQuorumFraction_init(_quorumNumerator);
74           __GovernorPreventLateQuorum_init(_minPeriodAfterQuorum);
75           __ArbitrumGovernorProposalExpirationUpgradeable_init(_proposalExpirationBlocks);
76           _transferOwnership(_owner);
77   
78           if (!Address.isContract(address(_securityCouncilManager))) {
79               revert NotAContract(address(_securityCouncilManager));
80           }
81   
82           securityCouncilManager = _securityCouncilManager;
83           _setVoteSuccessNumerator(_voteSuccessNumerator);
84:      }

```
*GitHub*: [58](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L58-L84)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

103      function initialize(InitParams memory params) public initializer {
104          __Governor_init("SecurityCouncilNomineeElectionGovernor");
105          __GovernorVotes_init(params.token);
106          __SecurityCouncilNomineeElectionGovernorCounting_init();
107          __ArbitrumGovernorVotesQuorumFraction_init(params.quorumNumeratorValue);
108          __GovernorSettings_init(0, params.votingPeriod, 0); // votingDelay and proposalThreshold are set to 0
109          __SecurityCouncilNomineeElectionGovernorTiming_init(
110              params.firstNominationStartDate, params.nomineeVettingDuration
111          );
112          _transferOwnership(params.owner);
113  
114          nomineeVetter = params.nomineeVetter;
115          if (!Address.isContract(address(params.securityCouncilManager))) {
116              revert NotAContract(address(params.securityCouncilManager));
117          }
118          securityCouncilManager = params.securityCouncilManager;
119          if (!Address.isContract(address(params.securityCouncilMemberElectionGovernor))) {
120              revert NotAContract(address(params.securityCouncilMemberElectionGovernor));
121          }
122          securityCouncilMemberElectionGovernor = params.securityCouncilMemberElectionGovernor;
123  
124          // elsewhere we make assumptions that the number of nominees
125          // is not greater than 500
126          // This value can still be updated via updateQuorumNumerator to a lower value
127          // if it is deemed ok, however we put a quick check here as a reminder
128          if ((quorumDenominator() / params.quorumNumeratorValue) > 500) {
129              revert QuorumNumeratorTooLow(params.quorumNumeratorValue);
130          }
131:     }

```
*GitHub*: [103](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L103-L131)


### [L&#x2011;12] Consider implementing two-step procedure for updating protocol addresses
A copy-paste error or a typo may end up bricking protocol functionality, or sending tokens to an address with no known private key. Consider implementing a two-step procedure for updating protocol addresses, where the recipient is set as pending, and must 'accept' the assignment by making an affirmative call. A straight forward way of doing this would be to have the target contracts implement [EIP-165](https://eips.ethereum.org/EIPS/eip-165), and to have the 'set' functions ensure that the recipient is of the right interface type.

*There are 2 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

315      function _setUpgradeExecRouteBuilder(UpgradeExecRouteBuilder _router) internal {
316          address routerAddress = address(_router);
317  
318          if (!Address.isContract(routerAddress)) {
319              revert NotAContract({account: routerAddress});
320          }
321  
322          router = _router;
323          emit UpgradeExecRouteBuilderSet(routerAddress);
324:     }

```
*GitHub*: [315](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L315-L324)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

246      function setNomineeVetter(address _nomineeVetter) external onlyGovernance {
247          address oldNomineeVetter = nomineeVetter;
248          nomineeVetter = _nomineeVetter;
249          emit NomineeVetterChanged(oldNomineeVetter, _nomineeVetter);
250:     }

```
*GitHub*: [246](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L246-L250)

## Non-critical Issues


### [N&#x2011;01] `public` functions not called by the contract should be declared `external` instead
Contracts [are allowed](https://docs.soliditylang.org/en/latest/contracts.html#function-overriding) to override their parents' functions and change the visibility from `external` to `public`.

*There are 34 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

186       function createActionRouteDataWithDefaults(
187           uint256[] memory chainIds,
188           address[] memory actionAddresses,
189           bytes32 timelockSalt
190:      ) public view returns (address, bytes memory) {

```
*GitHub*: [186](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L186-L190)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

349:      function securityCouncilsLength() public view returns (uint256) {

```
*GitHub*: [349](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L349)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

48        function initialize(
49            ISecurityCouncilNomineeElectionGovernor _nomineeElectionGovernor,
50            ISecurityCouncilManager _securityCouncilManager,
51            IVotesUpgradeable _token,
52            address _owner,
53            uint256 _votingPeriod,
54            uint256 _fullWeightDuration
55:       ) public initializer {

138       function proposalThreshold()
139           public
140           pure
141           override(GovernorSettingsUpgradeable, GovernorUpgradeable)
142:          returns (uint256)

181       function propose(address[] memory, uint256[] memory, bytes[] memory, string memory)
182           public
183           virtual
184           override
185:          returns (uint256)

191:      function castVote(uint256, uint8) public virtual override returns (uint256) {

196       function castVoteWithReason(uint256, uint8, string calldata)
197           public
198           virtual
199           override
200:          returns (uint256)

206       function castVoteBySig(uint256, uint8, uint8, bytes32, bytes32)
207           public
208           virtual
209           override
210:          returns (uint256)

```
*GitHub*: [48](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L48-L55), [138](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L138-L142), [181](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L181-L185), [191](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L191), [196](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L196-L200), [206](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L206-L210)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

58        function initialize(
59            uint256 _voteSuccessNumerator,
60            ISecurityCouncilManager _securityCouncilManager,
61            IVotesUpgradeable _token,
62            address _owner,
63            uint256 _votingDelay,
64            uint256 _votingPeriod,
65            uint256 _quorumNumerator,
66            uint256 _proposalThreshold,
67            uint64 _minPeriodAfterQuorum,
68            uint256 _proposalExpirationBlocks
69:       ) public initializer {

106       function propose(
107           address[] memory targets,
108           uint256[] memory values,
109           bytes[] memory calldatas,
110           string memory description
111:      ) public override returns (uint256) {

178:      function setVoteSuccessNumerator(uint256 _voteSuccessNumerator) public onlyOwner {

191       function COUNTING_MODE()
192           public
193           pure
194           virtual
195           override(GovernorCountingSimpleUpgradeable, IGovernorUpgradeable)
196:          returns (string memory)

213       function proposalThreshold()
214           public
215           view
216           override(GovernorUpgradeable, GovernorSettingsUpgradeable)
217:          returns (uint256)

```
*GitHub*: [58](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L58-L69), [106](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L106-L111), [178](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L178), [191](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L191-L196), [213](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L213-L217)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

103:      function initialize(InitParams memory params) public initializer {

357       function proposalThreshold()
358           public
359           view
360           virtual
361           override(GovernorSettingsUpgradeable, GovernorUpgradeable)
362:          returns (uint256)

368:      function isCompliantNominee(uint256 proposalId, address account) public view returns (bool) {

373:      function compliantNominees(uint256 proposalId) public view returns (address[] memory) {

388:      function currentCohort() public view returns (Cohort) {

400:      function isExcluded(uint256 proposalId, address possibleExcluded) public view returns (bool) {

405:      function excludedNomineeCount(uint256 proposalId) public view returns (uint256) {

410       function isContender(uint256 proposalId, address possibleContender)
411           public
412           view
413           virtual
414           override
415:          returns (bool)

423       function propose(address[] memory, uint256[] memory, bytes[] memory, string memory)
424           public
425           virtual
426           override
427:          returns (uint256)

433:      function castVote(uint256, uint8) public virtual override returns (uint256) {

438       function castVoteWithReason(uint256, uint8, string calldata)
439           public
440           virtual
441           override
442:          returns (uint256)

448       function castVoteBySig(uint256, uint8, uint8, bytes32, bytes32)
449           public
450           virtual
451           override
452:          returns (uint256)

```
*GitHub*: [103](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L103), [357](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L357-L362), [368](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L368), [373](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L373), [388](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L388), [400](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L400), [405](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L405), [410](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L410-L415), [423](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L423-L427), [433](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L433), [438](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L438-L442), [448](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L448-L452)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

77:       function setFullWeightDuration(uint256 newFullWeightDuration) public onlyGovernance {

143:      function COUNTING_MODE() public pure virtual override returns (string memory) {

153:      function weightReceived(uint256 proposalId, address nominee) public view returns (uint256) {

158:      function hasVoted(uint256 proposalId, address account) public view override returns (bool) {

```
*GitHub*: [77](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L77), [143](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L143), [153](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L153), [158](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L158)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

128:      function COUNTING_MODE() public pure virtual override returns (string memory) {

133:      function hasVoted(uint256 proposalId, address account) public view override returns (bool) {

148:      function nominees(uint256 proposalId) public view returns (address[] memory) {

153:      function votesUsed(uint256 proposalId, address account) public view returns (uint256) {

158:      function votesReceived(uint256 proposalId, address contender) public view returns (uint256) {

```
*GitHub*: [128](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L128), [133](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L133), [148](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L148), [153](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L153), [158](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L158)

</details>

### [N&#x2011;02] `constant`s should be defined rather than using magic numbers
Even [assembly](https://github.com/code-423n4/2022-05-opensea-seaport/blob/9d7ce4d08bf3c3010304a0476a785c70c0e90ae7/contracts/lib/TokenTransferrer.sol#L35-L39) can benefit from using readable constants instead of hex/numeric literals

*There are 12 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

/// @audit 100
175:              address(100),

```
*GitHub*: [175](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L175)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

/// @audit 4
95:           bytes4 selector = bytes4(calldataWithSelector[:4]);

/// @audit 4
96:           bytes memory rest = calldataWithSelector[4:];

/// @audit 36
124:          if (calldatas[0].length != 36) {

```
*GitHub*: [95](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L95), [96](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L96), [124](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L124)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

/// @audit 500
128:          if ((quorumDenominator() / params.quorumNumeratorValue) > 500) {

```
*GitHub*: [128](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L128)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

/// @audit 10_000
46:           return 10_000;

```
*GitHub*: [46](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L46)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

/// @audit 64
106:          if (params.length != 64) {

/// @audit 16
206:              uint256 packed = (uint256(weights[i]) << 16) | i;

```
*GitHub*: [106](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L106), [206](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L206)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

/// @audit 64
73:           if (params.length != 64) {

```
*GitHub*: [73](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L73)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

/// @audit 6
79:           month += 6 * electionIndex;

/// @audit 12
80:           uint256 year = firstNominationStartDate.year + month / 12;

/// @audit 12
81:           month = month % 12;

```
*GitHub*: [79](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L79), [80](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L80), [81](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L81)

</details>

### [N&#x2011;03] Event is not properly `indexed`
Index event fields make the field more quickly accessible [to off-chain tools](https://ethereum.stackexchange.com/questions/40396/can-somebody-please-explain-the-concept-of-event-indexing) that parse events. This is especially useful when it comes to filtering based on an address. However, note that each index field costs extra gas during emission, so it's not necessarily best to index the maximum allowed per event (three fields). Where applicable, each `event` should use three `indexed` fields if there are three or more fields, and gas usage is not particularly of concern for the events in question. If there are fewer than three applicable fields, all of the applicable fields should be indexed.

*There are 4 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

38        event SecurityCouncilAdded(
39            address securityCouncil, address updateAction, uint256 securityCouncilsLength
40:       );

41        event SecurityCouncilRemoved(
42            address securityCouncil, address updateAction, uint256 securityCouncilsLength
43:       );

44:       event UpgradeExecRouteBuilderSet(address UpgradeExecRouteBuilder);

```
*GitHub*: [38](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L38-L40), [41](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L41-L43), [44](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L44)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

33:       event MemberRemovalProposed(address memberToRemove, string description);

```
*GitHub*: [33](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L33)


### [N&#x2011;04] Common functions should be refactored to a common base contract
The functions below have the same implementation as is seen in other files. The functions should be refactored into functions of a common base contract

*There are 9 instances of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

/// @audit seen in src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol
203       function relay(address target, uint256 value, bytes calldata data)
204           external
205           virtual
206           override
207           onlyOwner
208       {
209           AddressUpgradeable.functionCallWithValue(target, data, value);
210:      }

```
*GitHub*: [203](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L203-L210)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

/// @audit seen in src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol
254       function relay(address target, uint256 value, bytes calldata data)
255           external
256           virtual
257           override
258           onlyOwner
259       {
260           AddressUpgradeable.functionCallWithValue(target, data, value);
261:      }

/// @audit seen in src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol
423       function propose(address[] memory, uint256[] memory, bytes[] memory, string memory)
424           public
425           virtual
426           override
427           returns (uint256)
428       {
429           revert ProposeDisabled();
430:      }

/// @audit seen in src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol
433       function castVote(uint256, uint8) public virtual override returns (uint256) {
434           revert CastVoteDisabled();
435:      }

/// @audit seen in src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol
438       function castVoteWithReason(uint256, uint8, string calldata)
439           public
440           virtual
441           override
442           returns (uint256)
443       {
444           revert CastVoteDisabled();
445:      }

/// @audit seen in src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol
448       function castVoteBySig(uint256, uint8, uint8, bytes32, bytes32)
449           public
450           virtual
451           override
452           returns (uint256)
453       {
454           revert CastVoteDisabled();
455:      }

```
*GitHub*: [254](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L254-L261), [423](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L423-L430), [433](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L433-L435), [438](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L438-L445), [448](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L448-L455)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

/// @audit seen in src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol
153       function votesUsed(uint256 proposalId, address account) public view returns (uint256) {
154           return _elections[proposalId].votesUsed[account];
155:      }

/// @audit seen in src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol
170       function _quorumReached(uint256) internal pure override returns (bool) {
171           return true;
172:      }

/// @audit seen in src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol
175       function _voteSucceeded(uint256) internal pure override returns (bool) {
176           return true;
177:      }

```
*GitHub*: [153](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L153-L155), [170](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L170-L172), [175](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L175-L177)


### [N&#x2011;05] Vulnerable versions of packages are being used
This project's specific package versions are vulnerable to the specific CVEs listed below. Consider switching to more recent versions of these packages that don't have these vulnerabilities

*There is one instance of this issue:*

```solidity
File: Various Files

/// @audit Vulnerabilities:
///          
```



- [CVE-2023-30541](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-30541) - MEDIUM -  (@openzeppelin/contracts >=3.2.0 <4.8.3) - OpenZeppelin Contracts is a library for secure smart contract development. A function in the implementation contract may be inaccessible if its selector clashes with one of the proxy's own selectors. Specifically, if the clashing function has a different signature with incompatible ABI encoding, the proxy could revert while attempting to decode the arguments from calldata. The probability of an accidental clash is negligible, but one could be caused deliberately and could cause a reduction in availability. The issue has been fixed in version 4.8.3. As a workaround if a function appears to be inaccessible for this reason, it may be possible to craft the calldata such that ABI decoding does not fail at the proxy and the function is properly proxied through.
- [CVE-2023-30542](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-30542) - HIGH -  (@openzeppelin/contracts >=4.3.0 <4.8.3) - OpenZeppelin Contracts is a library for secure smart contract development. The proposal creation entrypoint (`propose`) in `GovernorCompatibilityBravo` allows the creation of proposals with a `signatures` array shorter than the `calldatas` array. This causes the additional elements of the latter to be ignored, and if the proposal succeeds the corresponding actions would eventually execute without any calldata. The `ProposalCreated` event correctly represents what will eventually execute, but the proposal parameters as queried through `getActions` appear to respect the original intended calldata. This issue has been patched in 4.8.3. As a workaround, ensure that all proposals that pass through governance have equal length `signatures` and `calldatas` parameters.
- [CVE-2022-35915](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-35915) - MEDIUM -  (@openzeppelin/contracts >= 2.0.0 <4.7.2) - OpenZeppelin Contracts is a library for secure smart contract development. The target contract of an EIP-165 `supportsInterface` query can cause unbounded gas consumption by returning a lot of data, while it is generally assumed that this operation has a bounded cost. The issue has been fixed in v4.7.2. Users are advised to upgrade. There are no known workarounds for this issue.
- [CVE-2022-39384](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-39384) - MEDIUM -  (@openzeppelin/contracts >=3.2.0 <4.4.1) - OpenZeppelin Contracts is a library for secure smart contract development. Before version 4.4.1 but after 3.2.0, initializer functions that are invoked separate from contract creation (the most prominent example being minimal proxies) may be reentered if they make an untrusted non-view external call. Once an initializer has finished running it can never be re-executed. However, an exception put in place to support multiple inheritance made reentrancy possible in the scenario described above, breaking the expectation that there is a single execution. Note that upgradeable proxies are commonly initialized together with contract creation, where reentrancy is not feasible, so the impact of this issue is believed to be minor. This issue has been patched, please upgrade to version 4.4.1. As a workaround, avoid untrusted external calls during initialization.
```

```


### [N&#x2011;06] Import declarations should import specific identifiers, rather than the whole file
Using import declarations of the form `import {<identifier_name>} from "some/file.sol"` avoids polluting the symbol namespace making flattened files smaller, and speeds up compilation (but does not save any gas)

*There are 82 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

4:    import "@arbitrum/nitro-contracts/src/precompiles/ArbSys.sol";

5:    import "./UpgradeExecutor.sol";

6:    import "./L1ArbitrumTimelock.sol";

7:    import "./security-council-mgmt/Common.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L7)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

4:    import "../../../security-council-mgmt/interfaces/IGnosisSafe.sol";

5:    import "../../address-registries/L2AddressRegistryInterfaces.sol";

6:    import "./SecurityCouncilMgmtUpgradeLib.sol";

7:    import "../../../interfaces/IArbitrumDAOConstitution.sol";

8:    import "../../../interfaces/IUpgradeExecutor.sol";

9:    import "../../../interfaces/ICoreTimelock.sol";

10:   import "@openzeppelin/contracts/utils/Address.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L7), [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L8), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L9), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L10)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

4:    import "../../../security-council-mgmt/interfaces/IGnosisSafe.sol";

5:    import "../../../interfaces/IUpgradeExecutor.sol";

6:    import "../../../interfaces/ICoreTimelock.sol";

7:    import "./SecurityCouncilMgmtUpgradeLib.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L7)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

4:    import "../../../security-council-mgmt/interfaces/IGnosisSafe.sol";

5:    import "./SecurityCouncilMgmtUpgradeLib.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L5)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

4:    import "../../../security-council-mgmt/interfaces/IGnosisSafe.sol";

5:    import "../../../interfaces/IUpgradeExecutor.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L5)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

4:    import "./KeyValueStore.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L4)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

4:    import "../ArbitrumTimelock.sol";

5:    import "../UpgradeExecutor.sol";

6:    import "../L1ArbitrumTimelock.sol";

7:    import "./SecurityCouncilMgmtUtils.sol";

8:    import "./interfaces/ISecurityCouncilManager.sol";

9:    import "./SecurityCouncilMemberSyncAction.sol";

10:   import "../UpgradeExecRouteBuilder.sol";

11:   import "@openzeppelin/contracts-upgradeable/proxy/utils/Initializable.sol";

12:   import "@openzeppelin/contracts/utils/Address.sol";

13:   import "@openzeppelin/contracts-upgradeable/access/AccessControlUpgradeable.sol";

14:   import "./Common.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L7), [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L8), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L9), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L10), [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L11), [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L12), [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L13), [14](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L14)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

4:    import "./interfaces/IGnosisSafe.sol";

5:    import "./SecurityCouncilMgmtUtils.sol";

6:    import "../gov-action-contracts/execution-record/ActionExecutionRecord.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L6)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

4:    import "@openzeppelin/contracts/access/Ownable.sol";

5:    import "@openzeppelin/contracts/utils/Address.sol";

6:    import "../governors/SecurityCouncilMemberElectionGovernor.sol";

7:    import "../governors/SecurityCouncilNomineeElectionGovernor.sol";

8:    import "../SecurityCouncilManager.sol";

9:    import "../governors/SecurityCouncilMemberRemovalGovernor.sol";

10:   import "@openzeppelin/contracts/proxy/transparent/TransparentUpgradeableProxy.sol";

11:   import "../interfaces/ISecurityCouncilManager.sol";

12:   import "../interfaces/IGnosisSafe.sol";

13:   import "../../ArbitrumTimelock.sol";

14:   import "@openzeppelin/contracts-upgradeable/governance/utils/IVotesUpgradeable.sol";

15:   import "../../UpgradeExecRouteBuilder.sol";

16:   import "../Common.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L7), [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L8), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L9), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L10), [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L11), [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L12), [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L13), [14](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L14), [15](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L15), [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L16)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

4:    import "@openzeppelin/contracts-upgradeable/governance/extensions/GovernorVotesUpgradeable.sol";

5:    import "@openzeppelin/contracts-upgradeable/governance/extensions/GovernorSettingsUpgradeable.sol";

6:    import "@openzeppelin/contracts-upgradeable/access/OwnableUpgradeable.sol";

7:    import "./modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol";

8:    import "../interfaces/ISecurityCouncilMemberElectionGovernor.sol";

9:    import "../interfaces/ISecurityCouncilNomineeElectionGovernor.sol";

10:   import "../interfaces/ISecurityCouncilManager.sol";

11:   import "./modules/ElectionGovernor.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L7), [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L8), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L9), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L10), [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L11)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

4     import
5:        "@openzeppelin/contracts-upgradeable/governance/extensions/GovernorPreventLateQuorumUpgradeable.sol";

6     import
7:        "@openzeppelin/contracts-upgradeable/governance/extensions/GovernorCountingSimpleUpgradeable.sol";

8:    import "@openzeppelin/contracts-upgradeable/governance/extensions/GovernorSettingsUpgradeable.sol";

9:    import "@openzeppelin/contracts-upgradeable/access/OwnableUpgradeable.sol";

10:   import "./../interfaces/ISecurityCouncilManager.sol";

11:   import "../Common.sol";

12:   import "./modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol";

13:   import "./modules/ArbitrumGovernorProposalExpirationUpgradeable.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L4-L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L6-L7), [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L8), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L9), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L10), [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L11), [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L12), [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L13)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

4:    import "@openzeppelin/contracts-upgradeable/governance/extensions/GovernorSettingsUpgradeable.sol";

5:    import "@openzeppelin/contracts-upgradeable/access/OwnableUpgradeable.sol";

6:    import "../interfaces/ISecurityCouncilMemberElectionGovernor.sol";

7:    import "../interfaces/ISecurityCouncilNomineeElectionGovernor.sol";

8:    import "./modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol";

9:    import "./modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol";

10:   import "./modules/SecurityCouncilNomineeElectionGovernorTiming.sol";

11:   import "./modules/ElectionGovernor.sol";

12:   import "../SecurityCouncilMgmtUtils.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L7), [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L8), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L9), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L10), [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L11), [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L12)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

4     import
5:        "@openzeppelin/contracts-upgradeable/governance/extensions/GovernorVotesQuorumFractionUpgradeable.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L4-L5)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

5:    import "@openzeppelin/contracts-upgradeable/utils/StringsUpgradeable.sol";

6:    import "../../Common.sol";

```
*GitHub*: [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L6)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

4:    import "@openzeppelin/contracts-upgradeable/governance/GovernorUpgradeable.sol";

6:    import "solady/utils/LibSort.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L4), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L6)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

4:    import "@openzeppelin/contracts-upgradeable/governance/GovernorUpgradeable.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L4)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

4:    import "../../interfaces/ISecurityCouncilManager.sol";

6:    import "@openzeppelin/contracts-upgradeable/governance/GovernorUpgradeable.sol";

7:    import "solady/utils/DateTimeLib.sol";

8:    import "../../Common.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L4), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L7), [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L8)

</details>

### [N&#x2011;07] Large multiples of ten should use scientific notation (e.g. `1e6`) rather than decimal literals (e.g. `1000000`), for readability


*There are 2 instances of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

28:       uint256 public constant voteSuccessDenominator = 10_000;

```
*GitHub*: [28](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L28)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

46:           return 10_000;

```
*GitHub*: [46](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L46)


### [N&#x2011;08] Events that mark critical parameter changes should contain both the old and the new value
This should especially be done if the new value is not required to be different from the old value

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

/// @audit setFullWeightDuration()
83:           emit FullWeightDurationSet(newFullWeightDuration);

```
*GitHub*: [83](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L83)


### [N&#x2011;09] Constant redefined elsewhere
Consider defining in only one contract so that values cannot become out of sync when only one location is updated. A [cheap way](https://medium.com/coinmonks/gas-cost-of-solidity-library-functions-dbe0cedd4678) to store constants in a single location is to create an `internal constant` in a `library`. If the variable is a local cache of another contract's value, consider making the cache variable internal or private, which will require external users to query the contract with the source of truth, so that callers don't get out of sync.

*There are 5 instances of this issue:*

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

/// @audit seen in src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol 
12:       uint256 public immutable emergencySecurityCouncilThreshold;

```
*GitHub*: [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L12)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

/// @audit seen in src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol 
8:        IGnosisSafe public immutable newEmergencySecurityCouncil;

/// @audit seen in src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol 
9:        IGnosisSafe public immutable prevEmergencySecurityCouncil;

/// @audit seen in src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol 
10:       uint256 public immutable emergencySecurityCouncilThreshold;

```
*GitHub*: [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L8), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L9), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L10)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

/// @audit seen in src/UpgradeExecRouteBuilder.sol 
77:       address public constant RETRYABLE_TICKET_MAGIC = 0xa723C008e76E379c55599D2E4d93879BeaFDa79C;

```
*GitHub*: [77](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L77)


### [N&#x2011;10] Use `@inheritdoc` rather than using a non-standard annotation


*There are 3 instances of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

101       /// @notice Allows the owner to make calls from the governor
102       /// @dev    See {L2ArbitrumGovernor-relay}
103       function relay(address target, uint256 value, bytes calldata data)
104           external
105           virtual
106           override
107:          onlyOwner

```
*GitHub*: [101](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L101-L107)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

201       /// @notice Allows the owner to make calls from the governor
202       /// @dev    See {L2ArbitrumGovernor-relay}
203       function relay(address target, uint256 value, bytes calldata data)
204           external
205           virtual
206           override
207:          onlyOwner

```
*GitHub*: [201](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L201-L207)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

252       /// @notice Allows the owner to make calls from the governor
253       /// @dev    See {L2ArbitrumGovernor-relay}
254       function relay(address target, uint256 value, bytes calldata data)
255           external
256           virtual
257           override
258:          onlyOwner

```
*GitHub*: [252](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L252-L258)


### [N&#x2011;11] Lines are too long
Usually lines in source code are limited to [80](https://softwareengineering.stackexchange.com/questions/148677/why-is-80-characters-the-standard-limit-for-code-width) characters. Today's screens are much larger so it's reasonable to stretch this in some cases. The solidity style guide recommends a maximumum line length of [120 characters](https://docs.soliditylang.org/en/v0.8.17/style-guide.html#maximum-line-length), so the lines below should be split when they reach that length.

*There are 28 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

48:       /// @notice Default args for creating a proposal, used by createProposalWithDefaulArgs and createProposalBatchWithDefaultArgs

```
*GitHub*: [48](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L48)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

103:          // revoke old security council cancel role; it is unnecessary to grant it to explicitly grant it to new security council since the security council can already cancel via the core governor's relay method.

```
*GitHub*: [103](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L103)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

49:       // change needs to be made, a change to these arrays is first made here locally, then pushed to each of the Security Councils

76:       ///         Value is defined in L1ArbitrumTimelock contract https://etherscan.io/address/0xE6841D92B0C345144506576eC13ECf5103aC7f49#readProxyContract#F5

418:      /// @dev Create a union of the second and first cohort, then update all Security Councils under management with that unioned array.

```
*GitHub*: [49](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L49), [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L76), [418](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L418)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

26:       /// @dev    This function contains O(n^2) operations, so doesnt scale for large numbers of members. Expected count is 12, which is acceptable.

29:       /// @param _updatedMembers  The new list of members. The Security Council will be updated to have this exact list of members

```
*GitHub*: [26](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L26), [29](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L29)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

54:   /// Prerequisites: core Arb DAO governance contracts, and a SecurityCouncilMemberSyncAction deployed for each governed security council (on each corresponding chain)

```
*GitHub*: [54](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L54)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

27:       /// @notice The SecurityCouncilNomineeElectionGovernor that creates proposals for this governor and contains the list of compliant nominees

135:      /// @notice Normally "the number of votes required in order for a voter to become a proposer." But in our case it is 0.

136:      /// @dev    Since we only want proposals to be created via `proposeFromNomineeElectionGovernor`, we set the proposal threshold to 0.

```
*GitHub*: [27](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L27), [135](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L135), [136](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L136)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

49:       /// @param _voteSuccessNumerator value that with denominator 10_000 determines the ration of for/against votes required for success

258:          // The manager does some checks to ensure that the removal can occur (eg the account is a member) - if these checks fail

```
*GitHub*: [49](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L49), [258](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L258)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

15:   /// @notice Governor contract for selecting Security Council Nominees (phase 1 of the Security Council election process).

37:       ///                     Note that the voting period + nominee vetting duration must be << than 6 months to ensure elections dont overlap

234:          // every 6 months. Updates to the sec council manager using methods other than replaceCohort can effect this check

264:      /// @dev    Can be called only after a nomninee election proposal has "succeeded" (voting has ended) and before the nominee vetting period has ended.

286:      /// @dev    Can be called only when a proposal is succeeded (voting has ended) and there are fewer compliant nominees than the target.

288:      ///         The Constitution must be followed adding nominees. For example this method can be used by the Foundation to add a

289:      ///         random member of the outgoing security council, if less than 6 members meet the threshold to become a nominee

310:          // every 6 months. Updates to the sec council manager using methods other than replaceCohort can effect this check

354:      /// @notice Normally "the number of votes required in order for a voter to become a proposer." But in our case it is 0.

```
*GitHub*: [15](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L15), [37](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L37), [234](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L234), [264](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L264), [286](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L286), [288](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L288), [289](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L289), [310](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L310), [354](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L354)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

21:       ///         Note that Excluded Address is a readable name with no code or PK associated with it, and thus can't vote.

```
*GitHub*: [21](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L21)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

175:      ///         Absolute worst case, this function uses 4502345 with 500 nominees, or about 9k gas per nominee (when called externally).

241:          // Between proposalSnapshot and fullWeightVotingDeadline all votes will have 100% weight - each vote has weight 1

247:          // Between the fullWeightVotingDeadline and the proposalDeadline each vote will have weight linearly decreased by time since fullWeightVotingDeadline

250:          // slope numerator is -votes, slope denominator is decreasingWeightDuration, delta x is blockNumber - fullWeightVotingDeadline_

```
*GitHub*: [175](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L175), [241](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L241), [247](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L247), [250](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L250)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

61:       /// @param params abi encoded (contender, votes) where votes is the amount of votes the account is using for this contender

```
*GitHub*: [61](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L61)

</details>

### [N&#x2011;12] Long functions should be refactored into multiple, smaller, functions


*There are 4 instances of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

/// @audit 74 lines (65 in the body)
105       function createActionRouteData(
106           uint256[] memory chainIds,
107           address[] memory actionAddresses,
108           uint256[] memory actionValues,
109           bytes[] memory actionDatas,
110           bytes32 predecessor,
111           bytes32 timelockSalt
112:      ) public view returns (address, bytes memory) {

```
*GitHub*: [105](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L105-L112)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

/// @audit 100 lines (98 in the body)
48        function perform() external {
49:           IUpgradeExecutor upgradeExecutor = IUpgradeExecutor(l2AddressRegistry.coreGov().owner());

```
*GitHub*: [48](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L48-L49)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

/// @audit 109 lines (103 in the body)
81        function deploy(DeployParams memory dp, ContractImplementations memory impls)
82            external
83            onlyOwner
84:           returns (DeployedContracts memory)

```
*GitHub*: [81](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L81-L84)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

/// @audit 57 lines (49 in the body)
62        function _countVote(
63            uint256 proposalId,
64            address account,
65            uint8 support,
66            uint256 weight,
67:           bytes memory params

```
*GitHub*: [62](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L62-L67)


### [N&#x2011;13] Variable names that consist of all capital letters should be reserved for `constant`/`immutable` variables
If the variable needs to be different based on which class it comes from, a `view`/`pure` _function_ should be used instead (e.g. like [this](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/76eee35971c2541585e05cbf258510dda7b2fbc6/contracts/token/ERC20/extensions/draft-IERC20Permit.sol#L59)).

*There are 6 instances of this issue:*

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

69:           bytes32 TIMELOCK_PROPOSAL_ROLE = l2CoreGovTimelock.PROPOSER_ROLE();

70:           bytes32 TIMELOCK_CANCELLER_ROLE = l2CoreGovTimelock.CANCELLER_ROLE();

114:          bytes32 EXECUTOR_ROLE = upgradeExecutor.EXECUTOR_ROLE();

```
*GitHub*: [69](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L69), [70](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L70), [114](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L114)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

40:           bytes32 TIMELOCK_CANCELLER_ROLE = l1Timelock.CANCELLER_ROLE();

```
*GitHub*: [40](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L40)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

35:           bytes32 EXECUTOR_ROLE = upgradeExecutor.EXECUTOR_ROLE();

```
*GitHub*: [35](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L35)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

15:           bytes32 EXECUTOR_ROLE = _upgradeExecutor.EXECUTOR_ROLE();

```
*GitHub*: [15](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L15)


### [N&#x2011;14] Typos


*There are 13 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

/// @audit targetted
56:       /// @notice Address of the L1 timelock targetted by this route builder

/// @audit targetted
58:       /// @notice The minimum delay of the L1 timelock targetted by this route builder

```
*GitHub*: [56](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L56), [58](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L58)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

/// @audit counicl
39:           // swap in new emergency security counicl canceller role

```
*GitHub*: [39](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L39)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

/// @audit memgency
26:           // swap in new memgency security council

```
*GitHub*: [26](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L26)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

/// @audit circumstancces
72:       /// @notice Size of cohort under ordinary circumstancces

/// @audit constucted
431:              // call to ArbSys.sendTxToL1; target the L1 timelock with the calldata previously constucted

```
*GitHub*: [72](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L72), [431](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L431)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

/// @audit propsoed
101:      ///         but enforces that only calls to securityCouncilManager's removeMember can be propsoed.

/// @audit removeMmeber
103:      /// @param values Value for removeMmeber; must be [0]

/// @audit theshold
160:      /// @notice A removal proposal if a theshold of all cast votes vote in favor of removal.

/// @audit numberator
177:      /// @param _voteSuccessNumerator new numberator value

```
*GitHub*: [101](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L101), [103](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L103), [160](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L160), [177](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L177)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

/// @audit nomninee
264:      /// @dev    Can be called only after a nomninee election proposal has "succeeded" (voting has ended) and before the nominee vetting period has ended.

```
*GitHub*: [264](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L264)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

/// @audit quorom
16:       ///         tokens will still count towards the total supply, and will therefore affect the quorom.

```
*GitHub*: [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L16)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

/// @audit deacreasing
224:      ///         deacreasing weight, reaching 0 at the proposalDeadline.

```
*GitHub*: [224](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L224)

</details>

### [N&#x2011;15] File is missing NatSpec


*There are 5 instances of this issue:*

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol


```
*GitHub*: [various](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol


```
*GitHub*: [various](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol


```
*GitHub*: [various](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol


```
*GitHub*: [various](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol


```
*GitHub*: [various](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol)


### [N&#x2011;16] NatSpec `@param` is missing


*There are 116 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

/// @audit Missing: '@param key'
/// @audit Missing: '@param value'
23        /// @notice Sets a value in the store
24        /// @dev    Combines the provided key with the action contract id
25:       function _set(uint256 key, uint256 value) internal {

/// @audit Missing: '@param key'
29        /// @notice Gets a value from the store
30        /// @dev    Combines the provided key with the action contract id
31:       function _get(uint256 key) internal view returns (uint256) {

/// @audit Missing: '@param key'
35        /// @notice This contract uses a composite key of the provided key and the action contract id.
36        ///         This function can be used to calculate the composite key
37:       function computeKey(uint256 key) public view returns (uint256) {

```
*GitHub*: [23](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L23-L25), [23](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L23-L25), [29](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L29-L31), [35](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L35-L37)

```solidity
File: src/gov-action-contracts/execution-record/KeyValueStore.sol

/// @audit Missing: '@param key'
/// @audit Missing: '@param value'
9         /// @notice Sets a value in the store
10        /// @dev    Combines the provided key with the msg.sender to ensure uniqueness
11:       function set(uint256 key, uint256 value) external {

/// @audit Missing: '@param key'
15        /// @notice Get a value from the store for the current msg.sender
16:       function get(uint256 key) external view returns (uint256) {

/// @audit Missing: '@param owner'
/// @audit Missing: '@param key'
20        /// @notice Get a value from the store for any sender
21:       function get(address owner, uint256 key) external view returns (uint256) {

/// @audit Missing: '@param owner'
/// @audit Missing: '@param key'
25        /// @notice Compute the composite key for a specific user
26:       function computeKey(address owner, uint256 key) public pure returns (uint256) {

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L9-L11), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L9-L11), [15](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L15-L16), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L20-L21), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L20-L21), [25](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L25-L26), [25](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L25-L26)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

/// @audit Missing: '@param _nonce'
25        /// @notice Updates members of security council multisig to match provided array
26        /// @dev    This function contains O(n^2) operations, so doesnt scale for large numbers of members. Expected count is 12, which is acceptable.
27        ///         Gnosis OwnerManager handles reverting if address(0) is passed to remove/add owner
28        /// @param _securityCouncil The security council to update
29        /// @param _updatedMembers  The new list of members. The Security Council will be updated to have this exact list of members
30        /// @return res indicates whether an update took place
31        function perform(address _securityCouncil, address[] memory _updatedMembers, uint256 _nonce)
32            external
33:           returns (bool res)

/// @audit Missing: '@param securityCouncil'
/// @audit Missing: '@param data'
126       /// @notice Execute provided operation via gnosis safe's trusted execTransactionFromModule entry point
127:      function _execFromModule(IGnosisSafe securityCouncil, bytes memory data) internal {

```
*GitHub*: [25](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L25-L33), [126](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L126-L127), [126](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L126-L127)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

/// @audit Missing: '@param proxyAdmin'
/// @audit Missing: '@param impl'
/// @audit Missing: '@param initData'
70        /// @dev deploys a transparent proxy for the given implementation contract
71        function _deployProxy(address proxyAdmin, address impl, bytes memory initData)
72            internal
73:           returns (address)

/// @audit Missing: '@param dp'
/// @audit Missing: '@param _securityCouncilManager'
/// @audit Missing: '@param securityCouncilMemberRemoverGov'
191       /// @dev initializes the removal governor
192       function _initRemovalGov(
193           DeployParams memory dp,
194           ISecurityCouncilManager _securityCouncilManager,
195:          SecurityCouncilMemberRemovalGovernor securityCouncilMemberRemoverGov

/// @audit Missing: '@param dp'
/// @audit Missing: '@param securityCouncilManager'
/// @audit Missing: '@param nomineeElectionGovernor'
/// @audit Missing: '@param memberElectionGovernor'
211       /// @dev initializes the election governors
212       function _initElectionGovernors(
213           DeployParams memory dp,
214           ISecurityCouncilManager securityCouncilManager,
215           SecurityCouncilNomineeElectionGovernor nomineeElectionGovernor,
216:          SecurityCouncilMemberElectionGovernor memberElectionGovernor

```
*GitHub*: [70](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L70-L73), [70](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L70-L73), [70](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L70-L73), [191](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L191-L195), [191](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L191-L195), [191](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L191-L195), [211](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L211-L216), [211](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L211-L216), [211](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L211-L216), [211](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L211-L216)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param address[]'
/// @audit Missing: '@param uint256[]'
/// @audit Missing: '@param callDatas'
/// @audit Missing: '@param bytes32'
112       /// @dev    `GovernorUpgradeable` function to execute a proposal overridden to handle member elections.
113       ///         We know that topNominees() will return a full list.
114       ///         Calls `SecurityCouncilManager.replaceCohort` with the list of nominees.
115       function _execute(
116           uint256 proposalId,
117           address[] memory, /* targets */
118           uint256[] memory, /* values */
119           bytes[] memory callDatas,
120:          bytes32 /* descriptionHash */

/// @audit Missing: '@param uint256'
147       /// @notice Quorum is always 0.
148:      function quorum(uint256) public pure override returns (uint256) {

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param possibleNominee'
152       /// @dev Whether the account is a compliant nominee.
153       ///      checks the SecurityCouncilNomineeElectionGovernor to see if the account is a compliant nominee
154       function _isCompliantNominee(uint256 proposalId, address possibleNominee)
155           internal
156           view
157           override
158:          returns (bool)

/// @audit Missing: '@param proposalId'
163       /// @dev Returns all the compliant (non excluded) nominees for the requested proposal
164       function _compliantNominees(uint256 proposalId)
165           internal
166           view
167           override
168:          returns (address[] memory)

/// @audit Missing: '@param address[]'
/// @audit Missing: '@param uint256[]'
/// @audit Missing: '@param bytes[]'
/// @audit Missing: '@param string'
178       /// @notice Always reverts.
179       /// @dev    `GovernorUpgradeable` function to create a proposal overridden to just revert.
180       ///         We only want proposals to be created via `proposeFromNomineeElectionGovernor`.
181       function propose(address[] memory, uint256[] memory, bytes[] memory, string memory)
182           public
183           virtual
184           override
185:          returns (uint256)

/// @audit Missing: '@param uint256'
/// @audit Missing: '@param uint8'
190       /// @notice Always reverts. Use castVoteWithReasonAndParams instead
191:      function castVote(uint256, uint8) public virtual override returns (uint256) {

/// @audit Missing: '@param uint256'
/// @audit Missing: '@param uint8'
/// @audit Missing: '@param string'
195       /// @notice Always reverts. Use castVoteWithReasonAndParams instead
196       function castVoteWithReason(uint256, uint8, string calldata)
197           public
198           virtual
199           override
200:          returns (uint256)

/// @audit Missing: '@param uint256'
/// @audit Missing: '@param uint8'
/// @audit Missing: '@param bytes32'
205       /// @notice Always reverts. Use castVoteWithReasonAndParamsBySig instead
206       function castVoteBySig(uint256, uint8, uint8, bytes32, bytes32)
207           public
208           virtual
209           override
210:          returns (uint256)

```
*GitHub*: [112](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L112-L120), [112](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L112-L120), [112](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L112-L120), [112](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L112-L120), [112](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L112-L120), [147](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L147-L148), [152](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L152-L158), [152](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L152-L158), [163](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L163-L168), [178](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L178-L185), [178](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L178-L185), [178](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L178-L185), [178](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L178-L185), [190](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L190-L191), [190](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L190-L191), [195](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L195-L200), [195](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L195-L200), [195](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L195-L200), [205](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L205-L210), [205](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L205-L210), [205](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L205-L210)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

/// @audit Missing: '@param _proposalExpirationBlocks'
48        /// @notice Initialize the contract
49        /// @param _voteSuccessNumerator value that with denominator 10_000 determines the ration of for/against votes required for success
50        /// @param _securityCouncilManager security council manager contract
51        /// @param _token The address of the governance token
52        /// @param _owner The DAO (Upgrade Executor); admin over proposal role
53        /// @param _votingDelay The delay between a proposal submission and voting starts
54        /// @param _votingPeriod The period for which the vote lasts
55        /// @param _quorumNumerator The proportion of the circulating supply required to reach a quorum
56        /// @param _proposalThreshold The number of delegated votes required to create a proposal
57        /// @param _minPeriodAfterQuorum The minimum number of blocks available for voting after the quorum is reached
58        function initialize(
59            uint256 _voteSuccessNumerator,
60            ISecurityCouncilManager _securityCouncilManager,
61            IVotesUpgradeable _token,
62            address _owner,
63            uint256 _votingDelay,
64            uint256 _votingPeriod,
65            uint256 _quorumNumerator,
66            uint256 _proposalThreshold,
67            uint64 _minPeriodAfterQuorum,
68            uint256 _proposalExpirationBlocks
69:       ) public initializer {

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param account'
/// @audit Missing: '@param support'
/// @audit Missing: '@param weight'
/// @audit Missing: '@param params'
160       /// @notice A removal proposal if a theshold of all cast votes vote in favor of removal.
161       ///         Thus, abstaining would be exactly equivalent to voting against.
162       ///         To prevent any confusion, abstaining is disallowed.
163       function _countVote(
164           uint256 proposalId,
165           address account,
166           uint8 support,
167           uint256 weight,
168:          bytes memory params

```
*GitHub*: [48](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L48-L69), [160](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L160-L168), [160](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L160-L168), [160](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L160-L168), [160](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L160-L168), [160](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L160-L168)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

/// @audit Missing: '@param params'
102       /// @notice Initializes the governor
103:      function initialize(InitParams memory params) public initializer {

/// @audit Missing: '@param proposalId'
211       /// @notice Put `msg.sender` up for nomination. Must be called before a contender can receive votes.
212       ///         Contenders are expected to control an address than can create a signature that would be a
213       ///         recognised by a Gnosis Safe. They need to be able to do this with this same address on each of the
214       ///         chains where the Security Council is active. It is expected that the nominee vetter will check this
215       ///         during the vetting phase and exclude any contenders which dont meet this criteria.
216       /// @dev    Can be called only while a proposal is active (in voting phase)
217       ///         A contender cannot be a member of the opposite cohort.
218:      function addContender(uint256 proposalId) external {

/// @audit Missing: '@param _nomineeVetter'
245       /// @notice Allows the owner to change the nomineeVetter
246:      function setNomineeVetter(address _nomineeVetter) external onlyGovernance {

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param nominee'
263       /// @notice Allows the nomineeVetter to exclude a noncompliant nominee.
264       /// @dev    Can be called only after a nomninee election proposal has "succeeded" (voting has ended) and before the nominee vetting period has ended.
265       ///         Will revert if the provided account is not a nominee (had less than the required votes).
266       function excludeNominee(uint256 proposalId, address nominee)
267           external
268           onlyNomineeVetter
269:          onlyVettingPeriod(proposalId)

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param account'
285       /// @notice Allows the nomineeVetter to explicitly include a nominee if there are fewer nominees than the target.
286       /// @dev    Can be called only when a proposal is succeeded (voting has ended) and there are fewer compliant nominees than the target.
287       ///         Will revert if the provided account is already a nominee
288       ///         The Constitution must be followed adding nominees. For example this method can be used by the Foundation to add a
289       ///         random member of the outgoing security council, if less than 6 members meet the threshold to become a nominee
290:      function includeNominee(uint256 proposalId, address account) external onlyNomineeVetter {

/// @audit Missing: '@param address[]'
/// @audit Missing: '@param uint256[]'
/// @audit Missing: '@param callDatas'
/// @audit Missing: '@param bytes32'
319       /// @dev    `GovernorUpgradeable` function to execute a proposal overridden to handle nominee elections.
320       ///         Can be called by anyone via `execute` after voting and nominee vetting periods have ended.
321       ///         If the number of compliant nominees is > the target number of nominees,
322       ///         we move on to the next phase by calling the SecurityCouncilMemberElectionGovernor.
323       /// @param  proposalId The id of the proposal
324       function _execute(
325           uint256 proposalId,
326           address[] memory, /* targets */
327           uint256[] memory, /* values */
328           bytes[] memory callDatas,
329:          bytes32 /*descriptionHash*/

/// @audit Missing: '@param proposalId'
382       /// @notice Current number of compliant nominees for the proposal
383:      function compliantNomineeCount(uint256 proposalId) public view returns (uint256) {

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param possibleExcluded'
399       /// @notice returns true if the nominee has been excluded by the nomineeVetter for the given proposal
400:      function isExcluded(uint256 proposalId, address possibleExcluded) public view returns (bool) {

/// @audit Missing: '@param proposalId'
404       /// @notice returns the number of excluded nominees for the given proposal
405:      function excludedNomineeCount(uint256 proposalId) public view returns (uint256) {

/// @audit Missing: '@param address[]'
/// @audit Missing: '@param uint256[]'
/// @audit Missing: '@param bytes[]'
/// @audit Missing: '@param string'
420       /// @notice Always reverts.
421       /// @dev    `GovernorUpgradeable` function to create a proposal overridden to just revert.
422       ///         We only want proposals to be created via `createElection`.
423       function propose(address[] memory, uint256[] memory, bytes[] memory, string memory)
424           public
425           virtual
426           override
427:          returns (uint256)

/// @audit Missing: '@param uint256'
/// @audit Missing: '@param uint8'
432       /// @notice Always reverts. Use castVoteWithReasonAndParams instead
433:      function castVote(uint256, uint8) public virtual override returns (uint256) {

/// @audit Missing: '@param uint256'
/// @audit Missing: '@param uint8'
/// @audit Missing: '@param string'
437       /// @notice Always reverts. Use castVoteWithReasonAndParams instead
438       function castVoteWithReason(uint256, uint8, string calldata)
439           public
440           virtual
441           override
442:          returns (uint256)

/// @audit Missing: '@param uint256'
/// @audit Missing: '@param uint8'
/// @audit Missing: '@param bytes32'
447       /// @notice Always reverts. Use castVoteWithReasonAndParamsBySig instead
448       function castVoteBySig(uint256, uint8, uint8, bytes32, bytes32)
449           public
450           virtual
451           override
452:          returns (uint256)

```
*GitHub*: [102](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L102-L103), [211](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L211-L218), [245](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L245-L246), [263](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L263-L269), [263](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L263-L269), [285](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L285-L290), [285](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L285-L290), [319](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L319-L329), [319](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L319-L329), [319](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L319-L329), [319](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L319-L329), [382](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L382-L383), [399](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L399-L400), [399](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L399-L400), [404](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L404-L405), [420](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L420-L427), [420](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L420-L427), [420](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L420-L427), [420](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L420-L427), [432](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L432-L433), [432](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L432-L433), [437](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L437-L442), [437](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L437-L442), [437](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L437-L442), [447](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L447-L452), [447](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L447-L452), [447](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L447-L452)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

/// @audit Missing: '@param blockNumber'
31        /// @notice Get "circulating" votes supply; i.e., total minus excluded vote exclude address.
32:       function getPastCirculatingSupply(uint256 blockNumber) public view virtual returns (uint256) {

/// @audit Missing: '@param blockNumber'
37        /// @notice Calculates the quorum size, excludes token delegated to the exclude address
38:       function quorum(uint256 blockNumber) public view virtual override returns (uint256) {

```
*GitHub*: [31](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L31-L32), [37](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L37-L38)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

/// @audit Missing: '@param electionIndex'
49        /// @notice Returns the cohort for a given `electionIndex`
50:       function electionIndexToCohort(uint256 electionIndex) public pure returns (Cohort) {

```
*GitHub*: [49](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L49-L50)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

/// @audit Missing: '@param newFullWeightDuration'
76        /// @notice Set the full weight duration
77:       function setFullWeightDuration(uint256 newFullWeightDuration) public onlyGovernance {

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param account'
147       /// @notice Number of votes used by an account for a given proposal
148:      function votesUsed(uint256 proposalId, address account) public view returns (uint256) {

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param nominee'
152       /// @notice Weight received by a nominee for a given proposal
153:      function weightReceived(uint256 proposalId, address nominee) public view returns (uint256) {

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param account'
157       /// @notice Whether the account has voted any amount for any nominee in the proposal
158:      function hasVoted(uint256 proposalId, address account) public view override returns (bool) {

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param blockNumber'
/// @audit Missing: '@param votes'
222       /// @notice Returns the weight of a vote for a given proposal, block number, and number of votes.
223       ///         Each vote has weight 1 until the fullWeightVotingDeadline is reached, after which each vote has linearly
224       ///         deacreasing weight, reaching 0 at the proposalDeadline.
225       function votesToWeight(uint256 proposalId, uint256 blockNumber, uint256 votes)
226           public
227           view
228:          returns (uint240)

/// @audit Missing: '@param x'
258       /// @notice Downcasts a uint256 to a uint240, reverting if the input is too large
259:      function _downCast(uint256 x) internal pure returns (uint240) {

/// @audit Missing: '@param uint256'
266       /// @notice True, since there is no minimum quorum
267:      function _quorumReached(uint256) internal pure override returns (bool) {

/// @audit Missing: '@param uint256'
271       /// @notice True, since an election can only be only started if there are enough nominees
272       ///         and candidates cannot be excluded after the election has started
273:      function _voteSucceeded(uint256) internal pure override returns (bool) {

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param possibleNominee'
277       /// @dev Whether the possibleNominee is a compliant nominee for the given proposal
278       function _isCompliantNominee(uint256 proposalId, address possibleNominee)
279           internal
280           view
281           virtual
282:          returns (bool);

/// @audit Missing: '@param proposalId'
284       /// @dev The list of all compliant (non excluded) nominees for the requested proposal
285       function _compliantNominees(uint256 proposalId)
286           internal
287           view
288           virtual
289:          returns (address[] memory);

```
*GitHub*: [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L76-L77), [147](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L147-L148), [147](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L147-L148), [152](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L152-L153), [152](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L152-L153), [157](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L157-L158), [157](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L157-L158), [222](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L222-L228), [222](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L222-L228), [222](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L222-L228), [258](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L258-L259), [266](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L266-L267), [271](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L271-L273), [277](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L277-L282), [277](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L277-L282), [284](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L284-L289)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param account'
120       /// @dev Transitions an account to being a nominee
121:      function _addNominee(uint256 proposalId, address account) internal {

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param account'
132       /// @notice Whether the account has voted any amount for any contender in the proposal
133:      function hasVoted(uint256 proposalId, address account) public view override returns (bool) {

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param contender'
137       /// @notice Whether the contender has enough votes to be a nominee
138:      function isNominee(uint256 proposalId, address contender) public view returns (bool) {

/// @audit Missing: '@param proposalId'
142       /// @notice The number of nominees for a given proposal
143:      function nomineeCount(uint256 proposalId) public view returns (uint256) {

/// @audit Missing: '@param proposalId'
147       /// @notice The list of nominees for a given proposal
148:      function nominees(uint256 proposalId) public view returns (address[] memory) {

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param account'
152       /// @notice The amount of votes an account has used for a given proposal
153:      function votesUsed(uint256 proposalId, address account) public view returns (uint256) {

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param contender'
157       /// @notice The amount of votes a contender has received for a given proposal
158:      function votesReceived(uint256 proposalId, address contender) public view returns (uint256) {

/// @audit Missing: '@param proposalId'
/// @audit Missing: '@param possibleContender'
162       /// @dev Whether the account is a contender for the proposal
163       function isContender(uint256 proposalId, address possibleContender)
164           public
165           view
166           virtual
167:          returns (bool);

/// @audit Missing: '@param uint256'
169       /// @dev there is no minimum quorum for nominations proposals to pass, so we just return true
170:      function _quorumReached(uint256) internal pure override returns (bool) {

/// @audit Missing: '@param uint256'
174       /// @dev the vote always succeeds, so we just return true
175:      function _voteSucceeded(uint256) internal pure override returns (bool) {

```
*GitHub*: [120](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L120-L121), [120](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L120-L121), [132](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L132-L133), [132](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L132-L133), [137](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L137-L138), [137](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L137-L138), [142](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L142-L143), [147](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L147-L148), [152](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L152-L153), [152](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L152-L153), [157](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L157-L158), [157](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L157-L158), [162](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L162-L167), [162](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L162-L167), [169](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L169-L170), [174](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L174-L175)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

/// @audit Missing: '@param _firstNominationStartDate'
/// @audit Missing: '@param _nomineeVettingDuration'
26        /// @notice Initialize the timing module
27        /// @dev    Checks to make sure the start date is in the future and is valid
28        function __SecurityCouncilNomineeElectionGovernorTiming_init(
29            Date memory _firstNominationStartDate,
30            uint256 _nomineeVettingDuration
31:       ) internal onlyInitializing {

/// @audit Missing: '@param proposalId'
68        /// @notice Deadline for the nominee vetting period for a given `proposalId`
69:       function proposalVettingDeadline(uint256 proposalId) public view returns (uint256) {

```
*GitHub*: [26](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L26-L31), [26](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L26-L31), [68](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L68-L69)

</details>

### [N&#x2011;17] NatSpec `@return` argument is missing


*There are 59 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

/// @audit Missing: '@return'
91        /// @notice Check if an upgrade executor exists for the supplied chain id
92        /// @param _chainId ChainId for target UpExecLocation
93:       function upExecLocationExists(uint256 _chainId) public view returns (bool) {

/// @audit Missing: '@return'
103       /// @param predecessor      A predecessor value for the l1 timelock operation
104       /// @param timelockSalt     A salt for the l1 timelock operation
105       function createActionRouteData(
106           uint256[] memory chainIds,
107           address[] memory actionAddresses,
108           uint256[] memory actionValues,
109           bytes[] memory actionDatas,
110           bytes32 predecessor,
111           bytes32 timelockSalt
112:      ) public view returns (address, bytes memory) {

/// @audit Missing: '@return'
184       /// @param actionAddresses  Addresses of the action contracts to be called
185       /// @param timelockSalt     A salt for the l1 timelock operation
186       function createActionRouteDataWithDefaults(
187           uint256[] memory chainIds,
188           address[] memory actionAddresses,
189           bytes32 timelockSalt
190:      ) public view returns (address, bytes memory) {

```
*GitHub*: [91](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L91-L93), [103](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L103-L112), [184](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L184-L190)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

/// @audit Missing: '@return'
29        /// @notice Gets a value from the store
30        /// @dev    Combines the provided key with the action contract id
31:       function _get(uint256 key) internal view returns (uint256) {

/// @audit Missing: '@return'
35        /// @notice This contract uses a composite key of the provided key and the action contract id.
36        ///         This function can be used to calculate the composite key
37:       function computeKey(uint256 key) public view returns (uint256) {

```
*GitHub*: [29](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L29-L31), [35](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L35-L37)

```solidity
File: src/gov-action-contracts/execution-record/KeyValueStore.sol

/// @audit Missing: '@return'
15        /// @notice Get a value from the store for the current msg.sender
16:       function get(uint256 key) external view returns (uint256) {

/// @audit Missing: '@return'
20        /// @notice Get a value from the store for any sender
21:       function get(address owner, uint256 key) external view returns (uint256) {

/// @audit Missing: '@return'
25        /// @notice Compute the composite key for a specific user
26:       function computeKey(address owner, uint256 key) public pure returns (uint256) {

```
*GitHub*: [15](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L15-L16), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L20-L21), [25](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L25-L26)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

/// @audit Missing: '@return'
70        /// @dev deploys a transparent proxy for the given implementation contract
71        function _deployProxy(address proxyAdmin, address impl, bytes memory initData)
72            internal
73:           returns (address)

/// @audit Missing: '@return'
79        /// @param  dp the deployment parameters
80        /// @param  impls contract implementations to deploy proxies for
81        function deploy(DeployParams memory dp, ContractImplementations memory impls)
82            external
83            onlyOwner
84:           returns (DeployedContracts memory)

```
*GitHub*: [70](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L70-L73), [79](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L79-L84)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

/// @audit Missing: '@return'
136       /// @dev    Since we only want proposals to be created via `proposeFromNomineeElectionGovernor`, we set the proposal threshold to 0.
137       ///         `proposeFromNomineeElectionGovernor` determines the rules for creating a proposal.
138       function proposalThreshold()
139           public
140           pure
141           override(GovernorSettingsUpgradeable, GovernorUpgradeable)
142:          returns (uint256)

/// @audit Missing: '@return'
147       /// @notice Quorum is always 0.
148:      function quorum(uint256) public pure override returns (uint256) {

/// @audit Missing: '@return'
152       /// @dev Whether the account is a compliant nominee.
153       ///      checks the SecurityCouncilNomineeElectionGovernor to see if the account is a compliant nominee
154       function _isCompliantNominee(uint256 proposalId, address possibleNominee)
155           internal
156           view
157           override
158:          returns (bool)

/// @audit Missing: '@return'
163       /// @dev Returns all the compliant (non excluded) nominees for the requested proposal
164       function _compliantNominees(uint256 proposalId)
165           internal
166           view
167           override
168:          returns (address[] memory)

/// @audit Missing: '@return'
178       /// @notice Always reverts.
179       /// @dev    `GovernorUpgradeable` function to create a proposal overridden to just revert.
180       ///         We only want proposals to be created via `proposeFromNomineeElectionGovernor`.
181       function propose(address[] memory, uint256[] memory, bytes[] memory, string memory)
182           public
183           virtual
184           override
185:          returns (uint256)

/// @audit Missing: '@return'
190       /// @notice Always reverts. Use castVoteWithReasonAndParams instead
191:      function castVote(uint256, uint8) public virtual override returns (uint256) {

/// @audit Missing: '@return'
195       /// @notice Always reverts. Use castVoteWithReasonAndParams instead
196       function castVoteWithReason(uint256, uint8, string calldata)
197           public
198           virtual
199           override
200:          returns (uint256)

/// @audit Missing: '@return'
205       /// @notice Always reverts. Use castVoteWithReasonAndParamsBySig instead
206       function castVoteBySig(uint256, uint8, uint8, bytes32, bytes32)
207           public
208           virtual
209           override
210:          returns (uint256)

```
*GitHub*: [136](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L136-L142), [147](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L147-L148), [152](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L152-L158), [163](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L163-L168), [178](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L178-L185), [190](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L190-L191), [195](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L195-L200), [205](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L205-L210)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

/// @audit Missing: '@return'
104       /// @param calldatas Operation calldata; must be [removeMember with address argument]
105       /// @param description rationale for member removal
106       function propose(
107           address[] memory targets,
108           uint256[] memory values,
109           bytes[] memory calldatas,
110           string memory description
111:      ) public override returns (uint256) {

/// @audit Missing: '@return'
145       /// @notice override to allow for required vote success ratio that isn't 0.5
146       /// @param proposalId target proposal id
147       function _voteSucceeded(uint256 proposalId)
148           internal
149           view
150           virtual
151           override(GovernorCountingSimpleUpgradeable, GovernorUpgradeable)
152:          returns (bool)

```
*GitHub*: [104](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L104-L111), [145](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L145-L152)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

/// @audit Missing: '@return'
355       /// @dev    Since we only want proposals to be created via `createElection`, we set the proposal threshold to 0.
356       ///         `createElection` determines the rules for creating a proposal.
357       function proposalThreshold()
358           public
359           view
360           virtual
361           override(GovernorSettingsUpgradeable, GovernorUpgradeable)
362:          returns (uint256)

/// @audit Missing: '@return'
382       /// @notice Current number of compliant nominees for the proposal
383:      function compliantNomineeCount(uint256 proposalId) public view returns (uint256) {

/// @audit Missing: '@return'
387       /// @notice Returns cohort currently up for election
388:      function currentCohort() public view returns (Cohort) {

/// @audit Missing: '@return'
393       /// @notice Returns cohort not currently up for election
394:      function otherCohort() public view returns (Cohort) {

/// @audit Missing: '@return'
399       /// @notice returns true if the nominee has been excluded by the nomineeVetter for the given proposal
400:      function isExcluded(uint256 proposalId, address possibleExcluded) public view returns (bool) {

/// @audit Missing: '@return'
404       /// @notice returns the number of excluded nominees for the given proposal
405:      function excludedNomineeCount(uint256 proposalId) public view returns (uint256) {

/// @audit Missing: '@return'
420       /// @notice Always reverts.
421       /// @dev    `GovernorUpgradeable` function to create a proposal overridden to just revert.
422       ///         We only want proposals to be created via `createElection`.
423       function propose(address[] memory, uint256[] memory, bytes[] memory, string memory)
424           public
425           virtual
426           override
427:          returns (uint256)

/// @audit Missing: '@return'
432       /// @notice Always reverts. Use castVoteWithReasonAndParams instead
433:      function castVote(uint256, uint8) public virtual override returns (uint256) {

/// @audit Missing: '@return'
437       /// @notice Always reverts. Use castVoteWithReasonAndParams instead
438       function castVoteWithReason(uint256, uint8, string calldata)
439           public
440           virtual
441           override
442:          returns (uint256)

/// @audit Missing: '@return'
447       /// @notice Always reverts. Use castVoteWithReasonAndParamsBySig instead
448       function castVoteBySig(uint256, uint8, uint8, bytes32, bytes32)
449           public
450           virtual
451           override
452:          returns (uint256)

```
*GitHub*: [355](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L355-L362), [382](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L382-L383), [387](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L387-L388), [393](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L393-L394), [399](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L399-L400), [404](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L404-L405), [420](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L420-L427), [432](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L432-L433), [437](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L437-L442), [447](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L447-L452)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

/// @audit Missing: '@return'
31        /// @notice Get "circulating" votes supply; i.e., total minus excluded vote exclude address.
32:       function getPastCirculatingSupply(uint256 blockNumber) public view virtual returns (uint256) {

/// @audit Missing: '@return'
37        /// @notice Calculates the quorum size, excludes token delegated to the exclude address
38:       function quorum(uint256 blockNumber) public view virtual override returns (uint256) {

```
*GitHub*: [31](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L31-L32), [37](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L37-L38)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

/// @audit Missing: '@return'
32        /// @notice Extract the election index from the call data
33        /// @param callDatas The proposal call data
34:       function extractElectionIndex(bytes[] memory callDatas) internal pure returns (uint256) {

/// @audit Missing: '@return'
38        /// @notice Proposal descriptions are created deterministically from the election index
39        /// @param electionIndex The index of the election to create a proposal for
40        function electionIndexToDescription(uint256 electionIndex)
41            public
42            pure
43:           returns (string memory)

/// @audit Missing: '@return'
49        /// @notice Returns the cohort for a given `electionIndex`
50:       function electionIndexToCohort(uint256 electionIndex) public pure returns (Cohort) {

```
*GitHub*: [32](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L32-L34), [38](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L38-L43), [49](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L49-L50)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

/// @audit Missing: '@return'
147       /// @notice Number of votes used by an account for a given proposal
148:      function votesUsed(uint256 proposalId, address account) public view returns (uint256) {

/// @audit Missing: '@return'
152       /// @notice Weight received by a nominee for a given proposal
153:      function weightReceived(uint256 proposalId, address nominee) public view returns (uint256) {

/// @audit Missing: '@return'
157       /// @notice Whether the account has voted any amount for any nominee in the proposal
158:      function hasVoted(uint256 proposalId, address account) public view override returns (bool) {

/// @audit Missing: '@return'
162       /// @notice The deadline after which voting weight will linearly decrease
163       /// @param proposalId The proposal to check the deadline for
164:      function fullWeightVotingDeadline(uint256 proposalId) public view returns (uint256) {

/// @audit Missing: '@return'
175       ///         Absolute worst case, this function uses 4502345 with 500 nominees, or about 9k gas per nominee (when called externally).
176       /// @param proposalId The proposal to find the top nominees for
177:      function topNominees(uint256 proposalId) public view returns (address[] memory) {

/// @audit Missing: '@return'
189       /// @param weights  The weights of the nominees
190       /// @param k        The number of nominees to select
191       function selectTopNominees(address[] memory nominees, uint240[] memory weights, uint256 k)
192           public
193           pure
194:          returns (address[] memory)

/// @audit Missing: '@return'
222       /// @notice Returns the weight of a vote for a given proposal, block number, and number of votes.
223       ///         Each vote has weight 1 until the fullWeightVotingDeadline is reached, after which each vote has linearly
224       ///         deacreasing weight, reaching 0 at the proposalDeadline.
225       function votesToWeight(uint256 proposalId, uint256 blockNumber, uint256 votes)
226           public
227           view
228:          returns (uint240)

/// @audit Missing: '@return'
258       /// @notice Downcasts a uint256 to a uint240, reverting if the input is too large
259:      function _downCast(uint256 x) internal pure returns (uint240) {

/// @audit Missing: '@return'
266       /// @notice True, since there is no minimum quorum
267:      function _quorumReached(uint256) internal pure override returns (bool) {

/// @audit Missing: '@return'
271       /// @notice True, since an election can only be only started if there are enough nominees
272       ///         and candidates cannot be excluded after the election has started
273:      function _voteSucceeded(uint256) internal pure override returns (bool) {

/// @audit Missing: '@return'
277       /// @dev Whether the possibleNominee is a compliant nominee for the given proposal
278       function _isCompliantNominee(uint256 proposalId, address possibleNominee)
279           internal
280           view
281           virtual
282:          returns (bool);

/// @audit Missing: '@return'
284       /// @dev The list of all compliant (non excluded) nominees for the requested proposal
285       function _compliantNominees(uint256 proposalId)
286           internal
287           view
288           virtual
289:          returns (address[] memory);

/// @audit Missing: '@return'
291       /// @dev The target number of members to elect
292:      function _targetMemberCount() internal view virtual returns (uint256);

```
*GitHub*: [147](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L147-L148), [152](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L152-L153), [157](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L157-L158), [162](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L162-L164), [175](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L175-L177), [189](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L189-L194), [222](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L222-L228), [258](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L258-L259), [266](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L266-L267), [271](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L271-L273), [277](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L277-L282), [284](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L284-L289), [291](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L291-L292)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

/// @audit Missing: '@return'
132       /// @notice Whether the account has voted any amount for any contender in the proposal
133:      function hasVoted(uint256 proposalId, address account) public view override returns (bool) {

/// @audit Missing: '@return'
137       /// @notice Whether the contender has enough votes to be a nominee
138:      function isNominee(uint256 proposalId, address contender) public view returns (bool) {

/// @audit Missing: '@return'
142       /// @notice The number of nominees for a given proposal
143:      function nomineeCount(uint256 proposalId) public view returns (uint256) {

/// @audit Missing: '@return'
147       /// @notice The list of nominees for a given proposal
148:      function nominees(uint256 proposalId) public view returns (address[] memory) {

/// @audit Missing: '@return'
152       /// @notice The amount of votes an account has used for a given proposal
153:      function votesUsed(uint256 proposalId, address account) public view returns (uint256) {

/// @audit Missing: '@return'
157       /// @notice The amount of votes a contender has received for a given proposal
158:      function votesReceived(uint256 proposalId, address contender) public view returns (uint256) {

/// @audit Missing: '@return'
162       /// @dev Whether the account is a contender for the proposal
163       function isContender(uint256 proposalId, address possibleContender)
164           public
165           view
166           virtual
167:          returns (bool);

/// @audit Missing: '@return'
169       /// @dev there is no minimum quorum for nominations proposals to pass, so we just return true
170:      function _quorumReached(uint256) internal pure override returns (bool) {

/// @audit Missing: '@return'
174       /// @dev the vote always succeeds, so we just return true
175:      function _voteSucceeded(uint256) internal pure override returns (bool) {

```
*GitHub*: [132](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L132-L133), [137](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L137-L138), [142](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L142-L143), [147](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L147-L148), [152](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L152-L153), [157](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L157-L158), [162](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L162-L167), [169](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L169-L170), [174](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L174-L175)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

/// @audit Missing: '@return'
68        /// @notice Deadline for the nominee vetting period for a given `proposalId`
69:       function proposalVettingDeadline(uint256 proposalId) public view returns (uint256) {

/// @audit Missing: '@return'
73        /// @notice Start timestamp of an election
74        /// @param electionIndex The index of the election
75:       function electionToTimestamp(uint256 electionIndex) public view returns (uint256) {

```
*GitHub*: [68](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L68-L69), [73](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L73-L75)

</details>

### [N&#x2011;18] Function ordering does not follow the Solidity style guide
According to the [Solidity style guide](https://docs.soliditylang.org/en/v0.8.17/style-guide.html#order-of-functions), functions should be laid out in the following order :`constructor()`, `receive()`, `fallback()`, `external`, `public`, `internal`, `private`, but the cases below do not follow this pattern

*There are 26 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

/// @audit perform() came earlier
67        constructor(
68            ChainAndUpExecLocation[] memory _upgradeExecutors,
69            address _l1ArbitrumTimelock,
70:           uint256 _l1TimelockMinDelay

```
*GitHub*: [67](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L67-L70)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

/// @audit requireSafesEquivalent() came earlier
52        function areAddressArraysEqual(address[] memory array1, address[] memory array2)
53            public
54            pure
55:           returns (bool)

```
*GitHub*: [52](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L52-L55)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

/// @audit _get() came earlier
37:       function computeKey(uint256 key) public view returns (uint256) {

```
*GitHub*: [37](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L37)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

/// @audit _removeMemberFromCohortArray() came earlier
176:      function addMember(address _newMember, Cohort _cohort) external onlyRole(MEMBER_ADDER_ROLE) {

/// @audit _addSecurityCouncil() came earlier
271       function addSecurityCouncil(SecurityCouncilData memory _securityCouncilData)
272           external
273:          onlyRole(DEFAULT_ADMIN_ROLE)

/// @audit _setUpgradeExecRouteBuilder() came earlier
327:      function getFirstCohort() external view returns (address[] memory) {

/// @audit cohortIncludes() came earlier
370       function generateSalt(address[] memory _members, uint256 nonce)
371           external
372           pure
373:          returns (bytes32)

```
*GitHub*: [176](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L176), [271](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L271-L273), [327](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L327), [370](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L370-L373)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

/// @audit _removeMember() came earlier
97        function getPrevOwner(IGnosisSafe securityCouncil, address _owner)
98            public
99            view
100:          returns (address)

```
*GitHub*: [97](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L97-L100)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

/// @audit _deployProxy() came earlier
81        function deploy(DeployParams memory dp, ContractImplementations memory impls)
82            external
83            onlyOwner
84:           returns (DeployedContracts memory)

```
*GitHub*: [81](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L81-L84)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

/// @audit initialize() came earlier
86        function proposeFromNomineeElectionGovernor(uint256 electionIndex)
87            external
88            onlyNomineeElectionGovernor
89:           returns (uint256)

/// @audit _execute() came earlier
138       function proposalThreshold()
139           public
140           pure
141           override(GovernorSettingsUpgradeable, GovernorUpgradeable)
142:          returns (uint256)

/// @audit _targetMemberCount() came earlier
181       function propose(address[] memory, uint256[] memory, bytes[] memory, string memory)
182           public
183           virtual
184           override
185:          returns (uint256)

```
*GitHub*: [86](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L86-L89), [138](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L138-L142), [181](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L181-L185)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

/// @audit initialize() came earlier
90        function separateSelector(bytes calldata calldataWithSelector)
91            external
92            pure
93:           returns (bytes4, bytes memory)

/// @audit _countVote() came earlier
178:      function setVoteSuccessNumerator(uint256 _voteSuccessNumerator) public onlyOwner {

/// @audit _setVoteSuccessNumerator() came earlier
191       function COUNTING_MODE()
192           public
193           pure
194           virtual
195           override(GovernorCountingSimpleUpgradeable, IGovernorUpgradeable)
196:          returns (string memory)

/// @audit COUNTING_MODE() came earlier
203       function relay(address target, uint256 value, bytes calldata data)
204           external
205           virtual
206           override
207:          onlyOwner

/// @audit _castVote() came earlier
240       function proposalDeadline(uint256 proposalId)
241           public
242           view
243           override(GovernorUpgradeable, GovernorPreventLateQuorumUpgradeable)
244:          returns (uint256)

```
*GitHub*: [90](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L90-L93), [178](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L178), [191](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L191-L196), [203](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L203-L207), [240](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L240-L244)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

/// @audit initialize() came earlier
161:      function createElection() external returns (uint256 proposalId) {

/// @audit _requireLastMemberElectionHasExecuted() came earlier
218:      function addContender(uint256 proposalId) external {

/// @audit _execute() came earlier
357       function proposalThreshold()
358           public
359           view
360           virtual
361           override(GovernorSettingsUpgradeable, GovernorUpgradeable)
362:          returns (uint256)

```
*GitHub*: [161](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L161), [218](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L218), [357](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L357-L362)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

/// @audit __ArbitrumGovernorVotesQuorumFraction_init() came earlier
32:       function getPastCirculatingSupply(uint256 blockNumber) public view virtual returns (uint256) {

```
*GitHub*: [32](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L32)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

/// @audit extractElectionIndex() came earlier
40        function electionIndexToDescription(uint256 electionIndex)
41            public
42            pure
43:           returns (string memory)

```
*GitHub*: [40](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L40-L43)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

/// @audit __SecurityCouncilMemberElectionGovernorCounting_init() came earlier
77:       function setFullWeightDuration(uint256 newFullWeightDuration) public onlyGovernance {

/// @audit _countVote() came earlier
143:      function COUNTING_MODE() public pure virtual override returns (string memory) {

```
*GitHub*: [77](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L77), [143](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L143)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

/// @audit _addNominee() came earlier
128:      function COUNTING_MODE() public pure virtual override returns (string memory) {

```
*GitHub*: [128](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L128)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

/// @audit __SecurityCouncilNomineeElectionGovernorTiming_init() came earlier
69:       function proposalVettingDeadline(uint256 proposalId) public view returns (uint256) {

```
*GitHub*: [69](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L69)

</details>

### [N&#x2011;19] Contract does not follow the Solidity style guide's suggested layout ordering
The [style guide](https://docs.soliditylang.org/en/v0.8.16/style-guide.html#order-of-layout) says that, within a contract, the ordering should be 1) Type declarations, 2) State variables, 3) Events, 4) Modifiers, and 5) Functions, but the contract(s) below do not follow this ordering

*There are 10 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

/// @audit function perform came earlier
47:       address public constant RETRYABLE_TICKET_MAGIC = 0xa723C008e76E379c55599D2E4d93879BeaFDa79C;

```
*GitHub*: [47](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L47)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

/// @audit event UpgradeExecRouteBuilderSet came earlier
51:       address[] internal firstCohort;

```
*GitHub*: [51](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L51)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

/// @audit event UpdateNonceTooLow came earlier
19:       address public constant SENTINEL_OWNERS = address(0x1);

```
*GitHub*: [19](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L19)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

/// @audit function initialize came earlier
78        modifier onlyNomineeElectionGovernor() {
79            if (msg.sender != address(nomineeElectionGovernor)) {
80                revert OnlyNomineeElectionGovernor();
81            }
82            _;
83:       }

```
*GitHub*: [78](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L78-L83)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

/// @audit function initialize came earlier
134       modifier onlyNomineeVetter() {
135           if (msg.sender != nomineeVetter) {
136               revert OnlyNomineeVetter();
137           }
138           _;
139:      }

```
*GitHub*: [134](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L134-L139)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

/// @audit function quorumDenominator came earlier
54:       uint256[50] private __gap;

```
*GitHub*: [54](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L54)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

/// @audit function electionIndexToCohort came earlier
59:       uint256[50] private __gap;

```
*GitHub*: [59](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L59)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

/// @audit function _targetMemberCount came earlier
299:      uint256[48] private __gap;

```
*GitHub*: [299](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L299)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

/// @audit function _voteSucceeded came earlier
184:      uint256[49] private __gap;

```
*GitHub*: [184](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L184)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

/// @audit function electionToTimestamp came earlier
101:      uint256[45] private __gap;

```
*GitHub*: [101](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L101)

</details>

### [N&#x2011;20] Interfaces should be indicated with an `I` prefix in the contract name


*There is one instance of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

9:    interface DefaultGovAction {

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L9)


### [N&#x2011;21] Control structures do not follow the Solidity Style Guide
See the [control structures](https://docs.soliditylang.org/en/latest/style-guide.html#control-structures) section of the Solidity Style Guide

*There are 32 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

105       function createActionRouteData(
106:          uint256[] memory chainIds,

186       function createActionRouteDataWithDefaults(
187:          uint256[] memory chainIds,

```
*GitHub*: [105](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L105-L106), [186](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L186-L187)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

8         function replaceEmergencySecurityCouncil(
9:            IGnosisSafe _prevSecurityCouncil,

29        function requireSafesEquivalent(
30:           IGnosisSafe _safe1,

```
*GitHub*: [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L8-L9), [29](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L29-L30)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

15        /// @notice A unique id for this action contract
16:       bytes32 public immutable actionContractId;

```
*GitHub*: [15](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L15-L16)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

236           if (
237:              _securityCouncilData.updateAction == address(0)

254               if (
255:                  existantSecurityCouncil.chainId == _securityCouncilData.chainId

286               if (
287:                  securityCouncilData.securityCouncil == _securityCouncilData.securityCouncil

89        function initialize(
90:           address[] memory _firstCohort,

23    ///         An example of this could be replacing a member whilst there is an ongoing election. This contract
24:   ///         ensures that a member cannot be in both cohorts, so if a cohort is elected but just prior the security

```
*GitHub*: [236](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L236-L237), [254](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L254-L255), [286](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L286-L287), [89](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L89-L90), [23](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L23-L24)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

128           if (
129:              !securityCouncil.execTransactionFromModule(

```
*GitHub*: [128](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L128-L129)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

15        function filterAddressesWithExcludeList(
16:           address[] memory input,

```
*GitHub*: [15](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L15-L16)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

192       function _initRemovalGov(
193:          DeployParams memory dp,

212       function _initElectionGovernors(
213:          DeployParams memory dp,

70        /// @dev deploys a transparent proxy for the given implementation contract
71:       function _deployProxy(address proxyAdmin, address impl, bytes memory initData)

```
*GitHub*: [192](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L192-L193), [212](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L212-L213), [70](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L70-L71)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

48        function initialize(
49:           ISecurityCouncilNomineeElectionGovernor _nomineeElectionGovernor,

115       function _execute(
116:          uint256 proposalId,

```
*GitHub*: [48](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L48-L49), [115](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L115-L116)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

134           if (
135:              !securityCouncilManager.firstCohortIncludes(memberToRemove)

58        function initialize(
59:           uint256 _voteSuccessNumerator,

106       function propose(
107:          address[] memory targets,

163       function _countVote(
164:          uint256 proposalId,

223       function _castVote(
224:          uint256 proposalId,

48        /// @notice Initialize the contract
49:       /// @param _voteSuccessNumerator value that with denominator 10_000 determines the ration of for/against votes required for success

50        /// @param _securityCouncilManager security council manager contract
51:       /// @param _token The address of the governance token

```
*GitHub*: [134](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L134-L135), [58](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L58-L59), [106](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L106-L107), [163](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L163-L164), [223](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L223-L224), [48](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L48-L49), [50](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L50-L51)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

202           if (
203:              IGovernorUpgradeable(address(securityCouncilMemberElectionGovernor)).state(

324       function _execute(
325:          uint256 proposalId,

32        /// @param securityCouncilManager Security council manager contract
33:       /// @param token Token used for voting

63        /// @notice Security council manager contract
64:       /// @dev    Used to execute the election result immediately if <= 6 compliant nominees are chosen

67        /// @notice Security council member election governor contract
68:       ISecurityCouncilMemberElectionGovernor public securityCouncilMemberElectionGovernor;

```
*GitHub*: [202](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L202-L203), [324](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L324-L325), [32](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L32-L33), [63](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L63-L64), [67](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L67-L68)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

95        function _countVote(
96:           uint256 proposalId,

```
*GitHub*: [95](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L95-L96)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

62        function _countVote(
63:           uint256 proposalId,

```
*GitHub*: [62](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L62-L63)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

28        function __SecurityCouncilNomineeElectionGovernorTiming_init(
29:           Date memory _firstNominationStartDate,

```
*GitHub*: [28](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L28-L29)

</details>

### [N&#x2011;22] Top-level declarations should be separated by at least two lines


*There are 26 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

46        }
47    
48:       function perform() external {

```
*GitHub*: [46](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L46-L48)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

28        }
29    
30:       function perform() external {

```
*GitHub*: [28](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L28-L30)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

23        }
24    
25:       function perform() external {

```
*GitHub*: [23](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L23-L25)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

27        }
28    
29:       function requireSafesEquivalent(

50        }
51    
52:       function areAddressArraysEqual(address[] memory array1, address[] memory array2)

```
*GitHub*: [27](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L27-L29), [50](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L50-L52)

```solidity
File: src/gov-action-contracts/execution-record/KeyValueStore.sol

28        }
29    
30:       function _get(address owner, uint256 key) internal view returns (uint256) {

```
*GitHub*: [28](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L28-L30)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

87        }
88    
89:       function initialize(

141       }
142   
143:      function _addMemberToCohortArray(address _newMember, Cohort _cohort) internal {

159       }
160   
161:      function _removeMemberFromCohortArray(address _member) internal returns (Cohort) {

216       }
217   
218:      function _swapMembers(address _addressToRemove, address _addressToAdd)

229       }
230   
231:      function _addSecurityCouncil(SecurityCouncilData memory _securityCouncilData) internal {

313       }
314   
315:      function _setUpgradeExecRouteBuilder(UpgradeExecRouteBuilder _router) internal {

```
*GitHub*: [87](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L87-L89), [141](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L141-L143), [159](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L159-L161), [216](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L216-L218), [229](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L229-L231), [313](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L313-L315)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

74        }
75    
76:       function _addMember(IGnosisSafe securityCouncil, address _member, uint256 _threshold)

83        }
84    
85:       function _removeMember(IGnosisSafe securityCouncil, address _member, uint256 _threshold)

95        }
96    
97:       function getPrevOwner(IGnosisSafe securityCouncil, address _owner)

116       }
117   
118:      function getUpdateNonce(address securityCouncil) public view returns (uint256) {

120       }
121   
122:      function _setUpdateNonce(address securityCouncil, uint256 nonce) internal {

```
*GitHub*: [74](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L74-L76), [83](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L83-L85), [95](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L95-L97), [116](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L116-L118), [120](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L120-L122)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

102       /// @dev    See {L2ArbitrumGovernor-relay}
103:      function relay(address target, uint256 value, bytes calldata data)

110       }
111   
112:      /// @dev    `GovernorUpgradeable` function to execute a proposal overridden to handle member elections.

```
*GitHub*: [102](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L102-L103), [110](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L110-L112)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

84        }
85    
86:       /// @notice Assumes the passed in bytes is an abi encoded function call, and splits into the selector and the rest

180       }
181   
182:      function _setVoteSuccessNumerator(uint256 _voteSuccessNumerator) internal {

202       /// @dev    See {L2ArbitrumGovernor-relay}
203:      function relay(address target, uint256 value, bytes calldata data)

247       }
248   
249:      function state(uint256 proposalId)

```
*GitHub*: [84](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L84-L86), [180](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L180-L182), [202](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L202-L203), [247](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L247-L249)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

253       /// @dev    See {L2ArbitrumGovernor-relay}
254:      function relay(address target, uint256 value, bytes calldata data)

317       }
318   
319:      /// @dev    `GovernorUpgradeable` function to execute a proposal overridden to handle nominee elections.

```
*GitHub*: [253](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L253-L254), [317](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L317-L319)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

52        function __SecurityCouncilNomineeElectionGovernorCounting_init() internal onlyInitializing {}
53    
54:       /// @dev This function is responsible for counting votes when they are cast.

```
*GitHub*: [52](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L52-L54)

</details>

### [N&#x2011;23] Consider using `delete` rather than assigning zero/false to clear values
The `delete` keyword more closely matches the semantics of what is being done, and draws more attention to the changing of state, which may lead to a more thorough audit of its associated logic

*There is one instance of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

150:                  schedValues[i] = 0;

```
*GitHub*: [150](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L150)


### [N&#x2011;24] Contracts should have full test coverage
While 100% code coverage does not guarantee that there are no bugs, it often will catch easy-to-find bugs, and will ensure that there are fewer regressions when the code invariably has to be modified. Furthermore, in order to get full coverage, code authors will often have to re-organize their code so that it is more modular, so that each component can be tested separately, which reduces interdependencies between modules and layers, and makes for code that is easier to reason about and audit.

*There is one instance of this issue:*

```solidity
File: Various Files


```


### [N&#x2011;25] Large or complicated code bases should implement invariant tests
Large code bases, or code with lots of inline-assembly, complicated math, or complicated interactions between multiple contracts, should implement [invariant fuzzing tests](https://medium.com/coinmonks/smart-contract-fuzzing-d9b88e0b0a05). Invariant fuzzers such as Echidna require the test writer to come up with invariants which should not be violated under any circumstances, and the fuzzer tests various inputs and function calls to ensure that the invariants always hold. Even code with 100% code coverage can still have bugs due to the order of the operations a user performs, and invariant fuzzers, with properly and extensively-written invariants, can close this testing gap significantly.

*There is one instance of this issue:*

```solidity
File: Various Files


```


### [N&#x2011;26] Enable IR-based code generation
By using `--via-ir` or `{"viaIR": true}`, the compiler is able to use more advanced [multi-function optimizations](https://docs.soliditylang.org/en/v0.8.17/ir-breaking-changes.html#solidity-ir-based-codegen-changes), for extra gas savings.

*There is one instance of this issue:*

```solidity
File: Various Files


```


### [N&#x2011;27] Custom errors should be used rather than `revert()`/`require()`
Custom errors are available from solidity version 0.8.4. Custom errors are more easily processed in `try`-`catch` blocks, and are easier to re-use and maintain.

*There are 22 instances of this issue:*

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

72            require(
73                l2CoreGovTimelock.hasRole(
74                    TIMELOCK_PROPOSAL_ROLE, address(prevNonEmergencySecurityCouncil)
75                ),
76                "GovernanceChainSCMgmtActivationAction: prev nonemergency council doesn't have proposal role"
77:           );

78            require(
79                !l2CoreGovTimelock.hasRole(
80                    TIMELOCK_PROPOSAL_ROLE, address(newNonEmergencySecurityCouncil)
81                ),
82                "GovernanceChainSCMgmtActivationAction: new nonemergency council already has proposal role"
83:           );

92            require(
93                Address.isContract(securityCouncilManager),
94                "GovernanceChainSCMgmtActivationAction: manager address isn't a contract"
95:           );

97            require(
98                !l2CoreGovTimelock.hasRole(TIMELOCK_PROPOSAL_ROLE, securityCouncilManager),
99                "GovernanceChainSCMgmtActivationAction: securityCouncilManager already has proposal role"
100:          );

104           require(
105               l2CoreGovTimelock.hasRole(
106                   TIMELOCK_CANCELLER_ROLE, address(prevEmergencySecurityCouncil)
107               ),
108               "GovernanceChainSCMgmtActivationAction: prev emergency security council should have cancellor role"
109:          );

115           require(
116               upgradeExecutor.hasRole(EXECUTOR_ROLE, address(newEmergencySecurityCouncil)),
117               "NonGovernanceChainSCMgmtActivationAction: new emergency security council not set"
118:          );

119           require(
120               !upgradeExecutor.hasRole(EXECUTOR_ROLE, address(prevEmergencySecurityCouncil)),
121               "NonGovernanceChainSCMgmtActivationAction: prev emergency security council still set"
122:          );

124           require(
125               !l2CoreGovTimelock.hasRole(
126                   TIMELOCK_PROPOSAL_ROLE, address(prevNonEmergencySecurityCouncil)
127               ),
128               "GovernanceChainSCMgmtActivationAction: prev nonemergency council still has proposal role"
129:          );

130           require(
131               l2CoreGovTimelock.hasRole(
132                   TIMELOCK_PROPOSAL_ROLE, address(newNonEmergencySecurityCouncil)
133               ),
134               "GovernanceChainSCMgmtActivationAction: new nonemergency doesn't have proposal role"
135:          );

137           require(
138               l2CoreGovTimelock.hasRole(TIMELOCK_PROPOSAL_ROLE, securityCouncilManager),
139               "GovernanceChainSCMgmtActivationAction: securityCouncilManager doesn't have proposal role"
140:          );

141           require(
142               !l2CoreGovTimelock.hasRole(
143                   TIMELOCK_CANCELLER_ROLE, address(prevEmergencySecurityCouncil)
144               ),
145               "GovernanceChainSCMgmtActivationAction: prev emergency security council still has cancellor role"
146:          );

```
*GitHub*: [72](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L72-L77), [78](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L78-L83), [92](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L92-L95), [97](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L97-L100), [104](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L104-L109), [115](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L115-L118), [119](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L119-L122), [124](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L124-L129), [130](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L130-L135), [137](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L137-L140), [141](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L141-L146)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

41            require(
42                l1Timelock.hasRole(TIMELOCK_CANCELLER_ROLE, address(prevEmergencySecurityCouncil)),
43                "GovernanceChainSCMgmtActivationAction: prev emergency security council should have cancellor role"
44:           );

45            require(
46                !l1Timelock.hasRole(TIMELOCK_CANCELLER_ROLE, address(l1UpgradeExecutor)),
47                "GovernanceChainSCMgmtActivationAction: l1UpgradeExecutor already has cancellor role"
48:           );

54            require(
55                l1Timelock.hasRole(TIMELOCK_CANCELLER_ROLE, address(l1UpgradeExecutor)),
56                "GovernanceChainSCMgmtActivationAction: l1UpgradeExecutor canceller role not set"
57:           );

58            require(
59                !l1Timelock.hasRole(TIMELOCK_CANCELLER_ROLE, address(prevEmergencySecurityCouncil)),
60                "GovernanceChainSCMgmtActivationAction: prevEmergencySecurityCouncil canceller role not revoked"
61:           );

```
*GitHub*: [41](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L41-L44), [45](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L45-L48), [54](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L54-L57), [58](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L58-L61)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

36            require(
37                upgradeExecutor.hasRole(EXECUTOR_ROLE, address(newEmergencySecurityCouncil)),
38                "NonGovernanceChainSCMgmtActivationAction: new emergency security council not set"
39:           );

40            require(
41                !upgradeExecutor.hasRole(EXECUTOR_ROLE, address(prevEmergencySecurityCouncil)),
42                "NonGovernanceChainSCMgmtActivationAction: prev emergency security council still set"
43:           );

```
*GitHub*: [36](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L36-L39), [40](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L40-L43)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

16            require(
17                _upgradeExecutor.hasRole(EXECUTOR_ROLE, address(_prevSecurityCouncil)),
18                "SecurityCouncilMgmtUpgradeLib: prev council not executor"
19:           );

20            require(
21                !_upgradeExecutor.hasRole(EXECUTOR_ROLE, address(_newSecurityCouncil)),
22                "SecurityCouncilMgmtUpgradeLib: new council already executor"
23:           );

35            require(
36                _safe1.getThreshold() == newSecurityCouncilThreshold,
37                "SecurityCouncilMgmtUpgradeLib: threshold mismatch"
38:           );

39            require(
40                newSecurityCouncilThreshold == _expectedThreshold,
41                "SecurityCouncilMgmtUpgradeLib: unexpected threshold"
42:           );

46            require(
47                areAddressArraysEqual(prevOwners, newOwners),
48                "SecurityCouncilMgmtUpgradeLib: owners mismatch"
49:           );

```
*GitHub*: [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L16-L19), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L20-L23), [35](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L35-L38), [39](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L39-L42), [46](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L46-L49)


### [N&#x2011;28] Array indicies should be referenced via `enum`s rather than via numeric literals


*There are 13 instances of this issue:*

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

147:         memberRemovers[0] = address(deployedContracts.securityCouncilMemberRemoverGov);

148:         memberRemovers[1] = dp.govChainEmergencySecurityCouncil;

```
*GitHub*: [147](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L147-L147), [148](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L148-L148)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

117:         if (targets[0] != address(securityCouncilManager)) {

118:             revert TargetNotManager(targets[0]);

120:         if (values[0] != 0) {

121:             revert ValueNotZero(values[0]);

124:         if (calldatas[0].length != 36) {

125:             revert UnexpectedCalldataLength(calldatas[0].length);

128:         (bytes4 selector, bytes memory rest) = this.separateSelector(calldatas[0]);

```
*GitHub*: [117](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L117-L117), [118](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L118-L118), [120](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L120-L120), [121](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L121-L121), [124](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L124-L124), [125](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L125-L125), [128](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L128-L128)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

23:          electionData[0] = abi.encode(electionIndex);

35:          return abi.decode(callDatas[0], (uint256));

```
*GitHub*: [23](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L23-L23), [35](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L35-L35)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

208:             if (topNomineesPacked[0] < packed) {

209:                 topNomineesPacked[0] = packed;

```
*GitHub*: [208](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L208-L208), [209](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L209-L209)


### [N&#x2011;29] Variable names for constants don't follow the Solidity style guide
For `constant` variable names, each word should use all capital letters, with underscores separating each word (CONSTANT_CASE)

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

28:      uint256 public constant voteSuccessDenominator = 10_000;

```
*GitHub*: [28](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L28-L28)


### [N&#x2011;30] Contracts containing only utility functions should be made into libraries


*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

9    contract ElectionGovernor {
10       /// @notice Generate arguments to be passed to the governor propose function
11       /// @param electionIndex The index of the election to create a proposal for
12       /// @return Targets
13       /// @return Values
14       /// @return Calldatas
15:      /// @return Description

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L9-L15)


### [N&#x2011;31] Events are missing sender information
When an action is triggered based on a user's action, not being able to filter based on who triggered the action makes event processing a lot more cumbersome. Including the `msg.sender` the events of these types of action will make events much more useful to end users, especially when `msg.sender` is not `tx.origin`.

*There are 19 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

140:         emit CohortReplaced(_newCohort, _cohort);

179:         emit MemberAdded(_newMember, _cohort);

189:         emit MemberRemoved({member: _member, cohort: cohort});

198          emit MemberReplaced({
199              replacedMember: _memberToReplace,
200              newMember: _newMember,
201              cohort: cohort
202:         });

211          emit MemberRotated({
212              replacedAddress: _currentAddress,
213              newAddress: _newAddress,
214              cohort: cohort
215:         });

263          emit SecurityCouncilAdded(
264              _securityCouncilData.securityCouncil,
265              _securityCouncilData.updateAction,
266              securityCouncils.length
267:         );

296                  emit SecurityCouncilRemoved(
297                      securityCouncilData.securityCouncil,
298                      securityCouncilData.updateAction,
299                      securityCouncils.length
300:                 );

323:         emit UpgradeExecRouteBuilderSet(routerAddress);

```
*GitHub*: [140](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L140-L140), [179](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L179-L179), [189](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L189-L189), [198](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L198-L202), [211](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L211-L215), [263](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L263-L267), [296](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L296-L300), [323](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L323-L323)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

46:              emit UpdateNonceTooLow(_securityCouncil, updateNonce, _nonce);

```
*GitHub*: [46](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L46-L46)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

187:         emit ContractsDeployed(deployedContracts);

```
*GitHub*: [187](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L187-L187)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

141:         emit MemberRemovalProposed(memberToRemove, description);

187:         emit VoteSuccessNumeratorSet(_voteSuccessNumerator);

```
*GitHub*: [141](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L141-L141), [187](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L187-L187)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

249:         emit NomineeVetterChanged(oldNomineeVetter, _nomineeVetter);

282:         emit NomineeExcluded(proposalId, nominee);

```
*GitHub*: [249](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L249-L249), [282](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L282-L282)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

73:          emit FullWeightDurationSet(initialFullWeightDuration);

83:          emit FullWeightDurationSet(newFullWeightDuration);

130          emit VoteCastForNominee({
131              voter: account,
132              proposalId: proposalId,
133              nominee: nominee,
134              votes: votes,
135              weight: weight,
136              totalUsedVotes: prevVotesUsed + votes,
137              usableVotes: availableVotes,
138              weightReceived: election.weightReceived[nominee]
139:         });

```
*GitHub*: [73](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L73-L73), [83](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L83-L83), [130](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L130-L139)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

110          emit VoteCastForContender({
111              proposalId: proposalId,
112              voter: account,
113              contender: contender,
114              votes: actualVotes,
115              totalUsedVotes: prevVotesUsed + actualVotes,
116              usableVotes: weight
117:         });

124:         emit NewNominee(proposalId, account);

```
*GitHub*: [110](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L110-L117), [124](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L124-L124)

</details>

### [N&#x2011;32] `internal` functions not called by the contract should be removed
All unused code should be removed

*There are 9 instances of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

115      function _execute(
116          uint256 proposalId,
117          address[] memory, /* targets */
118          uint256[] memory, /* values */
119          bytes[] memory callDatas,
120          bytes32 /* descriptionHash */
121:     ) internal override {

154      function _isCompliantNominee(uint256 proposalId, address possibleNominee)
155          internal
156          view
157          override
158          returns (bool)
159:     {

164      function _compliantNominees(uint256 proposalId)
165          internal
166          view
167          override
168          returns (address[] memory)
169:     {

174:     function _targetMemberCount() internal view override returns (uint256) {

```
*GitHub*: [115](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L115-L121), [154](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L154-L159), [164](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L164-L169), [174](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L174-L174)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

223      function _castVote(
224          uint256 proposalId,
225          address account,
226          uint8 support,
227          string memory reason,
228          bytes memory params
229      )
230          internal
231          override(GovernorUpgradeable, GovernorPreventLateQuorumUpgradeable)
232          returns (uint256)
233:     {

```
*GitHub*: [223](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L223-L233)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

267:     function _quorumReached(uint256) internal pure override returns (bool) {

273:     function _voteSucceeded(uint256) internal pure override returns (bool) {

```
*GitHub*: [267](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L267-L267), [273](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L273-L273)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

170:     function _quorumReached(uint256) internal pure override returns (bool) {

175:     function _voteSucceeded(uint256) internal pure override returns (bool) {

```
*GitHub*: [170](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L170-L170), [175](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L175-L175)


### [N&#x2011;33] `address`s shouldn't be hard-coded
It is often better to declare `address`es as `immutable`, and assign them via constructor arguments. This allows the code to remain the same across deployments on different networks, and avoids recompilation when addresses need to change.

*There are 4 instances of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

47:      address public constant RETRYABLE_TICKET_MAGIC = 0xa723C008e76E379c55599D2E4d93879BeaFDa79C;

```
*GitHub*: [47](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L47-L47), [47](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L47-L47)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

77:      address public constant RETRYABLE_TICKET_MAGIC = 0xa723C008e76E379c55599D2E4d93879BeaFDa79C;

```
*GitHub*: [77](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L77-L77), [77](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L77-L77)


### [N&#x2011;34] Variables need not be initialized to zero
The default value for variables is zero, so initializing them to zero is superfluous.

*There are 59 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

52:      uint256 public constant DEFAULT_VALUE = 0;

76:          for (uint256 i = 0; i < _upgradeExecutors.length; i++) {

129:         for (uint256 i = 0; i < chainIds.length; i++) {

193:         for (uint256 i = 0; i < chainIds.length; i++) {

```
*GitHub*: [52](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L52-L52), [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L76-L76), [129](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L129-L129), [193](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L193-L193)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

63:              for (uint256 j = 0; j < array2.length; j++) {

61:          for (uint256 i = 0; i < array1.length; i++) {

76:              for (uint256 j = 0; j < array1.length; j++) {

74:          for (uint256 i = 0; i < array2.length; i++) {

```
*GitHub*: [63](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L63-L63), [61](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L61-L61), [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L76-L76), [74](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L74-L74)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

106:         for (uint256 i = 0; i < _roles.memberRemovers.length; i++) {

118:         for (uint256 i = 0; i < _securityCouncils.length; i++) {

135:         for (uint256 i = 0; i < _newCohort.length; i++) {

164:             for (uint256 j = 0; j < cohort.length; j++) {

162:         for (uint256 i = 0; i < 2; i++) {

251:         for (uint256 i = 0; i < securityCouncils.length; i++) {

284:         for (uint256 i = 0; i < securityCouncils.length; i++) {

339:         for (uint256 i = 0; i < firstCohort.length; i++) {

342:         for (uint256 i = 0; i < secondCohort.length; i++) {

392:         for (uint256 i = 0; i < securityCouncils.length; i++) {

```
*GitHub*: [106](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L106-L106), [118](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L118-L118), [135](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L135-L135), [164](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L164-L164), [162](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L162-L162), [251](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L251-L251), [284](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L284-L284), [339](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L339-L339), [342](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L342-L342), [392](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L392-L392)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

60:          for (uint256 i = 0; i < _updatedMembers.length; i++) {

67:          for (uint256 i = 0; i < previousOwners.length; i++) {

105:         for (uint256 i = 0; i < owners.length; i++) {

```
*GitHub*: [60](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L60-L60), [67](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L67-L67), [105](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L105-L105)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

6:           for (uint256 i = 0; i < arr.length; i++) {

20:          uint256 intermediateLength = 0;

22:          for (uint256 i = 0; i < input.length; i++) {

31:          for (uint256 i = 0; i < intermediateLength; i++) {

```
*GitHub*: [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L6-L6), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L20-L20), [22](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L22-L22), [31](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L31-L31)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

111:         for (uint256 i = 0; i < dp.firstCohort.length; i++) {

117:         for (uint256 i = 0; i < dp.secondCohort.length; i++) {

```
*GitHub*: [111](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L111-L111), [117](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L117-L117)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

181:         for (uint256 i = 0; i < nominees.length; i++) {

205:         for (uint16 i = 0; i < nominees.length; i++) {

215:         for (uint16 i = 0; i < k; i++) {

```
*GitHub*: [181](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L181-L181), [205](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L205-L205), [215](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L215-L215)

```solidity
File: src/UpgradeExecRouteBuilder.sol

76:          for (uint256 i = 0; i < _upgradeExecutors.length; i++) {

129:         for (uint256 i = 0; i < chainIds.length; i++) {

193:         for (uint256 i = 0; i < chainIds.length; i++) {

```
*GitHub*: [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L76-L76), [129](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L129-L129), [193](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L193-L193)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

63:              for (uint256 j = 0; j < array2.length; j++) {

61:          for (uint256 i = 0; i < array1.length; i++) {

76:              for (uint256 j = 0; j < array1.length; j++) {

74:          for (uint256 i = 0; i < array2.length; i++) {

```
*GitHub*: [63](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L63-L63), [61](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L61-L61), [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L76-L76), [74](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L74-L74)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

106:         for (uint256 i = 0; i < _roles.memberRemovers.length; i++) {

118:         for (uint256 i = 0; i < _securityCouncils.length; i++) {

135:         for (uint256 i = 0; i < _newCohort.length; i++) {

164:             for (uint256 j = 0; j < cohort.length; j++) {

162:         for (uint256 i = 0; i < 2; i++) {

251:         for (uint256 i = 0; i < securityCouncils.length; i++) {

284:         for (uint256 i = 0; i < securityCouncils.length; i++) {

339:         for (uint256 i = 0; i < firstCohort.length; i++) {

342:         for (uint256 i = 0; i < secondCohort.length; i++) {

392:         for (uint256 i = 0; i < securityCouncils.length; i++) {

```
*GitHub*: [106](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L106-L106), [118](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L118-L118), [135](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L135-L135), [164](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L164-L164), [162](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L162-L162), [251](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L251-L251), [284](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L284-L284), [339](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L339-L339), [342](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L342-L342), [392](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L392-L392)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

60:          for (uint256 i = 0; i < _updatedMembers.length; i++) {

67:          for (uint256 i = 0; i < previousOwners.length; i++) {

105:         for (uint256 i = 0; i < owners.length; i++) {

```
*GitHub*: [60](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L60-L60), [67](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L67-L67), [105](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L105-L105)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

6:           for (uint256 i = 0; i < arr.length; i++) {

20:          uint256 intermediateLength = 0;

22:          for (uint256 i = 0; i < input.length; i++) {

31:          for (uint256 i = 0; i < intermediateLength; i++) {

```
*GitHub*: [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L6-L6), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L20-L20), [22](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L22-L22), [31](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L31-L31)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

111:         for (uint256 i = 0; i < dp.firstCohort.length; i++) {

117:         for (uint256 i = 0; i < dp.secondCohort.length; i++) {

```
*GitHub*: [111](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L111-L111), [117](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L117-L117)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

181:         for (uint256 i = 0; i < nominees.length; i++) {

205:         for (uint16 i = 0; i < nominees.length; i++) {

215:         for (uint16 i = 0; i < k; i++) {

```
*GitHub*: [181](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L181-L181), [205](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L205-L205), [215](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L215-L215)

</details>

### [N&#x2011;35] Consider using named mappings
Consider moving to solidity version 0.8.18 or later, and using [named mappings](https://ethereum.stackexchange.com/a/145555) to make it easier to understand the purpose of each mapping

*There are 13 instances of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

62:      mapping(uint256 => UpExecLocation) public upExecLocations;

```
*GitHub*: [62](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L62-L62)

```solidity
File: src/gov-action-contracts/execution-record/KeyValueStore.sol

7:       mapping(uint256 => uint256) public store;

```
*GitHub*: [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L7-L7)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

17:          mapping(address => bool) storage excludeList

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L17-L17)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

55:          mapping(address => bool) isContender;

56:          mapping(address => bool) isExcluded;

74:      mapping(uint256 => ElectionInfo) internal _elections;

```
*GitHub*: [55](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L55-L55), [56](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L56-L56), [74](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L74-L74)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

19:          mapping(address => uint256) votesUsed;

24:          mapping(address => uint240) weightReceived;

31:      mapping(uint256 => ElectionInfo) private _elections;

```
*GitHub*: [19](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L19-L19), [24](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L24-L24), [31](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L31-L31)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

19:          mapping(address => uint256) votesUsed;

20:          mapping(address => uint256) votesReceived;

22:          mapping(address => bool) isNominee;

26:      mapping(uint256 => NomineeElectionCountingInfo) private _elections;

```
*GitHub*: [19](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L19-L19), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L20-L20), [22](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L22-L22), [26](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L26-L26)


### [N&#x2011;36] Consider adding a block/deny-list
Doing so will significantly increase centralization, but will help to prevent hackers from using stolen tokens

*There are 7 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

39:  contract UpgradeExecRouteBuilder {

```
*GitHub*: [39](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L39-L39)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

12:  contract GovernanceChainSCMgmtActivationAction {

```
*GitHub*: [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L12-L12)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

28   contract SecurityCouncilManager is
29       Initializable,
30       AccessControlUpgradeable,
31       ISecurityCouncilManager
32:  {

```
*GitHub*: [28](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L28-L32)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

55:  contract L2SecurityCouncilMgmtFactory is Ownable {

```
*GitHub*: [55](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L55-L55)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

17   contract SecurityCouncilMemberElectionGovernor is
18       Initializable,
19       GovernorUpgradeable,
20       GovernorVotesUpgradeable,
21       SecurityCouncilMemberElectionGovernorCountingUpgradeable,
22       GovernorSettingsUpgradeable,
23       OwnableUpgradeable,
24       ElectionGovernor,
25       ISecurityCouncilMemberElectionGovernor
26   {
27:      /// @notice The SecurityCouncilNomineeElectionGovernor that creates proposals for this governor and contains the list of compliant nominees

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L17-L27)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

17   contract SecurityCouncilMemberRemovalGovernor is
18       Initializable,
19       GovernorUpgradeable,
20       GovernorVotesUpgradeable,
21       GovernorPreventLateQuorumUpgradeable,
22       GovernorCountingSimpleUpgradeable,
23       ArbitrumGovernorVotesQuorumFractionUpgradeable,
24       GovernorSettingsUpgradeable,
25       ArbitrumGovernorProposalExpirationUpgradeable,
26       OwnableUpgradeable
27:  {

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L17-L27)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

16   contract SecurityCouncilNomineeElectionGovernor is
17       Initializable,
18       GovernorUpgradeable,
19       GovernorVotesUpgradeable,
20       SecurityCouncilNomineeElectionGovernorCountingUpgradeable,
21       ArbitrumGovernorVotesQuorumFractionUpgradeable,
22       GovernorSettingsUpgradeable,
23       OwnableUpgradeable,
24       SecurityCouncilNomineeElectionGovernorTiming,
25       ElectionGovernor,
26       ISecurityCouncilNomineeElectionGovernor
27   {
28       /// @notice parameters for `initialize`
29       /// @param firstNominationStartDate First election start date
30       /// @param nomineeVettingDuration Duration of the nominee vetting period (expressed in blocks)
31       /// @param nomineeVetter Address of the nominee vetter
32       /// @param securityCouncilManager Security council manager contract
33       /// @param token Token used for voting
34       /// @param owner Owner of the governor (the Arbitrum DAO)
35       /// @param quorumNumeratorValue Numerator of the quorum fraction (0.2% = 20)
36       /// @param votingPeriod Duration of the voting period (expressed in blocks)
37:      ///                     Note that the voting period + nominee vetting duration must be << than 6 months to ensure elections dont overlap

```
*GitHub*: [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L16-L37)

</details>

### [N&#x2011;37] Non-`external`/`public` variable and function names should begin with an underscore
According to the Solidity Style Guide, non-`external`/`public` function names should begin with an [underscore](https://docs.soliditylang.org/en/latest/style-guide.html#underscore-prefix-for-non-external-functions-and-variables)

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

34:      function extractElectionIndex(bytes[] memory callDatas) internal pure returns (uint256) {

```
*GitHub*: [34](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L34-L34)


### [N&#x2011;38] Non-`external`/`public` variable names should begin with an underscore
According to the Solidity Style Guide, non-`external`/`public` variable names should begin with an [underscore](https://docs.soliditylang.org/en/latest/style-guide.html#underscore-prefix-for-non-external-functions-and-variables)

*There are 2 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

51:      address[] internal firstCohort;

52:      address[] internal secondCohort;

```
*GitHub*: [51](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L51-L51), [52](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L52-L52)


### [N&#x2011;39] Use of `override` is unnecessary
Starting with Solidity version [0.8.8](https://docs.soliditylang.org/en/v0.8.20/contracts.html#function-overriding), using the `override` keyword when the function solely overrides an interface function, and the function doesn't exist in multiple base contracts, is unnecessary.

*There are 40 instances of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

103      function relay(address target, uint256 value, bytes calldata data)
104          external
105          virtual
106          override
107          onlyOwner
108:     {

115      function _execute(
116          uint256 proposalId,
117          address[] memory, /* targets */
118          uint256[] memory, /* values */
119          bytes[] memory callDatas,
120          bytes32 /* descriptionHash */
121:     ) internal override {

138      function proposalThreshold()
139          public
140          pure
141          override(GovernorSettingsUpgradeable, GovernorUpgradeable)
142          returns (uint256)
143:     {

148:     function quorum(uint256) public pure override returns (uint256) {

154      function _isCompliantNominee(uint256 proposalId, address possibleNominee)
155          internal
156          view
157          override
158          returns (bool)
159:     {

164      function _compliantNominees(uint256 proposalId)
165          internal
166          view
167          override
168          returns (address[] memory)
169:     {

174:     function _targetMemberCount() internal view override returns (uint256) {

181      function propose(address[] memory, uint256[] memory, bytes[] memory, string memory)
182          public
183          virtual
184          override
185          returns (uint256)
186:     {

191:     function castVote(uint256, uint8) public virtual override returns (uint256) {

196      function castVoteWithReason(uint256, uint8, string calldata)
197          public
198          virtual
199          override
200          returns (uint256)
201:     {

206      function castVoteBySig(uint256, uint8, uint8, bytes32, bytes32)
207          public
208          virtual
209          override
210          returns (uint256)
211:     {

```
*GitHub*: [103](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L103-L108), [115](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L115-L121), [138](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L138-L143), [148](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L148-L148), [154](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L154-L159), [164](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L164-L169), [174](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L174-L174), [181](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L181-L186), [191](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L191-L191), [196](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L196-L201), [206](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L206-L211)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

106      function propose(
107          address[] memory targets,
108          uint256[] memory values,
109          bytes[] memory calldatas,
110          string memory description
111:     ) public override returns (uint256) {

147      function _voteSucceeded(uint256 proposalId)
148          internal
149          view
150          virtual
151          override(GovernorCountingSimpleUpgradeable, GovernorUpgradeable)
152          returns (bool)
153:     {

163      function _countVote(
164          uint256 proposalId,
165          address account,
166          uint8 support,
167          uint256 weight,
168          bytes memory params
169:     ) internal virtual override(GovernorCountingSimpleUpgradeable, GovernorUpgradeable) {

191      function COUNTING_MODE()
192          public
193          pure
194          virtual
195          override(GovernorCountingSimpleUpgradeable, IGovernorUpgradeable)
196          returns (string memory)
197:     {

203      function relay(address target, uint256 value, bytes calldata data)
204          external
205          virtual
206          override
207          onlyOwner
208:     {

213      function proposalThreshold()
214          public
215          view
216          override(GovernorUpgradeable, GovernorSettingsUpgradeable)
217          returns (uint256)
218:     {

223      function _castVote(
224          uint256 proposalId,
225          address account,
226          uint8 support,
227          string memory reason,
228          bytes memory params
229      )
230          internal
231          override(GovernorUpgradeable, GovernorPreventLateQuorumUpgradeable)
232          returns (uint256)
233:     {

240      function proposalDeadline(uint256 proposalId)
241          public
242          view
243          override(GovernorUpgradeable, GovernorPreventLateQuorumUpgradeable)
244          returns (uint256)
245:     {

249      function state(uint256 proposalId)
250          public
251          view
252          override(ArbitrumGovernorProposalExpirationUpgradeable, GovernorUpgradeable)
253          returns (ProposalState)
254:     {

```
*GitHub*: [106](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L106-L111), [147](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L147-L153), [163](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L163-L169), [191](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L191-L197), [203](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L203-L208), [213](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L213-L218), [223](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L223-L233), [240](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L240-L245), [249](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L249-L254)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

254      function relay(address target, uint256 value, bytes calldata data)
255          external
256          virtual
257          override
258          onlyOwner
259:     {

324      function _execute(
325          uint256 proposalId,
326          address[] memory, /* targets */
327          uint256[] memory, /* values */
328          bytes[] memory callDatas,
329          bytes32 /*descriptionHash*/
330:     ) internal virtual override {

357      function proposalThreshold()
358          public
359          view
360          virtual
361          override(GovernorSettingsUpgradeable, GovernorUpgradeable)
362          returns (uint256)
363:     {

410      function isContender(uint256 proposalId, address possibleContender)
411          public
412          view
413          virtual
414          override
415          returns (bool)
416:     {

423      function propose(address[] memory, uint256[] memory, bytes[] memory, string memory)
424          public
425          virtual
426          override
427          returns (uint256)
428:     {

433:     function castVote(uint256, uint8) public virtual override returns (uint256) {

438      function castVoteWithReason(uint256, uint8, string calldata)
439          public
440          virtual
441          override
442          returns (uint256)
443:     {

448      function castVoteBySig(uint256, uint8, uint8, bytes32, bytes32)
449          public
450          virtual
451          override
452          returns (uint256)
453:     {

```
*GitHub*: [254](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L254-L259), [324](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L324-L330), [357](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L357-L363), [410](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L410-L416), [423](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L423-L428), [433](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L433-L433), [438](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L438-L443), [448](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L448-L453)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

38:      function quorum(uint256 blockNumber) public view virtual override returns (uint256) {

44:      function quorumDenominator() public pure virtual override returns (uint256) {

```
*GitHub*: [38](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L38-L38), [44](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L44-L44)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

95       function _countVote(
96           uint256 proposalId,
97           address account,
98           uint8 support,
99           uint256 availableVotes,
100          bytes memory params
101:     ) internal virtual override {

143:     function COUNTING_MODE() public pure virtual override returns (string memory) {

158:     function hasVoted(uint256 proposalId, address account) public view override returns (bool) {

267:     function _quorumReached(uint256) internal pure override returns (bool) {

273:     function _voteSucceeded(uint256) internal pure override returns (bool) {

```
*GitHub*: [95](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L95-L101), [143](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L143-L143), [158](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L158-L158), [267](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L267-L267), [273](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L273-L273)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

62       function _countVote(
63           uint256 proposalId,
64           address account,
65           uint8 support,
66           uint256 weight,
67           bytes memory params
68:      ) internal virtual override {

128:     function COUNTING_MODE() public pure virtual override returns (string memory) {

133:     function hasVoted(uint256 proposalId, address account) public view override returns (bool) {

170:     function _quorumReached(uint256) internal pure override returns (bool) {

175:     function _voteSucceeded(uint256) internal pure override returns (bool) {

```
*GitHub*: [62](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L62-L68), [128](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L128-L128), [133](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L133-L133), [170](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L170-L170), [175](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L175-L175)


### [N&#x2011;40] Array is `push()`ed but not `pop()`ed
Array entries are added but are never removed. Consider whether this should be the case, or whether there should be a maximum, or whether old entries should be removed. Cases where there are specific potential problems will be flagged separately under a different issue.

*There are 3 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

158:         cohort.push(_newMember);

262:         securityCouncils.push(_securityCouncilData);

```
*GitHub*: [158](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L158-L158), [262](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L262-L262)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

122:         _elections[proposalId].nominees.push(account);

```
*GitHub*: [122](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L122-L122)


### [N&#x2011;41] Redundant inheritance specifier
The contracts below already extend the specified contract, so there is no need to list it in the inheritance list again

*There are 8 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

/// @audit AccessControlUpgradeable already extends Initializable
29:      Initializable,

```
*GitHub*: [29](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L29-L29)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

/// @audit GovernorUpgradeable already extends Initializable
18:      Initializable,

```
*GitHub*: [18](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L18-L18)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

/// @audit GovernorUpgradeable already extends Initializable
18:      Initializable,

```
*GitHub*: [18](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L18-L18)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

/// @audit GovernorUpgradeable already extends Initializable
17:      Initializable,

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L17-L17)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

/// @audit GovernorVotesQuorumFractionUpgradeable already extends Initializable
10:      Initializable,

```
*GitHub*: [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L10-L10)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

/// @audit GovernorUpgradeable already extends Initializable
14:      Initializable,

```
*GitHub*: [14](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L14-L14)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

/// @audit GovernorUpgradeable already extends Initializable
11:      Initializable,

```
*GitHub*: [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L11-L11)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

/// @audit GovernorUpgradeable already extends Initializable
13:      Initializable,

```
*GitHub*: [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L13-L13)

</details>

### [N&#x2011;42] Use `abi.encodeCall()` instead of `abi.encodeWithSignature()`/`abi.encodeWithSelector()`
`abi.encodeCall()` has compiler [type safety](https://github.com/OpenZeppelin/openzeppelin-contracts/issues/3693), whereas the other two functions do not

*There are 7 instances of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

51:          abi.encodeWithSelector(DefaultGovAction.perform.selector);

138:             bytes memory executorData = abi.encodeWithSelector(

163:         bytes memory timelockCallData = abi.encodeWithSelector(

176:             abi.encodeWithSelector(ArbSys.sendTxToL1.selector, l1TimelockAddr, timelockCallData)

```
*GitHub*: [51](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L51-L51), [138](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L138-L138), [163](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L163-L163), [176](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L176-L176)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

396:             actionDatas[i] = abi.encodeWithSelector(

```
*GitHub*: [396](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L396-L396)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

81:              abi.encodeWithSelector(IGnosisSafe.addOwnerWithThreshold.selector, _member, _threshold)

91:              abi.encodeWithSelector(

```
*GitHub*: [81](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L81-L81), [91](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L91-L91)


### [N&#x2011;43] Consider using descriptive `constant`s when passing zero as a function argument
Passing zero as a function argument can sometimes result in a security issue (e.g. passing zero as the slippage parameter). Consider using a `constant` variable with a descriptive name, so it's clear that the argument is intentionally being used, and for the right reasons.

*There are 9 instances of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

151                  schedData[i] = abi.encode(
152                      upExecLocation.inbox,
153                      upExecLocation.upgradeExecutor,
154                      actionValues[i],
155                      0,
156                      0,
157                      executorData
158:                 );

```
*GitHub*: [151](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L151-L158)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

406          (address to, bytes memory data) = router.createActionRouteData(
407              chainIds,
408              actionAddresses,
409              new uint256[](securityCouncils.length), // all values are always 0
410              actionDatas,
411              0,
412              salt
413:         );

428          ArbitrumTimelock(l2CoreGovTimelock).schedule({
429              target: to, // ArbSys address - this will trigger a call from L2->L1
430              value: 0,
431              // call to ArbSys.sendTxToL1; target the L1 timelock with the calldata previously constucted
432              data: data,
433              predecessor: bytes32(0),
434              // must be unique as the proposal hash is used for replay protection in the L2 timelock
435              // we cant be sure another proposal wont use this salt, and the same target + data
436              // but in that case the proposal will do what we want it to do anyway
437              // this can however block the execution of the election - so in this case the
438              // Security Council would need to unblock it by setting the election to executed state
439              // in the Member Election governor
440              salt: this.generateSalt(newMembers, updateNonce),
441              delay: ArbitrumTimelock(l2CoreGovTimelock).getMinDelay()
442:         });

```
*GitHub*: [406](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L406-L413), [428](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L428-L442)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

129              !securityCouncil.execTransactionFromModule(
130                  address(securityCouncil), 0, data, OpEnum.Operation.Call
131:             )

```
*GitHub*: [129](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L129-L131)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

65:          __GovernorSettings_init(0, _votingPeriod, 0);

```
*GitHub*: [65](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L65-L65)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

108:         __GovernorSettings_init(0, params.votingPeriod, 0); // votingDelay and proposalThreshold are set to 0

```
*GitHub*: [108](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L108-L108)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

32           bool isSupportedDateTime = DateTimeLib.isSupportedDateTime({
33               year: _firstNominationStartDate.year,
34               month: _firstNominationStartDate.month,
35               day: _firstNominationStartDate.day,
36               hour: _firstNominationStartDate.hour,
37               minute: 0,
38               second: 0
39:          });

51           uint256 startTimestamp = DateTimeLib.dateTimeToTimestamp({
52               year: _firstNominationStartDate.year,
53               month: _firstNominationStartDate.month,
54               day: _firstNominationStartDate.day,
55               hour: _firstNominationStartDate.hour,
56               minute: 0,
57               second: 0
58:          });

86           return DateTimeLib.dateTimeToTimestamp({
87               year: year,
88               month: month,
89               day: firstNominationStartDate.day,
90               hour: firstNominationStartDate.hour,
91               minute: 0,
92               second: 0
93:          });

```
*GitHub*: [32](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L32-L39), [51](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L51-L58), [86](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L86-L93)


### [N&#x2011;44] Constants in comparisons should appear on the left side
Doing so will prevent [typo bugs](https://www.moserware.com/2008/01/constants-on-left-are-better-but-this.html)

*There are 14 instances of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

134:             if (actionDatas[i].length == 0) {

```
*GitHub*: [134](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L134-L134)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

163:             address[] storage cohort = i == 0 ? firstCohort : secondCohort;

168:                     return i == 0 ? Cohort.FIRST : Cohort.SECOND;

243:         if (_securityCouncilData.chainId == 0) {

```
*GitHub*: [163](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L163-L163), [168](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L168-L168), [243](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L243-L243)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

112:         if (targets.length != 1) {

120:         if (values[0] != 0) {

124:         if (calldatas[0].length != 36) {

```
*GitHub*: [112](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L112-L112), [120](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L120-L120), [124](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L124-L124)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

188:         if (electionCount == 0) {

390:         return electionCount == 0 ? Cohort.FIRST : electionIndexToCohort(electionCount - 1);

```
*GitHub*: [188](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L188-L188), [390](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L390-L390)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

102:         if (support != 1) {

106:         if (params.length != 64) {

116:         if (weight == 0) {

```
*GitHub*: [102](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L102-L102), [106](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L106-L106), [116](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L116-L116)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

69:          if (support != 1) {

73:          if (params.length != 64) {

```
*GitHub*: [69](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L69-L69), [73](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L73-L73)


### [N&#x2011;45] Expressions for constant values should use `immutable` rather than `constant`
While it does not save gas for some simple binary expressions because the compiler knows that developers often make this mistake, it's still best to use the right tool for the task at hand. There is a difference between `constant` variables and `immutable` variables, and they should each be used in their appropriate contexts. `constants` should be used for literal values written into the code, and `immutable` variables should be used for expressions, or values calculated in, or passed into the constructor.

*There are 9 instances of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

50       bytes public constant DEFAULT_GOV_ACTION_CALLDATA =
51:          abi.encodeWithSelector(DefaultGovAction.perform.selector);

54:      bytes32 public constant DEFAULT_PREDECESSOR = bytes32(0);

```
*GitHub*: [50](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L50-L51), [54](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L54-L54)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

79:      bytes32 public constant COHORT_REPLACER_ROLE = keccak256("COHORT_REPLACER");

80:      bytes32 public constant MEMBER_ADDER_ROLE = keccak256("MEMBER_ADDER");

81:      bytes32 public constant MEMBER_REPLACER_ROLE = keccak256("MEMBER_REPLACER");

82:      bytes32 public constant MEMBER_ROTATOR_ROLE = keccak256("MEMBER_ROTATOR");

83:      bytes32 public constant MEMBER_REMOVER_ROLE = keccak256("MEMBER_REMOVER");

```
*GitHub*: [79](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L79-L79), [80](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L80-L80), [81](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L81-L81), [82](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L82-L82), [83](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L83-L83)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

19:      address public constant SENTINEL_OWNERS = address(0x1);

```
*GitHub*: [19](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L19-L19)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

22:      address public constant EXCLUDE_ADDRESS = address(0xA4b86);

```
*GitHub*: [22](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L22-L22)


### [N&#x2011;46] Consider disabling `renounceOwnership()`
If the plan for your project does not include eventually giving up all ownership control, consider overwriting OpenZeppelin's `Ownable`'s `renounceOwnership()` function in order to disable it.

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

55:  contract L2SecurityCouncilMgmtFactory is Ownable {

```
*GitHub*: [55](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L55-L55)


### [N&#x2011;47] Custom error has no error details
Consider adding parameters to the error to indicate which user or values caused the failure

*There are 8 instances of this issue:*

```solidity
File: src/security-council-mgmt/Common.sol

20:  error ZeroAddress();

```
*GitHub*: [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/Common.sol#L20-L20)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

34:      error OnlyNomineeElectionGovernor();

35:      error ProposeDisabled();

36:      error CastVoteDisabled();

```
*GitHub*: [34](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L34-L34), [35](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L35-L35), [36](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L36-L36)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

41:      error AbstainDisallowed();

```
*GitHub*: [41](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L41-L41)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

80:      error OnlyNomineeVetter();

91:      error ProposeDisabled();

95:      error CastVoteDisabled();

```
*GitHub*: [80](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L80-L80), [91](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L91-L91), [95](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L95-L95)


### [N&#x2011;48] Consider bounding input array length
The functions below take in an unbounded array, and make function calls for entries in the array. While the function will revert if it eventually runs out of gas, it may be a nicer user experience to `require()` that the length of the array is below some reasonable maximum, so that the user doesn't have to use up a full transaction's gas only to see that the transaction reverts.

*There are 9 instances of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

76           for (uint256 i = 0; i < _upgradeExecutors.length; i++) {
77               ChainAndUpExecLocation memory chainAndUpExecLocation = _upgradeExecutors[i];
78               if (chainAndUpExecLocation.location.upgradeExecutor == address(0)) {
79                   revert ZeroAddress();
80               }
81               if (upExecLocationExists(chainAndUpExecLocation.chainId)) {
82                   revert UpgradeExecAlreadyExists(chainAndUpExecLocation.chainId);
83               }
84               upExecLocations[chainAndUpExecLocation.chainId] = chainAndUpExecLocation.location;
85:          }

129          for (uint256 i = 0; i < chainIds.length; i++) {
130              UpExecLocation memory upExecLocation = upExecLocations[chainIds[i]];
131              if (upExecLocation.upgradeExecutor == address(0)) {
132                  revert UpgadeExecDoesntExist(chainIds[i]);
133              }
134              if (actionDatas[i].length == 0) {
135                  revert EmptyActionBytesData(actionDatas);
136              }
137  
138              bytes memory executorData = abi.encodeWithSelector(
139                  UpgradeExecutor.execute.selector, actionAddresses[i], actionDatas[i]
140              );
141  
142              // for L1, inbox is set to address(0):
143              if (upExecLocation.inbox == address(0)) {
144                  schedTargets[i] = upExecLocation.upgradeExecutor;
145                  schedValues[i] = actionValues[i];
146                  schedData[i] = executorData;
147              } else {
148                  // For L2 actions, magic is top level target, and value and calldata are encoded in payload
149                  schedTargets[i] = RETRYABLE_TICKET_MAGIC;
150                  schedValues[i] = 0;
151                  schedData[i] = abi.encode(
152                      upExecLocation.inbox,
153                      upExecLocation.upgradeExecutor,
154                      actionValues[i],
155                      0,
156                      0,
157                      executorData
158                  );
159              }
160:         }

```
*GitHub*: [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L76-L85), [129](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L129-L160)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

106          for (uint256 i = 0; i < _roles.memberRemovers.length; i++) {
107              _grantRole(MEMBER_REMOVER_ROLE, _roles.memberRemovers[i]);
108:         }

118          for (uint256 i = 0; i < _securityCouncils.length; i++) {
119              _addSecurityCouncil(_securityCouncils[i]);
120:         }

135          for (uint256 i = 0; i < _newCohort.length; i++) {
136              _addMemberToCohortArray(_newCohort[i], _cohort);
137:         }

```
*GitHub*: [106](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L106-L108), [118](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L118-L120), [135](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L135-L137)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

60           for (uint256 i = 0; i < _updatedMembers.length; i++) {
61               address member = _updatedMembers[i];
62               if (!securityCouncil.isOwner(member)) {
63                   _addMember(securityCouncil, member, threshold);
64               }
65:          }

67           for (uint256 i = 0; i < previousOwners.length; i++) {
68               address owner = previousOwners[i];
69               if (!SecurityCouncilMgmtUtils.isInArray(owner, _updatedMembers)) {
70                   _removeMember(securityCouncil, owner, threshold);
71               }
72:          }

```
*GitHub*: [60](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L60-L65), [67](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L67-L72)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

205          for (uint16 i = 0; i < nominees.length; i++) {
206              uint256 packed = (uint256(weights[i]) << 16) | i;
207  
208              if (topNomineesPacked[0] < packed) {
209                  topNomineesPacked[0] = packed;
210                  LibSort.insertionSort(topNomineesPacked);
211              }
212:         }

215          for (uint16 i = 0; i < k; i++) {
216              topNomineesAddresses[i] = nominees[uint16(topNomineesPacked[i])];
217:         }

```
*GitHub*: [205](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L205-L212), [215](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L215-L217)


### [N&#x2011;49] Interfaces should be defined in separate files from their usage
The interfaces below should be defined in separate files, so that it's easier for future projects to import them, and to avoid duplication later on if they need to be used elsewhere in the project

*There is one instance of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

9:   interface DefaultGovAction {

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L9-L9)


### [N&#x2011;50] Contract declarations should have NatSpec descriptions
e.g. `@dev` or `@notice`, and it must appear above the contract definition braces in order to be identified by the compiler as NatSpec

*There are 6 instances of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

9:   interface DefaultGovAction {

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L9-L9)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

12:  contract GovernanceChainSCMgmtActivationAction {

```
*GitHub*: [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L12-L12)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

9:   contract L1SCMgmtActivationAction {

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L9-L9)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

7:   contract NonGovernanceChainSCMgmtActivationAction {

```
*GitHub*: [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L7-L7)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

7:   library SecurityCouncilMgmtUpgradeLib {

```
*GitHub*: [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L7-L7)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

4:   library SecurityCouncilMgmtUtils {

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L4-L4)


### [N&#x2011;51] Contract declarations should have NatSpec `@title` annotations


*There are 20 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

9:   interface DefaultGovAction {

39:  contract UpgradeExecRouteBuilder {

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L9-L9), [39](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L39-L39)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

12:  contract GovernanceChainSCMgmtActivationAction {

```
*GitHub*: [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L12-L12)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

9:   contract L1SCMgmtActivationAction {

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L9-L9)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

7:   contract NonGovernanceChainSCMgmtActivationAction {

```
*GitHub*: [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L7-L7)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

7:   library SecurityCouncilMgmtUpgradeLib {

```
*GitHub*: [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L7-L7)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

10   contract ActionExecutionRecord {
11       /// @notice The key value store used to record the execution
12:      /// @dev    Local storage cannot be used in action contracts as they're delegate called into

```
*GitHub*: [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L10-L12)

```solidity
File: src/gov-action-contracts/execution-record/KeyValueStore.sol

6:   contract KeyValueStore {

```
*GitHub*: [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L6-L6)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

28   contract SecurityCouncilManager is
29       Initializable,
30       AccessControlUpgradeable,
31       ISecurityCouncilManager
32:  {

```
*GitHub*: [28](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L28-L32)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

10:  contract SecurityCouncilMemberSyncAction is ActionExecutionRecord {

```
*GitHub*: [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L10-L10)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

4:   library SecurityCouncilMgmtUtils {

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L4-L4)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

55:  contract L2SecurityCouncilMgmtFactory is Ownable {

```
*GitHub*: [55](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L55-L55)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

17   contract SecurityCouncilMemberElectionGovernor is
18       Initializable,
19       GovernorUpgradeable,
20       GovernorVotesUpgradeable,
21       SecurityCouncilMemberElectionGovernorCountingUpgradeable,
22       GovernorSettingsUpgradeable,
23       OwnableUpgradeable,
24       ElectionGovernor,
25       ISecurityCouncilMemberElectionGovernor
26   {
27:      /// @notice The SecurityCouncilNomineeElectionGovernor that creates proposals for this governor and contains the list of compliant nominees

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L17-L27)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

17   contract SecurityCouncilMemberRemovalGovernor is
18       Initializable,
19       GovernorUpgradeable,
20       GovernorVotesUpgradeable,
21       GovernorPreventLateQuorumUpgradeable,
22       GovernorCountingSimpleUpgradeable,
23       ArbitrumGovernorVotesQuorumFractionUpgradeable,
24       GovernorSettingsUpgradeable,
25       ArbitrumGovernorProposalExpirationUpgradeable,
26       OwnableUpgradeable
27:  {

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L17-L27)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

16   contract SecurityCouncilNomineeElectionGovernor is
17       Initializable,
18       GovernorUpgradeable,
19       GovernorVotesUpgradeable,
20       SecurityCouncilNomineeElectionGovernorCountingUpgradeable,
21       ArbitrumGovernorVotesQuorumFractionUpgradeable,
22       GovernorSettingsUpgradeable,
23       OwnableUpgradeable,
24       SecurityCouncilNomineeElectionGovernorTiming,
25       ElectionGovernor,
26       ISecurityCouncilNomineeElectionGovernor
27   {
28       /// @notice parameters for `initialize`
29       /// @param firstNominationStartDate First election start date
30       /// @param nomineeVettingDuration Duration of the nominee vetting period (expressed in blocks)
31       /// @param nomineeVetter Address of the nominee vetter
32       /// @param securityCouncilManager Security council manager contract
33       /// @param token Token used for voting
34       /// @param owner Owner of the governor (the Arbitrum DAO)
35       /// @param quorumNumeratorValue Numerator of the quorum fraction (0.2% = 20)
36       /// @param votingPeriod Duration of the voting period (expressed in blocks)
37:      ///                     Note that the voting period + nominee vetting duration must be << than 6 months to ensure elections dont overlap

```
*GitHub*: [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L16-L37)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

9    abstract contract ArbitrumGovernorVotesQuorumFractionUpgradeable is
10       Initializable,
11       GovernorVotesQuorumFractionUpgradeable
12   {
13       /// @notice address for which votes will not be counted toward quorum
14       /// @dev    A portion of the Arbitrum tokens will be held by entities (eg the treasury) that
15       ///         are not eligible to vote. However, even if their voting/delegation is restricted their
16       ///         tokens will still count towards the total supply, and will therefore affect the quorom.
17       ///         Restricted addresses should be forced to delegate their votes to this special exclude
18       ///         addresses which is not counted when calculating quorum
19       ///         Example address that should be excluded: DAO treasury, foundation, unclaimed tokens,
20       ///         burned tokens and swept (see TokenDistributor) tokens.
21:      ///         Note that Excluded Address is a readable name with no code or PK associated with it, and thus can't vote.

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L9-L21)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

9    contract ElectionGovernor {
10       /// @notice Generate arguments to be passed to the governor propose function
11       /// @param electionIndex The index of the election to create a proposal for
12       /// @return Targets
13       /// @return Values
14       /// @return Calldatas
15:      /// @return Description

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L9-L15)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

13   abstract contract SecurityCouncilMemberElectionGovernorCountingUpgradeable is
14       Initializable,
15       GovernorUpgradeable
16:  {

```
*GitHub*: [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L13-L16)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

10   abstract contract SecurityCouncilNomineeElectionGovernorCountingUpgradeable is
11       Initializable,
12       GovernorUpgradeable
13   {
14       /// @param votesUsed The amount of votes a voter has used
15       /// @param votesReceived The amount of votes a contender has received
16       /// @param nominees The list of contenders who've received enough votes to become a nominee
17:      /// @param isNominee A mapping of contenders to whether or not they are a nominee

```
*GitHub*: [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L10-L17)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

12   abstract contract SecurityCouncilNomineeElectionGovernorTiming is
13       Initializable,
14       GovernorUpgradeable
15   {
16:      /// @notice First election start date

```
*GitHub*: [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L12-L16)

</details>

### [N&#x2011;52] Contract declarations should have NatSpec `@title` annotations


*There are 11 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

9:   interface DefaultGovAction {

39:  contract UpgradeExecRouteBuilder {

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L9-L9), [39](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L39-L39)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

12:  contract GovernanceChainSCMgmtActivationAction {

```
*GitHub*: [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L12-L12)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

9:   contract L1SCMgmtActivationAction {

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L9-L9)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

7:   contract NonGovernanceChainSCMgmtActivationAction {

```
*GitHub*: [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L7-L7)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

7:   library SecurityCouncilMgmtUpgradeLib {

```
*GitHub*: [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L7-L7)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

10   contract ActionExecutionRecord {
11       /// @notice The key value store used to record the execution
12:      /// @dev    Local storage cannot be used in action contracts as they're delegate called into

```
*GitHub*: [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L10-L12)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

10:  contract SecurityCouncilMemberSyncAction is ActionExecutionRecord {

```
*GitHub*: [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L10-L10)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

4:   library SecurityCouncilMgmtUtils {

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L4-L4)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

55:  contract L2SecurityCouncilMgmtFactory is Ownable {

```
*GitHub*: [55](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L55-L55)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

9    contract ElectionGovernor {
10       /// @notice Generate arguments to be passed to the governor propose function
11       /// @param electionIndex The index of the election to create a proposal for
12       /// @return Targets
13       /// @return Values
14       /// @return Calldatas
15:      /// @return Description

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L9-L15)

</details>

### [N&#x2011;53] Function declarations should have NatSpec descriptions


*There are 18 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

10:      function perform() external;

```
*GitHub*: [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L10-L10)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

25       constructor(
26           IGnosisSafe _newEmergencySecurityCouncil,
27           IGnosisSafe _newNonEmergencySecurityCouncil,
28           IGnosisSafe _prevEmergencySecurityCouncil,
29           IGnosisSafe _prevNonEmergencySecurityCouncil,
30           uint256 _emergencySecurityCouncilThreshold,
31           uint256 _nonEmergencySecurityCouncilThreshold,
32           address _securityCouncilManager,
33           IL2AddressRegistry _l2AddressRegistry
34:      ) {

48:      function perform() external {

```
*GitHub*: [25](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L25-L34), [48](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L48-L48)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

16       constructor(
17           IGnosisSafe _newEmergencySecurityCouncil,
18           IGnosisSafe _prevEmergencySecurityCouncil,
19           uint256 _emergencySecurityCouncilThreshold,
20           IUpgradeExecutor _l1UpgradeExecutor,
21           ICoreTimelock _l1Timelock
22:      ) {

30:      function perform() external {

```
*GitHub*: [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L16-L22), [30](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L30-L30)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

13       constructor(
14           IGnosisSafe _newEmergencySecurityCouncil,
15           IGnosisSafe _prevEmergencySecurityCouncil,
16           uint256 _emergencySecurityCouncilThreshold,
17           IUpgradeExecutor _upgradeExecutor
18:      ) {

25:      function perform() external {

```
*GitHub*: [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L13-L18), [25](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L25-L25)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

52       function areAddressArraysEqual(address[] memory array1, address[] memory array2)
53           public
54           pure
55           returns (bool)
56:      {

```
*GitHub*: [52](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L52-L56)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

18:      constructor(KeyValueStore _store, string memory _uniqueActionName) {

```
*GitHub*: [18](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L18-L18)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

85:      constructor() {

89       function initialize(
90           address[] memory _firstCohort,
91           address[] memory _secondCohort,
92           SecurityCouncilData[] memory _securityCouncils,
93           SecurityCouncilManagerRoles memory _roles,
94           address payable _l2CoreGovTimelock,
95           UpgradeExecRouteBuilder _router
96:      ) external initializer {

```
*GitHub*: [85](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L85-L85), [89](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L89-L96)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

21       constructor(KeyValueStore _store)
22           ActionExecutionRecord(_store, "SecurityCouncilMemberSyncAction")
23:      {}

97       function getPrevOwner(IGnosisSafe securityCouncil, address _owner)
98           public
99           view
100          returns (address)
101:     {

118:     function getUpdateNonce(address securityCouncil) public view returns (uint256) {

```
*GitHub*: [21](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L21-L23), [97](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L97-L101), [118](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L118-L118)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

38:      constructor() {

```
*GitHub*: [38](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L38-L38)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

44:      constructor() {

249      function state(uint256 proposalId)
250          public
251          view
252          override(ArbitrumGovernorProposalExpirationUpgradeable, GovernorUpgradeable)
253          returns (ProposalState)
254:     {

```
*GitHub*: [44](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L44-L44), [249](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L249-L254)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

98:      constructor() {

```
*GitHub*: [98](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L98-L98)

</details>

### [N&#x2011;54] Setters should prevent re-setting of the same value
This especially problematic when the setter also emits the same value, which may be confusing to offline parsers

*There are 4 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

315      function _setUpgradeExecRouteBuilder(UpgradeExecRouteBuilder _router) internal {
316          address routerAddress = address(_router);
317  
318          if (!Address.isContract(routerAddress)) {
319              revert NotAContract({account: routerAddress});
320          }
321  
322          router = _router;
323          emit UpgradeExecRouteBuilderSet(routerAddress);
324:     }

```
*GitHub*: [315](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L315-L324)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

182      function _setVoteSuccessNumerator(uint256 _voteSuccessNumerator) internal {
183          if (!(0 < _voteSuccessNumerator && _voteSuccessNumerator <= voteSuccessDenominator)) {
184              revert InvalidVoteSuccessNumerator(_voteSuccessNumerator);
185          }
186          voteSuccessNumerator = _voteSuccessNumerator;
187          emit VoteSuccessNumeratorSet(_voteSuccessNumerator);
188:     }

```
*GitHub*: [182](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L182-L188)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

246      function setNomineeVetter(address _nomineeVetter) external onlyGovernance {
247          address oldNomineeVetter = nomineeVetter;
248          nomineeVetter = _nomineeVetter;
249          emit NomineeVetterChanged(oldNomineeVetter, _nomineeVetter);
250:     }

```
*GitHub*: [246](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L246-L250)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

77       function setFullWeightDuration(uint256 newFullWeightDuration) public onlyGovernance {
78           if (newFullWeightDuration > votingPeriod()) {
79               revert FullWeightDurationGreaterThanVotingPeriod(newFullWeightDuration, votingPeriod());
80           }
81   
82           fullWeightDuration = newFullWeightDuration;
83           emit FullWeightDurationSet(newFullWeightDuration);
84:      }

```
*GitHub*: [77](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L77-L84)


### [N&#x2011;55] Named imports of parent contracts are missing


*There are 40 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

/// @audit Initializable
29:      Initializable,

/// @audit AccessControlUpgradeable
30:      AccessControlUpgradeable,

/// @audit ISecurityCouncilManager
31:      ISecurityCouncilManager

```
*GitHub*: [29](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L29-L29), [30](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L30-L30), [31](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L31-L31)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

/// @audit ActionExecutionRecord
10:  contract SecurityCouncilMemberSyncAction is ActionExecutionRecord {

```
*GitHub*: [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L10-L10)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

/// @audit Ownable
55:  contract L2SecurityCouncilMgmtFactory is Ownable {

```
*GitHub*: [55](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L55-L55)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

/// @audit Initializable
18:      Initializable,

/// @audit GovernorUpgradeable
19:      GovernorUpgradeable,

/// @audit GovernorVotesUpgradeable
20:      GovernorVotesUpgradeable,

/// @audit SecurityCouncilMemberElectionGovernorCountingUpgradeable
21:      SecurityCouncilMemberElectionGovernorCountingUpgradeable,

/// @audit GovernorSettingsUpgradeable
22:      GovernorSettingsUpgradeable,

/// @audit OwnableUpgradeable
23:      OwnableUpgradeable,

/// @audit ElectionGovernor
24:      ElectionGovernor,

/// @audit ISecurityCouncilMemberElectionGovernor
25:      ISecurityCouncilMemberElectionGovernor

```
*GitHub*: [18](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L18-L18), [19](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L19-L19), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L20-L20), [21](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L21-L21), [22](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L22-L22), [23](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L23-L23), [24](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L24-L24), [25](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L25-L25)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

/// @audit Initializable
18:      Initializable,

/// @audit GovernorUpgradeable
19:      GovernorUpgradeable,

/// @audit GovernorVotesUpgradeable
20:      GovernorVotesUpgradeable,

/// @audit GovernorPreventLateQuorumUpgradeable
21:      GovernorPreventLateQuorumUpgradeable,

/// @audit GovernorCountingSimpleUpgradeable
22:      GovernorCountingSimpleUpgradeable,

/// @audit ArbitrumGovernorVotesQuorumFractionUpgradeable
23:      ArbitrumGovernorVotesQuorumFractionUpgradeable,

/// @audit GovernorSettingsUpgradeable
24:      GovernorSettingsUpgradeable,

/// @audit ArbitrumGovernorProposalExpirationUpgradeable
25:      ArbitrumGovernorProposalExpirationUpgradeable,

/// @audit OwnableUpgradeable
26:      OwnableUpgradeable

```
*GitHub*: [18](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L18-L18), [19](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L19-L19), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L20-L20), [21](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L21-L21), [22](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L22-L22), [23](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L23-L23), [24](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L24-L24), [25](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L25-L25), [26](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L26-L26)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

/// @audit Initializable
17:      Initializable,

/// @audit GovernorUpgradeable
18:      GovernorUpgradeable,

/// @audit GovernorVotesUpgradeable
19:      GovernorVotesUpgradeable,

/// @audit SecurityCouncilNomineeElectionGovernorCountingUpgradeable
20:      SecurityCouncilNomineeElectionGovernorCountingUpgradeable,

/// @audit ArbitrumGovernorVotesQuorumFractionUpgradeable
21:      ArbitrumGovernorVotesQuorumFractionUpgradeable,

/// @audit GovernorSettingsUpgradeable
22:      GovernorSettingsUpgradeable,

/// @audit OwnableUpgradeable
23:      OwnableUpgradeable,

/// @audit SecurityCouncilNomineeElectionGovernorTiming
24:      SecurityCouncilNomineeElectionGovernorTiming,

/// @audit ElectionGovernor
25:      ElectionGovernor,

/// @audit ISecurityCouncilNomineeElectionGovernor
26:      ISecurityCouncilNomineeElectionGovernor

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L17-L17), [18](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L18-L18), [19](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L19-L19), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L20-L20), [21](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L21-L21), [22](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L22-L22), [23](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L23-L23), [24](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L24-L24), [25](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L25-L25), [26](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L26-L26)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

/// @audit Initializable
10:      Initializable,

/// @audit GovernorVotesQuorumFractionUpgradeable
11:      GovernorVotesQuorumFractionUpgradeable

```
*GitHub*: [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L10-L10), [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L11-L11)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

/// @audit Initializable
14:      Initializable,

/// @audit GovernorUpgradeable
15:      GovernorUpgradeable

```
*GitHub*: [14](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L14-L14), [15](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L15-L15)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

/// @audit Initializable
11:      Initializable,

/// @audit GovernorUpgradeable
12:      GovernorUpgradeable

```
*GitHub*: [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L11-L11), [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L12-L12)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

/// @audit Initializable
13:      Initializable,

/// @audit GovernorUpgradeable
14:      GovernorUpgradeable

```
*GitHub*: [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L13-L13), [14](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L14-L14)

</details>

### [N&#x2011;56] Polymorphic functions make security audits more time-consuming and error-prone
The instances below point to one of two functions with the same name. Consider naming each function differently, in order to make code navigation and analysis easier.

*There is one instance of this issue:*

```solidity
File: src/gov-action-contracts/execution-record/KeyValueStore.sol

21:      function get(address owner, uint256 key) external view returns (uint256) {

```
*GitHub*: [21](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L21-L21)


### [N&#x2011;57] Use the latest solidity (prior to 0.8.20 if on L2s) for deployment
```
When deploying contracts, you should use the latest released version of Solidity. Apart from exceptional cases, only the latest version receives security fixes.
```
https://docs.soliditylang.org/en/v0.8.20/

*There are 17 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L2-L2)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L2-L2)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L2-L2)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L2-L2)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L2-L2)

```solidity
File: src/gov-action-contracts/execution-record/KeyValueStore.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L2-L2)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L2-L2)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L2-L2)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L2-L2)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L2-L2)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L2-L2)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L2-L2)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L2-L2)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

3:   pragma solidity 0.8.16;

```
*GitHub*: [3](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L3-L3)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L2-L2)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L2-L2)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L2-L2)

</details>

### [N&#x2011;58] Public variable declarations should have NatSpec descriptions
e.g. `@dev` or `@notice`

*There are 27 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

52:      uint256 public constant DEFAULT_VALUE = 0;

```
*GitHub*: [52](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L52-L52)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

13:      IGnosisSafe public immutable newEmergencySecurityCouncil;

14:      IGnosisSafe public immutable newNonEmergencySecurityCouncil;

16:      IGnosisSafe public immutable prevEmergencySecurityCouncil;

17:      IGnosisSafe public immutable prevNonEmergencySecurityCouncil;

19:      uint256 public immutable emergencySecurityCouncilThreshold;

20:      uint256 public immutable nonEmergencySecurityCouncilThreshold;

22:      address public immutable securityCouncilManager;

23:      IL2AddressRegistry public immutable l2AddressRegistry;

```
*GitHub*: [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L13-L13), [14](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L14-L14), [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L16-L16), [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L17-L17), [19](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L19-L19), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L20-L20), [22](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L22-L22), [23](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L23-L23)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

10:      IGnosisSafe public immutable newEmergencySecurityCouncil;

11:      IGnosisSafe public immutable prevEmergencySecurityCouncil;

12:      uint256 public immutable emergencySecurityCouncilThreshold;

13:      IUpgradeExecutor public immutable l1UpgradeExecutor;

14:      ICoreTimelock public immutable l1Timelock;

```
*GitHub*: [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L10-L10), [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L11-L11), [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L12-L12), [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L13-L13), [14](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L14-L14)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

8:       IGnosisSafe public immutable newEmergencySecurityCouncil;

9:       IGnosisSafe public immutable prevEmergencySecurityCouncil;

10:      uint256 public immutable emergencySecurityCouncilThreshold;

11:      IUpgradeExecutor public immutable upgradeExecutor;

```
*GitHub*: [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L8-L8), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L9-L9), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L10-L10), [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L11-L11)

```solidity
File: src/gov-action-contracts/execution-record/KeyValueStore.sol

7:       mapping(uint256 => uint256) public store;

```
*GitHub*: [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L7-L7)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

79:      bytes32 public constant COHORT_REPLACER_ROLE = keccak256("COHORT_REPLACER");

80:      bytes32 public constant MEMBER_ADDER_ROLE = keccak256("MEMBER_ADDER");

81:      bytes32 public constant MEMBER_REPLACER_ROLE = keccak256("MEMBER_REPLACER");

82:      bytes32 public constant MEMBER_ROTATOR_ROLE = keccak256("MEMBER_ROTATOR");

83:      bytes32 public constant MEMBER_REMOVER_ROLE = keccak256("MEMBER_REMOVER");

```
*GitHub*: [79](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L79-L79), [80](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L80-L80), [81](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L81-L81), [82](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L82-L82), [83](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L83-L83)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

28:      uint256 public constant voteSuccessDenominator = 10_000;

29:      uint256 public voteSuccessNumerator;

30:      ISecurityCouncilManager public securityCouncilManager;

```
*GitHub*: [28](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L28-L28), [29](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L29-L29), [30](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L30-L30)

</details>
## Gas Optimizations


### [G&#x2011;01] Structs can be packed into fewer storage slots
Each slot saved can avoid an extra Gsset (**20000 gas**) for the first setting of the struct. Subsequent reads as well as writes have smaller gas savings

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

/// @audit Variable ordering with 24 slots instead of the current 25:
///           user-defined[](32):upgradeExecutors, address[](32):secondCohort, address[](32):firstCohort, uint256(32):l1TimelockMinDelay, uint256(32):removalGovVotingDelay, uint256(32):removalGovVotingPeriod, uint256(32):removalGovQuorumNumerator, uint256(32):removalGovProposalThreshold, uint256(32):removalGovVoteSuccessNumerator, uint256(32):removalProposalExpirationBlocks, user-defined[](32):securityCouncils, user-defined(32):firstNominationStartDate, uint256(32):nomineeVettingDuration, uint256(32):nomineeQuorumNumerator, uint256(32):nomineeVotingPeriod, uint256(32):memberVotingPeriod, uint256(32):fullWeightDuration, address(20):govChainEmergencySecurityCouncil, uint64(8):removalGovMinPeriodAfterQuorum, address(20):l1ArbitrumTimelock, address(20):l2CoreGovTimelock, address(20):govChainProxyAdmin, address(20):l2UpgradeExecutor, address(20):arbToken, address(20):nomineeVetter
18    struct DeployParams {
19        ChainAndUpExecLocation[] upgradeExecutors;
20        address govChainEmergencySecurityCouncil;
21        address l1ArbitrumTimelock;
22        address l2CoreGovTimelock;
23        address govChainProxyAdmin;
24        address[] secondCohort;
25        address[] firstCohort;
26        address l2UpgradeExecutor;
27        address arbToken;
28        uint256 l1TimelockMinDelay;
29        uint256 removalGovVotingDelay;
30        uint256 removalGovVotingPeriod;
31        uint256 removalGovQuorumNumerator;
32        uint256 removalGovProposalThreshold;
33        uint256 removalGovVoteSuccessNumerator;
34        uint64 removalGovMinPeriodAfterQuorum;
35        uint256 removalProposalExpirationBlocks;
36        SecurityCouncilData[] securityCouncils;
37        Date firstNominationStartDate;
38        uint256 nomineeVettingDuration;
39        address nomineeVetter;
40        uint256 nomineeQuorumNumerator;
41        uint256 nomineeVotingPeriod;
42        uint256 memberVotingPeriod;
43        uint256 fullWeightDuration;
44:   }

```
*GitHub*: [18](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L18-L44)


### [G&#x2011;02] Structs can be packed into fewer storage slots by truncating timestamp bytes
By using a `uint32` rather than a larger type for variables that track timestamps, one can save gas by using fewer storage slots per struct, at the expense of the protocol breaking after the year 2106 (when `uint32` wraps). If this is an acceptable tradeoff, each slot saved can avoid an extra Gsset (**20000 gas**) for the first setting of the struct. Subsequent reads as well as writes have smaller gas savings

*There are 2 instances of this issue:*

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

/// @audit Variable ordering with 18 slots instead of the current 25:
///           user-defined[](32):upgradeExecutors, address[](32):secondCohort, address[](32):firstCohort, uint256(32):removalGovQuorumNumerator, uint256(32):removalGovProposalThreshold, uint256(32):removalGovVoteSuccessNumerator, user-defined[](32):securityCouncils, user-defined(32):firstNominationStartDate, uint256(32):nomineeVettingDuration, uint256(32):nomineeQuorumNumerator, uint256(32):fullWeightDuration, address(20):govChainEmergencySecurityCouncil, uint32(4):l1TimelockMinDelay, uint32(4):removalGovVotingDelay, uint32(4):removalGovVotingPeriod, address(20):l1ArbitrumTimelock, uint32(4):removalGovMinPeriodAfterQuorum, uint32(4):removalProposalExpirationBlocks, uint32(4):nomineeVotingPeriod, address(20):l2CoreGovTimelock, uint32(4):memberVotingPeriod, address(20):govChainProxyAdmin, address(20):l2UpgradeExecutor, address(20):arbToken, address(20):nomineeVetter
18    struct DeployParams {
19        ChainAndUpExecLocation[] upgradeExecutors;
20        address govChainEmergencySecurityCouncil;
21        address l1ArbitrumTimelock;
22        address l2CoreGovTimelock;
23        address govChainProxyAdmin;
24        address[] secondCohort;
25        address[] firstCohort;
26        address l2UpgradeExecutor;
27        address arbToken;
28        uint256 l1TimelockMinDelay;
29        uint256 removalGovVotingDelay;
30        uint256 removalGovVotingPeriod;
31        uint256 removalGovQuorumNumerator;
32        uint256 removalGovProposalThreshold;
33        uint256 removalGovVoteSuccessNumerator;
34        uint64 removalGovMinPeriodAfterQuorum;
35        uint256 removalProposalExpirationBlocks;
36        SecurityCouncilData[] securityCouncils;
37        Date firstNominationStartDate;
38        uint256 nomineeVettingDuration;
39        address nomineeVetter;
40        uint256 nomineeQuorumNumerator;
41        uint256 nomineeVotingPeriod;
42        uint256 memberVotingPeriod;
43        uint256 fullWeightDuration;
44:   }

```
*GitHub*: [18](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L18-L44)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

/// @audit Variable ordering with 8 slots instead of the current 9:
///           user-defined(32):firstNominationStartDate, uint256(32):nomineeVettingDuration, uint256(32):quorumNumeratorValue, address(20):nomineeVetter, uint32(4):votingPeriod, user-defined(20):securityCouncilManager, user-defined(20):securityCouncilMemberElectionGovernor, user-defined(20):token, address(20):owner
38        struct InitParams {
39            Date firstNominationStartDate;
40            uint256 nomineeVettingDuration;
41            address nomineeVetter;
42            ISecurityCouncilManager securityCouncilManager;
43            ISecurityCouncilMemberElectionGovernor securityCouncilMemberElectionGovernor;
44            IVotesUpgradeable token;
45            address owner;
46            uint256 quorumNumeratorValue;
47            uint256 votingPeriod;
48:       }

```
*GitHub*: [38](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L38-L48)


### [G&#x2011;03] Using `storage` instead of `memory` for structs/arrays saves gas
When fetching data from a storage location, assigning the data to a `memory` variable causes all fields of the struct/array to be read from storage, which incurs a Gcoldsload (**2100 gas**) for *each* field of the struct/array. If the fields are read from the new memory variable, they incur an additional `MLOAD` rather than a cheap stack read. Instead of declearing the variable with the `memory` keyword, declaring the variable with the `storage` keyword and caching any fields that need to be re-read in stack variables, will be much cheaper, only incuring the Gcoldsload for the fields actually read. The only time it makes sense to read the whole struct/array into a `memory` variable, is if the full struct/array is being returned by the function, is being passed to a function that requires `memory`, or if the array/struct is being read from another `memory` array/struct

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

393:              SecurityCouncilData memory securityCouncilData = securityCouncils[i];

```
*GitHub*: [393](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L393)


### [G&#x2011;04] State variables should be cached in stack variables rather than re-reading them from storage
The instances below point to the second+ access of a state variable within a function. Caching of a state variable replaces each Gwarmaccess (**100 gas**) with a much cheaper stack read. Other less obvious fixes/optimizations include having local memory caches of state variable structs, or having local caches of state variable contracts/addresses.

*There are 34 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

/// @audit firstCohort on line 338
339:          for (uint256 i = 0; i < firstCohort.length; i++) {

/// @audit firstCohort on line 339
340:              members[i] = firstCohort[i];

/// @audit firstCohort on line 340
343:              members[firstCohort.length + i] = secondCohort[i];

/// @audit secondCohort on line 338
342:          for (uint256 i = 0; i < secondCohort.length; i++) {

/// @audit secondCohort on line 342
343:              members[firstCohort.length + i] = secondCohort[i];

/// @audit l2CoreGovTimelock on line 428
441:              delay: ArbitrumTimelock(l2CoreGovTimelock).getMinDelay()

/// @audit securityCouncils on line 251
252:              SecurityCouncilData storage existantSecurityCouncil = securityCouncils[i];

/// @audit securityCouncils on line 252
262:          securityCouncils.push(_securityCouncilData);

/// @audit securityCouncils on line 262
266:              securityCouncils.length

/// @audit securityCouncils on line 284
285:              SecurityCouncilData storage securityCouncilData = securityCouncils[i];

/// @audit securityCouncils on line 285
/// @audit securityCouncils on line 292
292:                      securityCouncils[securityCouncils.length - 1];

/// @audit securityCouncils on line 294
295:                  securityCouncils.pop();

/// @audit securityCouncils on line 295
299:                      securityCouncils.length

/// @audit securityCouncils on line 388
389:          bytes[] memory actionDatas = new bytes[](securityCouncils.length);

/// @audit securityCouncils on line 389
390:          uint256[] memory chainIds = new uint256[](securityCouncils.length);

/// @audit securityCouncils on line 390
392:          for (uint256 i = 0; i < securityCouncils.length; i++) {

/// @audit securityCouncils on line 392
393:              SecurityCouncilData memory securityCouncilData = securityCouncils[i];

/// @audit securityCouncils on line 393
409:              new uint256[](securityCouncils.length), // all values are always 0

/// @audit updateNonce on line 424
426:              getScheduleUpdateInnerData(updateNonce);

/// @audit updateNonce on line 426
440:              salt: this.generateSalt(newMembers, updateNonce),

/// @audit cohortSize on line 128
/// @audit cohortSize on line 129
129:              revert InvalidNewCohortLength({cohort: _newCohort, cohortSize: cohortSize});

```
*GitHub*: [339](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L339), [340](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L340), [343](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L343), [342](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L342), [343](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L343), [441](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L441), [252](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L252), [262](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L262), [266](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L266), [285](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L285), [292](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L292), [292](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L292), [295](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L295), [299](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L299), [389](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L389), [390](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L390), [392](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L392), [393](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L393), [409](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L409), [426](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L426), [440](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L440), [129](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L129), [129](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L129)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

/// @audit securityCouncilManager on line 117
135:              !securityCouncilManager.firstCohortIncludes(memberToRemove)

/// @audit securityCouncilManager on line 135
136:                  && !securityCouncilManager.secondCohortIncludes(memberToRemove)

```
*GitHub*: [135](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L135), [136](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L136)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

/// @audit securityCouncilManager on line 301
312:          if (securityCouncilManager.cohortIncludes(otherCohort(), account)) {

/// @audit electionCount on line 166
176:          ) = getProposeArgs(electionCount);

/// @audit electionCount on line 176
180:          electionCount++;

/// @audit electionCount on line 188
197:          ) = getProposeArgs(electionCount - 1);

/// @audit electionCount on line 390
390:          return electionCount == 0 ? Cohort.FIRST : electionIndexToCohort(electionCount - 1);

/// @audit electionCount on line 396
396:          return (electionCount < 2) ? Cohort.SECOND : electionIndexToCohort(electionCount - 2);

```
*GitHub*: [312](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L312), [176](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L176), [180](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L180), [197](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L197), [390](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L390), [396](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L396)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

/// @audit firstNominationStartDate on line 77
80:           uint256 year = firstNominationStartDate.year + month / 12;

/// @audit firstNominationStartDate on line 80
89:               day: firstNominationStartDate.day,

/// @audit firstNominationStartDate on line 89
90:               hour: firstNominationStartDate.hour,

```
*GitHub*: [80](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L80), [89](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L89), [90](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L90)


### [G&#x2011;05] Multiple accesses of a mapping/array should use a local variable cache
The instances below point to the second+ access of a value inside a mapping/array, within a function. Caching a mapping's value in a local `storage` or `calldata` variable when the value is accessed [multiple times](https://gist.github.com/IllIllI000/ec23a57daa30a8f8ca8b9681c8ccefb0), saves **~42 gas per access** due to not having to recalculate the key's keccak256 hash (Gkeccak256 - **30 gas**) and that calculation's associated stack operations. Caching an array's struct avoids recalculating the array offsets into memory/calldata

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

/// @audit _elections[proposalId] on line 122
123:          _elections[proposalId].isNominee[account] = true;

```
*GitHub*: [123](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L123)


### [G&#x2011;06] `internal` functions only called once can be inlined to save gas
Not inlining costs **20 to 40 gas** because of two extra `JUMP` instructions and additional stack operations needed for function calls.

*There are 6 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

76:       function _addMember(IGnosisSafe securityCouncil, address _member, uint256 _threshold)

85:       function _removeMember(IGnosisSafe securityCouncil, address _member, uint256 _threshold)

122:      function _setUpdateNonce(address securityCouncil, uint256 nonce) internal {

```
*GitHub*: [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L76), [85](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L85), [122](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L122)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

192       function _initRemovalGov(
193           DeployParams memory dp,
194           ISecurityCouncilManager _securityCouncilManager,
195:          SecurityCouncilMemberRemovalGovernor securityCouncilMemberRemoverGov

212       function _initElectionGovernors(
213           DeployParams memory dp,
214           ISecurityCouncilManager securityCouncilManager,
215           SecurityCouncilNomineeElectionGovernor nomineeElectionGovernor,
216:          SecurityCouncilMemberElectionGovernor memberElectionGovernor

```
*GitHub*: [192](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L192-L195), [212](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L212-L216)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

187       function _requireLastMemberElectionHasExecuted() internal view {
188:          if (electionCount == 0) {

```
*GitHub*: [187](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L187-L188)


### [G&#x2011;07] `<array>.length` should not be looked up in every loop of a `for`-loop
The overheads outlined below are _PER LOOP_, excluding the first loop
* storage arrays incur a Gwarmaccess (**100 gas**)
* memory arrays use `MLOAD` (**3 gas**)
* calldata arrays use `CALLDATALOAD` (**3 gas**)

Caching the length changes each of these to a `DUP<N>` (**3 gas**), and gets rid of the extra `DUP<N>` needed to store the stack offset

*There are 25 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

76:           for (uint256 i = 0; i < _upgradeExecutors.length; i++) {

129:          for (uint256 i = 0; i < chainIds.length; i++) {

193:          for (uint256 i = 0; i < chainIds.length; i++) {

```
*GitHub*: [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L76), [129](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L129), [193](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L193)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

61:           for (uint256 i = 0; i < array1.length; i++) {

63:               for (uint256 j = 0; j < array2.length; j++) {

74:           for (uint256 i = 0; i < array2.length; i++) {

76:               for (uint256 j = 0; j < array1.length; j++) {

```
*GitHub*: [61](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L61), [63](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L63), [74](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L74), [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L76)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

106:          for (uint256 i = 0; i < _roles.memberRemovers.length; i++) {

118:          for (uint256 i = 0; i < _securityCouncils.length; i++) {

135:          for (uint256 i = 0; i < _newCohort.length; i++) {

164:              for (uint256 j = 0; j < cohort.length; j++) {

251:          for (uint256 i = 0; i < securityCouncils.length; i++) {

284:          for (uint256 i = 0; i < securityCouncils.length; i++) {

339:          for (uint256 i = 0; i < firstCohort.length; i++) {

342:          for (uint256 i = 0; i < secondCohort.length; i++) {

392:          for (uint256 i = 0; i < securityCouncils.length; i++) {

```
*GitHub*: [106](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L106), [118](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L118), [135](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L135), [164](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L164), [251](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L251), [284](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L284), [339](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L339), [342](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L342), [392](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L392)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

60:           for (uint256 i = 0; i < _updatedMembers.length; i++) {

67:           for (uint256 i = 0; i < previousOwners.length; i++) {

105:          for (uint256 i = 0; i < owners.length; i++) {

```
*GitHub*: [60](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L60), [67](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L67), [105](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L105)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

6:            for (uint256 i = 0; i < arr.length; i++) {

22:           for (uint256 i = 0; i < input.length; i++) {

```
*GitHub*: [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L6), [22](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L22)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

111:          for (uint256 i = 0; i < dp.firstCohort.length; i++) {

117:          for (uint256 i = 0; i < dp.secondCohort.length; i++) {

```
*GitHub*: [111](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L111), [117](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L117)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

181:          for (uint256 i = 0; i < nominees.length; i++) {

205:          for (uint16 i = 0; i < nominees.length; i++) {

```
*GitHub*: [181](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L181), [205](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L205)

</details>

### [G&#x2011;08] `++i`/`i++` should be `unchecked{++i}`/`unchecked{i++}` when it is not possible for them to overflow, as is the case when used in `for`- and `while`-loops
The `unchecked` keyword is new in solidity version 0.8.0, so this only applies to that version or higher, which these instances are. This saves **30-40 gas [per loop](https://gist.github.com/hrkrshnn/ee8fabd532058307229d65dcd5836ddc#the-increment-in-for-loop-post-condition-can-be-made-unchecked)**

*There are 28 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

76:           for (uint256 i = 0; i < _upgradeExecutors.length; i++) {

129:          for (uint256 i = 0; i < chainIds.length; i++) {

193:          for (uint256 i = 0; i < chainIds.length; i++) {

```
*GitHub*: [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L76), [129](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L129), [193](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L193)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

61:           for (uint256 i = 0; i < array1.length; i++) {

63:               for (uint256 j = 0; j < array2.length; j++) {

74:           for (uint256 i = 0; i < array2.length; i++) {

76:               for (uint256 j = 0; j < array1.length; j++) {

```
*GitHub*: [61](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L61), [63](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L63), [74](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L74), [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L76)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

106:          for (uint256 i = 0; i < _roles.memberRemovers.length; i++) {

118:          for (uint256 i = 0; i < _securityCouncils.length; i++) {

135:          for (uint256 i = 0; i < _newCohort.length; i++) {

162:          for (uint256 i = 0; i < 2; i++) {

164:              for (uint256 j = 0; j < cohort.length; j++) {

251:          for (uint256 i = 0; i < securityCouncils.length; i++) {

284:          for (uint256 i = 0; i < securityCouncils.length; i++) {

339:          for (uint256 i = 0; i < firstCohort.length; i++) {

342:          for (uint256 i = 0; i < secondCohort.length; i++) {

392:          for (uint256 i = 0; i < securityCouncils.length; i++) {

```
*GitHub*: [106](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L106), [118](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L118), [135](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L135), [162](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L162), [164](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L164), [251](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L251), [284](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L284), [339](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L339), [342](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L342), [392](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L392)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

60:           for (uint256 i = 0; i < _updatedMembers.length; i++) {

67:           for (uint256 i = 0; i < previousOwners.length; i++) {

105:          for (uint256 i = 0; i < owners.length; i++) {

```
*GitHub*: [60](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L60), [67](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L67), [105](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L105)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

6:            for (uint256 i = 0; i < arr.length; i++) {

22:           for (uint256 i = 0; i < input.length; i++) {

31:           for (uint256 i = 0; i < intermediateLength; i++) {

```
*GitHub*: [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L6), [22](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L22), [31](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L31)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

111:          for (uint256 i = 0; i < dp.firstCohort.length; i++) {

117:          for (uint256 i = 0; i < dp.secondCohort.length; i++) {

```
*GitHub*: [111](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L111), [117](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L117)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

181:          for (uint256 i = 0; i < nominees.length; i++) {

205:          for (uint16 i = 0; i < nominees.length; i++) {

215:          for (uint16 i = 0; i < k; i++) {

```
*GitHub*: [181](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L181), [205](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L205), [215](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L215)

</details>

### [G&#x2011;09] `require()`/`revert()` strings longer than 32 bytes cost extra gas
Each extra memory word of bytes past the original 32 [incurs an MSTORE](https://gist.github.com/hrkrshnn/ee8fabd532058307229d65dcd5836ddc#consider-having-short-revert-strings) which costs **3 gas**

*There are 22 instances of this issue:*

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

72            require(
73                l2CoreGovTimelock.hasRole(
74                    TIMELOCK_PROPOSAL_ROLE, address(prevNonEmergencySecurityCouncil)
75                ),
76                "GovernanceChainSCMgmtActivationAction: prev nonemergency council doesn't have proposal role"
77:           );

78            require(
79                !l2CoreGovTimelock.hasRole(
80                    TIMELOCK_PROPOSAL_ROLE, address(newNonEmergencySecurityCouncil)
81                ),
82                "GovernanceChainSCMgmtActivationAction: new nonemergency council already has proposal role"
83:           );

92            require(
93                Address.isContract(securityCouncilManager),
94                "GovernanceChainSCMgmtActivationAction: manager address isn't a contract"
95:           );

97            require(
98                !l2CoreGovTimelock.hasRole(TIMELOCK_PROPOSAL_ROLE, securityCouncilManager),
99                "GovernanceChainSCMgmtActivationAction: securityCouncilManager already has proposal role"
100:          );

104           require(
105               l2CoreGovTimelock.hasRole(
106                   TIMELOCK_CANCELLER_ROLE, address(prevEmergencySecurityCouncil)
107               ),
108               "GovernanceChainSCMgmtActivationAction: prev emergency security council should have cancellor role"
109:          );

115           require(
116               upgradeExecutor.hasRole(EXECUTOR_ROLE, address(newEmergencySecurityCouncil)),
117               "NonGovernanceChainSCMgmtActivationAction: new emergency security council not set"
118:          );

119           require(
120               !upgradeExecutor.hasRole(EXECUTOR_ROLE, address(prevEmergencySecurityCouncil)),
121               "NonGovernanceChainSCMgmtActivationAction: prev emergency security council still set"
122:          );

124           require(
125               !l2CoreGovTimelock.hasRole(
126                   TIMELOCK_PROPOSAL_ROLE, address(prevNonEmergencySecurityCouncil)
127               ),
128               "GovernanceChainSCMgmtActivationAction: prev nonemergency council still has proposal role"
129:          );

130           require(
131               l2CoreGovTimelock.hasRole(
132                   TIMELOCK_PROPOSAL_ROLE, address(newNonEmergencySecurityCouncil)
133               ),
134               "GovernanceChainSCMgmtActivationAction: new nonemergency doesn't have proposal role"
135:          );

137           require(
138               l2CoreGovTimelock.hasRole(TIMELOCK_PROPOSAL_ROLE, securityCouncilManager),
139               "GovernanceChainSCMgmtActivationAction: securityCouncilManager doesn't have proposal role"
140:          );

141           require(
142               !l2CoreGovTimelock.hasRole(
143                   TIMELOCK_CANCELLER_ROLE, address(prevEmergencySecurityCouncil)
144               ),
145               "GovernanceChainSCMgmtActivationAction: prev emergency security council still has cancellor role"
146:          );

```
*GitHub*: [72](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L72-L77), [78](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L78-L83), [92](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L92-L95), [97](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L97-L100), [104](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L104-L109), [115](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L115-L118), [119](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L119-L122), [124](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L124-L129), [130](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L130-L135), [137](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L137-L140), [141](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L141-L146)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

41            require(
42                l1Timelock.hasRole(TIMELOCK_CANCELLER_ROLE, address(prevEmergencySecurityCouncil)),
43                "GovernanceChainSCMgmtActivationAction: prev emergency security council should have cancellor role"
44:           );

45            require(
46                !l1Timelock.hasRole(TIMELOCK_CANCELLER_ROLE, address(l1UpgradeExecutor)),
47                "GovernanceChainSCMgmtActivationAction: l1UpgradeExecutor already has cancellor role"
48:           );

54            require(
55                l1Timelock.hasRole(TIMELOCK_CANCELLER_ROLE, address(l1UpgradeExecutor)),
56                "GovernanceChainSCMgmtActivationAction: l1UpgradeExecutor canceller role not set"
57:           );

58            require(
59                !l1Timelock.hasRole(TIMELOCK_CANCELLER_ROLE, address(prevEmergencySecurityCouncil)),
60                "GovernanceChainSCMgmtActivationAction: prevEmergencySecurityCouncil canceller role not revoked"
61:           );

```
*GitHub*: [41](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L41-L44), [45](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L45-L48), [54](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L54-L57), [58](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L58-L61)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

36            require(
37                upgradeExecutor.hasRole(EXECUTOR_ROLE, address(newEmergencySecurityCouncil)),
38                "NonGovernanceChainSCMgmtActivationAction: new emergency security council not set"
39:           );

40            require(
41                !upgradeExecutor.hasRole(EXECUTOR_ROLE, address(prevEmergencySecurityCouncil)),
42                "NonGovernanceChainSCMgmtActivationAction: prev emergency security council still set"
43:           );

```
*GitHub*: [36](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L36-L39), [40](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L40-L43)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

16            require(
17                _upgradeExecutor.hasRole(EXECUTOR_ROLE, address(_prevSecurityCouncil)),
18                "SecurityCouncilMgmtUpgradeLib: prev council not executor"
19:           );

20            require(
21                !_upgradeExecutor.hasRole(EXECUTOR_ROLE, address(_newSecurityCouncil)),
22                "SecurityCouncilMgmtUpgradeLib: new council already executor"
23:           );

35            require(
36                _safe1.getThreshold() == newSecurityCouncilThreshold,
37                "SecurityCouncilMgmtUpgradeLib: threshold mismatch"
38:           );

39            require(
40                newSecurityCouncilThreshold == _expectedThreshold,
41                "SecurityCouncilMgmtUpgradeLib: unexpected threshold"
42:           );

46            require(
47                areAddressArraysEqual(prevOwners, newOwners),
48                "SecurityCouncilMgmtUpgradeLib: owners mismatch"
49:           );

```
*GitHub*: [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L16-L19), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L20-L23), [35](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L35-L38), [39](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L39-L42), [46](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L46-L49)


### [G&#x2011;10] Optimize names to save gas
`public`/`external` function names and `public` member variable names can be optimized to save gas. See [this](https://gist.github.com/IllIllI000/a5d8b486a8259f9f77891a919febd1a9) link for an example of how it works. Below are the interfaces/abstract contracts that can be optimized so that the most frequently-called functions use the least amount of gas possible during method lookup. Method IDs that have two leading zero bytes can save **128 gas** each during deployment, and renaming functions to have lower method IDs will save **22 gas** per call, [per sorted position shifted](https://medium.com/joyso/solidity-how-does-function-name-affect-gas-consumption-in-smart-contract-47d270d8ac92)

*There are 11 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

/// @audit upExecLocationExists(), createActionRouteData(), createActionRouteDataWithDefaults()
39:   contract UpgradeExecRouteBuilder {

```
*GitHub*: [39](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L39)

```solidity
File: src/gov-action-contracts/execution-record/KeyValueStore.sol

/// @audit set(), get(), get(), computeKey()
6:    contract KeyValueStore {

```
*GitHub*: [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L6)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

/// @audit initialize(), replaceCohort(), addMember(), removeMember(), replaceMember(), rotateMember(), addSecurityCouncil(), removeSecurityCouncil(), setUpgradeExecRouteBuilder(), getFirstCohort(), getSecondCohort(), getBothCohorts(), securityCouncilsLength(), firstCohortIncludes(), secondCohortIncludes(), cohortIncludes(), generateSalt(), getScheduleUpdateInnerData()
28:   contract SecurityCouncilManager is

```
*GitHub*: [28](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L28)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

/// @audit perform(), getPrevOwner(), getUpdateNonce()
10:   contract SecurityCouncilMemberSyncAction is ActionExecutionRecord {

```
*GitHub*: [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L10)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

/// @audit initialize(), proposeFromNomineeElectionGovernor()
17:   contract SecurityCouncilMemberElectionGovernor is

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L17)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

/// @audit initialize(), separateSelector(), setVoteSuccessNumerator()
17:   contract SecurityCouncilMemberRemovalGovernor is

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L17)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

/// @audit initialize(), createElection(), addContender(), setNomineeVetter(), excludeNominee(), includeNominee(), isCompliantNominee(), compliantNominees(), compliantNomineeCount(), currentCohort(), otherCohort(), isExcluded(), excludedNomineeCount()
16:   contract SecurityCouncilNomineeElectionGovernor is

```
*GitHub*: [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L16)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

/// @audit getProposeArgs(), electionIndexToDescription(), electionIndexToCohort()
9:    contract ElectionGovernor {

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L9)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

/// @audit setFullWeightDuration(), votesUsed(), weightReceived(), fullWeightVotingDeadline(), topNominees(), selectTopNominees(), votesToWeight()
13:   abstract contract SecurityCouncilMemberElectionGovernorCountingUpgradeable is

```
*GitHub*: [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L13)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

/// @audit isNominee(), nomineeCount(), nominees(), votesUsed(), votesReceived(), isContender()
10:   abstract contract SecurityCouncilNomineeElectionGovernorCountingUpgradeable is

```
*GitHub*: [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L10)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

/// @audit proposalVettingDeadline(), electionToTimestamp()
12:   abstract contract SecurityCouncilNomineeElectionGovernorTiming is

```
*GitHub*: [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L12)

</details>

### [G&#x2011;11] It costs more gas to initialize non-`constant`/non-`immutable` state variables to zero than to let the default of zero be applied
Not overwriting the default for storage variables avoids a Gsreset ([**2900 gas**](https://gist.github.com/IllIllI000/85b09af2291f626095eb11403ddc74f1)) during deployment

*There is one instance of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

54:       bytes32 public constant DEFAULT_PREDECESSOR = bytes32(0);

```
*GitHub*: [54](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L54)


### [G&#x2011;12] `++i` costs less gas than `i++`, especially when it's used in `for`-loops (`--i`/`i--` too)
Saves **5 gas per loop**

*There are 32 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

76:           for (uint256 i = 0; i < _upgradeExecutors.length; i++) {

129:          for (uint256 i = 0; i < chainIds.length; i++) {

193:          for (uint256 i = 0; i < chainIds.length; i++) {

```
*GitHub*: [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L76), [129](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L129), [193](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L193)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

61:           for (uint256 i = 0; i < array1.length; i++) {

63:               for (uint256 j = 0; j < array2.length; j++) {

74:           for (uint256 i = 0; i < array2.length; i++) {

76:               for (uint256 j = 0; j < array1.length; j++) {

```
*GitHub*: [61](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L61), [63](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L63), [74](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L74), [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L76)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

106:          for (uint256 i = 0; i < _roles.memberRemovers.length; i++) {

118:          for (uint256 i = 0; i < _securityCouncils.length; i++) {

135:          for (uint256 i = 0; i < _newCohort.length; i++) {

162:          for (uint256 i = 0; i < 2; i++) {

164:              for (uint256 j = 0; j < cohort.length; j++) {

251:          for (uint256 i = 0; i < securityCouncils.length; i++) {

284:          for (uint256 i = 0; i < securityCouncils.length; i++) {

339:          for (uint256 i = 0; i < firstCohort.length; i++) {

342:          for (uint256 i = 0; i < secondCohort.length; i++) {

392:          for (uint256 i = 0; i < securityCouncils.length; i++) {

424:          updateNonce++;

```
*GitHub*: [106](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L106), [118](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L118), [135](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L135), [162](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L162), [164](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L164), [251](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L251), [284](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L284), [339](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L339), [342](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L342), [392](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L392), [424](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L424)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

60:           for (uint256 i = 0; i < _updatedMembers.length; i++) {

67:           for (uint256 i = 0; i < previousOwners.length; i++) {

105:          for (uint256 i = 0; i < owners.length; i++) {

```
*GitHub*: [60](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L60), [67](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L67), [105](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L105)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

6:            for (uint256 i = 0; i < arr.length; i++) {

22:           for (uint256 i = 0; i < input.length; i++) {

26:                   intermediateLength++;

31:           for (uint256 i = 0; i < intermediateLength; i++) {

```
*GitHub*: [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L6), [22](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L22), [26](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L26), [31](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L31)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

111:          for (uint256 i = 0; i < dp.firstCohort.length; i++) {

117:          for (uint256 i = 0; i < dp.secondCohort.length; i++) {

```
*GitHub*: [111](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L111), [117](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L117)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

180:          electionCount++;

280:          election.excludedNomineeCount++;

```
*GitHub*: [180](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L180), [280](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L280)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

181:          for (uint256 i = 0; i < nominees.length; i++) {

205:          for (uint16 i = 0; i < nominees.length; i++) {

215:          for (uint16 i = 0; i < k; i++) {

```
*GitHub*: [181](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L181), [205](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L205), [215](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L215)

</details>

### [G&#x2011;13] Using `private` rather than `public` for constants, saves gas
If needed, the values can be read from the verified contract source code, or if there are multiple values there can be a single getter function that [returns a tuple](https://github.com/code-423n4/2022-08-frax/blob/90f55a9ce4e25bceed3a74290b854341d8de6afa/src/contracts/FraxlendPair.sol#L156-L178) of the values of all currently-public constants. Saves **3406-3606 gas** in deployment gas due to the compiler not having to create non-payable getter functions for deployment calldata, not having to store the bytes of the value outside of where it's used, and not adding another entry to the method ID table

*There are 16 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

50        bytes public constant DEFAULT_GOV_ACTION_CALLDATA =
51:           abi.encodeWithSelector(DefaultGovAction.perform.selector);

52:       uint256 public constant DEFAULT_VALUE = 0;

54:       bytes32 public constant DEFAULT_PREDECESSOR = bytes32(0);

60:       uint256 public immutable l1TimelockMinDelay;

```
*GitHub*: [50](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L50-L51), [52](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L52), [54](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L54), [60](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L60)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

19:       uint256 public immutable emergencySecurityCouncilThreshold;

20:       uint256 public immutable nonEmergencySecurityCouncilThreshold;

```
*GitHub*: [19](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L19), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L20)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

12:       uint256 public immutable emergencySecurityCouncilThreshold;

```
*GitHub*: [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L12)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

10:       uint256 public immutable emergencySecurityCouncilThreshold;

```
*GitHub*: [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L10)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

16:       bytes32 public immutable actionContractId;

```
*GitHub*: [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L16)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

67:       uint256 public immutable MAX_SECURITY_COUNCILS = 500;

79:       bytes32 public constant COHORT_REPLACER_ROLE = keccak256("COHORT_REPLACER");

80:       bytes32 public constant MEMBER_ADDER_ROLE = keccak256("MEMBER_ADDER");

81:       bytes32 public constant MEMBER_REPLACER_ROLE = keccak256("MEMBER_REPLACER");

82:       bytes32 public constant MEMBER_ROTATOR_ROLE = keccak256("MEMBER_ROTATOR");

83:       bytes32 public constant MEMBER_REMOVER_ROLE = keccak256("MEMBER_REMOVER");

```
*GitHub*: [67](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L67), [79](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L79), [80](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L80), [81](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L81), [82](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L82), [83](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L83)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

28:       uint256 public constant voteSuccessDenominator = 10_000;

```
*GitHub*: [28](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L28)

</details>

### [G&#x2011;14] Stack variable used as a cheaper cache for a state variable is only used once
If the variable is only accessed once, it's cheaper to use the state variable directly that one time, and save the **3 gas** the extra stack assignment would spend

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

247:          address oldNomineeVetter = nomineeVetter;

```
*GitHub*: [247](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L247)


### [G&#x2011;15] Use custom errors rather than `revert()`/`require()` strings to save gas
Custom errors are available from solidity version 0.8.4. Custom errors save [**~50 gas**](https://gist.github.com/IllIllI000/ad1bd0d29a0101b25e57c293b4b0c746) each time they're hit by [avoiding having to allocate and store the revert string](https://blog.soliditylang.org/2021/04/21/custom-errors/#errors-in-depth). Not defining the strings also save deployment gas

*There are 22 instances of this issue:*

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

72            require(
73                l2CoreGovTimelock.hasRole(
74                    TIMELOCK_PROPOSAL_ROLE, address(prevNonEmergencySecurityCouncil)
75                ),
76                "GovernanceChainSCMgmtActivationAction: prev nonemergency council doesn't have proposal role"
77:           );

78            require(
79                !l2CoreGovTimelock.hasRole(
80                    TIMELOCK_PROPOSAL_ROLE, address(newNonEmergencySecurityCouncil)
81                ),
82                "GovernanceChainSCMgmtActivationAction: new nonemergency council already has proposal role"
83:           );

92            require(
93                Address.isContract(securityCouncilManager),
94                "GovernanceChainSCMgmtActivationAction: manager address isn't a contract"
95:           );

97            require(
98                !l2CoreGovTimelock.hasRole(TIMELOCK_PROPOSAL_ROLE, securityCouncilManager),
99                "GovernanceChainSCMgmtActivationAction: securityCouncilManager already has proposal role"
100:          );

104           require(
105               l2CoreGovTimelock.hasRole(
106                   TIMELOCK_CANCELLER_ROLE, address(prevEmergencySecurityCouncil)
107               ),
108               "GovernanceChainSCMgmtActivationAction: prev emergency security council should have cancellor role"
109:          );

115           require(
116               upgradeExecutor.hasRole(EXECUTOR_ROLE, address(newEmergencySecurityCouncil)),
117               "NonGovernanceChainSCMgmtActivationAction: new emergency security council not set"
118:          );

119           require(
120               !upgradeExecutor.hasRole(EXECUTOR_ROLE, address(prevEmergencySecurityCouncil)),
121               "NonGovernanceChainSCMgmtActivationAction: prev emergency security council still set"
122:          );

124           require(
125               !l2CoreGovTimelock.hasRole(
126                   TIMELOCK_PROPOSAL_ROLE, address(prevNonEmergencySecurityCouncil)
127               ),
128               "GovernanceChainSCMgmtActivationAction: prev nonemergency council still has proposal role"
129:          );

130           require(
131               l2CoreGovTimelock.hasRole(
132                   TIMELOCK_PROPOSAL_ROLE, address(newNonEmergencySecurityCouncil)
133               ),
134               "GovernanceChainSCMgmtActivationAction: new nonemergency doesn't have proposal role"
135:          );

137           require(
138               l2CoreGovTimelock.hasRole(TIMELOCK_PROPOSAL_ROLE, securityCouncilManager),
139               "GovernanceChainSCMgmtActivationAction: securityCouncilManager doesn't have proposal role"
140:          );

141           require(
142               !l2CoreGovTimelock.hasRole(
143                   TIMELOCK_CANCELLER_ROLE, address(prevEmergencySecurityCouncil)
144               ),
145               "GovernanceChainSCMgmtActivationAction: prev emergency security council still has cancellor role"
146:          );

```
*GitHub*: [72](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L72-L77), [78](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L78-L83), [92](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L92-L95), [97](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L97-L100), [104](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L104-L109), [115](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L115-L118), [119](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L119-L122), [124](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L124-L129), [130](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L130-L135), [137](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L137-L140), [141](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L141-L146)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

41            require(
42                l1Timelock.hasRole(TIMELOCK_CANCELLER_ROLE, address(prevEmergencySecurityCouncil)),
43                "GovernanceChainSCMgmtActivationAction: prev emergency security council should have cancellor role"
44:           );

45            require(
46                !l1Timelock.hasRole(TIMELOCK_CANCELLER_ROLE, address(l1UpgradeExecutor)),
47                "GovernanceChainSCMgmtActivationAction: l1UpgradeExecutor already has cancellor role"
48:           );

54            require(
55                l1Timelock.hasRole(TIMELOCK_CANCELLER_ROLE, address(l1UpgradeExecutor)),
56                "GovernanceChainSCMgmtActivationAction: l1UpgradeExecutor canceller role not set"
57:           );

58            require(
59                !l1Timelock.hasRole(TIMELOCK_CANCELLER_ROLE, address(prevEmergencySecurityCouncil)),
60                "GovernanceChainSCMgmtActivationAction: prevEmergencySecurityCouncil canceller role not revoked"
61:           );

```
*GitHub*: [41](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L41-L44), [45](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L45-L48), [54](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L54-L57), [58](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L58-L61)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

36            require(
37                upgradeExecutor.hasRole(EXECUTOR_ROLE, address(newEmergencySecurityCouncil)),
38                "NonGovernanceChainSCMgmtActivationAction: new emergency security council not set"
39:           );

40            require(
41                !upgradeExecutor.hasRole(EXECUTOR_ROLE, address(prevEmergencySecurityCouncil)),
42                "NonGovernanceChainSCMgmtActivationAction: prev emergency security council still set"
43:           );

```
*GitHub*: [36](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L36-L39), [40](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L40-L43)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

16            require(
17                _upgradeExecutor.hasRole(EXECUTOR_ROLE, address(_prevSecurityCouncil)),
18                "SecurityCouncilMgmtUpgradeLib: prev council not executor"
19:           );

20            require(
21                !_upgradeExecutor.hasRole(EXECUTOR_ROLE, address(_newSecurityCouncil)),
22                "SecurityCouncilMgmtUpgradeLib: new council already executor"
23:           );

35            require(
36                _safe1.getThreshold() == newSecurityCouncilThreshold,
37                "SecurityCouncilMgmtUpgradeLib: threshold mismatch"
38:           );

39            require(
40                newSecurityCouncilThreshold == _expectedThreshold,
41                "SecurityCouncilMgmtUpgradeLib: unexpected threshold"
42:           );

46            require(
47                areAddressArraysEqual(prevOwners, newOwners),
48                "SecurityCouncilMgmtUpgradeLib: owners mismatch"
49:           );

```
*GitHub*: [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L16-L19), [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L20-L23), [35](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L35-L38), [39](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L39-L42), [46](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L46-L49)


### [G&#x2011;16] Functions guaranteed to revert when called by normal users can be marked `payable`
If a function modifier such as `onlyOwner` is used, the function will revert if a normal user tries to pay the function. Marking the function as `payable` will lower the gas cost for legitimate callers because the compiler will not include checks for whether a payment was provided. The extra opcodes avoided are 
`CALLVALUE`(2),`DUP1`(3),`ISZERO`(3),`PUSH2`(3),`JUMPI`(10),`PUSH1`(3),`DUP1`(3),`REVERT`(0),`JUMPDEST`(1),`POP`(2), which costs an average of about **21 gas per call** to the function, in addition to the extra deployment cost

*There are 22 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

124       function replaceCohort(address[] memory _newCohort, Cohort _cohort)
125           external
126:          onlyRole(COHORT_REPLACER_ROLE)

176:      function addMember(address _newMember, Cohort _cohort) external onlyRole(MEMBER_ADDER_ROLE) {

183:      function removeMember(address _member) external onlyRole(MEMBER_REMOVER_ROLE) {

193       function replaceMember(address _memberToReplace, address _newMember)
194           external
195:          onlyRole(MEMBER_REPLACER_ROLE)

206       function rotateMember(address _currentAddress, address _newAddress)
207           external
208:          onlyRole(MEMBER_ROTATOR_ROLE)

271       function addSecurityCouncil(SecurityCouncilData memory _securityCouncilData)
272           external
273:          onlyRole(DEFAULT_ADMIN_ROLE)

279       function removeSecurityCouncil(SecurityCouncilData memory _securityCouncilData)
280           external
281           onlyRole(DEFAULT_ADMIN_ROLE)
282:          returns (bool)

308       function setUpgradeExecRouteBuilder(UpgradeExecRouteBuilder _router)
309           external
310:          onlyRole(DEFAULT_ADMIN_ROLE)

```
*GitHub*: [124](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L124-L126), [176](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L176), [183](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L183), [193](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L193-L195), [206](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L206-L208), [271](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L271-L273), [279](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L279-L282), [308](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L308-L310)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

81        function deploy(DeployParams memory dp, ContractImplementations memory impls)
82            external
83            onlyOwner
84:           returns (DeployedContracts memory)

```
*GitHub*: [81](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L81-L84)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

86        function proposeFromNomineeElectionGovernor(uint256 electionIndex)
87            external
88            onlyNomineeElectionGovernor
89:           returns (uint256)

103       function relay(address target, uint256 value, bytes calldata data)
104           external
105           virtual
106           override
107:          onlyOwner

```
*GitHub*: [86](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L86-L89), [103](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L103-L107)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

178:      function setVoteSuccessNumerator(uint256 _voteSuccessNumerator) public onlyOwner {

203       function relay(address target, uint256 value, bytes calldata data)
204           external
205           virtual
206           override
207:          onlyOwner

```
*GitHub*: [178](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L178), [203](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L203-L207)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

246:      function setNomineeVetter(address _nomineeVetter) external onlyGovernance {

254       function relay(address target, uint256 value, bytes calldata data)
255           external
256           virtual
257           override
258:          onlyOwner

266       function excludeNominee(uint256 proposalId, address nominee)
267           external
268           onlyNomineeVetter
269:          onlyVettingPeriod(proposalId)

290:      function includeNominee(uint256 proposalId, address account) external onlyNomineeVetter {

```
*GitHub*: [246](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L246), [254](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L254-L258), [266](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L266-L269), [290](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L290)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

24        function __ArbitrumGovernorVotesQuorumFraction_init(uint256 quorumNumeratorValue)
25            internal
26:           onlyInitializing

```
*GitHub*: [24](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L24-L26)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

68        function __SecurityCouncilMemberElectionGovernorCounting_init(uint256 initialFullWeightDuration)
69            internal
70:           onlyInitializing

77:       function setFullWeightDuration(uint256 newFullWeightDuration) public onlyGovernance {

```
*GitHub*: [68](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L68-L70), [77](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L77)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

52:       function __SecurityCouncilNomineeElectionGovernorCounting_init() internal onlyInitializing {}

```
*GitHub*: [52](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L52)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

28        function __SecurityCouncilNomineeElectionGovernorTiming_init(
29            Date memory _firstNominationStartDate,
30            uint256 _nomineeVettingDuration
31:       ) internal onlyInitializing {

```
*GitHub*: [28](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L28-L31)

</details>

### [G&#x2011;17] Constructors can be marked `payable`
Payable functions cost less gas to execute, since the compiler does not have to add extra checks to ensure that a payment wasn't provided. A constructor can safely be marked as payable, since only the deployer would be able to pass funds, and the project itself would not pass any funds.

*There are 10 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

67        constructor(
68            ChainAndUpExecLocation[] memory _upgradeExecutors,
69            address _l1ArbitrumTimelock,
70:           uint256 _l1TimelockMinDelay

```
*GitHub*: [67](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L67-L70)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

25        constructor(
26            IGnosisSafe _newEmergencySecurityCouncil,
27            IGnosisSafe _newNonEmergencySecurityCouncil,
28            IGnosisSafe _prevEmergencySecurityCouncil,
29            IGnosisSafe _prevNonEmergencySecurityCouncil,
30            uint256 _emergencySecurityCouncilThreshold,
31            uint256 _nonEmergencySecurityCouncilThreshold,
32            address _securityCouncilManager,
33:           IL2AddressRegistry _l2AddressRegistry

```
*GitHub*: [25](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L25-L33)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

16        constructor(
17            IGnosisSafe _newEmergencySecurityCouncil,
18            IGnosisSafe _prevEmergencySecurityCouncil,
19            uint256 _emergencySecurityCouncilThreshold,
20            IUpgradeExecutor _l1UpgradeExecutor,
21:           ICoreTimelock _l1Timelock

```
*GitHub*: [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L16-L21)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

13        constructor(
14            IGnosisSafe _newEmergencySecurityCouncil,
15            IGnosisSafe _prevEmergencySecurityCouncil,
16            uint256 _emergencySecurityCouncilThreshold,
17:           IUpgradeExecutor _upgradeExecutor

```
*GitHub*: [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L13-L17)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

18:       constructor(KeyValueStore _store, string memory _uniqueActionName) {

```
*GitHub*: [18](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L18)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

85        constructor() {
86:           _disableInitializers();

```
*GitHub*: [85](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L85-L86)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

21        constructor(KeyValueStore _store)
22:           ActionExecutionRecord(_store, "SecurityCouncilMemberSyncAction")

```
*GitHub*: [21](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L21-L22)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

38        constructor() {
39:           _disableInitializers();

```
*GitHub*: [38](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L38-L39)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

44        constructor() {
45:           _disableInitializers();

```
*GitHub*: [44](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L44-L45)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

98        constructor() {
99:           _disableInitializers();

```
*GitHub*: [98](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L98-L99)

</details>

### [G&#x2011;18] Not using the named return variables anywhere in the function is confusing
Consider changing the variable to be an unnamed one, since the variable is never assigned, nor is it returned by name. If the optimizer is not turned on, leaving the code as it is will also waste gas for the stack variable.

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

/// @audit res
31        function perform(address _securityCouncil, address[] memory _updatedMembers, uint256 _nonce)
32            external
33:           returns (bool res)

```
*GitHub*: [31](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L31-L33)


### [G&#x2011;19] Use assembly to emit events, in order to save gas
Using the [scratch space](https://github.com/Vectorized/solady/blob/30558f5402f02351b96eeb6eaf32bcea29773841/src/tokens/ERC1155.sol#L501-L504) for event arguments (two words or fewer) will save gas over needing Solidity's full abi memory expansion used for emitting normally.

*There are 13 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

140:         emit CohortReplaced(_newCohort, _cohort);

179:         emit MemberAdded(_newMember, _cohort);

189:         emit MemberRemoved({member: _member, cohort: cohort});

323:         emit UpgradeExecRouteBuilderSet(routerAddress);

```
*GitHub*: [140](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L140-L140), [179](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L179-L179), [189](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L189-L189), [323](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L323-L323)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

187:         emit ContractsDeployed(deployedContracts);

```
*GitHub*: [187](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L187-L187)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

141:         emit MemberRemovalProposed(memberToRemove, description);

187:         emit VoteSuccessNumeratorSet(_voteSuccessNumerator);

```
*GitHub*: [141](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L141-L141), [187](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L187-L187)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

242:         emit ContenderAdded(proposalId, msg.sender);

249:         emit NomineeVetterChanged(oldNomineeVetter, _nomineeVetter);

282:         emit NomineeExcluded(proposalId, nominee);

```
*GitHub*: [242](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L242-L242), [249](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L249-L249), [282](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L282-L282)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

73:          emit FullWeightDurationSet(initialFullWeightDuration);

83:          emit FullWeightDurationSet(newFullWeightDuration);

```
*GitHub*: [73](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L73-L73), [83](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L83-L83)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

124:         emit NewNominee(proposalId, account);

```
*GitHub*: [124](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L124-L124)


### [G&#x2011;20] Use assembly for small keccak256 hashes, in order to save gas
If the arguments to the encode call can fit into the scratch space (two words or fewer), then it's more efficient to use assembly to generate the hash (**80 gas**):
`keccak256(abi.encodePacked(x, y))` -> `assembly {mstore(0x00, a); mstore(0x20, b); let hash := keccak256(0x00, 0x40); }`

*There are 3 instances of this issue:*

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

38:          return uint256(keccak256(abi.encode(actionContractId, key)));

```
*GitHub*: [38](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L38-L38)

```solidity
File: src/gov-action-contracts/execution-record/KeyValueStore.sol

27:          return uint256(keccak256(abi.encode(owner, key)));

```
*GitHub*: [27](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L27-L27)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

375:         return keccak256(abi.encodePacked(_members, nonce));

```
*GitHub*: [375](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L375-L375)


### [G&#x2011;21] Events should be emitted outside of loops
Emitting an event has an overhead of **375 gas**, which will be incurred on every iteration of the loop. It is cheaper to `emit` only [once](https://github.com/ethereum/EIPs/blob/adad5968fd6de29902174e0cb51c8fc3dceb9ab5/EIPS/eip-1155.md?plain=1#L68) after the loop has finished.

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

296                  emit SecurityCouncilRemoved(
297                      securityCouncilData.securityCouncil,
298                      securityCouncilData.updateAction,
299                      securityCouncils.length
300:                 );

```
*GitHub*: [296](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L296-L300)


### [G&#x2011;22] `internal` functions not called by the contract should be removed to save deployment gas
If the functions are required by an interface, the contract should inherit from that interface and use the `override` keyword

*There are 9 instances of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

115      function _execute(
116          uint256 proposalId,
117          address[] memory, /* targets */
118          uint256[] memory, /* values */
119          bytes[] memory callDatas,
120          bytes32 /* descriptionHash */
121:     ) internal override {

154      function _isCompliantNominee(uint256 proposalId, address possibleNominee)
155          internal
156          view
157          override
158          returns (bool)
159:     {

164      function _compliantNominees(uint256 proposalId)
165          internal
166          view
167          override
168          returns (address[] memory)
169:     {

174:     function _targetMemberCount() internal view override returns (uint256) {

```
*GitHub*: [115](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L115-L121), [154](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L154-L159), [164](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L164-L169), [174](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L174-L174)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

223      function _castVote(
224          uint256 proposalId,
225          address account,
226          uint8 support,
227          string memory reason,
228          bytes memory params
229      )
230          internal
231          override(GovernorUpgradeable, GovernorPreventLateQuorumUpgradeable)
232          returns (uint256)
233:     {

```
*GitHub*: [223](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L223-L233)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

267:     function _quorumReached(uint256) internal pure override returns (bool) {

273:     function _voteSucceeded(uint256) internal pure override returns (bool) {

```
*GitHub*: [267](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L267-L267), [273](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L273-L273)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

170:     function _quorumReached(uint256) internal pure override returns (bool) {

175:     function _voteSucceeded(uint256) internal pure override returns (bool) {

```
*GitHub*: [170](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L170-L170), [175](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L175-L175)


### [G&#x2011;23] Reduce gas usage by moving to Solidity 0.8.19 or later
See [this](https://blog.soliditylang.org/2023/02/22/solidity-0.8.19-release-announcement/#preventing-dead-code-in-runtime-bytecode) link for the full details

*There are 20 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L2-L2)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L2-L2)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L2-L2)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L2-L2)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L2-L2)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L2-L2)

```solidity
File: src/gov-action-contracts/execution-record/KeyValueStore.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L2-L2)

```solidity
File: src/security-council-mgmt/Common.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/Common.sol#L2-L2)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L2-L2)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L2-L2)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L2-L2)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L2-L2)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L2-L2)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L2-L2)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L2-L2)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L2-L2)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

3:   pragma solidity 0.8.16;

```
*GitHub*: [3](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L3-L3)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L2-L2)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L2-L2)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

2:   pragma solidity 0.8.16;

```
*GitHub*: [2](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L2-L2)

</details>

### [G&#x2011;24] Add `unchecked {}` for subtractions where the operands cannot underflow because of a previous `require()` or `if`-statement
`require(a <= b); x = b - a` => `require(a <= b); unchecked { x = b - a }`

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

390:         return electionCount == 0 ? Cohort.FIRST : electionIndexToCohort(electionCount - 1);

```
*GitHub*: [390](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L390-L390)


### [G&#x2011;25] Avoid updating storage when the value hasn't changed
If the old value is equal to the new value, not re-storing the value will avoid a Gsreset (**2900 gas**), potentially at the expense of a Gcoldsload (**2100 gas**) or a Gwarmaccess (**100 gas**)

*There are 4 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

315      function _setUpgradeExecRouteBuilder(UpgradeExecRouteBuilder _router) internal {
316          address routerAddress = address(_router);
317  
318          if (!Address.isContract(routerAddress)) {
319              revert NotAContract({account: routerAddress});
320          }
321  
322          router = _router;
323          emit UpgradeExecRouteBuilderSet(routerAddress);
324:     }

```
*GitHub*: [315](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L315-L324)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

182      function _setVoteSuccessNumerator(uint256 _voteSuccessNumerator) internal {
183          if (!(0 < _voteSuccessNumerator && _voteSuccessNumerator <= voteSuccessDenominator)) {
184              revert InvalidVoteSuccessNumerator(_voteSuccessNumerator);
185          }
186          voteSuccessNumerator = _voteSuccessNumerator;
187          emit VoteSuccessNumeratorSet(_voteSuccessNumerator);
188:     }

```
*GitHub*: [182](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L182-L188)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

246      function setNomineeVetter(address _nomineeVetter) external onlyGovernance {
247          address oldNomineeVetter = nomineeVetter;
248          nomineeVetter = _nomineeVetter;
249          emit NomineeVetterChanged(oldNomineeVetter, _nomineeVetter);
250:     }

```
*GitHub*: [246](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L246-L250)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

77       function setFullWeightDuration(uint256 newFullWeightDuration) public onlyGovernance {
78           if (newFullWeightDuration > votingPeriod()) {
79               revert FullWeightDurationGreaterThanVotingPeriod(newFullWeightDuration, votingPeriod());
80           }
81   
82           fullWeightDuration = newFullWeightDuration;
83           emit FullWeightDurationSet(newFullWeightDuration);
84:      }

```
*GitHub*: [77](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L77-L84)


### [G&#x2011;26] State variable read in a loop
The state variable should be cached in a local variable rather than reading it on every iteration of the for-loop, which will replace each Gwarmaccess (**100 gas**) with a much cheaper stack read.

*There are 11 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

/// @audit MEMBER_REMOVER_ROLE
107:             _grantRole(MEMBER_REMOVER_ROLE, _roles.memberRemovers[i]);

/// @audit secondCohort
/// @audit firstCohort
163:             address[] storage cohort = i == 0 ? firstCohort : secondCohort;

/// @audit securityCouncils
251:         for (uint256 i = 0; i < securityCouncils.length; i++) {

/// @audit securityCouncils
292:                     securityCouncils[securityCouncils.length - 1];

/// @audit securityCouncils
299:                     securityCouncils.length

/// @audit securityCouncils
284:         for (uint256 i = 0; i < securityCouncils.length; i++) {

/// @audit firstCohort
339:         for (uint256 i = 0; i < firstCohort.length; i++) {

/// @audit firstCohort
343:             members[firstCohort.length + i] = secondCohort[i];

/// @audit secondCohort
342:         for (uint256 i = 0; i < secondCohort.length; i++) {

/// @audit securityCouncils
392:         for (uint256 i = 0; i < securityCouncils.length; i++) {

```
*GitHub*: [107](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L107-L107), [163](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L163-L163), [163](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L163-L163), [251](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L251-L251), [292](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L292-L292), [299](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L299-L299), [284](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L284-L284), [339](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L339-L339), [343](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L343-L343), [342](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L342-L342), [392](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L392-L392)


### [G&#x2011;27] Using `this` to access functions results in an external call, wasting gas
External calls have an overhead of **100 gas**, which can be avoided by not referencing the function using `this`. Contracts [are allowed](https://docs.soliditylang.org/en/latest/contracts.html#function-overriding) to override their parents' functions and change the visibility from `external` to `public`, so make this change if it's required in order to call the function internally.

*There are 3 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

405:         bytes32 salt = this.generateSalt(newMembers, nonce);

440:             salt: this.generateSalt(newMembers, updateNonce),

```
*GitHub*: [405](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L405-L405), [440](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L440-L440)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

128:         (bytes4 selector, bytes memory rest) = this.separateSelector(calldatas[0]);

```
*GitHub*: [128](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L128-L128)


### [G&#x2011;28] `unchecked {}`  can be used on the division of two `uint`s in order to save gas
The division cannot overflow, since both the numerator and the denominator are non-negative

*There are 3 instances of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

128:         if ((quorumDenominator() / params.quorumNumeratorValue) > 500) {

```
*GitHub*: [128](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L128-L128)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

39           return (getPastCirculatingSupply(blockNumber) * quorumNumerator(blockNumber))
40:              / quorumDenominator();

```
*GitHub*: [39](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L39-L40)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

253:             votes * (blockNumber - fullWeightVotingDeadline_) / decreasingWeightDuration;

```
*GitHub*: [253](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L253-L253)


### [G&#x2011;29] Simple checks for zero can be done using assembly to save gas


*There are 10 instances of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

72:          if (_l1ArbitrumTimelock == address(0)) {

78:              if (chainAndUpExecLocation.location.upgradeExecutor == address(0)) {

131:             if (upExecLocation.upgradeExecutor == address(0)) {

134:             if (actionDatas[i].length == 0) {

```
*GitHub*: [72](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L72-L72), [78](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L78-L78), [131](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L131-L131), [134](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L134-L134)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

144:         if (_newMember == address(0)) {

184:         if (_member == address(0)) {

243:         if (_securityCouncilData.chainId == 0) {

```
*GitHub*: [144](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L144-L144), [184](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L184-L184), [243](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L243-L243)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

102:         if (dp.nomineeVetter == address(0)) {

```
*GitHub*: [102](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L102-L102)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

188:         if (electionCount == 0) {

```
*GitHub*: [188](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L188-L188)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

116:         if (weight == 0) {

```
*GitHub*: [116](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L116-L116)

## Disputed Issues

The issues below may be reported by other bots/wardens, but can be penalized/ignored since either the rule or the specified instances are invalid


### [D&#x2011;01] ~~`abi.encodePacked()` should not be used with dynamic types when passing the result to a hash function such as `keccak256()`~~
The cases below do not have consecutive `bytes`/`string` arguments

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

375:          return keccak256(abi.encodePacked(_members, nonce));

```
*GitHub*: [375](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L375)


### [D&#x2011;02] ~~SPDX identifier should be the in the first line of a solidity file~~
It's already on the first line

*There are 20 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L1)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L1)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L1)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L1)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L1)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L1)

```solidity
File: src/gov-action-contracts/execution-record/KeyValueStore.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L1)

```solidity
File: src/security-council-mgmt/Common.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/Common.sol#L1)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L1)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L1)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L1)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L1)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L1)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L1)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L1)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L1)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L1)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L1)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L1)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

1:    // SPDX-License-Identifier: Apache-2.0

```
*GitHub*: [1](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L1)

</details>

### [D&#x2011;03] ~~Inconsistent comment spacing~~
URLs are not comments

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

76:       ///         Value is defined in L1ArbitrumTimelock contract https://etherscan.io/address/0xE6841D92B0C345144506576eC13ECf5103aC7f49#readProxyContract#F5

```
*GitHub*: [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L76)


### [D&#x2011;04] ~~Overly complicated arithmetic~~
At least one bot is incorrectly flagging code comments as 'complicated arithmetic'

*There are 6 instances of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

117:          address[] memory, /* targets */

118:          uint256[] memory, /* values */

120:          bytes32 /* descriptionHash */

```
*GitHub*: [117](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L117), [118](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L118), [120](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L120)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

326:          address[] memory, /* targets */

327:          uint256[] memory, /* values */

329:          bytes32 /*descriptionHash*/

```
*GitHub*: [326](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L326), [327](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L327), [329](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L329)


### [D&#x2011;05] ~~Public functions not used internally can be marked as external to save gas~~
After Solidity version 0.6.9 both `public` and `external` functions save the [same amount of gas](https://ethereum.stackexchange.com/a/107939), and since these files are >0.6.9, these findings are invalid

*There are 34 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

186       function createActionRouteDataWithDefaults(
187           uint256[] memory chainIds,
188           address[] memory actionAddresses,
189           bytes32 timelockSalt
190:      ) public view returns (address, bytes memory) {

```
*GitHub*: [186](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L186-L190)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

349:      function securityCouncilsLength() public view returns (uint256) {

```
*GitHub*: [349](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L349)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

48        function initialize(
49            ISecurityCouncilNomineeElectionGovernor _nomineeElectionGovernor,
50            ISecurityCouncilManager _securityCouncilManager,
51            IVotesUpgradeable _token,
52            address _owner,
53            uint256 _votingPeriod,
54            uint256 _fullWeightDuration
55:       ) public initializer {

138       function proposalThreshold()
139           public
140           pure
141           override(GovernorSettingsUpgradeable, GovernorUpgradeable)
142:          returns (uint256)

181       function propose(address[] memory, uint256[] memory, bytes[] memory, string memory)
182           public
183           virtual
184           override
185:          returns (uint256)

191:      function castVote(uint256, uint8) public virtual override returns (uint256) {

196       function castVoteWithReason(uint256, uint8, string calldata)
197           public
198           virtual
199           override
200:          returns (uint256)

206       function castVoteBySig(uint256, uint8, uint8, bytes32, bytes32)
207           public
208           virtual
209           override
210:          returns (uint256)

```
*GitHub*: [48](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L48-L55), [138](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L138-L142), [181](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L181-L185), [191](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L191), [196](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L196-L200), [206](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L206-L210)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

58        function initialize(
59            uint256 _voteSuccessNumerator,
60            ISecurityCouncilManager _securityCouncilManager,
61            IVotesUpgradeable _token,
62            address _owner,
63            uint256 _votingDelay,
64            uint256 _votingPeriod,
65            uint256 _quorumNumerator,
66            uint256 _proposalThreshold,
67            uint64 _minPeriodAfterQuorum,
68            uint256 _proposalExpirationBlocks
69:       ) public initializer {

106       function propose(
107           address[] memory targets,
108           uint256[] memory values,
109           bytes[] memory calldatas,
110           string memory description
111:      ) public override returns (uint256) {

178:      function setVoteSuccessNumerator(uint256 _voteSuccessNumerator) public onlyOwner {

191       function COUNTING_MODE()
192           public
193           pure
194           virtual
195           override(GovernorCountingSimpleUpgradeable, IGovernorUpgradeable)
196:          returns (string memory)

213       function proposalThreshold()
214           public
215           view
216           override(GovernorUpgradeable, GovernorSettingsUpgradeable)
217:          returns (uint256)

```
*GitHub*: [58](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L58-L69), [106](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L106-L111), [178](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L178), [191](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L191-L196), [213](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L213-L217)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

103:      function initialize(InitParams memory params) public initializer {

357       function proposalThreshold()
358           public
359           view
360           virtual
361           override(GovernorSettingsUpgradeable, GovernorUpgradeable)
362:          returns (uint256)

368:      function isCompliantNominee(uint256 proposalId, address account) public view returns (bool) {

373:      function compliantNominees(uint256 proposalId) public view returns (address[] memory) {

388:      function currentCohort() public view returns (Cohort) {

400:      function isExcluded(uint256 proposalId, address possibleExcluded) public view returns (bool) {

405:      function excludedNomineeCount(uint256 proposalId) public view returns (uint256) {

410       function isContender(uint256 proposalId, address possibleContender)
411           public
412           view
413           virtual
414           override
415:          returns (bool)

423       function propose(address[] memory, uint256[] memory, bytes[] memory, string memory)
424           public
425           virtual
426           override
427:          returns (uint256)

433:      function castVote(uint256, uint8) public virtual override returns (uint256) {

438       function castVoteWithReason(uint256, uint8, string calldata)
439           public
440           virtual
441           override
442:          returns (uint256)

448       function castVoteBySig(uint256, uint8, uint8, bytes32, bytes32)
449           public
450           virtual
451           override
452:          returns (uint256)

```
*GitHub*: [103](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L103), [357](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L357-L362), [368](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L368), [373](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L373), [388](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L388), [400](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L400), [405](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L405), [410](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L410-L415), [423](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L423-L427), [433](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L433), [438](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L438-L442), [448](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L448-L452)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

77:       function setFullWeightDuration(uint256 newFullWeightDuration) public onlyGovernance {

143:      function COUNTING_MODE() public pure virtual override returns (string memory) {

153:      function weightReceived(uint256 proposalId, address nominee) public view returns (uint256) {

158:      function hasVoted(uint256 proposalId, address account) public view override returns (bool) {

```
*GitHub*: [77](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L77), [143](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L143), [153](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L153), [158](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L158)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

128:      function COUNTING_MODE() public pure virtual override returns (string memory) {

133:      function hasVoted(uint256 proposalId, address account) public view override returns (bool) {

148:      function nominees(uint256 proposalId) public view returns (address[] memory) {

153:      function votesUsed(uint256 proposalId, address account) public view returns (uint256) {

158:      function votesReceived(uint256 proposalId, address contender) public view returns (uint256) {

```
*GitHub*: [128](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L128), [133](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L133), [148](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L148), [153](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L153), [158](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L158)

</details>

### [D&#x2011;06] ~~Shorten the array rather than copying to a new one~~
None of these examples are of filtering out entries from an array.

*There are 11 instances of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

191          uint256[] memory values = new uint256[](chainIds.length);
192          bytes[] memory actionDatas = new bytes[](chainIds.length);
193          for (uint256 i = 0; i < chainIds.length; i++) {
194:             actionDatas[i] = DEFAULT_GOV_ACTION_CALLDATA;

192          bytes[] memory actionDatas = new bytes[](chainIds.length);
193          for (uint256 i = 0; i < chainIds.length; i++) {
194              actionDatas[i] = DEFAULT_GOV_ACTION_CALLDATA;
195:             values[i] = DEFAULT_VALUE;

```
*GitHub*: [191](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L191-L194), [192](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L192-L195)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

338          address[] memory members = new address[](firstCohort.length + secondCohort.length);
339          for (uint256 i = 0; i < firstCohort.length; i++) {
340              members[i] = firstCohort[i];
341:         }

388          address[] memory actionAddresses = new address[](securityCouncils.length);
389          bytes[] memory actionDatas = new bytes[](securityCouncils.length);
390          uint256[] memory chainIds = new uint256[](securityCouncils.length);
391: 

389          bytes[] memory actionDatas = new bytes[](securityCouncils.length);
390          uint256[] memory chainIds = new uint256[](securityCouncils.length);
391  
392:         for (uint256 i = 0; i < securityCouncils.length; i++) {

390          uint256[] memory chainIds = new uint256[](securityCouncils.length);
391  
392          for (uint256 i = 0; i < securityCouncils.length; i++) {
393:             SecurityCouncilData memory securityCouncilData = securityCouncils[i];

```
*GitHub*: [338](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L338-L341), [388](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L388-L391), [389](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L389-L392), [390](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L390-L393)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

19           address[] memory intermediate = new address[](input.length);
20           uint256 intermediateLength = 0;
21   
22:          for (uint256 i = 0; i < input.length; i++) {

30           address[] memory output = new address[](intermediateLength);
31           for (uint256 i = 0; i < intermediateLength; i++) {
32               output[i] = intermediate[i];
33:          }

```
*GitHub*: [19](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L19-L22), [30](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L30-L33)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

179          uint240[] memory weights = new uint240[](nominees.length);
180          ElectionInfo storage election = _elections[proposalId];
181          for (uint256 i = 0; i < nominees.length; i++) {
182:             weights[i] = election.weightReceived[nominees[i]];

203          uint256[] memory topNomineesPacked = new uint256[](k);
204  
205          for (uint16 i = 0; i < nominees.length; i++) {
206:             uint256 packed = (uint256(weights[i]) << 16) | i;

214          address[] memory topNomineesAddresses = new address[](k);
215          for (uint16 i = 0; i < k; i++) {
216              topNomineesAddresses[i] = nominees[uint16(topNomineesPacked[i])];
217:         }

```
*GitHub*: [179](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L179-L182), [203](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L203-L206), [214](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L214-L217)


### [D&#x2011;07] ~~`require()` / `revert()` statements should have descriptive reason strings~~
These are not `revert()` calls, so these findings are invalid

*There are 92 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

73:              revert ZeroAddress();

79:                  revert ZeroAddress();

82:                  revert UpgradeExecAlreadyExists(chainAndUpExecLocation.chainId);

114:             revert ParamLengthMismatch(chainIds.length, actionAddresses.length);

117:             revert ParamLengthMismatch(chainIds.length, actionValues.length);

120:             revert ParamLengthMismatch(chainIds.length, actionDatas.length);

132:                 revert UpgadeExecDoesntExist(chainIds[i]);

135:                 revert EmptyActionBytesData(actionDatas);

```
*GitHub*: [73](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L73-L73), [79](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L79-L79), [82](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L82-L82), [114](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L114-L114), [117](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L117-L117), [120](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L120-L120), [132](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L132-L132), [135](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L135-L135)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

98:              revert CohortLengthMismatch(_firstCohort, _secondCohort);

113:             revert NotAContract({account: _l2CoreGovTimelock});

129:             revert InvalidNewCohortLength({cohort: _newCohort, cohortSize: cohortSize});

145:             revert ZeroAddress();

149:             revert CohortFull({cohort: _cohort});

152:             revert MemberInCohort({member: _newMember, cohort: Cohort.FIRST});

155:             revert MemberInCohort({member: _newMember, cohort: Cohort.SECOND});

172:         revert NotAMember({member: _member});

185:             revert ZeroAddress();

223:             revert ZeroAddress();

233:             revert MaxSecurityCouncils(securityCouncils.length);

240:             revert ZeroAddress();

244:             revert SecurityCouncilZeroChainID(_securityCouncilData);

248:             revert SecurityCouncilNotInRouter(_securityCouncilData);

258:                 revert SecurityCouncilAlreadyInRouter(_securityCouncilData);

304:         revert SecurityCouncilNotInManager(_securityCouncilData);

319:             revert NotAContract({account: routerAddress});

```
*GitHub*: [98](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L98-L98), [113](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L113-L113), [129](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L129-L129), [145](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L145-L145), [149](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L149-L149), [152](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L152-L152), [155](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L155-L155), [172](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L172-L172), [185](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L185-L185), [223](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L223-L223), [233](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L233-L233), [240](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L240-L240), [244](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L244-L244), [248](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L248-L248), [258](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L258-L258), [304](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L304-L304), [319](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L319-L319)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

112          revert PreviousOwnerNotFound({
113              targetOwner: _owner,
114              securityCouncil: address(securityCouncil)
115:         });

133:             revert ExecFromModuleError({data: data, securityCouncil: address(securityCouncil)});

```
*GitHub*: [112](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L112-L115), [133](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L133-L133)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

87:              revert NotAContract(dp.govChainEmergencySecurityCouncil);

91:              revert NotAContract(dp.govChainProxyAdmin);

95:              revert NotAContract(dp.l2UpgradeExecutor);

99:              revert NotAContract(dp.arbToken);

103:             revert ZeroAddress();

108:             revert InvalidCohortsSize(owners.length, dp.firstCohort.length, dp.secondCohort.length);

113:                 revert AddressNotInCouncil(owners, dp.firstCohort[i]);

119:                 revert AddressNotInCouncil(owners, dp.secondCohort[i]);

```
*GitHub*: [87](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L87-L87), [91](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L91-L91), [95](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L95-L95), [99](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L99-L99), [103](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L103-L103), [108](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L108-L108), [113](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L113-L113), [119](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L119-L119)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

57:              revert InvalidDurations(_fullWeightDuration, _votingPeriod);

69:              revert NotAContract(address(_nomineeElectionGovernor));

73:              revert NotAContract(address(_securityCouncilManager));

80:              revert OnlyNomineeElectionGovernor();

187:         revert ProposeDisabled();

192:         revert CastVoteDisabled();

202:         revert CastVoteDisabled();

212:         revert CastVoteDisabled();

```
*GitHub*: [57](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L57-L57), [69](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L69-L69), [73](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L73-L73), [80](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L80-L80), [187](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L187-L187), [192](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L192-L192), [202](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L202-L202), [212](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L212-L212)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

79:              revert NotAContract(address(_securityCouncilManager));

113:             revert InvalidOperationsLength(targets.length);

118:             revert TargetNotManager(targets[0]);

121:             revert ValueNotZero(values[0]);

125:             revert UnexpectedCalldataLength(calldatas[0].length);

130:             revert CallNotRemoveMember(selector, ISecurityCouncilManager.removeMember.selector);

138:             revert MemberNotFound(memberToRemove);

171:             revert AbstainDisallowed();

184:             revert InvalidVoteSuccessNumerator(_voteSuccessNumerator);

```
*GitHub*: [79](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L79-L79), [113](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L113-L113), [118](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L118-L118), [121](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L121-L121), [125](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L125-L125), [130](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L130-L130), [138](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L138-L138), [171](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L171-L171), [184](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L184-L184)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

116:             revert NotAContract(address(params.securityCouncilManager));

120:             revert NotAContract(address(params.securityCouncilMemberElectionGovernor));

129:             revert QuorumNumeratorTooLow(params.quorumNumeratorValue);

136:             revert OnlyNomineeVetter();

146:             revert ProposalNotSucceededState(state_);

152:             revert ProposalNotInVettingPeriod(block.number, vettingDeadline);

168:             revert CreateTooEarly(block.timestamp, thisElectionStartTs);

207:             revert LastMemberElectionNotExecuted(prevProposalId);

222:             revert AlreadyContender(msg.sender);

227:             revert ProposalNotActive(state_);

237:             revert AccountInOtherCohort(otherCohort(), msg.sender);

273:             revert NomineeAlreadyExcluded(nominee);

276:             revert NotNominee(nominee);

293:             revert ProposalNotSucceededState(state_);

297:             revert NomineeAlreadyAdded(account);

303:             revert CompliantNomineeTargetHit(cnCount, cohortSize);

313:             revert AccountInOtherCohort(otherCohort(), account);

334:             revert ProposalInVettingPeriod(block.number, vettingDeadline);

340:             revert InsufficientCompliantNomineeCount(cnCount, cohortSize);

350:             revert ProposalIdMismatch(proposalId, memberElectionProposalId);

429:         revert ProposeDisabled();

434:         revert CastVoteDisabled();

444:         revert CastVoteDisabled();

454:         revert CastVoteDisabled();

```
*GitHub*: [116](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L116-L116), [120](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L120-L120), [129](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L129-L129), [136](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L136-L136), [146](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L146-L146), [152](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L152-L152), [168](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L168-L168), [207](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L207-L207), [222](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L222-L222), [227](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L227-L227), [237](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L237-L237), [273](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L273-L273), [276](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L276-L276), [293](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L293-L293), [297](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L297-L297), [303](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L303-L303), [313](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L313-L313), [334](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L334-L334), [340](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L340-L340), [350](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L350-L350), [429](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L429-L429), [434](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L434-L434), [444](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L444-L444), [454](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L454-L454)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

79:              revert FullWeightDurationGreaterThanVotingPeriod(newFullWeightDuration, votingPeriod());

103:             revert InvalidSupport(support);

107:             revert UnexpectedParamsLength(params.length);

112:             revert NotCompliantNominee(nominee);

117:             revert ZeroWeightVote(block.number, votes);

123:             revert InsufficientVotes(prevVotesUsed, votes, availableVotes);

197:             revert LengthsDontMatch(nominees.length, weights.length);

200:             revert NotEnoughNominees(nominees.length, k);

261:             revert UintTooLarge(x);

```
*GitHub*: [79](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L79-L79), [103](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L103-L103), [107](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L107-L107), [112](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L112-L112), [117](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L117-L117), [123](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L123-L123), [197](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L197-L197), [200](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L200-L200), [261](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L261-L261)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

70:              revert InvalidSupport(support);

74:              revert UnexpectedParamsLength(params.length);

81:              revert NotEligibleContender(contender);

84:              revert NomineeAlreadyAdded(contender);

91:              revert InsufficientTokens(votes, prevVotesUsed, weight);

```
*GitHub*: [70](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L70-L70), [74](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L74-L74), [81](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L81-L81), [84](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L84-L84), [91](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L91-L91)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

42               revert InvalidStartDate(
43                   _firstNominationStartDate.year,
44                   _firstNominationStartDate.month,
45                   _firstNominationStartDate.day,
46                   _firstNominationStartDate.hour
47:              );

61:              revert StartDateTooEarly(startTimestamp, block.timestamp);

```
*GitHub*: [42](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L42-L47), [61](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L61-L61)

</details>

### [D&#x2011;08] ~~Use delete instead of setting mapping/state variable to zero, to save gas~~
Using delete instead of assigning zero to state variables does not save any extra gas with the optimizer [on](https://gist.github.com/IllIllI000/ef8ec3a70aede7f12433fe63dc418515#with-the-optimizer-set-at-200-runs) (saves 5-8 gas with optimizer completely off), so this finding is invalid, especially since if they were interested in gas savings, they'd have the optimizer enabled.

*There is one instance of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

150:                 schedValues[i] = 0;

```
*GitHub*: [150](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L150-L150)


### [D&#x2011;09] ~~Events that mark critical parameter changes should contain both the old and the new value~~
These are not critical parameter changes

*There are 16 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

140:         emit CohortReplaced(_newCohort, _cohort);

179:         emit MemberAdded(_newMember, _cohort);

189:         emit MemberRemoved({member: _member, cohort: cohort});

198          emit MemberReplaced({
199              replacedMember: _memberToReplace,
200              newMember: _newMember,
201              cohort: cohort
202:         });

211          emit MemberRotated({
212              replacedAddress: _currentAddress,
213              newAddress: _newAddress,
214              cohort: cohort
215:         });

263          emit SecurityCouncilAdded(
264              _securityCouncilData.securityCouncil,
265              _securityCouncilData.updateAction,
266              securityCouncils.length
267:         );

296                  emit SecurityCouncilRemoved(
297                      securityCouncilData.securityCouncil,
298                      securityCouncilData.updateAction,
299                      securityCouncils.length
300:                 );

```
*GitHub*: [140](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L140-L140), [179](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L179-L179), [189](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L189-L189), [198](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L198-L202), [211](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L211-L215), [263](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L263-L267), [296](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L296-L300)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

46:              emit UpdateNonceTooLow(_securityCouncil, updateNonce, _nonce);

```
*GitHub*: [46](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L46-L46)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

187:         emit ContractsDeployed(deployedContracts);

```
*GitHub*: [187](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L187-L187)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

141:         emit MemberRemovalProposed(memberToRemove, description);

```
*GitHub*: [141](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L141-L141)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

242:         emit ContenderAdded(proposalId, msg.sender);

282:         emit NomineeExcluded(proposalId, nominee);

```
*GitHub*: [242](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L242-L242), [282](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L282-L282)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

73:          emit FullWeightDurationSet(initialFullWeightDuration);

130          emit VoteCastForNominee({
131              voter: account,
132              proposalId: proposalId,
133              nominee: nominee,
134              votes: votes,
135              weight: weight,
136              totalUsedVotes: prevVotesUsed + votes,
137              usableVotes: availableVotes,
138              weightReceived: election.weightReceived[nominee]
139:         });

```
*GitHub*: [73](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L73-L73), [130](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L130-L139)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

110          emit VoteCastForContender({
111              proposalId: proposalId,
112              voter: account,
113              contender: contender,
114              votes: actualVotes,
115              totalUsedVotes: prevVotesUsed + actualVotes,
116              usableVotes: weight
117:         });

124:         emit NewNominee(proposalId, account);

```
*GitHub*: [110](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L110-L117), [124](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L124-L124)

</details>

### [D&#x2011;10] ~~Empty function body~~
These constructors have calls to base contracts, so the empty function body cannot be removed

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

21       constructor(KeyValueStore _store)
22           ActionExecutionRecord(_store, "SecurityCouncilMemberSyncAction")
23:      {}

```
*GitHub*: [21](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L21-L23)


### [D&#x2011;11] ~~Cast to `bytes` or `bytes32` for clearer semantic meaning~~
These calls to `abi.encodePacked()` have more than one argument

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

375:         return keccak256(abi.encodePacked(_members, nonce));

```
*GitHub*: [375](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L375-L375)


### [D&#x2011;12] ~~`abi.encode()` is less efficient than `abi.encodepacked()`~~
`abi.encodePacked()` does not always save gas over `abi.encode()` and in fact often costs [more](https://gist.github.com/IllIllI000/2ee970e4f05af4d2a3d89a56b5cc93a5) gas. The [comparison](https://github.com/ConnorBlockchain/Solidity-Encode-Gas-Comparison) sometimes linked to itself even shows that when addresses are involved, the packed flavor costs more gas.

*There are 2 instances of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

151:                 schedData[i] = abi.encode(

```
*GitHub*: [151](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L151-L151)

```solidity
File: src/gov-action-contracts/execution-record/KeyValueStore.sol

27:          return uint256(keccak256(abi.encode(owner, key)));

```
*GitHub*: [27](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L27-L27)


### [D&#x2011;13] ~~Event names should use CamelCase~~
The instances below are already CamelCase (events are supposed to use CamelCase, not lowerCamelCase)

*There are 19 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

33:      event CohortReplaced(address[] newCohort, Cohort indexed cohort);

34:      event MemberAdded(address indexed newMember, Cohort indexed cohort);

35:      event MemberRemoved(address indexed member, Cohort indexed cohort);

36:      event MemberReplaced(address indexed replacedMember, address indexed newMember, Cohort cohort);

37:      event MemberRotated(address indexed replacedAddress, address indexed newAddress, Cohort cohort);

38       event SecurityCouncilAdded(
39           address securityCouncil, address updateAction, uint256 securityCouncilsLength
40:      );

41       event SecurityCouncilRemoved(
42           address securityCouncil, address updateAction, uint256 securityCouncilsLength
43:      );

44:      event UpgradeExecRouteBuilderSet(address UpgradeExecRouteBuilder);

```
*GitHub*: [33](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L33-L33), [34](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L34-L34), [35](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L35-L35), [36](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L36-L36), [37](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L37-L37), [38](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L38-L40), [41](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L41-L43), [44](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L44-L44)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

14       event UpdateNonceTooLow(
15           address indexed securityCouncil, uint256 currrentNonce, uint256 providedNonce
16:      );

```
*GitHub*: [14](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L14-L16)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

56:      event ContractsDeployed(DeployedContracts deployedContracts);

```
*GitHub*: [56](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L56-L56)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

32:      event VoteSuccessNumeratorSet(uint256 indexed voteSuccessNumerator);

33:      event MemberRemovalProposed(address memberToRemove, string description);

```
*GitHub*: [32](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L32-L32), [33](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L33-L33)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

76:      event NomineeVetterChanged(address indexed oldNomineeVetter, address indexed newNomineeVetter);

77:      event ContenderAdded(uint256 indexed proposalId, address indexed contender);

78:      event NomineeExcluded(uint256 indexed proposalId, address indexed nominee);

```
*GitHub*: [76](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L76-L76), [77](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L77-L77), [78](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L78-L78)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

42       event VoteCastForNominee(
43           address indexed voter,
44           uint256 indexed proposalId,
45           address indexed nominee,
46           uint256 votes,
47           uint256 weight,
48           uint256 totalUsedVotes,
49           uint256 usableVotes,
50           uint256 weightReceived
51:      );

53:      event FullWeightDurationSet(uint256 newFullWeightDuration);

```
*GitHub*: [42](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L42-L51), [53](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L53-L53)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

35       event VoteCastForContender(
36           uint256 indexed proposalId,
37           address indexed voter,
38           address indexed contender,
39           uint256 votes,
40           uint256 totalUsedVotes,
41           uint256 usableVotes
42:      );

44:      event NewNominee(uint256 indexed proposalId, address indexed nominee);

```
*GitHub*: [35](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L35-L42), [44](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L44-L44)

</details>

### [D&#x2011;14] ~~`internal` functions not called by the contract should be removed~~
These functions are referenced by other contracts extending the current one

*There are 11 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

8        function replaceEmergencySecurityCouncil(
9            IGnosisSafe _prevSecurityCouncil,
10           IGnosisSafe _newSecurityCouncil,
11           uint256 _threshold,
12           IUpgradeExecutor _upgradeExecutor
13:      ) internal {

29       function requireSafesEquivalent(
30           IGnosisSafe _safe1,
31           IGnosisSafe safe2,
32           uint256 _expectedThreshold
33:      ) internal view {

```
*GitHub*: [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L8-L13), [29](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L29-L33)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

25:      function _set(uint256 key, uint256 value) internal {

31:      function _get(uint256 key) internal view returns (uint256) {

```
*GitHub*: [25](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L25-L25), [31](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L31-L31)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

5:       function isInArray(address addr, address[] memory arr) internal pure returns (bool) {

15       function filterAddressesWithExcludeList(
16           address[] memory input,
17           mapping(address => bool) storage excludeList
18:      ) internal view returns (address[] memory) {

```
*GitHub*: [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L5-L5), [15](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L15-L18)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

24       function __ArbitrumGovernorVotesQuorumFraction_init(uint256 quorumNumeratorValue)
25           internal
26           onlyInitializing
27:      {

```
*GitHub*: [24](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L24-L27)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

34:      function extractElectionIndex(bytes[] memory callDatas) internal pure returns (uint256) {

```
*GitHub*: [34](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L34-L34)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

68       function __SecurityCouncilMemberElectionGovernorCounting_init(uint256 initialFullWeightDuration)
69           internal
70           onlyInitializing
71:      {

```
*GitHub*: [68](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L68-L71)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

52:      function __SecurityCouncilNomineeElectionGovernorCounting_init() internal onlyInitializing {}

```
*GitHub*: [52](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L52-L52)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

28       function __SecurityCouncilNomineeElectionGovernorTiming_init(
29           Date memory _firstNominationStartDate,
30           uint256 _nomineeVettingDuration
31:      ) internal onlyInitializing {

```
*GitHub*: [28](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L28-L31)

</details>

### [D&#x2011;15] ~~Change `public` to `external` for functions that are not called internally~~
These functions are referenced by modifiers

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

69:      function proposalVettingDeadline(uint256 proposalId) public view returns (uint256) {

```
*GitHub*: [69](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L69-L69)


### [D&#x2011;16] ~~Initialization can be front-run~~
These initializers are called by other contracts in the project, and thus cannot be front-run

*There are 3 instances of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

48       function initialize(
49           ISecurityCouncilNomineeElectionGovernor _nomineeElectionGovernor,
50           ISecurityCouncilManager _securityCouncilManager,
51           IVotesUpgradeable _token,
52           address _owner,
53           uint256 _votingPeriod,
54           uint256 _fullWeightDuration
55:      ) public initializer {

```
*GitHub*: [48](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L48-L55)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

58       function initialize(
59           uint256 _voteSuccessNumerator,
60           ISecurityCouncilManager _securityCouncilManager,
61           IVotesUpgradeable _token,
62           address _owner,
63           uint256 _votingDelay,
64           uint256 _votingPeriod,
65           uint256 _quorumNumerator,
66           uint256 _proposalThreshold,
67           uint64 _minPeriodAfterQuorum,
68           uint256 _proposalExpirationBlocks
69:      ) public initializer {

```
*GitHub*: [58](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L58-L69)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

103:     function initialize(InitParams memory params) public initializer {

```
*GitHub*: [103](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L103-L103)


### [D&#x2011;17] ~~Use multiple `require()` and `if` statements instead of `&&`~~
The suggestion in this rule is not logically equivalent for if-statements, and doesn't seem more readable for `require()`s either

*There are 3 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

255                  existantSecurityCouncil.chainId == _securityCouncilData.chainId
256                      && existantSecurityCouncil.securityCouncil == _securityCouncilData.securityCouncil
257              ) {
258:                 revert SecurityCouncilAlreadyInRouter(_securityCouncilData);

287                  securityCouncilData.securityCouncil == _securityCouncilData.securityCouncil
288                      && securityCouncilData.chainId == _securityCouncilData.chainId
289                      && securityCouncilData.updateAction == _securityCouncilData.updateAction
290              ) {
291:                 SecurityCouncilData storage lastSecurityCouncil =

```
*GitHub*: [255](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L255-L258), [287](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L287-L291)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

135              !securityCouncilManager.firstCohortIncludes(memberToRemove)
136                  && !securityCouncilManager.secondCohortIncludes(memberToRemove)
137          ) {
138:             revert MemberNotFound(memberToRemove);

```
*GitHub*: [135](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L135-L138)


### [D&#x2011;18] ~~Use `@inheritdoc` rather than using a non-standard annotation~~


*There are 27 instances of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

112      /// @dev    `GovernorUpgradeable` function to execute a proposal overridden to handle member elections.
113      ///         We know that topNominees() will return a full list.
114      ///         Calls `SecurityCouncilManager.replaceCohort` with the list of nominees.
115      function _execute(
116          uint256 proposalId,
117          address[] memory, /* targets */
118          uint256[] memory, /* values */
119          bytes[] memory callDatas,
120          bytes32 /* descriptionHash */
121:     ) internal override {

135      /// @notice Normally "the number of votes required in order for a voter to become a proposer." But in our case it is 0.
136      /// @dev    Since we only want proposals to be created via `proposeFromNomineeElectionGovernor`, we set the proposal threshold to 0.
137      ///         `proposeFromNomineeElectionGovernor` determines the rules for creating a proposal.
138      function proposalThreshold()
139          public
140          pure
141          override(GovernorSettingsUpgradeable, GovernorUpgradeable)
142          returns (uint256)
143:     {

147      /// @notice Quorum is always 0.
148:     function quorum(uint256) public pure override returns (uint256) {

152      /// @dev Whether the account is a compliant nominee.
153      ///      checks the SecurityCouncilNomineeElectionGovernor to see if the account is a compliant nominee
154      function _isCompliantNominee(uint256 proposalId, address possibleNominee)
155          internal
156          view
157          override
158          returns (bool)
159:     {

163      /// @dev Returns all the compliant (non excluded) nominees for the requested proposal
164      function _compliantNominees(uint256 proposalId)
165          internal
166          view
167          override
168          returns (address[] memory)
169:     {

178      /// @notice Always reverts.
179      /// @dev    `GovernorUpgradeable` function to create a proposal overridden to just revert.
180      ///         We only want proposals to be created via `proposeFromNomineeElectionGovernor`.
181      function propose(address[] memory, uint256[] memory, bytes[] memory, string memory)
182          public
183          virtual
184          override
185          returns (uint256)
186:     {

190      /// @notice Always reverts. Use castVoteWithReasonAndParams instead
191:     function castVote(uint256, uint8) public virtual override returns (uint256) {

195      /// @notice Always reverts. Use castVoteWithReasonAndParams instead
196      function castVoteWithReason(uint256, uint8, string calldata)
197          public
198          virtual
199          override
200          returns (uint256)
201:     {

205      /// @notice Always reverts. Use castVoteWithReasonAndParamsBySig instead
206      function castVoteBySig(uint256, uint8, uint8, bytes32, bytes32)
207          public
208          virtual
209          override
210          returns (uint256)
211:     {

```
*GitHub*: [112](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L112-L121), [135](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L135-L143), [147](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L147-L148), [152](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L152-L159), [163](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L163-L169), [178](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L178-L186), [190](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L190-L191), [195](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L195-L201), [205](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L205-L211)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

101      ///         but enforces that only calls to securityCouncilManager's removeMember can be propsoed.
102      /// @param targets Target contract operation; must be [securityCouncilManager]
103      /// @param values Value for removeMmeber; must be [0]
104      /// @param calldatas Operation calldata; must be [removeMember with address argument]
105      /// @param description rationale for member removal
106      function propose(
107          address[] memory targets,
108          uint256[] memory values,
109          bytes[] memory calldatas,
110          string memory description
111:     ) public override returns (uint256) {

145      /// @notice override to allow for required vote success ratio that isn't 0.5
146      /// @param proposalId target proposal id
147      function _voteSucceeded(uint256 proposalId)
148          internal
149          view
150          virtual
151          override(GovernorCountingSimpleUpgradeable, GovernorUpgradeable)
152          returns (bool)
153:     {

160      /// @notice A removal proposal if a theshold of all cast votes vote in favor of removal.
161      ///         Thus, abstaining would be exactly equivalent to voting against.
162      ///         To prevent any confusion, abstaining is disallowed.
163      function _countVote(
164          uint256 proposalId,
165          address account,
166          uint8 support,
167          uint256 weight,
168          bytes memory params
169:     ) internal virtual override(GovernorCountingSimpleUpgradeable, GovernorUpgradeable) {

```
*GitHub*: [101](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L101-L111), [145](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L145-L153), [160](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L160-L169)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

319      /// @dev    `GovernorUpgradeable` function to execute a proposal overridden to handle nominee elections.
320      ///         Can be called by anyone via `execute` after voting and nominee vetting periods have ended.
321      ///         If the number of compliant nominees is > the target number of nominees,
322      ///         we move on to the next phase by calling the SecurityCouncilMemberElectionGovernor.
323      /// @param  proposalId The id of the proposal
324      function _execute(
325          uint256 proposalId,
326          address[] memory, /* targets */
327          uint256[] memory, /* values */
328          bytes[] memory callDatas,
329          bytes32 /*descriptionHash*/
330:     ) internal virtual override {

354      /// @notice Normally "the number of votes required in order for a voter to become a proposer." But in our case it is 0.
355      /// @dev    Since we only want proposals to be created via `createElection`, we set the proposal threshold to 0.
356      ///         `createElection` determines the rules for creating a proposal.
357      function proposalThreshold()
358          public
359          view
360          virtual
361          override(GovernorSettingsUpgradeable, GovernorUpgradeable)
362          returns (uint256)
363:     {

420      /// @notice Always reverts.
421      /// @dev    `GovernorUpgradeable` function to create a proposal overridden to just revert.
422      ///         We only want proposals to be created via `createElection`.
423      function propose(address[] memory, uint256[] memory, bytes[] memory, string memory)
424          public
425          virtual
426          override
427          returns (uint256)
428:     {

432      /// @notice Always reverts. Use castVoteWithReasonAndParams instead
433:     function castVote(uint256, uint8) public virtual override returns (uint256) {

437      /// @notice Always reverts. Use castVoteWithReasonAndParams instead
438      function castVoteWithReason(uint256, uint8, string calldata)
439          public
440          virtual
441          override
442          returns (uint256)
443:     {

447      /// @notice Always reverts. Use castVoteWithReasonAndParamsBySig instead
448      function castVoteBySig(uint256, uint8, uint8, bytes32, bytes32)
449          public
450          virtual
451          override
452          returns (uint256)
453:     {

```
*GitHub*: [319](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L319-L330), [354](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L354-L363), [420](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L420-L428), [432](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L432-L433), [437](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L437-L443), [447](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L447-L453)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

37       /// @notice Calculates the quorum size, excludes token delegated to the exclude address
38:      function quorum(uint256 blockNumber) public view virtual override returns (uint256) {

```
*GitHub*: [37](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L37-L38)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

90       /// @param  proposalId The id of the proposal
91       /// @param  account The account that is voting
92       /// @param  support The support of the vote (forced to 1)
93       /// @param  availableVotes The amount of votes that account had at the time of the proposal snapshot
94       /// @param  params Abi encoded (address nominee, uint256 votes)
95       function _countVote(
96           uint256 proposalId,
97           address account,
98           uint8 support,
99           uint256 availableVotes,
100          bytes memory params
101:     ) internal virtual override {

157      /// @notice Whether the account has voted any amount for any nominee in the proposal
158:     function hasVoted(uint256 proposalId, address account) public view override returns (bool) {

266      /// @notice True, since there is no minimum quorum
267:     function _quorumReached(uint256) internal pure override returns (bool) {

271      /// @notice True, since an election can only be only started if there are enough nominees
272      ///         and candidates cannot be excluded after the election has started
273:     function _voteSucceeded(uint256) internal pure override returns (bool) {

```
*GitHub*: [90](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L90-L101), [157](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L157-L158), [266](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L266-L267), [271](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L271-L273)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

57       /// @param proposalId the id of the proposal
58       /// @param account the account that is casting the vote
59       /// @param support the support of the vote (forced to 1)
60       /// @param weight the amount of vote that account held at time of snapshot
61       /// @param params abi encoded (contender, votes) where votes is the amount of votes the account is using for this contender
62       function _countVote(
63           uint256 proposalId,
64           address account,
65           uint8 support,
66           uint256 weight,
67           bytes memory params
68:      ) internal virtual override {

132      /// @notice Whether the account has voted any amount for any contender in the proposal
133:     function hasVoted(uint256 proposalId, address account) public view override returns (bool) {

169      /// @dev there is no minimum quorum for nominations proposals to pass, so we just return true
170:     function _quorumReached(uint256) internal pure override returns (bool) {

174      /// @dev the vote always succeeds, so we just return true
175:     function _voteSucceeded(uint256) internal pure override returns (bool) {

```
*GitHub*: [57](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L57-L68), [132](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L132-L133), [169](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L169-L170), [174](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L174-L175)


### [D&#x2011;19] ~~Functions which are either private or internal should have a preceding _ in their name~~
This rule does not apply to internal library functions, so these instances are invalid.

*There are 4 instances of this issue:*

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

8        function replaceEmergencySecurityCouncil(
9            IGnosisSafe _prevSecurityCouncil,
10           IGnosisSafe _newSecurityCouncil,
11           uint256 _threshold,
12           IUpgradeExecutor _upgradeExecutor
13:      ) internal {

29       function requireSafesEquivalent(
30           IGnosisSafe _safe1,
31           IGnosisSafe safe2,
32           uint256 _expectedThreshold
33:      ) internal view {

```
*GitHub*: [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L8-L13), [29](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L29-L33)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

5:       function isInArray(address addr, address[] memory arr) internal pure returns (bool) {

15       function filterAddressesWithExcludeList(
16           address[] memory input,
17           mapping(address => bool) storage excludeList
18:      ) internal view returns (address[] memory) {

```
*GitHub*: [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L5-L5), [15](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L15-L18)


### [D&#x2011;20] ~~Contracts are not using their OZ Upgradeable counterparts~~
The rule is true only when the contract being defined is upgradeable, which isn't the case for these invalid examples

*There are 4 instances of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

/// @audit SecurityCouncilManager is a non-upgradeable contract
12:  import "@openzeppelin/contracts/utils/Address.sol";

```
*GitHub*: [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L12-L12)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

/// @audit L2SecurityCouncilMgmtFactory is a non-upgradeable contract
4:   import "@openzeppelin/contracts/access/Ownable.sol";

/// @audit L2SecurityCouncilMgmtFactory is a non-upgradeable contract
5:   import "@openzeppelin/contracts/utils/Address.sol";

/// @audit L2SecurityCouncilMgmtFactory is a non-upgradeable contract
10:  import "@openzeppelin/contracts/proxy/transparent/TransparentUpgradeableProxy.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L4-L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L5-L5), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L10-L10)


### [D&#x2011;21] ~~All interfaces used within a project should be imported~~
These contracts don't rely on other contracts for their definitions, so there's nothing to import

*There are 10 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

9:   interface DefaultGovAction {

39:  contract UpgradeExecRouteBuilder {

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L9-L9), [39](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L39-L39)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

12:  contract GovernanceChainSCMgmtActivationAction {

```
*GitHub*: [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L12-L12)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

9:   contract L1SCMgmtActivationAction {

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L9-L9)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

7:   contract NonGovernanceChainSCMgmtActivationAction {

```
*GitHub*: [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L7-L7)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

7:   library SecurityCouncilMgmtUpgradeLib {

```
*GitHub*: [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L7-L7)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

10   contract ActionExecutionRecord {
11       /// @notice The key value store used to record the execution
12:      /// @dev    Local storage cannot be used in action contracts as they're delegate called into

```
*GitHub*: [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L10-L12)

```solidity
File: src/gov-action-contracts/execution-record/KeyValueStore.sol

6:   contract KeyValueStore {

```
*GitHub*: [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/KeyValueStore.sol#L6-L6)

```solidity
File: src/security-council-mgmt/SecurityCouncilMgmtUtils.sol

4:   library SecurityCouncilMgmtUtils {

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMgmtUtils.sol#L4-L4)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

9    contract ElectionGovernor {
10       /// @notice Generate arguments to be passed to the governor propose function
11       /// @param electionIndex The index of the election to create a proposal for
12       /// @return Targets
13       /// @return Values
14       /// @return Calldatas
15:      /// @return Description

```
*GitHub*: [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L9-L15)

</details>

### [D&#x2011;22] ~~Change `public` function visibility to `external` to save gas~~
Both `public` and `external` functions use the same amount of gas (both deployment and runtime gas), so this finding is invalid

*There are 22 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

186      function createActionRouteDataWithDefaults(
187          uint256[] memory chainIds,
188          address[] memory actionAddresses,
189          bytes32 timelockSalt
190:     ) public view returns (address, bytes memory) {

```
*GitHub*: [186](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L186-L190)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

349:     function securityCouncilsLength() public view returns (uint256) {

```
*GitHub*: [349](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L349-L349)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

48       function initialize(
49           ISecurityCouncilNomineeElectionGovernor _nomineeElectionGovernor,
50           ISecurityCouncilManager _securityCouncilManager,
51           IVotesUpgradeable _token,
52           address _owner,
53           uint256 _votingPeriod,
54           uint256 _fullWeightDuration
55:      ) public initializer {

```
*GitHub*: [48](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L48-L55)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

58       function initialize(
59           uint256 _voteSuccessNumerator,
60           ISecurityCouncilManager _securityCouncilManager,
61           IVotesUpgradeable _token,
62           address _owner,
63           uint256 _votingDelay,
64           uint256 _votingPeriod,
65           uint256 _quorumNumerator,
66           uint256 _proposalThreshold,
67           uint64 _minPeriodAfterQuorum,
68           uint256 _proposalExpirationBlocks
69:      ) public initializer {

178:     function setVoteSuccessNumerator(uint256 _voteSuccessNumerator) public onlyOwner {

```
*GitHub*: [58](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L58-L69), [178](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L178-L178)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

103:     function initialize(InitParams memory params) public initializer {

368:     function isCompliantNominee(uint256 proposalId, address account) public view returns (bool) {

373:     function compliantNominees(uint256 proposalId) public view returns (address[] memory) {

388:     function currentCohort() public view returns (Cohort) {

400:     function isExcluded(uint256 proposalId, address possibleExcluded) public view returns (bool) {

405:     function excludedNomineeCount(uint256 proposalId) public view returns (uint256) {

```
*GitHub*: [103](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L103-L103), [368](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L368-L368), [373](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L373-L373), [388](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L388-L388), [400](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L400-L400), [405](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L405-L405)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

16       function getProposeArgs(uint256 electionIndex)
17           public
18           pure
19           returns (address[] memory, uint256[] memory, bytes[] memory, string memory)
20:      {

50:      function electionIndexToCohort(uint256 electionIndex) public pure returns (Cohort) {

```
*GitHub*: [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L16-L20), [50](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L50-L50)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

77:      function setFullWeightDuration(uint256 newFullWeightDuration) public onlyGovernance {

153:     function weightReceived(uint256 proposalId, address nominee) public view returns (uint256) {

177:     function topNominees(uint256 proposalId) public view returns (address[] memory) {

```
*GitHub*: [77](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L77-L77), [153](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L153-L153), [177](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L177-L177)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

143:     function nomineeCount(uint256 proposalId) public view returns (uint256) {

148:     function nominees(uint256 proposalId) public view returns (address[] memory) {

153:     function votesUsed(uint256 proposalId, address account) public view returns (uint256) {

158:     function votesReceived(uint256 proposalId, address contender) public view returns (uint256) {

```
*GitHub*: [143](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L143-L143), [148](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L148-L148), [153](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L153-L153), [158](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L158-L158)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

69:      function proposalVettingDeadline(uint256 proposalId) public view returns (uint256) {

75:      function electionToTimestamp(uint256 electionIndex) public view returns (uint256) {

```
*GitHub*: [69](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L69-L69), [75](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L75-L75)

</details>

### [D&#x2011;23] ~~Re-org attack~~
No specific vulnerability has been outlined, other than the fact that block chains have re-orgs, and nothing is being cloned

*There are 2 instances of this issue:*

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

75:          return address(new TransparentUpgradeableProxy(impl, proxyAdmin, initData));

158:         deployedContracts.upgradeExecRouteBuilder = new UpgradeExecRouteBuilder({

```
*GitHub*: [75](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L75-L75), [158](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L158-L158)


### [D&#x2011;24] ~~A function which defines named returns in it's declaration doesn't need to use return~~
It needs to use a return here, or else the function won't work

*There is one instance of this issue:*

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

47:              return false;

```
*GitHub*: [47](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L47-L47)


### [D&#x2011;25] ~~State variable read in a loop~~
these references to the variable cannot be cached

*There are 13 instances of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

/// @audit upExecLocations
84:              upExecLocations[chainAndUpExecLocation.chainId] = chainAndUpExecLocation.location;

/// @audit upExecLocations
130:             UpExecLocation memory upExecLocation = upExecLocations[chainIds[i]];

/// @audit RETRYABLE_TICKET_MAGIC
149:                 schedTargets[i] = RETRYABLE_TICKET_MAGIC;

/// @audit DEFAULT_GOV_ACTION_CALLDATA
194:             actionDatas[i] = DEFAULT_GOV_ACTION_CALLDATA;

/// @audit DEFAULT_VALUE
195:             values[i] = DEFAULT_VALUE;

```
*GitHub*: [84](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L84-L84), [130](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L130-L130), [149](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L149-L149), [194](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L194-L194), [195](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L195-L195)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

/// @audit securityCouncils
252:             SecurityCouncilData storage existantSecurityCouncil = securityCouncils[i];

/// @audit securityCouncils
285:             SecurityCouncilData storage securityCouncilData = securityCouncils[i];

/// @audit securityCouncils
292:                     securityCouncils[securityCouncils.length - 1];

/// @audit securityCouncils
294:                 securityCouncils[i] = lastSecurityCouncil;

/// @audit securityCouncils
295:                 securityCouncils.pop();

/// @audit firstCohort
340:             members[i] = firstCohort[i];

/// @audit secondCohort
343:             members[firstCohort.length + i] = secondCohort[i];

/// @audit securityCouncils
393:             SecurityCouncilData memory securityCouncilData = securityCouncils[i];

```
*GitHub*: [252](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L252-L252), [285](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L285-L285), [292](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L292-L292), [294](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L294-L294), [295](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L295-L295), [340](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L340-L340), [343](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L343-L343), [393](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L393-L393)


### [D&#x2011;26] ~~Do not use underscore at the end of variable name~~
A common convention is to add a trailing underscore to a variable name in order to prevent the shadowing of [another variable](https://github.com/ethereum/solidity/issues/11764#issuecomment-895813808) or function name, as is the case with the examples below.

*There are 4 instances of this issue:*

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

144:         ProposalState state_ = state(proposalId);

225:         ProposalState state_ = state(proposalId);

291:         ProposalState state_ = state(proposalId);

```
*GitHub*: [144](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L144-L144), [225](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L225-L225), [291](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L291-L291)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

242:         uint256 fullWeightVotingDeadline_ = fullWeightVotingDeadline(proposalId);

```
*GitHub*: [242](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L242-L242)


### [D&#x2011;27] ~~Save gas with the use of specific import statements~~
Importing whole files rather than specific identifiers [does not waste gas](https://ethereum.stackexchange.com/questions/138876/does-solidity-optimizer-eliminate-unused-internal-functions-of-libraries), so this finding is invalid

*There are 82 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/UpgradeExecRouteBuilder.sol

4:   import "@arbitrum/nitro-contracts/src/precompiles/ArbSys.sol";

5:   import "./UpgradeExecutor.sol";

6:   import "./L1ArbitrumTimelock.sol";

7:   import "./security-council-mgmt/Common.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L4-L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L5-L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L6-L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L7-L7)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol

4:   import "../../../security-council-mgmt/interfaces/IGnosisSafe.sol";

5:   import "../../address-registries/L2AddressRegistryInterfaces.sol";

6:   import "./SecurityCouncilMgmtUpgradeLib.sol";

7:   import "../../../interfaces/IArbitrumDAOConstitution.sol";

8:   import "../../../interfaces/IUpgradeExecutor.sol";

9:   import "../../../interfaces/ICoreTimelock.sol";

10:  import "@openzeppelin/contracts/utils/Address.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L4-L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L5-L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L6-L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L7-L7), [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L8-L8), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L9-L9), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/GovernanceChainSCMgmtActivationAction.sol#L10-L10)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol

4:   import "../../../security-council-mgmt/interfaces/IGnosisSafe.sol";

5:   import "../../../interfaces/IUpgradeExecutor.sol";

6:   import "../../../interfaces/ICoreTimelock.sol";

7:   import "./SecurityCouncilMgmtUpgradeLib.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L4-L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L5-L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L6-L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/L1SCMgmtActivationAction.sol#L7-L7)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol

4:   import "../../../security-council-mgmt/interfaces/IGnosisSafe.sol";

5:   import "./SecurityCouncilMgmtUpgradeLib.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L4-L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/NonGovernanceChainSCMgmtActivationAction.sol#L5-L5)

```solidity
File: src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol

4:   import "../../../security-council-mgmt/interfaces/IGnosisSafe.sol";

5:   import "../../../interfaces/IUpgradeExecutor.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L4-L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/AIPs/SecurityCouncilMgmt/SecurityCouncilMgmtUpgradeLib.sol#L5-L5)

```solidity
File: src/gov-action-contracts/execution-record/ActionExecutionRecord.sol

4:   import "./KeyValueStore.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/gov-action-contracts/execution-record/ActionExecutionRecord.sol#L4-L4)

```solidity
File: src/security-council-mgmt/SecurityCouncilManager.sol

4:   import "../ArbitrumTimelock.sol";

5:   import "../UpgradeExecutor.sol";

6:   import "../L1ArbitrumTimelock.sol";

7:   import "./SecurityCouncilMgmtUtils.sol";

8:   import "./interfaces/ISecurityCouncilManager.sol";

9:   import "./SecurityCouncilMemberSyncAction.sol";

10:  import "../UpgradeExecRouteBuilder.sol";

11:  import "@openzeppelin/contracts-upgradeable/proxy/utils/Initializable.sol";

12:  import "@openzeppelin/contracts/utils/Address.sol";

13:  import "@openzeppelin/contracts-upgradeable/access/AccessControlUpgradeable.sol";

14:  import "./Common.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L4-L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L5-L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L6-L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L7-L7), [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L8-L8), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L9-L9), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L10-L10), [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L11-L11), [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L12-L12), [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L13-L13), [14](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilManager.sol#L14-L14)

```solidity
File: src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol

4:   import "./interfaces/IGnosisSafe.sol";

5:   import "./SecurityCouncilMgmtUtils.sol";

6:   import "../gov-action-contracts/execution-record/ActionExecutionRecord.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L4-L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L5-L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/SecurityCouncilMemberSyncAction.sol#L6-L6)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

4:   import "@openzeppelin/contracts/access/Ownable.sol";

5:   import "@openzeppelin/contracts/utils/Address.sol";

6:   import "../governors/SecurityCouncilMemberElectionGovernor.sol";

7:   import "../governors/SecurityCouncilNomineeElectionGovernor.sol";

8:   import "../SecurityCouncilManager.sol";

9:   import "../governors/SecurityCouncilMemberRemovalGovernor.sol";

10:  import "@openzeppelin/contracts/proxy/transparent/TransparentUpgradeableProxy.sol";

11:  import "../interfaces/ISecurityCouncilManager.sol";

12:  import "../interfaces/IGnosisSafe.sol";

13:  import "../../ArbitrumTimelock.sol";

14:  import "@openzeppelin/contracts-upgradeable/governance/utils/IVotesUpgradeable.sol";

15:  import "../../UpgradeExecRouteBuilder.sol";

16:  import "../Common.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L4-L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L5-L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L6-L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L7-L7), [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L8-L8), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L9-L9), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L10-L10), [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L11-L11), [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L12-L12), [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L13-L13), [14](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L14-L14), [15](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L15-L15), [16](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L16-L16)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol

4:   import "@openzeppelin/contracts-upgradeable/governance/extensions/GovernorVotesUpgradeable.sol";

5:   import "@openzeppelin/contracts-upgradeable/governance/extensions/GovernorSettingsUpgradeable.sol";

6:   import "@openzeppelin/contracts-upgradeable/access/OwnableUpgradeable.sol";

7:   import "./modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol";

8:   import "../interfaces/ISecurityCouncilMemberElectionGovernor.sol";

9:   import "../interfaces/ISecurityCouncilNomineeElectionGovernor.sol";

10:  import "../interfaces/ISecurityCouncilManager.sol";

11:  import "./modules/ElectionGovernor.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L4-L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L5-L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L6-L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L7-L7), [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L8-L8), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L9-L9), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L10-L10), [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberElectionGovernor.sol#L11-L11)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol

4    import
5:       "@openzeppelin/contracts-upgradeable/governance/extensions/GovernorPreventLateQuorumUpgradeable.sol";

6    import
7:       "@openzeppelin/contracts-upgradeable/governance/extensions/GovernorCountingSimpleUpgradeable.sol";

8:   import "@openzeppelin/contracts-upgradeable/governance/extensions/GovernorSettingsUpgradeable.sol";

9:   import "@openzeppelin/contracts-upgradeable/access/OwnableUpgradeable.sol";

10:  import "./../interfaces/ISecurityCouncilManager.sol";

11:  import "../Common.sol";

12:  import "./modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol";

13:  import "./modules/ArbitrumGovernorProposalExpirationUpgradeable.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L4-L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L6-L7), [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L8-L8), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L9-L9), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L10-L10), [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L11-L11), [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L12-L12), [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilMemberRemovalGovernor.sol#L13-L13)

```solidity
File: src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol

4:   import "@openzeppelin/contracts-upgradeable/governance/extensions/GovernorSettingsUpgradeable.sol";

5:   import "@openzeppelin/contracts-upgradeable/access/OwnableUpgradeable.sol";

6:   import "../interfaces/ISecurityCouncilMemberElectionGovernor.sol";

7:   import "../interfaces/ISecurityCouncilNomineeElectionGovernor.sol";

8:   import "./modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol";

9:   import "./modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol";

10:  import "./modules/SecurityCouncilNomineeElectionGovernorTiming.sol";

11:  import "./modules/ElectionGovernor.sol";

12:  import "../SecurityCouncilMgmtUtils.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L4-L4), [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L5-L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L6-L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L7-L7), [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L8-L8), [9](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L9-L9), [10](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L10-L10), [11](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L11-L11), [12](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/SecurityCouncilNomineeElectionGovernor.sol#L12-L12)

```solidity
File: src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol

4    import
5:       "@openzeppelin/contracts-upgradeable/governance/extensions/GovernorVotesQuorumFractionUpgradeable.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ArbitrumGovernorVotesQuorumFractionUpgradeable.sol#L4-L5)

```solidity
File: src/security-council-mgmt/governors/modules/ElectionGovernor.sol

5:   import "@openzeppelin/contracts-upgradeable/utils/StringsUpgradeable.sol";

6:   import "../../Common.sol";

```
*GitHub*: [5](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L5-L5), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/ElectionGovernor.sol#L6-L6)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol

4:   import "@openzeppelin/contracts-upgradeable/governance/GovernorUpgradeable.sol";

6:   import "solady/utils/LibSort.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L4-L4), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilMemberElectionGovernorCountingUpgradeable.sol#L6-L6)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol

4:   import "@openzeppelin/contracts-upgradeable/governance/GovernorUpgradeable.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorCountingUpgradeable.sol#L4-L4)

```solidity
File: src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol

4:   import "../../interfaces/ISecurityCouncilManager.sol";

6:   import "@openzeppelin/contracts-upgradeable/governance/GovernorUpgradeable.sol";

7:   import "solady/utils/DateTimeLib.sol";

8:   import "../../Common.sol";

```
*GitHub*: [4](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L4-L4), [6](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L6-L6), [7](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L7-L7), [8](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/governors/modules/SecurityCouncilNomineeElectionGovernorTiming.sol#L8-L8)

</details>

### [D&#x2011;28] ~~Unused `error` definition~~
The error is used in a file that is different from the one in which it is defined

*There are 2 instances of this issue:*

```solidity
File: src/security-council-mgmt/Common.sol

20:  error ZeroAddress();

21:  error NotAContract(address account);

```
*GitHub*: [20](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/Common.sol#L20-L20), [21](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/Common.sol#L21-L21)


### [D&#x2011;29] ~~Unused `struct` definition~~
These structs are used outside of the defining contract

*There are 5 instances of this issue:*

```solidity
File: src/UpgradeExecRouteBuilder.sol

17   struct UpExecLocation {
18       address inbox; // Inbox should be set to address(0) to signify that the upgrade executor is on the L1/host chain
19       address upgradeExecutor;
20:  }

22   struct ChainAndUpExecLocation {
23       uint256 chainId;
24       UpExecLocation location;
25:  }

```
*GitHub*: [17](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L17-L20), [22](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/UpgradeExecRouteBuilder.sol#L22-L25)

```solidity
File: src/security-council-mgmt/Common.sol

13   struct Date {
14       uint256 year;
15       uint256 month;
16       uint256 day;
17       uint256 hour;
18:  }

```
*GitHub*: [13](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/Common.sol#L13-L18)

```solidity
File: src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol

18   struct DeployParams {
19       ChainAndUpExecLocation[] upgradeExecutors;
20       address govChainEmergencySecurityCouncil;
21       address l1ArbitrumTimelock;
22       address l2CoreGovTimelock;
23       address govChainProxyAdmin;
24       address[] secondCohort;
25       address[] firstCohort;
26       address l2UpgradeExecutor;
27       address arbToken;
28       uint256 l1TimelockMinDelay;
29       uint256 removalGovVotingDelay;
30       uint256 removalGovVotingPeriod;
31       uint256 removalGovQuorumNumerator;
32       uint256 removalGovProposalThreshold;
33       uint256 removalGovVoteSuccessNumerator;
34       uint64 removalGovMinPeriodAfterQuorum;
35       uint256 removalProposalExpirationBlocks;
36       SecurityCouncilData[] securityCouncils;
37       Date firstNominationStartDate;
38       uint256 nomineeVettingDuration;
39       address nomineeVetter;
40       uint256 nomineeQuorumNumerator;
41       uint256 nomineeVotingPeriod;
42       uint256 memberVotingPeriod;
43       uint256 fullWeightDuration;
44:  }

46   struct ContractImplementations {
47       address nomineeElectionGovernor;
48       address memberElectionGovernor;
49       address securityCouncilManager;
50       address securityCouncilMemberRemoverGov;
51:  }

```
*GitHub*: [18](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L18-L44), [46](https://github.com/arbitrumfoundation/governance/blob/c18de53820c505fc459f766c1b224810eaeaabc5/src/security-council-mgmt/factories/L2SecurityCouncilMgmtFactory.sol#L46-L51)


## Rubric
See [this](https://illilli000.github.io/races/2023-07-lens/scorer.html) link for how to use this rubric:
```json
{"salt":"510700","hashes":["aff740bff4","bf636778cf","566bd9eb9f","0334da8c81","c49f72f303","a2cae3616e","3cd419b161","d83d4942bf","e22dc42adf","4c5485ae9d","4205c59e9b","7310717510","dc0328a664","11eb9b2c1f","beff99320e","afe5978957","dcf3ed350a","8b10bae3c1","ded73207d8","9ce029a012","d6b80ca9f3","eb7279a298","47e2d81aeb","97bd3f059a","40d696c828","672b65d54c","35b8ffb715","481695b6ac","e1409c9dbd","c9d562ecac","fe19e1632a","e7441aa76c","14b72d98a3","6244370e88","4aac19566c","2d67e45377","fd56471f51","224f2b32ff","fd74f2971f","9fad1971c6","f341a03fda","de3ee7a2b9","aff740bff4","bf636778cf","566bd9eb9f","0334da8c81","c49f72f303","a2cae3616e","3cd419b161","7669cf26de","6922823e9e","87a476d0a1","84b0fc18a1","3be9893be7","2a0c0d726f","de3e8078c6","5ac22bd82b","856e998e9d","e853444eb9","fa8157c9b1","82fe40bfd5","fe8d970790","87620511cc","a049d1203d","1282c5a2ca","c0a6838333","18a0a394bc","1af3080627","4fb15c683c","e4820afc32","d7836b63ba","c1c90f50e5","7a6b5cc414","fa97d14720","72309ffbb3","5e165d7f96","c0d17082f0","fabb333dcf","8de7aac15a","e48bf1b424","42ead7e4dc","c7dc984217","81bae15e6b","1cadc7faba","4e1ef4397c","4e05cb1f0f","fd8a6b5085","6f9633f694","d3bff19c32","edab88e73a","643109f731","ae85f03a25","a544250928","296b655eed","b223f6e0ec","1469b8961e","1c7ce4e145","8d87b6f59f","8cae703962","069c665948","1a7fcb44ff","60fa87d310","ebdca3889c","c0e093bb48","09b722ecfc","1d849810f8","18e8cdf556","8c2486fb44","a17b1edfde","e829ffdd7d","314f1681ac","ae1fa2b2a7","5e5a0b13e8","6ea42af1cf","446e58e8a6","2c10b37b20","53431fc2a8","ca6d2652c3","50824c6a8d","15eedc5e5d","0c6ece823b","982158648f","0100df5fef","345446c323","de07578be5","d38eda3aa3","c1e0843b40","491fcf9685","27d1172d7c","c41b17f9bf","f7bbc96a5e","82f94d0311","bbd870ae25","84446a5f53","c4c186a382","b246a3f72d","8ba4ff73e8","0a30262741","133436b9c0","baa99453ab","b3470cc977","f62c1d17b5","272578d4e2","3d15dcbb3d","aa94ebf49f","e89dd2bbf1","488de1898c","c3c4902845","53a6200d6b","29b708b7f8","8ac0824bb3","3e202e3486","2d8a1326ce","1f058c1e88","6772f1b485","4f58b514a2","ca85484108","0db90217dc","53b5a0b29e","9d8ec67b76","5e445e1426","9c855e01aa","13861b446c","abab76cc65","f957bf9a0b","02e81a6b8b","670c452efe","adaf9d2158","24220a1535","4b5cc181a1","9740d48816","a484d3389b","3905e1368d","76d5f8a4ff","9435ea9db7","006672cf14","6e065757f6","3d31998800","42888ce4a0","a07d6be273","bd872a5d4c","5c47c83178","f32aec8bb9","14c6cf2d25","bc57d73ceb","82ce4c9007","d5ea28798f","86ac5ae4f7","a6a8e15455","61410e5851","8ae2f21266","e164bf2737","a178a49f30","1cc0342f02","1994a43936","570e76c573","5070983d80","840d519dd2","35d8c3e09f","a15c497a24","e0638466c2","c7d5e17d99","670bddeef7","05943a1a1c","c488e0dd54","3f1e72f995","5511e9ec0f","c7adee9284","4a4e55cace","be3aa883fc","c0aad371f7","17ef29b5e3","44f923ab82","c3516a493f","e3f37f407a","791848ed2f","aa5c3eb54e","1457d02dc2","f321cea2cf","130bfd2b9d","7f0170a643","568a7c51f0","e28bccd0b4","d1841c74c3","37f8673a58","5dd2fe6bc7","8b048dbcc2","3de07a2825","b94d35aab9","02011793a6","a3f0170e78","c0aad371f7","17ef29b5e3","44f923ab82","c3516a493f","e3f37f407a","791848ed2f","aa5c3eb54e","6a04fadf52","987d947afa","8ee6cb1fb4","56a2c25520","76eafee8c1","a9fe184662","b1caefa0f7","9a13b94044","f652dab143","2b97d90e5f","58d7c61d3b","a0f5cd18f8","52f2fbe56c","ee39a97fb4","bf1db80021","076b230e56","1c0a2b9f64","60e015635a","428393e299","d6a8064a1f","3220d0034c","63527a66e5","147f738a6b","0e2202e07a","d04f697e8a","b9159be802","a09601ea03","93bc9a4c74","a102b01ca8","fa30fba141","3bb60041f4","4dbf0a5d15","8425b5d8f8","61baa7fa13","39d9e087b0","8607d3c6a4","2ee7ec8368","f0a95760f3","6ea8341faa","c2231e082b","6791197a2c","8e6a649568","55fc64f2a1","2c25f7f2da","9e5a74a3b0","b32ddc4272","a373571427","4064897de7","6ea9c6ba7a","4f913eeffb","f946b82bf7","49a3b82f22","0da725be71","e70956ed36","6c826121fc","5acd203999","e9c62a297b","230d12100f","e724517f9a","b257976f62","cc996053f7","f58629d4d8","85bd50b894","3f437ea04d","de0b0ef9cc","ea09fd2f66","7600c6ed52","05c21d60df","d2d045e5b8","be25216d08","b9cdd5ae8f","0c09dd1be4","544179f6ed","7390dde1d8","f7afea1444","59c9afd05c","9636fe42c6","84e3a72f43","2663d51378","a4943a2d65","a07cd5389c","ad9fd744f4","9d7b2ebc9c","fa68aec65f","f551992fdf","d45a052aaf","cb8f5e94dd","47b50eaa49","ef95666396","24b411948b","10770e864c","6e9fd4d5f9","d239b188cc","f6b6a15be1","08532bd178","7e4d27a902","777139ac98","621ff1ad4f","873ee76cce","caa80b81e0","e3bb8c77f1","53d0dea750","377fe7e2c8","7bddf4c269","000e27bcf8","e92c287fcc","737073fce3","8827054cb9","32b865692f","8f4095bb4a","be66e4d40c","7f3eef70e6","b7af0e6cf6","1e96aefccd","2db03eb241","54efbadaa1","f19bf95776","d3a6d0daee","5ab1a9aa81","5242b35a3f","bfae9903e1","445546da65","6249cbf680","5069e900f6","11bbc9e62f","3caddf7cf5","8c124afc1d","c2bd1ba764","db160c4e1e","80fe2df609","1ecff57118","5616b7cf1f","11cb8b3c70","f551992fdf","d45a052aaf","cb8f5e94dd","47b50eaa49","ef95666396","24b411948b","10770e864c","73c4bd2026","c7b9528732","e7c78d23e9","0d0dffa2ac","ce42ab5d2e","fd76cf7f54","a4e4ec020a","4d155772c9","b32a13201c","0d951e7ca8","f9838a5fa6","0ecf699a57","5ab4638e63","d1d1170ac5","20ab73fd59","db12b4a45f","2e58cfc5ee","48f7ab6c24","08315922d1","f2d82620e3","ff56d6c664","e4d752745f","745694b841","7479c564ee","bd8d21d29e","7c87c1708d","d2896ecdc0","05eb1ca6a4","dd0c70218f","2e1d1a6884","88808526a3","da57897fa6","cb2f24fb42","484598196a","ecc60f6cfe","b32c7b1dd5","f7a395c2fa","2457692a6a","6ecb78c8ce","bffb04c472","9d985dc259","ad7ba4dc6f","edbf805533","b0509c54cd","8e289798d4","1aa1781dcc","33ac7d6f82","48da2e3f70","34f686ff71","30ee6ce925","47ec03088f","b64dea3347","82230cf2b5","43bf6590cc","d3ba1b60b9","7f98808a33","c7e62c50f6","440c290307","ed58cd48ce","946b89ce40","999e679d45","b0e8767f2a","eebf2b5865","b32c7b1dd5","f7a395c2fa","2457692a6a","6ecb78c8ce","bffb04c472","9d985dc259","ad7ba4dc6f","9758449a85","1d4bd8fff0","fe42c7ab0f","bc88bc0183","1b0277fcf6","1ca6f52484","05ffe1f428","b34dba7dc9","374ba79475","4c37fbaddb","70074b5a19","30a74a80a0","d80fd26c27","b29f2ddfab","9207c3200e","53302789d7","3858f8412d","3f8a56649e","2bc97dd502","11312279f1","22d9b282b3","68ab28993a","169ee44f3d","ff50013078","b51a5c7929","e325ce8f41","85a08f1aa6","5c57b1a607","1213c0cfbe","365c602cf0","06ec67d7c6","ba0bab134a","037f70a408","febc1aa588","3a5d101597","8de75702a2","47ceae8c48","e7a01d4ddc","b8da07506b","d5b7b456a3","154428f0c8","8f2d909625","8a2aa89a0b","cc96c74264","8643c14590","f2569207e3","7d465f87a3","a2bfb76319","930bb578d5","623cf79cdd","5ac956382e","78224fd59a","da87cddb2e","bfc4d8a981","ff60fdd6df","6b7befa314","f9842502db","f1c14e2874","3391c71369","d82f4e8b2a","8dce4ceb37","74ea3d7f84","c0c73cfccb","f81ddb93b0","730b1a41e3","341bbe6149","80903df31e","89af56311e","681dee5028","607dea0cf7","b32461f415","15d6186715","b7c975952c","1abf99b563","0af5c533a6","4f792ea5a9","fd5e2f850d","a08f0aa868","c3becacd68","deed5c9dff","5c79f3b266","42d48fdfd2","f881a23258","8ab595ca4b","ee060fb1f8","4b49ba7fe6","d2bbd28231","8106f149a5","2aae41de2d","866f0276fc","8cd4ced41e","ef54e2a393","4ffa84506f","741fd6021e","d211608e72","2a53824b67","f4897d9f8c","722be739e5","c6c87b29c4","dc3c61f1f9","8201f55bfe","12a0e5cd76","fc47254a3d","6ea434c6cb","b154dec874","c6c87b29c4","dc3c61f1f9","8201f55bfe","12a0e5cd76","fc47254a3d","6ea434c6cb","b154dec874","9adb6f5d3a","aafde733ae","fa61a692af","a8e07d404b","f55228a59f","b1ef2d1e3b","cfc9765433","e5907592dc","633fcc0964","2301acb921","2f950e706f","83367dfd99","ccbc6b0db2","7c000aed8d","cb9f239250","8a7d6eaf4c","b3fcd7251c","6bb8dc5d3d","8d34d45e2f","ef8759c0d6","13cb35e2b0","f355ae64e8","b812ee9365","2ef08531dc","eb15c849cd","01674486d1","c3873b013c","39ea284fd5","20053b6aef","a272b60b41","475c875792","9084ef8709","0130a5a8d5","14243a9d06","eed58e94eb","7e7d12e95e","fe298ac94a","e0bca0e345","b05e314ee5","11304bdaa9","c8883a05c1","8238e99911","97e7921f7d","ef70b6efe8","6be15fcb89","81c935d961","5a02adb320","a225771039","f30ce111bb","70f7d806ba","efe7139d7c","2a367a4f5b","0bba94484f","af006055d5","7b223ed7da","b9070f78be","19c1e2403b","86a951cbbd","83d80b5b3c","b17f68dcba","f309801221","08dd8bc205","f62a0764a2","864beb7195","b9dab9d861","8202b3221a","32a5e60c18","3d1f406e57","c842b8b185","4cd09c4264","4fedcbe465","239da6dc47","7d6b0399db","22669bd71e","cca85fad98","fdc85db535","ddb470145a","b81b0566e7","28a1283d8f","5fef5e8f7a","a23645a2a2","38ffa7ddcf","2d8be84b25","ba73fef36f","17806ec076","6a465a82c4","dc4b5bcd92","c891e4b86d","2f4419c125","1bcf283d1f","9f214becb1","eec62ba94f","dde2fe115a","32c4692910","c95e1ca519","35109edc96","ae9a3f593e","1fb12887eb","f9929e1d5a","ec1c295676","967c5067b3","c41fd920a5","86469972ef","75a068d51f","0516666f3a","eec62ba94f","dde2fe115a","32c4692910","c95e1ca519","35109edc96","ae9a3f593e","1fb12887eb","17806ec076","6a465a82c4","dc4b5bcd92","c891e4b86d","2f4419c125","1bcf283d1f","9f214becb1","70ec12ec1c","95637b0811","a80984fc79","b7797ec530","dcfa6905b6","b9a3baeb53","097d38b6cf","2a8b7d4175","57c73075ff","8f9bf53892","a70d10c300","2a42069709","b15d79d1ca","1c0b5731d5","c8de36aa6d","ed2d2f728d","596b35e86d","ff1a718fe2","ebdbe331c0","6d04bd7e46","d44149365d","9c0cb758d8","a9ee9dfe91","2c2cea47fe","e9f549162d","5ad5dfd0b0","9e4110d6f0","a663e941a9","2b2ed9a0a2","e7ddc264fc","5f544355dd","1ada3ea8fc","baaa3cc35e","fa26ef4ca4","ba163a8a8e","cdc6356d6a","132731464a","4b19833ccd","a0083c44a3","efd5f0e75a","33b7194c1b","985485b7d0","faed8942cf","60032a9b74","8d9cdccd11","74153f6e3c","07e74fab9c","9504938cf8","3124c637f6","c00fc5bb99","b4ab5f07ae","7161aed0cb","1774cb80e1","58678ce9a5","6fa499e456","b937e35738","1631d12cfd","ad050553dc","fd767d714c","553f88db06","0c17d06e32","c982b6d830","5cb8d81fb1","cedaac9603","fdf695e52d","6238e89212","40b10cfdbe","75b29d4ea9","358d4a046c","d79fd98e73","abbc501d45","2e77306d17","428bb04415","71d80ae1fe","d01e047a4b","c8f4894e67","df1cae1d16","684e4704ac","d395de5db8","00872bfce2","ab300155a9","3f18e0375c","49c6abf6c6","250aee6785","e8f9ff0209","7e3726bb40","eabda1b8b7","f08545d489","b421eaa7bd","f6042e632c","8721a84111","97b62ea9f8","b30f5b54d9","65c82a6ebd","6e77247aab","66c5796e91","1139b8cf24","2cd25c1f31","cbee81368c","f598e40c00","c570234d3a","d4d1285e73","040bafbada","fc8c1ca091","6782e406c3","b706f589ab","69aa4c4a4b","9234b1c698","01e9d89540","e87fdcc913","d6bb76879e","2d58b13812","9058e85fad","16cad112d1","f7decab30d","ff02ee3d47","51f544d72f","e5c473bbc8","6d7c041097","a934d85241","ed58271412","3ebc6eb282","19d98b1189","111c63e23a","c117948516","cdd27cadec","9eb9048266","3fe31ff6e0","e3d01fcaf2","461650561a","af49838da9","791fde5cd5","fc1082e538","6b7a2be0cf","d6618ccd86","e326a792ad","6e706d0b62","11d58882b5","edbf8c06bd","7070ba2e94","632e738e7b","91e4844c51","c107567502","f81ef5ce6e","49a95834b4","d57306c7f2","6bde1f5d56","a934d85241","ed58271412","3ebc6eb282","19d98b1189","111c63e23a","c117948516","cdd27cadec","be4d045b68","2503a6a8ed","65f8143c37","dde81a9c75","c324702ec4","d47788cb19","c9264cde69","895214664f","3adaef17ca","a2a7f1d8ff","ab1cf94c31","26dcc6cb0b","d300b900e8","3fd0f92172","7baa2f0d7c","c8e060b4e6","7ff4d40186","2ecb2638f5","11a958759d","dde5ff504c","d0fc63ebaf","86245b9c81","902eec2363","1789f82d67","35e7d75a5b","3b6c6a6f1a","1615468ced","a7b66010c8","1f1a612384","ed5f2757d1","64cff861c8","0b9536dc3c","19e8c45475","426cb04630","476a0118ad","ae37868041","6dee4518af","ccbf467c7c","8583ccc9b0","408480cc6d","8a9c5291d7","35d2b1752c","7c326f16e7","0ccd5ae655","b9cc91ca59","efc2f811bf","72c3e7880e","ced0184b5f","2b3254c37f","754cbbd301","700fe95beb","c5e15bdd50","f8cbdc4700","07629d6225","c9b5e590fa","497024fd7c","2e2b7dfa8b","9b2100ae29","8b1325134a","64c9d9aae2","f215d1ae90","a814ac51ef","c42c7bcaf0","08e686ff26","49eb2a4bb3","1518f0ac63","bbbb4a8198","5e3a7693aa","777a096440","958930e7ac","15ce10ca78","a3a7696681","b4d66541ff","beb6699762","84cfe1bd36","d5e856595a","6b8777e0b6","f8ff6e91b8","d2d4fac2a0","deeb758277","2f4c80bafc","f8482bc74b","a88e5d43f9","ba068b1968","355b8a6fd0","89b10bc465","830ec5af1e","028a487525","625cd8e335","0981b24930","15a13885b9","135e746c86","89a6de5329","69ffdb9f29","efd46362c5","9aaa36877f","a4bf59fe94","2dda7af412","f450540187","324b767717","53b9b19359","1253c90df6","eb8421d353","5966485c1b","5db1c1c743","8c4f80d1fb","d604cecb82","1322aa4ce2","b46f920087","40090f530f","ecf99475d4","b3fb622c20","fec000ea54","22adea0191","d33fbc1ac6","81c9419d1f","9fb52f45da","5dd682afdb","076054af93","d63c51f3cf","51e8057b65","c9023a2f07","51488faa03","e4ed4c4763","6e211515ff","80d5850ca4","1f9dfb801c","53e796960e","d8b45f246c","9adb2577fb","2ec94661a3","83fe9cc5fa","7cb9e62cb3","cdaf121a7a","44cff580a5","f28aa36149","86dab2b424","13a23c5aa0","1a3bd0a6a6","15ec051344","a1241b0f63","b33a424844","a44f1d51a4","0b3e903bbc","09008f4801","d94dc3283e","4f2add46f3","5651c34e71","dc6f398ac7","81ce147561","2e43772311","619f7e18f5","98c1cfebb8","35ce12cba1","b6b8ab1798","9dd7ec4f35","c7b871497d","cf8e026a79","11474590bf","8dbfde13ae","a1d5457a22","e8c0f9c804","866906d856","2609e6b65d","7ea8c28f05","c2e1944324","53e706bb00","e34db54b94","106430c62c","ceacbcbe14","8d7ef06c74","f08130741f","1669d02e12","23b7969929","89cbf9477e","2a4ba72b68","0823bb2663","be6985fbb5","fdcaace319","7f01136f69","97aab8ce63","7de316f5f2","b81b5ead40","1d53fe27dc","6716b31217","a0f34ad08d","35648888e1","37eb29a46d","10d575c1c3","dde5ca5cdf","9dbcfebca3","eef06c477b","377ebff245","2eae77d04b","679029ee86","40c0efebbd","15a8e0ca5a","e3c0329b9f","f6d28e03c6","682bf02a81","6ce69c3cb1","b19d6a6991","8e1249c9a8","d74b2f2ec6","90f92fda29","f4e0dabadb","10b99ab05f","4ff51ac672","e6667eee99","6eb3f89dbd","7dedbc1d54","c47ba49b62","1db829e4a4","32574a62b7","f4368403f9","e1233b8866","76fd006607","3aea2b9f9f","17a2653437","6317e61400","1d507a6448","04088a8748","aea002bc95","a91d0c5d69","5de9a22e11","ccf18833c4","e5cf2fdd66","8df4040e4b","9bc763aadc","578d045a85","378e8427ee","ec97ce7bd3","e8ac1ed366","f6b1ca59f3","1327d08672","cbdae97eeb","03e68ae1eb","babd0ab49b","f006bf639e","7e6af4f585","78c22cc25e","b02b892cd8","248f168d47","08fdc03bc8","d1509f9402","f4cee63230","89cf954a04","d3f86bd031","2b1eb6ec22","9cdef250de","fe41437536","7f7ac0d333","a83dcd865e","55bf41744a","f52bd444fe","ed3f496bb4","7dbac9ca9a","30ecfeb583","b9a719f2fc","282cc0c107","dff11b81fa","45ffd11f37","9becc1d52b","51c4723e19","c10b27632e","2200f222bb","4cf0e2c4c2","c51bb298b1","ecad074b3f","0e22443bc3","38fe0b2b67","71070ef57b","c67321727a","29b44c80a6","4da17154b2","2ddbb1760d","c457dd62d6","e0abe2bb05","dd25c45b2c","c71a3d60bb","e9425f0976","ce4455d698","779108199e","c7f8e9b684","50dda71486","9894d53bf3","b1c2a90425","cd1b2bba85","4bcc800934","4e2be6f2d5","8e79f17a88","0b3bda92be","90a22c34f0","530f57cda6","2ecc3bdc61","676451e29d","615649c756","64f445395a","3ac03f83c7","1ea5dfe317","ce77859cb2","8775d03d5c","ad30370eda","cf70f848a1","56f7f8ca25","d7782bf1d5","14e44202dc","c20d0cba4a","45bfdf0226","70a6dfe64e","258061ddab","ff63f63f05","c59297285d","b11373b517","64b09c1630","7a86a6186a","e9445ff6f3","d4038049a5","68872667d9","abfa7313ec","02aa98351e","be6e91a3ff","119713dbde","6d00978115","e2ef7a04f5","7609407bd7","6ce4e1bbe0","eb49b6dded","d811cee38b","9f8dcf4dc5","485e44d2ab","14765f357e","3ae3e50cf8","4f5ae0b4e3","ce4ca03c16","5bb401726f","149f5e5742","b763163a59","91f4e2a058","13c0402515","ab8980e2b9","b3844bd1a2","816094b636","5596cfebe2","5d2e057fbf","717f60cf02","3088ad4b43","9b841367e1","89b952c28d","1ae4d10495","95e8ee8226","50ffb57112","d51fe1b5f2","9300cba268","28fcbbb52f","c3b498c6b3","b50c20b0d1","307727523c","b92fec1a7f","8fc01409a2","4587b114de","51cac10836","75efea86ec","eff4f0cad4","949d217606","335e65c71a","2e4ed20917","d263fa0f9d","6974ac979c","4992a58ef4","7988575b67","36b32777aa","c5c18b9dd3","a2e467d9f5","3f180f97fa","8aae3bc05b","7bcc61d894","4c550fc69b","710cdadb32","22a496e279","9c5009d013","a7d620013a","15d0cc3db7","00aaf77085","0c60cbbdeb","8bb2c17e61","4ea37da9eb","83d400c2e6","b93f1c617e","eca65e967b","c2fcea4587","5b811897f5","334def86c3","5211051ad2","c3dc0ddbc0","276daf941e","8d0e85b902","2877994479","75e49ea7e0","54e7029e00","9f4ba12478","317cba294c","0cac6f2466","51adae2f81","ff32f632b2","7b7f60fa9a","3bff785cfc","be49debb47","50ead39292","2345bce49c","2330546724","6aa4a0caaa","35262622d1","8216bf48af","207a8c11ae","eab37c9754","9f7e1405bf","00860ef81c","6e67b81700","5a0986c3bf","03368d274c","5b4d9f0183","360e9bc934","8e12b77ccd","099cdac91c","8c5377c99b","95ae7c5341","03368d274c","5b4d9f0183","360e9bc934","8e12b77ccd","099cdac91c","8c5377c99b","95ae7c5341","f177666bab","988f7b7cd1","9ffa760d92","4d47d8102a","36a8374f2c","658e6f9899","0ad937f12e","1ff2060e59","6e5bd949ec","7d9ff1daca","74ba3913e6","dda8a6d9a3","10189274b9","51cbbeb23f","782728c51f","0efdd36315","71c6f46060","6a350a8749","506aa65478","dddef67c57","8a46befd0a","64f39bd86c","f9a6b1a1c0","db51463608","9ed46ce444","0f7459cb44","9a2469c0f9","12a12dafe0","b6129ab965","c8a04049c9","09fff3ade5","2e5f36e2a4","c38b474956","2f2b28313e","b75530a10c","9f2cf8c7fb","2a7eb67dbc","edc0c62b46","aaa16078e7","5beec6e709","e33a5fb02c","890b732321","9e9eeb7c0f","6f74e09a8b","1891ca1a9c","e77ec282d8","c907f216a2","ac4c7ee566","8e1bcddf12","ae40aee30f","46095b043b","0e52bdd92d","9246dfb4c1","709a638977","cb6ecc3a46","0d86c5d645","26e8f24aed","b08d6da5bb","a2a1c5beaf","ee7fd17823","e30fc6a6ca","04d2b01240","ce4e57a5c3","b8a197de3f","24a16fbc72","6757b49db0","d7397ae010","ce30fba070","e47a697ee1","6796717d23","53422484e3","2cfbb10b2d","dd7c100be5","05d77e488d","448c960fdc","80de3f5822","40bfeef47f","d10d056ef9","3529a1d5b4","27c671bb27","77262b6419","0bf9b636a6","2bab30c50a","aa1c56c040","b60882b38b","cffa4f8695","63bd2f241b","067f1d7b32","6f1a1c1d4c","69812c0b0c","3267d7acf3","d3441b752a","eeeb239c75","e8c8362d14","3164c9d5dc","993e056f12","be598f32c5","dd8fbd4c80","1622b8f50f","e0d30c938a","18c28e8df7","3f47db48ae","21e81dd48c","165d3bb418","1a17170a7e","7fa278f5f5","7f001d04c7","71cb6a8809","846b4430db","ffbc0fb4d1","1a09255358","f617853bcd","b1b4717705","3536de1652","1be6387ec4","542c474163","f6ee730e3d","e99e44e28a","b047e32042","ef340d3a26","b7250320c1","fdcce381ed","074b2bd7cd","df1797408f","65477d0bd5","f77dc5f87c","56d122c170","7fc7eb8cb7","a592dcb100","844011b88a","eab657db31","61bd97d44f","8fa86df0cb","4f83f8d703","96a73de186","55bac309df","0b73538833","fe2cf957f9","0dd59188ed","4ba0adb603","aad9445299","c63e7fe8a8","39bd9b7081","09df684bb1","1423d609c5","3cf4b1d70c","20ad122529","f3e78be09a","e5c0c8971b","4549f22e14","396f1a3cce","fef734fd46","e9499348d2","b20a5ebabc","e80b2ab824","c0de899c76","b92414b341","5dc18a33e9","2a379077f2","6b10ff3f99","e9e2a285a9","a5cd2c3c30","5bfebab43e","ed940dd529","dc84788fea","4b2737b2a2","b71fcc567c","466ea1554d","727827b0df","e217848428","e9d9318d26","87e94d5878","89cb316921","47c33e0d3e","ddc9d59869","76086c4d2d","e04cfd4103","3ac80f48ca","3171deec3b","3e9b155730","98c8e82269","058fd5c0b7","76086c4d2d","e04cfd4103","3ac80f48ca","3171deec3b","3e9b155730","98c8e82269","058fd5c0b7","727827b0df","e217848428","e9d9318d26","87e94d5878","89cb316921","47c33e0d3e","ddc9d59869","4207b7b449","0fe1799af3","d0c273b158","6bc7e3093c","0e5aa4d5f5","44901590ab","838737c3d0","d40f772d02","a978a872ad","14f7c2d681","b325b2f556","34be80e321","280d979282","8db5ddb588","c7b2a0bf07","462f155a25","bcdbf6dbac","a4231ef6a0","c02f2868e1","5e05f17809","20852bc011","bb47c1c6f1","4764b38839","0b221ef84c","5803aa54d6","bf14ce3a30","209f2a4f1d","bad18ec97e","59bf2f97ff","2a924e6175","61829f0470","5a2c9b7f7f","e6d29c081c","9184db2a94","f8c931ed37","55fbf3b74a","3bbf279d82","067ac219a2","9e9aa190f8","504b97bbe3","f3eba17da5","df4767b47f","bb47c1c6f1","4764b38839","0b221ef84c","5803aa54d6","bf14ce3a30","209f2a4f1d","bad18ec97e","d7d7b70eb3","d0da7b94f3","7da1022af6","f4d16a250a","db33dbf365","57a37e2125","3d9b194fe5","0e89567678","86c8e53202","f0024188f5","fb48f6370d","07e8a6f4b4","b24a5455d8","e3750eb18e","49396ae843","003582c04c","4278d0e89a","d6059cb508","a81bbdf298","a5cae92750","4bb358c4d9","bc4a4093e2","cf73de2051","1c09ffde6f","68a2a3f162","0faa295095","43a90d8e90","4a8b1af24f","8821cc4c00","d3ba760163","fddfb7e01d","2992b89fe9","70b21bc405","fc01c2116a","b12cb3c62a","375b16db3a","13bdd79802","be080250a2","0b2c7f578c","ad474c1a97","3351617c28","0fd50d1abc","268117d445","5405bd81bc","3c33ac4572","04e86d90e0","7b66a86ace","ee2fc5248a","e0cbbb1ede","57f2cf8a86","2786bfa1cf","1f15b2d52c","dc76db1913","e54290bf99","452588a062","712c48d9f9","d7a17b4629","4060520053","2b2dbb133e","34fcb672ca","06a07ab3ff","e1137caead","6a6a101c13","470a3fbcdc","0aae254b48","5c89e2564f","cf103dd9e6","4b2f5ed539","24b218b841","333a9659f3","3ff1accdc2","6539b8a1b5","21b4322a64","04954b9229","a1f84f6a3c","4322ba457f","39ef495680","5fc3ec3ba4","6082ee23e1","e9f2f1423d","7aeeba6646","2603f133cd","ee2eb31ebe","b9c7a885d1","5c4ee05b38","5a9c43aace","31a75cabbd","227b406f0b","2568068681","791f681db8","52d8792458","b11dfb3a04","2101af8959","fecbf17114","b31976bbaa","49d6dc5786","b7fc2e935e","fe5bd0954b","7503acb3a8","f0347baa91","21c7779d5a","2f8f95c70e","48d1ea6c03","6b2012e187","f4cf06dadb","b11dfb3a04","2101af8959","fecbf17114","b31976bbaa","49d6dc5786","b7fc2e935e","fe5bd0954b","48dc209e4c","120f9f9ff8","7f726b5d2d","5416f386cb","da6fd2777a","7f78a80000","bfd5c256b9","fae4879748","0c18f7dd3c","9177a32794","2eb7ff6cad","48cb2e9b37","eec2c65478","e2610b151f","3150537ad3","2278f87f77","fa3dca8bef","4cfdce5906","ac48b71ee2","428aad5615","4aeb873796","2bbd1191ea","e5911e741c","6da7ee7a6a","75012f19b5","3717e985ba","378e18d236","44445027ca","25c29c805b","50484384a1","b5cab52cc3","4bf7efbeea","e796b06e02","976e50f247","91ad20c4f9","430a73b992","7133a78c16","9eba8fd32a","cc0a9a3668","dd0e50376e","eb26a33e34","7c13974150","0ebbf8ef30","a5a0ee0cf0","b2872144e5","dfb79bf37a","9f8b3b0804","71ba28a4dc","fd5a634af2","d00805bb8d","b3bf02a1cd","76eaa795d4","c1af83e67d","632c55edaf","9ca0a32bc4","6a06c6d6e6","e47d3fdbd8","1459553fe3","bf519bebc9","78544f9306","e7a7b38322","24e1a7bf6a","c9fc21f105","f99733287a","ff835aea64","3b949b3990","a89de5b228","40343071f2","d6941a5bf9","b9dfe86329","b1b3956a97","7e9631dec7","6c66b8256c","f4b867b934","35e363a0bf","6556978a75","f26ee798a5","3eb04414af","7649e95593","447a74e5f6","ecb29e502b","9d9b7ea49c","2c946df3e8","2d56d2fa86","f5d83e23a4","a7db087a5b","b24328ea79","960ed6f168","dadd1fe419","959b5dcf09","a5bdda96b3","3708603580","3b7ac4d7a9","d6d75073e3","a0e3405683","fef0290ff7","908c2ba549","86bd18e1b9","3eb04414af","7649e95593","447a74e5f6","ecb29e502b","9d9b7ea49c","2c946df3e8","2d56d2fa86","f99733287a","ff835aea64","3b949b3990","a89de5b228","40343071f2","d6941a5bf9","b9dfe86329","ad1c4c002f","b9e27895ce","de0631c706","a42a276536","8a4e8ba9bd","30e05ff62c","cd668b221d","88c1756305","dbe8847c50","6ce24b4b62","9a4f99b904","996576ca92","a6e9ac2880","1491a4055b","228fd1c692","63b739fee8","dd58fff8c3","c354c74313","15fcd17edc","6fd5ce0441","a02e833dc1","d013d9296a","dcdb93ffd3","184b1c130b","1ff0cb622a","20db0ddeff","f255b10926","2e68f3c0df","08ba27fb42","a67c345b09","7d54c646d8","f1d5a58035","a2758739b6","3c8bfd9087","95d3ebdf3d","dce711ad31","1a7944e221","053226269d","4196698539","266e693c0d","36b6afdaca","b0dc484302","a4c7da685e","a498d47912","47814114d5","ce978589bb","2b9e854228","0d4b439ca6","c14b63d135","e75657619f","f7d7facfbe","e7f2b8b816","1488d4533c","ae0bb3aa8c","a8003f30e1","ac26f6dc39","cc9ad16e7a","abf375ed9c","0bf5714d36","311dee5fa1","eeff7a83ae","773c2ac493","ea1ca67f93","b457602b9e","488ba04590","6bbdec0fc4","0ec5ba1964","b8ce12253b","4bc4464d3d","ad1f41f6fb","6766c330cd","7206ca1768","335eb1b1a0","65d871354e","c6dcd96565","114dc79393","913b2f1b95","cb23f83cc3","17ec52cedc","f7a1c82ff7","243bea8354","595e8915f3","650e6340e0","7b86309eae","0f73725930","feabe8e11f","b309f4a25c","d2d913169c","2dcf7562e7","02994a74fc","9becb5f32f","10c4582223","d500547a8a","ca6b2f410e","1f388ed345","7c5f140266","1140f8ccbb","6a148cd3c8","85298e0aed","27861e06d6","a95aa8530b","3d58fe83d4","af938eedf6","252647554d","f821e8d93e","2750079b9e","da469f2c6e","ad136d56f0","c20e82c66d","49c16e2822","8dcbbed708","167a32de4d","12ec2ef4d7","fd5b4158df","7dd0c9c1b1","058e439b0d","0db21bc7b9","3de0993be3","6ad99ee260","5da923cc54","0ee5223667","b27160e73e","5eba8b7c1d","74b60655ef","4f4de6ad62","e0219fe0ed","e14b72f11f","f459fa1d74","945866ffab","5c36431646","d8f25df9ab","915bb47301","0961517a9b","c5b9204015","5fb23c0ed0","c099075f51","1354d8b29c","14fc2281dd","285f50a470","c16e29da98","710484ce83","31538eb013","de24955748","0420a071ca","bc90f46860","dff6d15838","ab56c031c2","a56412e03f","a41afd9fab","ac3e3e38f6","cfc7047b80","0a0f202098","cb863584ed","617595aa9b","3352fc37ba","427673bada","cdf86d5f80","ad77dd99ee","58784004ad","13918fa079","e90b58264e","636f746626","68a4d7c975","fe7495c278","312c13d91c","561b8167c8","cdc826242a","3c4c78844c","8250ac039c","8ba1c63765","8c67abbdbd","eb21d2b312","24cf545567","60a9665923","215d92f5d5","9a65f42aab","f08937c8cc","2948ecdf24","d90b07a851","3a7d60c18d","ecfb943305","7765bbb5b1","85cff1d844","7fe682fe31","75d62b83fd","91208caedd","e8e270b4f7","3883aada99","2922123353","4efdd75d82","9b7658c62f","4e59470393","defd7afe44","1bd28d6229","2966d3a206","fd80c072df","98aff56da5","c67ff89139","4e5beeb615","73c452de86","9bb6008e31","1391551fe4","56dded2b84","6706cc20a2","fa9a964e7d","bec4371a1e","44b0f35f5d","b17d50d783","697e67d7b8","c431e48a5f","1ec453851b","c6ae294237","d83aaa861b","fb98346a90","9b2dc5addd","98aa6b315a","adde29179a","31b7fc2a12","f9bec6aa09","0e53c2f14e","a214a6e2bb","cbe0cbd4d7","1ad0437672","3469f00f05","02dd0345f8","5e852c4f5e","6662f2f2cd","e0331ce127","4623accf31","db75bcc6d0","fc837016e7","d13de53b4b","fe281c118a","a6f551de5f","3dfb32d88e","4f3cbb9b1d","07bb9e1f75","b8c9f3fe40","d42391c0e5","8e53f26f96","e67290192e","3155c53912","df27d34097","571a294dfc","97945c659d","aa9582e858","592e6274eb","196b33c37f","254afeecc1","a233b055d5","0645213ec8","007647f2a0","ce334d04fd","b9c87e994c","3956a10936","757896dbdc","3ee9b05692","c5ab53f6a5","4cd17851d3","4bdeb20626","6d43a902c2","34a64bcd7d","4f73357326","a04e9cd2d0","78b7e6b1c1","a375f775dd","d42391c0e5","8e53f26f96","e67290192e","3155c53912","df27d34097","571a294dfc","97945c659d","2177783446","93e7a57b0c","f254fd0263","69d2dd37e3","f5616f83e9","e4252ac338","570e2022ce","538d226aaf","162be4f69d","1fd82400d7","8ca12aae28","b7aacd4985","6c667e2314","8ed969984b","55a63cb4ba","0aa4c77d9e","ddf304ffc4","91e39c7caa","d418be1bd1","2af620c4ab","459224fcee","6b0894ea30","179c2bc8e8","b14b9371d8","1eb56bfc13","c48435346f","de173bfd62","19dc0d761a","0054401306","8f782d8bd7","dfb32f3338","c8f1eeae89","0beb5b4482","6970702507","7d10f77680","5f1ad02637","afb2a7edc5","beaa8664e7","53e76ff85b","9f9777af8b","0b0915305b","cc48547f47","b3ab516b1a","a26122a2a3","5850509270","b2978e7a5a","eaaf06b1d1","d9cc895fda","a5540726b2","b0b56b94b7","86d19496f8","0cc8147493","01267e88e2","911c86df5b","4db15e4278","61cf16bc25","27eecd7b77","09c551f7b8","889a02b6bf","2b7a2f484c","460b567c01","f614c087bf","d60ff35ca4","8339c70f90","2644bc8ec3","e54be8ad34","37ba581926","97e84d518c","77878d9c09","4267c761ac","ae3c904a73","e6703dd53d","b9bb2d7b86","751b546515","6c7b9e89a7","3949d8d22f","85810c1891","0bc3d01335","1cb81da36b","d5304f51db","b10ee9ee7c","659cc0b2b4","cd2ae0b6c3","0b42bc11a2","77a2f76de2","ac13b75eae","09f1501813","007636b4d8","0331724393","76b71405ec","e1e1c3b1cf","8a668ac1f6","fb4248ebae","88a64d0311","aa83b3315a","5add79df8f","e33bc05046","fb31908126","1844c65e55","ae3ed54844","fb8427ff12","7adb4560a8","b058f8e74e","9d265874a8","ef76e82373","ce743910dc","466f9a5f70","26d49ff078","62c32d5fa2","af72208a89","2e468d1421","365fb5fe09","8c8186ffe9","99ef62a9ac","c9116bc4c2","bb21a72257","3853621059","df0a052a18","090d06eae0","dba3b1f5a8","7af4e1bee2","214e34572d","aa7a3f8af7","98cb41b617","94b7d3acd2","7605103df3","dea5d48caf","62c0062b8e","af2a2447eb","821a52acb4","b51678cf88","3c11dcc2cd","d893a083b2","a24c3355b5","9e63820890","90aba793de","4116f4ecde","c10ad9952b","3623084e5a","1639cece82","27c379f3c7","5ccb682f93","462782b1d6","5942c49569","42165d77d8","9199b2d87c","1c8fab6062","9c9c5c1cfe","1ca6d6ed2b","d821a61899","ef2ab9010d","44f0e796be","574bff9658","b326925195","61d3c37071","54499888f9","dad91cb727","818f397953","7b13b66d4b","a30bdedcd9","fc072fde15","d85cc1662f","41a2f80ab9","bc06828b8f","368b705e14","c4ca655f39","141d6b5d8f","373a6cb4a7","9bf82ab8e4","53d0a139d7","de5988c666","0fffdab723","571a7de0da","549d73e228","3f1e14b01f","6aef2d50e0","e2e622e152","597ea199c2","707bf45bf9","7e79649317","d2669d65b3","4ef00bd521","f4ae64ccfd","58a38aa632","52bd2664f6","631bfa1899","c09088aacb","8ba36cbb22","ebae3c5af1","e328be1242","a1af7fb4b5","0c40c64a3f","e073ee0144","0df20256d3","eff4137542","151625c186","83bf73aace","2c0118ec75","a474ea2565","46c4929906","57075066ac","5fcaff91cb","6c5ee78a9f","78df511e27","19688e0d30","3a65d344c5","f60dffe387","5bee581d8f","24865494fa","b0965fb68f","bb81bcb576","aac7e4a3ea","c99b99c3a9","4f0292403c","71b5013826","6c175860a3","1ffc18c7b2","968e5787e4","6e15568e55","df94a54e8b","6db9b1a45a","7cdb61f96d","79459582b4","98b8d55614","e328be1242","a1af7fb4b5","0c40c64a3f","e073ee0144","0df20256d3","eff4137542","151625c186","48840fe882","064b2cc79f","7f74e1563c","c4b2825501","967e466f79","4112f33918","8c77054a9d","3f17ec845b","e75546f589","bdd8b39c37","643e88c12a","69dfac035c","e8a78bc609","42070de96d","6d852d7340","d0c8e08f70","6602813f24","c75de2444c","3cdfa7f89d","ecb33ada79","cd51e02f11","441d60ed4e","0e20959622","45bb610c26","6cdd5a2561","320bb004f1","4705c5791f","afd6ab9f2a","529af86214","2e32b9e549","6326684ca9","715ab7a43f","ae9d362abd","7e51d15803","ddf098503f","2a8338b34d","92c0104351","f4b9a405c5","8102dfde04","5e543646fc","b0a3948888","5adf2b89d7","f6b1a210fc","fb3b163f66","edf9f3eaba","739dfd6cba","3728631699","9b02ca48c8","723b18498f","b8822ac685","6ea769bd9e","08a1cd12e8","75f78e8c3d","f89437fce1","fea643385c","bf948a3de1","b8822ac685","6ea769bd9e","08a1cd12e8","75f78e8c3d","f89437fce1","fea643385c","bf948a3de1","0103d467a9","5fea9a2f09","bf819c5df2","2b722ed3b3","ec7c945a02","4a98111f82","51adc24ecd","0103d467a9","5fea9a2f09","bf819c5df2","2b722ed3b3","ec7c945a02","4a98111f82","51adc24ecd","51b6871fc3","33829ef4e4","ba42abe4f4","fbd1b2a4ef","109ff5076c","baa281dc68","e6ea14e2d2","07f8346282","3226046fac","487625bf09","634f7a4610","698b41a871","e23dd9d3a3","04259b96c9","e734360ff1","c9b24fce90","ffbe1610f7","b88e63e06f","9bc69e5be7","35e15b1241","051ba25e86","ded50bb7c5","101f8abef4","fd7ced3acd","171c975931","08e992c5d6","2402f07216","a7e567f248","21113721d3","4baab55f81","d175fdcbcd","35d3902ff4","ae9a22cac8","012014f90a","2cfd7538f5","187fc43dd7","09364a9007","bf45eb45a6","f83198bc35","0559328c40","80ccf0321a","83d8fa8ccc","07f8346282","3226046fac","487625bf09","634f7a4610","698b41a871","e23dd9d3a3","04259b96c9","faed6625e3","a84eebf3d5","d7b9f955a7","a839ff993b","e50d3ca384","c5dc9fc159","943c59cb22","3848b13159","7b3061c0e6","ea56e61449","854a891725","f0e985f69e","797541e073","9e291dcc7b","74233fb943","acc92fcc50","b534540373","2357813cd9","846838f48c","dd163c639d","9823672a63","289bb2cf4c","da0e7954dd","e888b5bc93","b6636f9b48","4f3fb035ca","9715e03f0c","c18523a5c7","9346966fa3","2f525bb804","5f3c3b1c26","96d56963d9","38a59fe129","0629a405af","9ce2ef7cbb","59b3070fdf","d8056006c1","9be6808c1e","5f7e555d7e","f6210b7a4d","17e823179a","e7dde72b60","59b3070fdf","d8056006c1","9be6808c1e","5f7e555d7e","f6210b7a4d","17e823179a","e7dde72b60","23f4a2bb9a","a134b77b4a","5d2787f968","8bf2ae8a2c","5f123fce42","934cb80bd5","bf613b8eb1","424b73ae23","4a9aa9d211","550f28156b","b434b405e7","75164d4b0c","811f6cfb1f","8d955daa4f","f846bdba34","5e1a8e63db","078633da9b","0321376438","548e4ef86c","c37bf4f0ec","9a2bf51f67","297a2b7bc1","3cd37a4b8a","9f9e8f0e94","fce51aea6b","9f40be4a3d","59122f536b","3a1d2bba2b","aa8c6fca97","7466f1a6a9","f6adddc69f","0946b04920","fcb8c99ffe","e3bfe62bcd","2edc153dec","c915705c5e","a1b8f0b2a4","4633aefea3","c684c2438f","b8dde7378f","8af2794577","38ab7e80a0","ce3c7770cf","9921915565","bbb233ee4a","2dd08e4de1","79f191778e","439cee79f9","ba45ff6a48","aa8c6fca97","7466f1a6a9","f6adddc69f","0946b04920","fcb8c99ffe","e3bfe62bcd","2edc153dec","05d64eb48f","5421ef8530","b62b70e4d8","792881ffed","682bf6e3cb","78620a3590","292e9bac9c","3cd904d8dd","060fc70b12","a9475a852b","5a3c349c10","6520e48a07","a03f576c7f","ede8adcd3f","706d007180","2ac6d04de8","ddfbf27cc3","b506e0a149","f8c58ea60a","d51bae658d","0d741b7831","eca897d31d","0cdf123178","4400e60e8b","f7bbd32216","c3d078f31a","5f893952b5","27b31539a0","3d8a84eea1","09b9988003","bd46937eb2","be9a0d9dc6","96c52d05e4","e6eb78b36f","54b00d3208","cc06145e57","572fffd3b4","c1501454ae","d0ca25297b","17c17d6721","f246724492","813a8ea953","e53fb01ea2","1004b1874f","d3c4735edd","9b2676cb65","01c470c358","c4d2b213ad","b03be6a9df","808a5cd30b","434ebe090e","906d2b32b6","274c6c6b8d","e17f8dd1ad","cfd997194a","9e347244b5","4082bdf388","395c7e0849","b369232b7b","d35c207cd6","e7db85564b","e96f9a7d1e","212a17ed0f","00eb03ed7c","cfd699c654","915eff827c","308777c8d6","b2f41ede96","a9830d4375","ace0dc32ff","6039a61f12","c0cfb4cfbf","9961892e55","a152b1e9c5","89831e0962","208611fbdb","791345f834","c2f6ed1924","cb711e315b","bbc03f781f","6dca560dcf","937c046de4","48d3db04d4","312810073b","5cdd11e629","4e26a6b27f","101e429daa","634a75b2d4","936cf0e49e","618e9b9774","0e447040a2","7663886ea3","f6a114fb65","5e8eb97720","2e494167cb","0ba1d0e39f","275a9fb57a","59f576d0d7","8e98537c8c","a905be71c0","40972a7a0b","410c5b87fd","385468efe3","bb852ba312","fc4769e749","2d5d4d80a0","e069c395af","d1f45cde00","40ef078831","14ccd00889","c43ae98d1d","1804a77ef8","47048fa222","6abd7fd275","e07cb887a1","0912ca2dad","a20569ddc3","b7b9720f74","8a51d04fdb","40a1b33235","638dd10266","fedf1f82d2","d268fd6a6c","3d47673ef4","e4db7bc34d","2766113be4","6d96d48475","89cf875e79","da24c351a4","927692afa5","411fe5cc3e","5cec9e1505","1324b79fba","d83f9d8df6","5f9a4561f8","5be5c9a1b5","d51f584031","d866ee5cbc","156102fa4d","4fe8625e9f","cec14d104f","73a9939524","3a5a8cc4aa","bcb8eab5ec","001b53fa06","59742a8407","3b452c6e99","e04f9fde4d","580d187662","bb312f296d","4c6268ef41","4187b395bd","c205b0e260","e3059362e3","de7847bab9","d2d28ebf4b","fa4f4f3d2c","b91d9f7539","58383920d8","2c1c900370","36cf9b613e","38c4e29451","1ef122853e","16a85d4f43","734dfb46d5","aedf1cb828","3474ccf6c2","12d58e07df","346c7b251f","7535efa216","f740cc1b86","a85e6c4a20","be9ac8b7cc","d99a0664fd","8b7edb8eef","644f24143e","78cb7e94be","5227ebfddb","a0d6a45a8c","c353f13692","488cefbfe9","a22b3ef290","8f2792bd93","37b778343a","9323f83dcc","1f1dfb20ee","29ff2bdb0b","88fa309c3c","8b883c8586","e592a925b2","3afabfc36f","e3f1bc549f","6392750628","cb808821ff","1cca5eb88b","55beac4d49","6f82bd2e95","97bbbc953b","ece721a555","3109093da2","b6257ede71","708f83b267","4ee486f074","7f2835bbe6","cd438103d1","b2d869802d","6bae3d5c74","9e05796d2d","51c44111f2","35ec940cc3","3dceb56621","e19c2b6177","810f8b5119","4dccf7f682","27ebae0eb6","304cf03dcb","3abc84112d","94cfd86d1b","0a338109a5","27a2b14ee4","927284042d","121832f597","a0cf10e242","4331fe05b7","63bbe19539","5375302dcc","69f5ab4cd1","e92592a8d8","e8eb33142b","b74523cbd8","3a6e177b23","09804495bb","b019ce9b5a","aca2d00eeb","f3e1e79dcf","9ba47da656","fc444b8781","39729b96ee","1d77fc2a05","fa0f74a571","bf0eae35d8","cb79a91c67","73dc275cfb","b48e310bf6","8c72f86a5d","6aa55b181e","af28b7799f","bb0bb2531d","ec722ab89b","24268987a3","0be6cd9653","2b389df0e2","0b86dd9a19","e757ed8644","886ca893f7","351fdde661","bfc2baf133","001031e655","0cc72fd4fd","0b7fe3d85a","fe44171600","501a39e9a3","6551034d0a","30eb51a50d","14be346f50","e43aef2881","314fd45934","8161498cd4","e1e143c83b","752d82c2ba","fa5a97bd4b","bf7defa1a9","0d492fb5b8","0b1dec9713","39d4b9879c","ac24596804","268441e363","f21d2a524f","f41d1fdc9c","534235cf42","0563e4ca9a","1764a8b8b7","14ddfed387","b0aac724ad","11fe8b05f5","7b36cfae65","008eb8dc3d","4c28f30d28","55f50f953e","4f530c69fe","c2f22ab92a","a9d768e97c","dcff2c0a34","7d468da0c0","7786a46c56","525c2d3409","7a372dffde","c76fe5d9b5","6c5de8269e","ffdd868e4f","76fde68e42","2276a72cce","09d3919f75","5be3379d35","351d3d9f34","b79146536a","f2cce209ce","5314519bba","8c1b3ebcd5","12909c23e5","737312acc9","7b4fbe6a74","f11b3060ce","a1bc2b2f99","64fe2eaa8c","63a29eac2a","55fa77fbb6","af811edb63","9cf6038535","eb61da31a9","c5fc880e47","3c670c0ac4","7d728c0cc1","c05f025c7d","9094173ffd","21769d3579","822ea52c1f","d8069d8ee2","87ea2d0b4b","e8f9a68fe1","1caaada8bb","987647dd04","6253b27522","fb047be167","acf0f4c3ab","37243cf223","6e69e882ec","52393b973f","cebaa03124","782cc3a389","e9d3a5276a","c2c75795b5","42f9b07640","7918a547f8","6a35c22cfc","30db568156","52618829b3","7d56e4deba","4c0afbbb84","406d1f9f15","46f6af4e02","231347a936","ca893cc204","3c8e6fb8c9","1a099f23ce","98e90ffe34","bbbcdad7c4","28575fc685","aa3c920cd3","1b332a8800","28b1fc3387","41f2834470","6894a72fdd","49546ec359","ad7e0d7082","4ae75269f6","6963a25733","bf4987cb6a","7874cfc805","1fe6716671","8bc233bf43","c402046d4b","3e8248c5cb","d59053b38f","c1111f1a8a","d804decc45","77b58dc954","81ff4542c0","f9ecbbce36","f096b81657","f34008e4c8","3123a33d30","2f10d8d539","c6925671ce","870fff888b","4f56559ebf","88c4c3eb01","6fb3d69b65","07ad7fc24e","c69c509c58","7cf863a2a3","24cf24f349","2475cd5ab2","63a4f604cf","68f13ed8f2","0aedf5e007","a1d54b8ea3","bef0264a46","c07abc06a0","2645dc1f78","15d6f085f5","9ef61182dd","43abe22b61","d3711e226e","736fcafc77","979e8f56f7","358a4fdc03","774175ebf5","1166451f32","43351135e9","bb4da1a114","9dc607b625","dfec8f1096","9f1d6d49f3","035f3eb3d8","168f194fc1","cb305fb599","a110bfa2c6","c5bdf139b4","0e18d352e3","35b5a7ca45","3485ca6524","975adce8fe","6183431cd8","c82c156df1","2a48becbf3","3afb050b5f","3942be1f23","88fa3f3462","68b697a218","24e330ceed","581d9721a1","4962221ff1","5f8ecf024a","dd9956dca1","abb15d956b","830b539d36","69258264ba","5ffab904a1","4a326bdc51","3ef1aab8d6","beb9c27f89","1967e91375","04b32bde1b","fb047bdc57","0032896ca2","b32afec9c8","ce3f6f842b","65886d5e59","8bf61a94d7","a7301ae00d","19c28ba59a","f23e303d70","f3b41450f7","73acfde66e","1dd64cbb78","758dcfb1b8","d321326b72","b174d187bf","cab75a1c72","bcef4029e7","801e87b8e5","9f7c7075ed","2324c5a123","74b864ed57","a4d79cf85f","015e6ba626","0ce4bf447b","e0023ad31d","3083752897","9abaa626ed","ce8f9ac201","60cc6a95cb","3ab6a3fefc","9eb9dbfc3a","f36f01d3df","1f97b9dfa6","45531e2372","0a01a2a22d","aa6b68a91f","6546eafefe","e824816cd4","16e0062193","0bab37892d","060ab1dd46","1240b3f12a","a24423847e","6e56045869","3225c2706c","4a703d0264","a455f97219","29cae22d8a","bcb1ffcf1e","89bb832399","dd777d5287","4563855f2d","eac6cba56d","e6da779d53","658d8cd4d6","b940041ae6","92142de5e4","e3feb047a6","b9b675a87a","094388ca93","f883115d90","1ff4382283","e47dc4c586","440d0d2bb5","da7cabd24e","9aed10b41a","27fbe67c5d","2074bdb355","d14bf6d7e7","8d3d96f241","fbc4906cf7","57ff73d8e4","8bc41cef2e","c47a348132","852ab492c4","3af848ce52","d4893f6566","85db18518c","62296e32b1","5a1a409cc4","684455a1a6","8430f32b25","c84e17ddd4","55dce65487","35699643d3","7482012ac6","75b01d721e","b86d2f7d90","1c72cfddb5","db19c7662e","8f931078f8","2604988068","7e540538fa","49d536bca0","6c08dfc185","25aa0cc2fc","71ac3b4f01","08e08af02e","e9e1a54276","8f615cd3c5","9c47d1a00e","136f425da8","a3d7d08298","9a2ac017c7","95af63bc92","c4696586e0","3c5daae69c","2b6c21ebdb","4810bf83fd","7e24bcfacb","f40661b499","ac6013e7ad","7d35d4b1ac","1d68a95812","85a4cb7d9f","00c14826cc","b8c8886595","e127c1db95","983714ea26","8128c67bc3","dc18c153d5","49c1ab2c83","b429c434f2","11095d7af3","860cb22e76","3ccfa2da36","8c390a9bbd","e1a2175c85","023cd1774e","bc0e381f4e","7a5f65ca9a","31fca21169","969aa7e494","50dd3f37e9","db6d80aec1","6621390d93","fb67493569","acedc3edbd","6d4c8c1ee0","2777f116ac","ebc2e8bc45","99f4e2a26a","2555287643","19f3a807c1","0ca68fbc2b","0d9b08d04b","51d897e9bf","f8eda1ddc1","d91be1dbc8","4d26e4d854","93b3260a93","49b2da5fba","beaa2d2eb8","6667034c83","4f38b4360b","902f6521ce","356f383da4","859782ad47","70cc5158ed","ba497961a3","0abb099fdb","c35343e7c1","82dbec5716","7b72b1a8ea","fb8d0da8d2","156161609b","aa7074ecea","33b8e7deeb","5a3bca7488","00b3686362","f09351a1e9","86553b93f6","267e05c56c","06889ab213","3b28d59d10","4f3c36d338","eb165b6ab6","0a460febdc","9870ea8d71","708c1df465","e6a143460d","5865c067d0","e23c07e4f5","bcd5e18e92","6f3912fd09","d06f2e9ddf","a034da7ce2","c18b43ee90","0785e09485","a3f693002e","7de4a8a4bd","55b7e82d89","41544394ae","0404dd2ecd","fb5ff52f21","a3f53cc7cd","29636d5366","f39a246640","954fc777ad","ef5ff7415f","370180f255","17c52f627b","6e8eec0d7c","123e540131","11a1f14d0b","27993a30b7","bb7c2d61bf","78d1ad5d9e","7e5d83d342","0c69a18000","27ff4dcc9c","9ba5957c23","a04459a295","ff0912d773","08211ef6fe","ed2712ca20","357fae204e","51d481e870","9db126bb9b","f4a17f921f","259c4b8ffa","f64d606772","5a103da7a7","e3babbe8e7","8703120d49","99ef4ca21a","04e71ac65f","96019f9b02","370180f255","17c52f627b","6e8eec0d7c","123e540131","11a1f14d0b","27993a30b7","bb7c2d61bf","c82da87e8b","62d9684f9c","cf0e46e1e2","74d9efbf26","7199fe64b9","8a54b4b69b","83b969c9e9","a30f9688fb","4047d06ceb","c4dc53cb04","ebcaf21c85","3bb81ac288","cfdb7f39c5","201d5be476","93a4d7b65a","83917a0c0f","2d2b646ce5","87c6a40e76","0c0b0cd45f","228afa1ef5","064027b584","bd9a44b178","6a7030aef7","d592585f69","66028bc88b","e6591e3e0a","02ecc60404","a30dcf902e","976552f635","eb140b6639","0aae6612d3","da004371e8","43713dd909","2589229f81","0baa083c20","d361ef5d65","f13f6c60b8","119358e7b4","4408436ead","8ce38bc26a","4ef681ca4d","ed112fca1c","bab37b613b","530121d913","2a700b2031","1bb752e96e","3ffadf3d12","2e783c4faf","8dffb3047a","d2ed9c77fe","e0ea233252","5b44339a25","b4f40b9080","acd7e28672","c3de8ba939","15539d93b1","c85e531bf4","f9b8c8db37","5c4f02c470","f02cc7b4f4","10f7348366","787eff6d70","75c95a41cf","d875c379ef","08e59318a2","a4d78e3392","07a7217721","ab2d0c1bc4","ae573eaec8","c8cf5d457d","788992a1e7","084e54aedd","775dbbaba5","cd05995e5e","e55bb20f38","7156c4a1de","f0590f48f9","b650a7b7d2","72ef3d9838","be16bffd58","ca0ea28562","cb30491f73","2c9673ddef","8cf24b54ee","d9faccdb2b","ff4fa0c8e9","aa1071a609","ec82f7e33f","970cfe8289","c73dcb3e8a","f461b1ed4b","ca8e585691","77126f01c7","24043733c6","f6d2d00a08","3caf86a488","991334e39e","96a0f7a6f6","dbfcac938f","220a6d8e7c","30bdf2433b","0d5d876638","8f9d34cfc7","deb760940b","adcc83354f","2bce8afe65","97f4ebd0c3","080b49c2db","60bb8675bf","5829bc44b7","a184a9ec5a","cded581e43","c01ef9de38","ad13ebc0b1","81a7fc27d6","54005f896e","7847765fab","ece6a187fc","4d598e625d","0925b5cec6","8282fcfe05","b9fe19a00d","5f48e40933","0a93a154ab","234ac6b4b1","5a5324bc26","96f6ba15fa","7fd32838ec","3b41022ca4","95b86251a7","0ce0352698","8789c2d6bf","d18a77d055","3747eba913","6d236aa1de","84d72067d7","42bb67df10","4a376441ae","187fb890b6","f31afc6b47","c56147881b","3ea38e37c3","699be2575a","3b9ac1c990","74e184f241","ebe37ae9ac","a9815d2d11","8170b21c51","5f08a62498","ed3560483f","7f90042986","1c46a8bae4","902b81b417","40741fdb79","9679189ff2","deed97d1ba","f381dac170","b30ab041d7","fdf0631481","5ffa7982fd","4b40e71ff1","fef8be7516","71957287fe","588c5f3fc4","4c9ee2b64e","33c9a1e056","58ac518a1b","7dbc6197d1","9679189ff2","deed97d1ba","f381dac170","b30ab041d7","fdf0631481","5ffa7982fd","4b40e71ff1","351e9fc0ae","dd0990d94e","8b8f019a35","eefa711b1c","7d23f65992","53345b125c","254cca924b","bf5e14ab17","4ff3d205ae","1df6ab4231","4703bf3417","c925df73bd","8bd9942604","a69e6dfc53","7dd2f5addc","7f78abbe8d","d5470ad8ca","72fb8df7c9","e6b2cf8ad5","1f45dff58c","2bbd9702ee","fbcccd7dfb","21842fd816","0ca1e713be","741bd62730","8054b91f8f","fba0b74371","9a07de8588","8e0a5b928b","b74c942415","2a4948e9b6","5391bae5df","c8b53e3077","efce916cf7","d4572ccc82","e20f074439","a9a40ca408","8d283dcbda","7bb35e8d2a","9ada4da611","aab3df48dd","b83e4ec170","e552d27470","7ddf3bc130","d715cfd0e7","05f894739d","07228d9cfa","be6b6e82c6","99d087be14","1725f299ff","be482c9346","de03fe1a5d","5fb4f81959","351022015e","de2bc8575c","d54dd46ab6","b56098e44e","5690207600","4f7daba9b2","845b238a11","27219f5df6","8faaf641e3","8cf907a363","4cc91d1967","01da08f351","89153cb970","c1ff5f42f9","41b8e29382","da60b6b4bc","7958c52f29","83dc4a1c49","76aa0afdf0","7f19aef950","98f42bb46c","4a4db720ce","61225b6d07","9e21327c25","6f801c5dcb","70a10b7939","8683ea8c64","4e2c6f3c0b","dcd71f606b","91fe20393a","26d331c5c2","358693c975","a4c105e138","b730b67f7a","54c52f0b17","4a6ac05245","c083b6d016","4c229c8478","5cb2f5ccc2","3dffbfa2b8","9648caa303","09f83dfc4e","9aab3dce70","92ae84a727","305caac05f","a14fac696e","749ae98e9d","18e49c14f9","b250bcc3b9","609501a336","ce416dfaf6","5415f7bd1b","a1751a733a","8e97130900","9e5ab5f4e7","053ad2f68c","54a2e4cd9c","92c69f1ab3","aaeef760cb","13460ef277","2e2fabe253","da2f5b68d4","c5d7e21f32","ad81e6d2bc","53e6c3cce2","d785a2c194","578e37b0d2","53d6c81739","30c18bba4b","e19617d31f","6a26f84a83","3d389c2740","4e90dfce49","661a0305b4","c8d791d356","8af71943c3","6e61ed3051","f5963c3865","352b426c26","91ce8ba021","7a1ed27400","fca9553c1a","dcee883aa4","5d13aa4d6a","13f53fb56e","136d8ca6a6","2d640f03a3","1b2ebf2349","08b47b9726","67abe85e2d","2081c25946","1a50d07449","29364eec41","d1bf956be8","5106c13427","32dda58215","80dd6ea64a","d04c576d1b","73666369b1","7ede6ece41","bcb5bde50f","5547fc0149","2c3b1963e5","fd804321c7","3be4ae9fb8","6d427e876e","b830b8c034","18f7057199","ff83f2d01d","a125a13550","d70be31352","87e1b772c6","346060fbff","0c41dbaab2","792ba46043","297a9a987e","6a050333ab","109615cf8b","ec8dcda0ce","234da3d4b6","945815d292","c643f82705","483a110a2a","38c25637fc","b65209a65e","b3f631dc20","74dfe29690","3602265fc0","2da4fc2082","9b790a9dba","06f05509b9","163233bd9a","e1af7e5252","27cf8fa560","ed9ef63f0a","1c65b06463","92fb51a39b","7a68c08300","84c59fc550","9e999986c3","c670bb1fd6","2844c59f5b","772cf13b69","1aa333a37e","9ff3df37e6","1519bd5f49","b7d26e23f5","b98c2b8916","5b40c67206","a4dca0f4fc","40927e8ee5","db7692dd46","2429d79d1c","40096df653","948afdb2c7","69da28dcec","032c07ae74","2d366d5688","1b3a78fc15","881bb99c4c","2d92fb74bc","8b081331f9","541f2c8614","36efa049a3","796fe05d07","699315f81f","1159db5e93","46fc439db7","0ffd77cf56","333d210e07","49111a50ac","ec59ec0130","83631d5514","d686bc28ff","13daf44640","b492d87d6e","859793c945","e6c2f08159","2d2419ce52","904d963ae7","49d8e04942","e6254adfd8","b3ec5eb4c3","d470dc829d","09843c73b8","1791a61459","8e21b714d1","cfeb693b00","bb03af970f","07ccb95d05","3dd3238af1","dc8bbbb990","4198adb0fd","fb98cec193","037774ea66","e864a161b5","0b253ec5f6","b45fc41e9a","f8e2ea7b38","44b8566645","f67416d776","3c9871d888","6873a49974","83130d945c","0a2f202780","914e70a5a9","d98a692beb","b8478410b2","24e1267994","d9763d22f3","9ba9db5fc9","db4de56f78","1cda4fc584","927d24b985","ea99119d1b","3790b07117","c497f37a4b","3e61269111","b0a547f946","f02122a320","43133c9f3b","436f847a70","2b04309468","1c9554766e","627ff4fb17","ba28f6a343","72e585e166","b114a91abc","345a29fccf","efb70330fc","0f054793ad","247f554237","6e901630d9","ea3386eb69","e3870ad9b2","2ff4f80d68","583f994b7a","ed47dc32f1","1204a3f9b2","6209cb77ec","10ff386f5a","c4a0949f8b","f6d17ebef1","cf01fa670f","761244e88c","cc643d799e","af0ebdb4a9","c12805a558","e331bf2da3","e6732445d6","41a543a427","f314645758","3b2f7ef0ff","71416fe4b4","7a26d2bdcf","57be69491b","b8ed082189","1b338a2f48","fc52085439","84f1001413","aa63c36ab0","4005d3d118","c65b11dacd","e1db1a9a42","256b82eb55","1e25c0c907","7b06232e27","8b01630705","a676a7dc63"]}
```
