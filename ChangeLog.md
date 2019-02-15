# Changelog
All notable changes to stumpless will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased
 - Compile-time log level filtering.
 - Format-string style logging from `stumpless` call.
 - Thread-safe operation.
 - Examples for file and socket targets.

## [1.3.1] - 2019-02-15
### Fixed
 - Code duplication in network target code.

## [1.3.0] - 2019-02-14
### Added
 - Install target and documentation.
 - Memory leak controlled with stumpless_free_all function.
 - Vision statement.
 - STUMPLESS_OPTION_NONE for code readability.
 - stumpless_perror function.
 - Network target capability.

### Fixed
 - Various memory leaks.

## [1.2.0] - 2018-11-09
### Added
 - Increased coverage on object cache.
 - Support for fractional timestamps.
 - File target capability.
 - Windows Event Log target capability.
 - Doxygen documentation support.
 - Tests for unsupported targets.
 - Stream target capability.

### Fixed
 - Use of unsafe fopen when fopen_s is available.
 - Use of unsafe gmtime function when gmtime_r is available.
 - Safely convert from size_t to int types.
 - Inclusion of RFC 5424 test sources in multiple executables, using an object
   library instead.

## [1.1.2] - 2018-10-04
### Fixed
 - Specify googletest release 1.8.1 to fix broken builds.

## [1.1.1] - 2018-08-28
### Added
 - Add SonarCloud quality gate badge to README.

## [1.1.0] - 2018-08-27
### Added
 - Benchmark tests measure the amount of memory allocated.
 - Add `stumpless_set_entry_message` function.
 - Integration with SonarCloud for analysis.

### Fixed
 - Removed versions prior to 1.0.0 to match repository history.
 - Benchmark tests now function properly.
 - Memory efficiency improved significantly.

## [1.0.0] - 2018-07-28
### Added
 - Add socket target capability.
 - Add buffer target capability.
 - Add Travis CI integration.
 - Add AppVeyor integration.
 - Add Google Test suites.
 - Add Google Benchmark capability.