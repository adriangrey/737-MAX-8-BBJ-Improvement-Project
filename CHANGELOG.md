# Changelog

All notable changes to this project will be documented in this file.

## [0.1.0-alpha] - 2026-06-26

### Added

- Initial public alpha release.
- Increased BBJ fuel capacity from approximately **45,694 lb** to approximately **69,499 lb**.
- Implemented using a clean MSFS 2024 modular merge patch.
- Targets only the default Boeing 737 MAX 8 BBJ preset.
- Initial SimBrief airframe profile for long-range BBJ operations.
- Initial project documentation.

### Verified

* Fuel loading through the default EFB.
* SimBrief route and payload import.
* VNAV operation through climb, cruise and step climbs.
* Cruise operation at FL400.
* Native MSFS 2024 passenger boarding and VIP cabin occupancy.
* Successful long-range validation flights in progress.

### Changed

- Updated the BBJ fuel system to more closely match the real-world BBJ MAX 8 auxiliary fuel configuration.

### Known Limitations

* Auxiliary fuel is currently represented by increased center tank capacity.
* Individual BBJ auxiliary tanks are not modeled.
* Aircraft selection screen specifications still require refinement (range and related metadata).
* GSX boarding does not currently populate the native cabin occupancy system.
* Additional real-world performance validation and fuel burn tuning are ongoing.