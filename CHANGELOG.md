# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.3.2] - 2026-02-14

### Fixed

- Removed duplicated `giantswarm.io/cluster` label in crossplane `Rule` resource.

## [1.3.1] - 2026-02-12

### Fixed

- Push chart to the `default` catalog.

## [1.3.0] - 2025-10-06

### Added

- Add permissions `autoscaling:DescribeLifecycleHooks` and `autoscaling:RecordLifecycleActionHeartbeat` because aws-node-termination-handler needs them for the heartbeat sending feature

### Fixed

- Fix rendering of OIDC providers in Helm template

## [1.2.0] - 2025-10-02

### Added

- Add `giantswarm.io/managed-by` tag to AWS Resources.

## [1.1.1] - 2025-04-10

### Changed

- Add support for multiple OIDC providers in the NTH IAM role
- Included the `giantswarm.io/cluster` label

## [1.1.0] - 2024-12-11

### Added

- Send spot instance interruption and instance state change events to SQS queue so that aws-node-termination-handler can react to them

## [1.0.0] - 2024-10-30

- changed: `app.giantswarm.io` label group was changed to `application.giantswarm.io`

[Unreleased]: https://github.com/giantswarm/aws-nth-crossplane-resources/compare/v1.3.2...HEAD
[1.3.2]: https://github.com/giantswarm/aws-nth-crossplane-resources/compare/v1.3.1...v1.3.2
[1.3.1]: https://github.com/giantswarm/aws-nth-crossplane-resources/compare/v1.3.0...v1.3.1
[1.3.0]: https://github.com/giantswarm/aws-nth-crossplane-resources/compare/v1.2.0...v1.3.0
[1.2.0]: https://github.com/giantswarm/aws-nth-crossplane-resources/compare/v1.1.1...v1.2.0
[1.1.1]: https://github.com/giantswarm/aws-nth-crossplane-resources/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/giantswarm/aws-nth-crossplane-resources/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/giantswarm/aws-nth-crossplane-resources/releases/tag/v1.0.0
