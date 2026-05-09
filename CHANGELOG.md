# Changelog

All notable changes to this project will be documented in this file.

## [1.3.0] - 2026-05-09

### Changed
- Port to webOS SDK v10 (Node.js 20.x)
- Upgrade @webos-tools/cli from 2.4.0 to 3.2.3
- Upgrade webOSTV.js from 1.2.11 to 1.2.13
- Bump Node.js in CI from 14.x to 20.x

### Fixed
- Timeout increased from 5s to 30s for server connections
- Open Jellyfin URL in system browser to bypass X-Frame-Options
- Deprecated `new Buffer()` replaced with `Buffer.from()`

### Removed
- Deprecated Eclipse project file (.project)
- Debug panel (DEBUG = false)