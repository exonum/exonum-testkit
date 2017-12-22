# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Added `rollback()` method for `TestKit` allowing to rollback blocks added to
  the testkit blockchain. (#8)

### Changed

- Reimplemented `probe()` / `probe_all()` methods of the testkit with
  a revertible database. (#8)

### Fixed

- Added missing documentation for `ApiKind` and improved documentation quality. (#15)

## 0.1.1 - 2017-12-14

### Added

- Added the usage manual. (#9)

### Fixed

- Fixed incorrect behavior of `TestKit::create_block_with_transactions()`,
  in which it would execute incorrect transactions. (#11)

## 0.1 - 2017-12-08

The first release of Exonum testkit.
