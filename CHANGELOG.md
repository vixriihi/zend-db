# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.

## 2.5.2 - TBD

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [#17](https://github.com/zendframework/zend-db/pull/17) removes an executable
  bit on a regular file.
- [#3](https://github.com/zendframework/zend-db/pull/3) updates the code to use
  closure binding (now that we're on 5.5+, this is possible).
- [#9](https://github.com/zendframework/zend-db/pull/9) thoroughly audits the
  OCI8 (Oracle) driver, ensuring it provides feature parity with other drivers,
  and fixes issues with subselects, limits, and offsets.
