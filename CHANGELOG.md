# Changelog DeviceReachabilityStatus
## Table of Contents
- [r1.1](#r11)

**Please be aware that the project will have frequent updates to the main branch. There are no compatibility guarantees associated with code in any branch, including main, until it has been released. For example, changes may be reverted before a release is published. For the best results, use the latest published release.**

The below sections record the changes for each API version in each release as follows:

  - for an alpha release, the delta with respect to the previous release
  - for the first release-candidate, all changes since the last public release
  - for subsequent release-candidate(s), only the delta to the previous release-candidate
  - for a public release, the consolidated changes since the previous public release

Note: this API had former releases in the [DeviceStatus](https://github.com/camaraproject/DeviceStatus) repository
# r1.1
## Release Notes

This pre-release contains the definition and documentation of
* device-reachability-status v1.1.0-rc.2
* device-reachability-status-subscriptions v0.8.0-rc.1

The API definition(s) are based on
* Commonalities v0.6.0-rc.1 (r3.2)
* Identity and Consent Management v0.4.0-rc.1 (r3.2)

## device-reachability-status v1.1.0-rc.2

**device-reachability-status v1.1.0-rc.2 is the first release candidate of the version 1.1.0**

device-reachability-status v1.1.0 will be a minor update of the API, and is backward compatible with v1.0.0.

- API definition **with inline documentation**:
  - [View it on ReDoc](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/DeviceReachabilityStatus/r1.1/code/API_definitions/device-reachability-status.yaml&nocors)
  - [View it on Swagger Editor](https://camaraproject.github.io/swagger-ui/?url=https://raw.githubusercontent.com/camaraproject/DeviceReachabilityStatus/r1.1/code/API_definitions/device-reachability-status.yaml)
  - OpenAPI [YAML spec file](https://github.com/camaraproject/DeviceReachabilityStatus/blob/r1.1/code/API_definitions/device-reachability-status.yaml)

### Added

### Changed
* Make lastStatusTime mandatory in 200 responses of the API by @eric-murray in https://github.com/camaraproject/DeviceReachabilityStatus/pull/18
* Update x-correlator schema by @eric-murray in https://github.com/camaraproject/DeviceReachabilityStatus/pull/28
* Update error response documentation in OAS definitions by @eric-murray in https://github.com/camaraproject/DeviceReachabilityStatus/pull/29
* Commonalities alignement for device reachability status by @bigludo7 in https://github.com/camaraproject/DeviceReachabilityStatus/pull/36

### Fixed

### Removed
* Remove AUTHENTICATION_REQUIRED error code by @eric-murray in https://github.com/camaraproject/DeviceReachabilityStatus/pull/13
* Update OAS and test definitions to remove IDENTIFIER_MISMATCH error code by @eric-murray in https://github.com/camaraproject/DeviceReachabilityStatus/pull/25

## device-reachability-status-subscriptions v0.8.0-rc.1

- API definition **with inline documentation**:
  - [View it on ReDoc](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/DeviceReachabilityStatus/r1.1/code/API_definitions/device-reachability-status-subscriptions.yaml&nocors)
  - [View it on Swagger Editor](https://camaraproject.github.io/swagger-ui/?url=https://raw.githubusercontent.com/camaraproject/DeviceReachabilityStatus/r1.1/code/API_definitions/device-reachability-status-subscriptions.yaml)
  - OpenAPI [YAML spec file](https://github.com/camaraproject/DeviceReachabilityStatus/blob/r1.1/code/API_definitions/device-reachability-status-subscriptions.yaml)

### Added
* Add subscription started & updated event by @bigludo7 in https://github.com/camaraproject/DeviceReachabilityStatus/pull/34

### Changed
* change sink format to format: uri by @maxl2287 in https://github.com/camaraproject/DeviceReachabilityStatus/pull/17
* Update x-correlator schema by @eric-murray in https://github.com/camaraproject/DeviceReachabilityStatus/pull/28
* Rename subscription-ends event to subscription-ended by @eric-murray in https://github.com/camaraproject/DeviceReachabilityStatus/pull/30
* Update error response documentation in OAS definitions by @eric-murray in https://github.com/camaraproject/DeviceReachabilityStatus/pull/29
* Commonalities alignement for device reachability subscription by @bigludo7 in https://github.com/camaraproject/DeviceReachabilityStatus/pull/36

### Fixed
* fix: remove "Generic High Entropy Secret" by @maxl2287 in https://github.com/camaraproject/DeviceReachabilityStatus/pull/16

### Removed
* Remove AUTHENTICATION_REQUIRED error code by @eric-murray in https://github.com/camaraproject/DeviceReachabilityStatus/pull/13
* Update OAS and test definitions to remove IDENTIFIER_MISMATCH error code by @eric-murray in https://github.com/camaraproject/DeviceReachabilityStatus/pull/25

**Full Changelog**: https://github.com/camaraproject/DeviceReachabilityStatus/commits/r1.1

