# Change Log
All notable changes to this project will be documented in this file
This project adheres to [Semantic Versioning](http://semver.org/)

## [0.2.1] - 2016-08-12
### Changed
 - Major improvements in the README

### Added
 - Add the `limit` method to cursor
 - Add the `skip` method to cursor
 - Add the `size` method to cursor

## [0.2.0] - 2016-08-12
### Added
 - Add the possibility to delete AppNexus entities
 
### Fixed
 - Fixed missing import in setup.py
 - Even strangely named envelope are now handled automatically through the
   models

## [0.1.3] - 2016-08-12
### Removed
 - Remove the envelope creation in services, since at least `custom-model`
   behave differently than other services and it breaks it

## [0.1.2] - 2016-08-11
### Added
 - Allow to change `representation`, `debug` and `test` settings with `connect`
   method
 - Automaticaly create the envelope in services

### Fixed
 - Fixed an IndexError occuring when getting first element of an empty cursor


[Unreleased]: https://github.com/numberly/appnexus-client/compare/0.2.1...HEAD
[0.2.1]: https://github.com/numberly/appnexus-client/compare/0.2.0...0.2.1
[0.2.0]: https://github.com/numberly/appnexus-client/compare/0.1.3...0.2.0
[0.1.3]: https://github.com/numberly/appnexus-client/compare/0.1.2...0.1.3
[0.1.2]: https://github.com/numberly/appnexus-client/compare/04af0c9a447c235bb8ba2512f710ac905c5d0c48...0.1.2
