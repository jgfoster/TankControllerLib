# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added

### Changed

### Deprecated

### Removed

### Fixed

### Security


## [0.1.0] - 2018-01-24
### Added
- Unit testing support
- Documentation for all Ruby methods
- `ArduinoInstallation` class for managing lib / executable paths
- `DisplayManager` class for managing Xvfb instance if needed
- `ArduinoCmd` captures and caches preferences
- `ArduinoCmd` reports on whether a board is installed
- `ArduinoCmd` sets preferences
- `ArduinoCmd` installs boards
- `ArduinoCmd` installs libraries
- `ArduinoCmd` selects boards (compiler preference)
- `ArduinoCmd` verifies sketches
- `CppLibrary` manages GCC for unittests
- `CIConfig` manages overridable config for all testing

### Changed
- `DisplayManger.with_display` doesn't `disable` if the display was enabled prior to starting the block

### Fixed
- Built gems are `.gitignore`d
- Updated gems based on Github's security advisories


## [0.0.1] - 2018-01-10
### Added
- Skeleton for gem with working unit tests


[Unreleased]: https://github.com/ifreecarve/arduino_ci/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/ifreecarve/arduino_ci/compare/v0.0.1...v0.1.0
[0.0.1]: https://github.com/ifreecarve/arduino_ci/compare/v0.0.0...v0.0.1