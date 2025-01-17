# Change Log
All notable changes to this project will be documented in this file.

## [1.0.9] - 2017-8-23
### Added
- Added to PioIoLink, method and example to use as only digital input, startIoLinkAsDigitalInput

## [1.0.8] - 2017-5-24
### Added
- Added PioAi constants for higher data rates, previously possible but required reading datasheet

## [1.0.7] - 2017-3-29
### Added
- Added PioLink methods for PD In and Out specifically

### Fixed
- Fixed issues with PioIoLink start, stop, start sequences.

## [1.0.6] - 2017-3-22
### Added
- Added advanced PioLink methods for raw reads and IODD file sharing with iOS app
- Added overload method for beginAPMode(char* pass) to allow for passcode for AP network

## [1.0.5] - 2017-2-19
### Fixed
- Fixed PioAi calibration issues, MVS (revA)

## [1.0.4] - 2016-12-17
### Added
- Added ISDU support to PioIoLink library (revA)
- Added PioIoLinkISDU example (revA)
- Added PioDo overload method for writeOutput, thus for one channel or all (revA)

### Fixed
- Fixed PioDo writes to only do write, no longer reads back status (revA)

## [1.0.3] - 2016-11-22
### Fixed
- Fixed PioIoLink IODD directory creation (revA)

## [1.0.2] - 2016-11-3
### Added
- Added PioIoLink library (revA)

## [1.0.1] - 2016-10-17
### Added
- rawRead to PioEnc (revA)

## [0.3.6] - 2016-09-22
### Fixed
- PioCom compiler errors fixed. (revP3)
- PioEnc compiler errors fixed. (revP3)
- PioGpioExp compiler errors fixed. (revP3)
- PioMtr compiler errors fixed. (revP3)
- PioUserLed compiler errors fixed. (revP3)

## [1.0.0] - 2016-09-21
### Added
- Comments to code.
- Folder for docs.

### Fixed
- PioEnc examples compiler errors fixed. (revA)

## [0.4.6] - 2016-09-14
### Fixed
- PioAi moved selfCal from init to initCal.  Also updated cal example to wait for 0 at start. (revA)

## [0.3.5] - 2016-09-13
### Fixed
- Compile error for PioAi lib (revP3)

### Updated
- Arduino Pocket IO™ title update

### Removed
- Removed duplicate example for PioEdLed, was EdLed (revP3)

## [0.4.5] - 2016-09-12
### Fixed
- Typo for PioCom lib (revA)

## [0.3.4] - 2016-09-12
### Changed
- Updated copyright on all libs (revP3)

## [0.3.3] - 2016-09-12
### Added
- Added support for WiFi in access point mode (revP3)
- Added examples for TCP servers in managed and ap modes (revP3)

### Removed
- Removed WiFi examples that may not have been compatible with Pocket IO™ (revP3)

## [0.3.2] - 2016-09-12
### Changed
- Updates for all libs to speed up spi transactions (revP3)

## [0.4.4] - 2016-09-12
### Changed
- Updated copyright on all libs (revA)

## [0.4.3] - 2016-09-12
### Added
- Added support for WiFi in access point mode
- Added examples for TCP servers in managed and ap modes

### Removed
- Removed WiFi examples that may not have been compatible with Pocket IO™

## [0.4.2] - 2016-09-06
### Changed
- Updates for all libs to speed up spi transactions (revA)

## [0.4.1] - 2016-09-06
### Fixed
- Updates for WiFi libs for connnect/disconnect issues (revA)

## [0.3.1] - 2016-09-06
### Fixed
- Updates for WiFi libs for connnect/disconnect issues (revP3)

## [0.4.0] - 2016-08-24
### Added
- Initial Arduino SW release for Pocket IO™ revA boards

## [0.3.0] - 2016-08-24
### Added
- Initial Arduino SW release for Pocket IO™ revP3 boards
