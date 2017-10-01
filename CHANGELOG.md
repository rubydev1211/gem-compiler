# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

Please take notes of *Changed*, *Removed* and *Deprecated* items prior
upgrading.

## [Unreleased]

### Changed
- Introduce `Makefile` for local development

## [0.6.0] - 2017-06-25

### Fixed
- Solve RubyGems 2.5 deprecation warnings

### Removed
- Drop support for any Ruby version prior to 2.1.0

### Changed
- Use Travis to automate new releases
- CI: Update test matrix (Travis and AppVeyor)

## [0.5.0] - 2016-04-24

### Fixed
- Workaround shortname directories on Windows. Thanks to @mbland (#17 & #19)
- Validate both Ruby and RubyGems versions defined in gemspec
- Ensure any RubyGems' `pre_install` hooks are run at extension compilation (#18)

### Changed
- Lock compile gems to Ruby's ABI version which can be disabled using
  `--no-abi-lock` option (#11)

### Removed
- Drop support for any Ruby version prior to 2.0.0

## [0.4.0] - 2015-07-18

### Added
- Introduce `--prune` option to cleanup gemspecs. Thanks to @androbtech [#13]

### Changed
- Test builds on both Travis (Linux) and AppVeyor (Windows) environments.

## [0.3.0] - 2014-04-19

### Added
- Support RubyGems 2.2.x thanks to @drbrain

### Changed
- Minor reorganization to make testing on Travis more easy

## [0.2.0] - 2013-04-28

### Added
- Support RubyGems 2.0.0 thanks to @mgoggin [#6]

## [0.1.1] - 2012-05-07

### Fixed
- Loose requirements to allow installation on Ruby 1.8.7 or greater. You
  still need RubyGems 1.8.24

## [0.1.0] - 2012-05-06

- Initial public release, extracted from internal project.

[Unreleased]: https://github.com/luislavena/gem-compiler/compare/v0.6.0...HEAD
[0.6.0]: https://github.com/luislavena/gem-compiler/compare/v0.5.0...v0.6.0
[0.5.0]: https://github.com/luislavena/gem-compiler/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/luislavena/gem-compiler/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/luislavena/gem-compiler/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/luislavena/gem-compiler/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/luislavena/gem-compiler/compare/v0.1.0...v0.1.1
