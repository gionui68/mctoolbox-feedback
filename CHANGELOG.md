# Changelog

Notable public releases, tool additions, and data fixes for [MC Toolbox](https://mctoolbox.net).

## 2026-11

### Added
- **Biome Spawns (`/minecraft-biome-spawns`):** New browser tool covering mob spawn pools across 17 Java Edition versions, including spawn conditions, hitboxes, and farm filters.
- **Pack Converter (`.mrpack` & `.mcpack`):** Added `.mrpack` mod list inspection with CSV export and direct `MCPACK` to `ZIP` workflow support.
- **Music Disc Maker:** Added Bedrock pack name color and formatting code support.

### Fixed & Improved
- **3D Schematic Renderer:** Fixed bare texture variable resolution for `minecraft:block/heavy_core` (`Missing texture: minecraft:all`) and aligned water tint rendering with vanilla appearance.
- **Papercraft Generators:** Separated standalone character and block papercraft generators cleanly for printing and indexing.
- **Performance:** Improved caching headers for static Minecraft textures and site assets.

## 2026-10

### Improved
- Updated core Java and Bedrock tool datasets, command generators, and `server.properties` defaults for newer 26.x releases.
- Expanded interactive schematic categories, material lists, and 3D preview performance for large builds.
