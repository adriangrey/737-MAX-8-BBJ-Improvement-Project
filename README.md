# 737 MAX 8 BBJ Improvement Project

Created by **Adrian Grey**.

A Microsoft Flight Simulator 2024 improvement project for the default Asobo Boeing 737 MAX 8 BBJ preset.

## Current Version

**0.1.0-alpha**

## What This Version Changes

- Increases the default BBJ preset fuel capacity from approximately **45,694 lb** to approximately **69,499 lb**.
- Uses MSFS 2024 modular merge patching.
- Only affects the `b737max8_bbj` preset.
- Does not modify Official files.
- Does not affect the passenger MAX 8 preset.

## Installation

1. Open the `mod` folder.
2. Copy `737max8-bbj-improvement-project` into your MSFS 2024 Community folder.
3. Restart MSFS 2024.
4. Select the default Boeing 737 MAX 8 BBJ preset.
5. Fuel capacity should show approximately **69,499 lb**.

## Removal

Delete `737max8-bbj-improvement-project` from your Community folder and restart MSFS 2024.

## Known Limitations

This first alpha uses a simple enlarged center tank to represent the missing BBJ auxiliary fuel capacity. Future versions may model individual auxiliary tanks, payload stations, and additional BBJ-specific operating characteristics if the default aircraft supports those changes cleanly.

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

This project is an independent community improvement project and is not affiliated with Microsoft, Asobo Studio, or Boeing.
