# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

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

[Unreleased]: https://github.com/giantswarm/aws-nth-crossplane-resources/compare/v1.1.1...HEAD
[1.1.1]: https://github.com/giantswarm/aws-nth-crossplane-resources/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/giantswarm/aws-nth-crossplane-resources/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/giantswarm/aws-nth-crossplane-resources/releases/tag/v1.0.0
