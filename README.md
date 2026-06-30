# 737 MAX 8 BBJ Improvement Project

Created by **Adrian Grey**.

A Microsoft Flight Simulator 2024 improvement project for the default Asobo Boeing 737 MAX 8 BBJ preset.

## Current Version

**v0.1.2**

## Current Status

This project has been validated on long-range flights, including KPHX → EGLL, and is considered suitable for normal use. However, it is still an alpha release and additional testing across different routes, weather conditions, and payloads is encouraged.
For visual boarding and visible cabin passengers in the BBJ, use MSFS 2024's native boarding service. GSX boarding currently does not populate the cabin because it does not trigger the native passenger occupancy system. Loading via the EBF Simbrief app also works, though without the fancy animations of GSX or Natvie MSFS boarding.

## What This Version Changes

- Increases the default BBJ preset fuel capacity from **45,694 lb** to **69,499 lb**.
- Correct range now listed on Aircraft Selections specifications card.
- Disables MSFS 2024 Native Boarding System, instant loading from EFB Weight/Balance screen and SimBrief now possible/Always works.
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

## Current Roadmap

Alpha v0.1.x

~~Fuel capacity~~
~~SimBrief compatibility~~
~~Range specs card corrected to 6550nm~~
~~UI polish (manufacturer/model localization)~~
~~MSFS Native Boarding System Diabled~~

Alpha v0.2.x

Use empty seats in cabin for more pax
Visible Co-Pilot
Autopilot tuning
GSX improvements
Flight model refinement

Release v1.0

## Credits

Created by **Adrian Grey**.

This project is an independent community improvement project and is not affiliated with Microsoft, Asobo Studio, or Boeing. This project modifies configuration files for the default Microsoft Flight Simulator 2024 Boeing 737 MAX 8 BBJ. It does not include or redistribute Microsoft or Asobo assets. Users must own Microsoft Flight Simulator 2024 to use this project.