# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

This changelog is inspired by [keepachangelog.com](http://http://keepachangelog.com/de/)

## [Unreleased](https://github.com/otto-de/gatekeeper/compare/4.0.0...HEAD)

## [4.0.0](https://github.com/otto-de/gatekeeper/compare/3.0.0...4.0.0) - 2017-06-13

### Changed
- Update to python 3.
- Change config file to enable the use of vault secrets (eliza).


## [3.0.0](https://github.com/otto-de/gatekeeper/compare/2.0.0...3.0.0) - 2016-12-08

### Changed
- If pipeline is closed by rules (aka build windows), gatekeeper will answer with 'denied'.

## [2.0.0](https://github.com/otto-de/gatekeeper/compare/1.0.1...2.0.0) - 2016-12-08

### Changed
- Remove legacy support.

## [1.0.2](https://github.com/otto-de/gatekeeper/compare/1.0.1...1.0.2) - 2016-05-09

### Fixed
- Add environment check.
- Pinned python2 as venv version ([thanks@qeqar](https://github.com/qeqar)).

## [1.0.1](https://github.com/otto-de/gatekeeper/compare/1.0.0...1.0.1) - 2016-05-09

### Fixed
- Gates and groups are ordered alphabetical.

## [1.0.0](https://github.com/otto-de/gatekeeper/compare/950359a01244904fa169492e4391e402398f2b17...1.0.0) - 2016-04-28

### Changed
- Refactored ticket handling.
- Groups are not cosmetic anymore but part of the resource url.
- If the gate was manually closed the gatekeeper answers with 'denied'.

### Fixed
- Fixed ghost tickets
