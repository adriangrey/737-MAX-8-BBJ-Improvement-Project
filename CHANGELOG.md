# Changelog

All notable changes to this project will be documented in this file.

## [0.2.0-alpha] - 2026-07-09

### Added/Changed

- Added autopilot tuning for smoother pitch response, roll tracking, and throttle changes.
- Refined pitch PID, roll PID, bank limits, pitch velocity, pitch acceleration, and autothrottle rate values for the BBJ preset.

### Known Limitations

* Auxiliary fuel is currently represented by increased center tank capacity.
* Individual BBJ auxiliary tanks are not modeled.
* GSX boarding does not currently populate the native cabin occupancy system.
* Additional real-world performance validation and fuel burn tuning are ongoing.

## [0.1.3-alpha] - 2026-07-02

### Added/Changed

- Initial public alpha release.
- Increased BBJ fuel capacity from **45,694 lb** to **69,499 lb**.
- Implemented using a clean MSFS 2024 modular merge patch.
- Targets only the default Boeing 737 MAX 8 BBJ preset.
- Initial SimBrief airframe profile for long-range BBJ operations.
- Initial project documentation.
- Correct range now listed on Aircraft Selections specifications card.
- Disabled forced native passenger boarding for the BBJ preset.
- Restored instant payload loading through the default EFB Weight & Balance page.
- Simbrief weight import now always works, and loading is instant.
- Bug fix: Fixed a typo in aircraft.cfg and flight_model.cfg that lowered the available seats by 2.

### Known Limitations

* Auxiliary fuel is currently represented by increased center tank capacity.
* Individual BBJ auxiliary tanks are not modeled.
* ~~Aircraft selection screen specifications still require refinement (range and related metadata).~~
* GSX boarding does not currently populate the native cabin occupancy system.
* ~~Unable to instantly load pax from EFB W/B screen.~~
* Additional real-world performance validation and fuel burn tuning are ongoing.
