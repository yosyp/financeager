# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## Unreleased
### Added
- Travis CI testing using Python version 3.6 and 3.7.
### Changed
- Send any HTTP request data in JSON format.
### Deprecated
### Removed
- `test.suites` module and `test.test_*.suite` functions in order to simplify test framework. Testing now invokes `unittest` discovery in an expected way.

### Fixed

## [v0.21] - 2019-08-19
### Added
- Changelog file and related tooling.
