# McServ

## [Unreleased]
### Added

### Changed

### Deprecated

### Removed

### Fixed

### Security

## [0.1.3] - 2022-04-29
### Changed
- Bump dependencies

### Fixes
- Bump wingetcreate to fix checksum calculation

## [0.1.1] - 2022-01-09
### Fixed
- Fixed Windows script generator

## [0.1.0] - 2022-01-09
### Changed
- Imrpoved JRE finding logic

### Fixed
- Fix mcserv installed JREs having wrongly detected home path (Fix #31)
- Fix new Eclipse Adoptium JREs not being detected

## [0.0.6] - 2021-12-29
### Fixed
- Fix installer not asking for eula
- Fix choco CI
- Fix docs CI

## [0.0.5] - 2021-12-29
### Fixed
- Fix docs CI failing
- Fix script generators not appending /bin/java

## [0.0.4] - 2021-12-10
### Changed
- Update dependencies
- Make Velocity use the PaperMC API

## [0.0.3] - 2021-09-08
### Fixed
- Fix Bug causing process to not terminate correctly when downloading items
- Fix JDK installer

## [0.0.2] - 2021-09-05
### Added
- non-interactive CLI flags for all interactive components
- `--ascii` mode (Use `--no-ascii` on Windows to restore old mode)
- Loading spinners for expensive tasks (e.g. Unpacking a JDK)
- Human-readable filesize in Download progress instead of byte count

### Changed
- Use interact for progress bars

### Fixed
- Cursor invisible after exiting with Ctrl+C [#12](https://github.com/DRSchlaubi/mcserv/issues/12)
- Long process exit times due to left-open resources
- 64-bit program installed to `Program Files (x86)` on Windows

## [0.0.1]
### Added
- Initial version.