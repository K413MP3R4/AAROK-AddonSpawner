# AAROK Add-On Vehicle Spawner

AAROK Add-On Vehicle Spawner is a custom build of the GTA V Add-On Vehicle Spawner by ikt. It adds a purple AAROK visual identity, a custom preview image, safer test defaults, and a built-in **automatic paint menu** that opens immediately after spawning any vehicle.

![AAROK preview](preview.png)

## Features

- Purple AAROK menu theme.
- Internal menu title patched to `AAROK`.
- Custom default preview image using the AAROK logo mark.
- Top-left menu positioning.
- Safer test defaults:
  - official DLC listing disabled by default,
  - persistent vehicles disabled by default,
  - spawn-in-place disabled by default.
- **Auto paint menu** — opens automatically after every spawn:
  - Liveries list (shows all available camos/skins with active indicator).
  - Primary color picker (23 named colors).
  - Secondary color picker (23 named colors).

## Download

Use the release ZIP:

[AAROK-AddonSpawner-v1.7.0-paint-menu.zip](release/AAROK-AddonSpawner-v1.7.0-paint-menu.zip)

## Installation

1. Download the release ZIP.
2. Extract it.
3. Copy `AddonSpawner.asi` into your main GTA V folder.
4. Copy the `AddonSpawner` folder into your main GTA V folder.
5. Replace existing files if Windows asks.
6. Launch GTA V in story mode and press `F5`.

## Vehicle Test Groups

To group vehicles for testing:

1. Open `AddonSpawner/UserDLC`.
2. Create a `.list` file, for example `AAROK Tests.list`.
3. Add one vehicle spawn name per line.

Example:

```txt
nisgtr32
ae86
```

The group will appear in the spawner under user add-on groupings.

## Important Notes

- Use this only in GTA V story mode.
- Do not use modded files in GTA Online.
- This package is branded as `1.7.0` for the AAROK paint-menu build.
- The core ASI is based on Add-On Vehicle Spawner `1.6.2` with custom source modifications.
- Built with Visual Studio Build Tools 2022 (v143 toolset).
- Add-On Vehicle Spawner / GTAVAddonLoader is licensed under MPL 2.0. Keep the original credits and source link when redistributing.

## Credits

- Original Add-On Vehicle Spawner: ikt.
- AAROK theme, configuration, and preview asset: AAROK.
