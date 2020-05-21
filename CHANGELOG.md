# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.2.0] - 2020-05-20
### Added
- Uses in memory database in dev mode if database is not configured


## [2.1.0] - 2020-04-30
### Added
- Compatibility with CDI 2.0
- API versions
- SameSite cookie option
- Updating of JWT payload
- Session expired status code configuration
- Partial lmrt support

## [2.0.0] - 2020-04-07
### Added
- Compatibility with NoSQL databases like MongoDB
- Setting sameSite cookie option. However, this is not usable in this release.

## [1.1.1] - 2020-03-23
### Changed
- Adds #!/bin/bash in scripts

## [1.1.0] - 2020-03-23
### Changed
- Allow for an unlimited number of SuperTokens instances in production mode
- License changes to reflect the above