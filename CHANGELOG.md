# Changelog

## 20.10.4

### Additions and Improvements
* Implemented [EIP-778](https://eips.ethereum.org/EIPS/eip-778): Ethereum Node Records (ENR) [\#1680](https://github.com/hyperledger/besu/pull/1680)
* Implemented [EIP-868](https://eips.ethereum.org/EIPS/eip-868): Simple Subroutines for the EVM [\#1721](https://github.com/hyperledger/besu/pull/1721)
* Added revert reason to eth_estimateGas RPC call. [\#1730](https://github.com/hyperledger/besu/pull/1730)

### Bug Fixes

#### Previously identified known issues

- [Fast sync when running Besu on cloud providers](KNOWN_ISSUES.md#fast-sync-when-running-besu-on-cloud-providers)
- [Privacy users with private transactions created using v1.3.4 or earlier](KNOWN_ISSUES.md#privacy-users-with-private-transactions-created-using-v134-or-earlier)

### Download link
TBA

## 20.10.3

### Additions and Improvements
* Added `memory` as an option to `--key-value-storage`.  This ephemeral storage is intended for sync testing and debugging.  [\#1617](https://github.com/hyperledger/besu/pull/1617)
* Fixed gasPrice parameter not always respected when passed to `eth_estimateGas` endpoint [\#1636](https://github.com/hyperledger/besu/pull/1636)
* Enabled eth65 by default [\#1682](https://github.com/hyperledger/besu/pull/1682)
* Warn that bootnodes will be ignored if specified with discovery disabled [\#1717](https://github.com/hyperledger/besu/pull/1717)

### Bug Fixes
* Accept to use default port values if not in use. [#1673](https://github.com/hyperledger/besu/pull/1673)
* Block Validation Errors should be at least INFO level not DEBUG or TRACE.  Bug [\#1568](https://github.com/hyperledger/besu/pull/1568) PR [\#1706](https://github.com/hyperledger/besu/pull/1706)
* Fixed invalid and wrong trace data, especially when calling a precompiled contract [#1710](https://github.com/hyperledger/besu/pull/1710)

#### Previously identified known issues

- [Fast sync when running Besu on cloud providers](KNOWN_ISSUES.md#fast-sync-when-running-besu-on-cloud-providers)
- [Privacy users with private transactions created using v1.3.4 or earlier](KNOWN_ISSUES.md#privacy-users-with-private-transactions-created-using-v134-or-earlier)

### Download link
https://dl.bintray.com/hyperledger-org/besu-repo/besu-20.10.3.zip
sha256: `b5f46d945754dedcbbb1e5dd96bf2bfd13272ff09c6a66c0150b979a578f4389`
