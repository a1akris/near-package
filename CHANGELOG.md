# Changelog

## [0.3.0](https://github.com/kurtosis-tech/near-package/compare/0.2.0...0.3.0) (2022-12-22)


### ⚠ BREAKING CHANGES

* Uses the `plan` object. Users will have to update their Kurtosis CLI >= 0.63.0 and do a restart.

### Bug Fixes

* Use the `plan` object ([#27](https://github.com/kurtosis-tech/near-package/issues/27)) ([40eb864](https://github.com/kurtosis-tech/near-package/commit/40eb864a0c44bbbcd3d3e48ab43c41e3cfd49c1b))

## 0.2.0

### Breaking Change
- Introduced optional application protocol and renamed protocol to transport_protocol

## 0.1.0

### Breaking Change
- Updated struct to PortSpec to define ports

### Features
- Use `wait` command to wait for availability of PG

### Changes
- Change `exec` syntax

## 0.0.1

### Fixes
- Did some intial work to cleanup
- Made the readme better
- Fix pre-release-script

### Features
- Added static files
- Added package_io
- Added contract_helper_postgresql
- Added contract_helper_dynamodb
- Added indexer
- Added wallet, frontend explorer, backend explorer
- Added historical notes
- Added launch-local-near-cluster.sh script

## 0.0.0
- Initial commit
