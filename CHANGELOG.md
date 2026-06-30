# Changelog

All notable changes to this project will be documented in this file.

## [0.1.1-alpha] - 2026-06-28

### Added/Changed

- Initial public alpha release.
- Increased BBJ fuel capacity from **45,694 lb** to **69,499 lb**.
- Implemented using a clean MSFS 2024 modular merge patch.
- Targets only the default Boeing 737 MAX 8 BBJ preset.
- Initial SimBrief airframe profile for long-range BBJ operations.
- Initial project documentation.
- Correct range now listed on Aircraft Selections specifications card.

### Known Limitations

* Auxiliary fuel is currently represented by increased center tank capacity.
* Individual BBJ auxiliary tanks are not modeled.
* ~~Aircraft selection screen specifications still require refinement (range and related metadata).~~
* GSX boarding does not currently populate the native cabin occupancy system.
* Additional real-world performance validation and fuel burn tuning are ongoing.
* Native BBJ passenger occupancy: MSFS 2024 supports 12 visible cabin passengers in the BBJ interior. The aircraft weight and balance screen shows 14 total seats, which appears to include pilot and copilot stations. The copilot station is represented in payload but is not visually populated in the cockpit. Several additional VIP cabin seats are modeled but are not currently used by the native passenger occupancy system.