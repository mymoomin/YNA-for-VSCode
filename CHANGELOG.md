# Changelog

All notable changes to the extension will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [2.4.0] - 2018-12-20

### Added

- `{arglen}` and `{talen}` are now keywords (this just changes what shade of blue they are)
- `{embed:` is now highlighted as a function
- Will now outdent after a `}`, as well as after a `;}`

### Fixed

- Now highlights attributes in `{nameof:` and `{user:` e.g. the mention in `{nameof:346555330358149120;mention;}`
- The icon looks better!

## [2.3.1] - 2018-08-01

### Fixed

-Now autoindents after `{loop:`

## [2.3.0] - 2018-08-01

### Added

- Now higlights `{loop:` statements and `{iter}`

## [2.2.0] - 2018-08-01

### Added

- Now only highlights `{some_builtin_function;}` when that's correct syntax (no more accidentally typing `{set;var;stuff;}`)

### Fixed

- Now recognises decimals as numeric

## [2.1.3] - 2018-07-17

### Fixed

- All arithmetic operators are now highlighted, and in all of contexts they're used in

## [2.1.2] - 2018-07-17

### Fixed

- Syntax highlighting now works on lines with 2 consecutive semi-colons

## [2.1.0] - 2018-07-14

### Added

- This changelog!
- Icon for the extension

### Changed

- README now reads better