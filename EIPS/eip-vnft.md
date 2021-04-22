---
eip: <to be assigned>
title: <Versatile NFT Standard>
author: Will Wang <will@solv.finance>, Mike Meng <myan@solv.finance>, Yee Tsai <yee@solv.finance>, Ryan Chow <ryanchow@solv.finance>, Zhongxin Wu <wuzhongxin@solv.finance>, Yuyi Wang <>
discussions-to: <URL>
status: Draft
type: Standards Track
category: ERC
created: <2020-12-01>
requires: <EIP-721, EIP-20, EIP-165>
---

## Simple Summary
A set of standard interfaces for contracts that representing versatile types of digital assets. A single vnft contract can represent/contain any kind of, or various combinations of digital assets, i.e. fungible tokens, non-fungible tokens, or other vnfts.

## Abstract
This standard describes a set of smart contract interfaces that can represent any number of fungible tokens, or one or more non-fungible tokens, named as underlying assets. The representation itself is semi-fungible, that is: besides its ID property, it has an amount property, called 'units', which can be treated as quantity attributes 'within' the token. 

The _id argument contained in each function's argument set indicates a specific token or token type in a transaction.

## Motivation
The motivation section should describe the "why" of this EIP. What problem does it solve? Why should someone want to implement this standard? What benefit does it provide to the Ethereum ecosystem? What use cases does this EIP address?

## Specification
The technical specification should describe the syntax and semantics of any new feature. The specification should be detailed enough to allow competing, interoperable implementations for any of the current Ethereum platforms (go-ethereum, parity, cpp-ethereum, ethereumj, ethereumjs, and [others](https://github.com/ethereum/wiki/wiki/Clients)).

## Rationale
The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages.

## Backwards Compatibility
All EIPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The EIP must explain how the author proposes to deal with these incompatibilities. EIP submissions without a sufficient backwards compatibility treatise may be rejected outright.

## Test Cases
Test cases for an implementation are mandatory for EIPs that are affecting consensus changes. Other EIPs can choose to include links to test cases if applicable.

## Reference Implementation
An optional section that contains a reference/example implementation that people can use to assist in understanding or implementing this specification.  If the implementation is too large to reasonably be included inline, then consider adding it as one or more files in `../assets/eip-####/`.

## Security Considerations
All EIPs must contain a section that discusses the security implications/considerations relevant to the proposed change. Include information that might be important for security discussions, surfaces risks and can be used throughout the life cycle of the proposal. E.g. include security-relevant design decisions, concerns, important discussions, implementation-specific guidance and pitfalls, an outline of threats and risks and how they are being addressed. EIP submissions missing the "Security Considerations" section will be rejected. An EIP cannot proceed to status "Final" without a Security Considerations discussion deemed sufficient by the reviewers.

## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).