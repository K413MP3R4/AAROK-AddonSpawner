# Release Notes

## AAROK 1.7.0 — Paint Menu Build

This release adds a compiled source modification: an automatic paint menu that opens immediately after every vehicle spawn.

### Added

- **Auto paint menu** — appears right after spawning any vehicle:
  - Liveries submenu — lists all available liveries with `[Active]` indicator.
  - Primary color picker — 23 named paint colors.
  - Secondary color picker — 23 named paint colors.
- Source compiled from GTAVAddonLoader with custom `NavigateTo()` API added to NativeMenu.

### Carried Over from 1.6.5

- AAROK purple menu styling.
- AAROK title branding in the menu.
- Custom `noimage.png` preview using the AAROK logo mark.
- Menu position moved toward the top-left corner.
- Safer defaults:
  - `ListAllDLCs = false`
  - `Persistent = false`
  - `SpawnInplace = false`

### Known Limits

- Based on Add-On Vehicle Spawner 1.6.2 source.
- Built with VS Build Tools 2022 — not tested against all GTA V versions.
