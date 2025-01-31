# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.4] - 2025-01-31

### Added

- Allow egress from the SCIM bridge to the public internet.

## [0.0.3] - 2025-01-28

### Added

- Add affinity to separate the bridge pod from redis.

### Changed

- Deliver credentials via secret instead of volume.
- Change OCI registry to `gsoci.azurecr.io` instead of `quay.io`.

## [0.0.2] - 2025-01-28

### Added

- Add CiliumNetworkPolicy allowing ingress to acme solvers during TLS setup.

## [0.0.1] - 2025-01-28

### Added

- Initial release of v2.9.9 of the OnePassword SCIM bridge.

[Unreleased]: https://github.com/giantswarm/onepassword-scim-bridge-app/compare/v0.0.4...HEAD
[0.0.4]: https://github.com/giantswarm/onepassword-scim-bridge-app/compare/v0.0.3...v0.0.4
[0.0.3]: https://github.com/giantswarm/onepassword-scim-bridge-app/compare/v0.0.2...v0.0.3
[0.0.2]: https://github.com/giantswarm/onepassword-scim-bridge-app/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/giantswarm/onepassword-scim-bridge-app/releases/tag/v0.0.1
