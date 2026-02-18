# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0] - 2026-02-18

### Added

- Add Gateway API route (e.g. `HTTPRoute`) as an alternative to Ingress.
- Add `io.giantswarm.application.audience` and `io.giantswarm.application.managed` chart annotations for Backstage visibility.

### Changed

- Remove default Ingress configuration (was already disabled by default).
- Update to upstream chart version 2.11.10, containing bridge version v2.9.13.
- Migrate chart metadata annotations to OCI-compatible format.

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

[Unreleased]: https://github.com/giantswarm/onepassword-scim-bridge-app/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/giantswarm/onepassword-scim-bridge-app/compare/v0.0.4...v1.0.0
[0.0.4]: https://github.com/giantswarm/onepassword-scim-bridge-app/compare/v0.0.3...v0.0.4
[0.0.3]: https://github.com/giantswarm/onepassword-scim-bridge-app/compare/v0.0.2...v0.0.3
[0.0.2]: https://github.com/giantswarm/onepassword-scim-bridge-app/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/giantswarm/onepassword-scim-bridge-app/releases/tag/v0.0.1
