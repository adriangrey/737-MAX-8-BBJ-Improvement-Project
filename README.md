# 737 MAX 8 BBJ Improvement Project

Created by **Adrian Grey**.

A Microsoft Flight Simulator 2024 improvement project for the default Asobo Boeing 737 MAX 8 BBJ preset.

## Current Version

**0.1.1-alpha**

## Current Status

This project has been validated on long-range flights, including KPHX → EGLL, and is considered suitable for normal use. However, it is still an alpha release and additional testing across different routes, weather conditions, and payloads is encouraged.
For visual boarding and visible cabin passengers in the BBJ, use MSFS 2024's native boarding service. GSX boarding currently does not populate the cabin because it does not trigger the native passenger occupancy system. Loading via the EBF Simbrief app also works, though without the fancy animations of GSX or Natvie MSFS boarding.

## What This Version Changes

- Increases the default BBJ preset fuel capacity from approximately **45,694 lb** to approximately **69,499 lb**.
- Correct range now listed on Aircraft Selections specifications card.
- Uses MSFS 2024 modular merge patching.
- Only affects the `b737max8_bbj` preset.
- Does not modify Official files.
- Does not affect the passenger MAX 8 preset.

## Installation

1. Open the `mod` folder.
2. Copy `737max8-bbj-improvement-project` into your MSFS 2024 Community folder.
3. Restart MSFS 2024.
4. Select the default Boeing 737 MAX 8 BBJ preset.
5. Fuel capacity should show **69,499 lb**.

## Removal

Delete `737max8-bbj-improvement-project` from your Community folder and restart MSFS 2024.

## Known Limitations

This first alpha uses a simple enlarged center tank to represent the missing BBJ auxiliary fuel capacity. Future versions may model individual auxiliary tanks, payload stations, and additional BBJ-specific operating characteristics if the default aircraft supports those changes cleanly. 
Native BBJ passenger occupancy: MSFS 2024 supports 12 visible cabin passengers in the BBJ interior. The aircraft weight and balance screen shows 14 total seats, which appears to include pilot and copilot stations. The copilot station is represented in payload but is not visually populated in the cockpit. Several additional VIP cabin seats are modeled but are not currently used by the native passenger occupancy system.

## Project Structure

```text
737max8-bbj-improvement-project/
├── README.md
├── CHANGELOG.md
├── LICENSE.md
├── .gitignore
├── docs/
│   └── roadmap.md
├── mod/
│   └── 737max8-bbj-improvement-project/
│       ├── manifest.json
│       ├── layout.json
│       └── SimObjects/
└── screenshots/
```

## Credits

Created by **Adrian Grey**.

This project is an independent community improvement project and is not affiliated with Microsoft, Asobo Studio, or Boeing. This project modifies configuration files for the default Microsoft Flight Simulator 2024 Boeing 737 MAX 8 BBJ. It does not include or redistribute Microsoft or Asobo assets. Users must own Microsoft Flight Simulator 2024 to use this project.