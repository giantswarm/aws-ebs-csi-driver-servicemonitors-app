# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project's packages adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixed

- Remove duplicate `application.giantswarm.io/team` label in PodMonitor that caused install failure. The label is already included via the common labels helper.

## [0.1.1] - 2026-02-19

### Changed

- Migrate to App Build Suite (ABS).

## [0.1.0] - 2024-04-02

### Added

- First release.


[Unreleased]: https://github.com/giantswarm/aws-ebs-csi-driver-servicemonitors-app/compare/v0.1.1...HEAD
[0.1.1]: https://github.com/giantswarm/aws-ebs-csi-driver-servicemonitors-app/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/giantswarm/aws-ebs-csi-driver-servicemonitors-app/compare/v0.0.0...v0.1.0
