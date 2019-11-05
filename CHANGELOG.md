# Changelog

## [0.2.0] - 2019-11-04

### Changed

* Reimplemented in pure safe rust, with a much more accurate parser
* A bunch of minor API tweaks, some backwards-incompatible

## [0.1.2] - 2016-06-04

### Fixed

* Fix returning uninit memory in get_string_formatted/get_string_plaintext
* Handle emoji and zero width unicode characters properly
* Fix cursor positioning with regards to scroll regions and wrapping
* Fix parsing of (ignored) character set escapes
* Explicitly suppress status report escapes

## [0.1.1] - 2016-04-28

### Fixed

* Fix builds

## [0.1.0] - 2016-04-28

### Added

* Initial release