# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased][unreleased]
### Changed
- Nothing yet.

## [0.0.3] - 2015-05-22
### Changed
- Transformer output now uses the new `:local(.identifier)` syntax.

### Added
- Simple global leak detection. Non-local selectors like `input{}` and `[data-foobar]` now throw when not marked as global.

## [0.0.2] - 2015-05-14
### Added
- Support for global selectors appended directly to locals, e.g. `.foo:global(.bar)`

## 0.0.1 - 2015-05-12
### Added
- Automatic local classes
- Explicit global selectors with `:global`

[unreleased]: https://github.com/markdalgleish/postcss-local-scope/compare/v0.0.3...HEAD
[0.0.2]:      https://github.com/markdalgleish/postcss-local-scope/compare/v0.0.1...v0.0.2
[0.0.2]:      https://github.com/markdalgleish/postcss-local-scope/compare/v0.0.2...v0.0.3