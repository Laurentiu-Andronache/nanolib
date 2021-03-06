# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2] - 2019-03-07
### Added
 - `Block.has_valid_work` and `Block.has_valid_signature` properties are cached to prevent redundant work.

### Changed
 - PyPI package `pynanocurrency` and module `nanocurrency` have both been renamed to `nanolib`.
 - Improved performance when encoding or decoding account IDs.

### Fixed
 - Raise a `decimal.Inexact` exception when trying to convert amounts with higher precision than a single raw.

## 0.1 - 2019-03-01
### Added
- Initial release

[0.2]: https://github.com/Matoking/nanolib/compare/0.2...0.1
[Unreleased]: https://github.com/Matoking/nanolib/compare/0.1...HEAD
