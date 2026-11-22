# Changelog

Public release history of tools, features, and Minecraft version updates on [MC Toolbox](https://mctoolbox.net).

---

## 2026-11

### New Tools
- **Minecraft Biome Spawns (`/minecraft-biome-spawns`)** *(2026-11-21)*: Mob spawn pool reference across 17 Java Edition versions with spawn conditions, hitboxes, combined weights, and farm filters.

### Improvements & Fixes
- **Pack Converter & Pack Doctor** *(2026-11-20)*: Added `.mrpack` mod list inspection with CSV export and direct `MCPACK` to `ZIP` workflow support.
- **Music Disc Maker** *(2026-11-21)*: Added Bedrock pack name color and formatting code support.
- **3D Schematic Renderer** *(2026-11-21)*: Fixed bare texture variable resolution for `minecraft:block/heavy_core` (`Missing texture: minecraft:all`) and aligned schematic water tint with vanilla appearance.
- **Papercraft Generators** *(2026-11-22)*: Separated standalone character and block papercraft generators cleanly.
- **Bedrock Seed Map** *(2026-11-08)*: Added verified Bedrock `26.63` profiles and simplified version labels.
- **Performance** *(2026-11-21)*: Extended caching headers for Minecraft textures and static assets.

---

## 2026-10

### New Tools
- **MIDI to Note Blocks Converter (`/midi-to-note-blocks`)** *(2026-10-31)*: Convert MIDI files into playable Minecraft note block builds with step-by-step playback, multi-part lanes, compact folded layouts, and `.schem` / `.litematic` / `.mcfunction` export verified on Java `1.21.11` and `26.3`.
- **Clone Command Generator (`/clone`)** *(2026-10-20)*: Visual `/clone` builder with textured region preview and common error checks.
- **Note Block Tuner (`/note-block-tuner`)** *(2026-10-20)*: Interactive 25-note keyboard with real instrument sounds and block mappings.
- **Villager Discount Calculator (`/villager-discount-calculator`)** *(2026-10-20)*: Calculates zombie cure, reputation, Hero of the Village, and demand pricing.
- **Superflat Preset Generator (`/superflat-preset-generator`)** *(2026-10-20)*: Textured layer editor with version-aware preset output.
- **Command & Text Builders** *(2026-10-12 – 2026-10-13)*: Launched `/kill`, `/attribute`, and `/ride` command generators, **Java to Bedrock Command Converter**, **Minecraft Font Generator**, and **Block Letter Generator**.
- **Block & Version References** *(2026-10-11 – 2026-10-12)*: Launched **Block Gradient Generator**, **Block Properties Table** (Java `26.3`), and **Minecraft Java Version List** (data versions & pack formats).

### Improvements & Fixes
- **Beacon Calculator** *(2026-10-31)*: Added beam color finder using Java integer averaging, OKLab search, glass stack preview, and 16-color reference.
- **UUID Lookup** *(2026-10-31)*: Added Minecraft username availability checker (single and batch up to 10 names).
- **Armor Trim Viewer** *(2026-10-31)*: Added Java leather dye recipe finder (exact mixing rules up to 3 steps).
- **Seed Finder & Bedrock Seed Map** *(2026-10-21 – 2026-10-30)*: Added Trial Chambers (`1.21+`) with `/tp` copy; improved Bedrock End biome tiles, End Cities validation, and Trail Ruins / Fortress chunk anchoring (`BDS 1.26.52`).
- **Server Start Script** *(2026-10-28)*: Added Flags presets (None, Aikar's, Velocity proxy) and memory slider with RAM hints.
- **Schematics & Pixel Art** *(2026-10-11 – 2026-10-28)*: Added large-build schematic support, voxel night lighting, printable PDF chart & 1:1 PNG export for Pixel Art, and survival material breakdowns.

---

## 2026-09

### New Tools
- **Pixel Art Editor & Library (`/pixel-art-editor`)** *(2026-09-20)*: Interactive block-based pixel art editor with direct image import, fullscreen workspace, transparent PNG / blueprint grid export, and material lists.
- **Community Banner Library (`/community-banners`)** *(2026-09-15)*: Shareable banner gallery with command import and previews.
- **Gameplay Calculators** *(2026-09-12 – 2026-09-13)*: Launched **Explosion Calculator**, **Crop Growth Calculator**, **Java Fishing Calculator**, and **Loot Odds Calculator** (barter, fishing, and mob tables).
- **Locator Bar Color Tool (`/locator-bar-color`)** *(2026-09-09)*: Added public locator bar color utility.

### Improvements & Fixes
- **Seed Map** *(2026-09-21)*: Added Bedrock `26.51` support.
- **Papercraft** *(2026-09-22)*: Refined printable character and block cube nets and print controls.
- **Custom Totem** *(2026-09-09 – 2026-09-21)*: Expanded totem styles, exports, and preview controls.
- **Earth Map** *(2026-09-21)*: Added resilient keyless fallback map tiles.

---

## 2026-08

### New Tools
- **GUI Colorizer (`/gui-colorizer`)** *(2026-08-31)*: Native Java ZIP and Bedrock `textures/ui` pack exporter.
- **Mob Spawn Planner (`/mob-spawn-planner`)** *(2026-08-29)*: Spawn and despawn sphere calculator.
- **Resource Pack Studio (`/resource-pack-studio`) & Custom Sky Maker (`/custom-sky-maker`)** *(2026-08-28)*.
- **Minecraft Skin Library (`/skin`)** *(2026-08-27)*: Browseable 3D skin library with Java and Bedrock downloads.
- **Stair Calculator (`/stair-calculator`)** *(2026-08-25)* & **Bedrock Skin Pack Builder (`/skin-pack-builder`)** *(2026-08-23)*.
- **Crash Report Analyzer (`/crash-report-analyzer`)** *(2026-08-22)*: Identifies common Java, memory, dependency, and mod errors from crash logs.
- **Raid Planner, Horse Breeding, UUID Lookup, Enchanting Table Translator & Particle Preview** *(2026-08-17)*.

### Improvements & Fixes
- **3D Skin Editor** *(2026-08-31)*: Centered camera orbit, upgraded layer controls, precision painting, and grid tools.
- **Give Command Generator** *(2026-08-25)* & **MiniMessage** *(2026-08-18)*: Expanded command options and live previews.

---

## 2026-07

### New Tools
- **Material Calculator (`/minecraft-material-calculator`)** *(2026-07-31)* & **Bedrock Pack Doctor (`/bedrock-pack-doctor`)** *(2026-07-30)*.
- **Ore Distribution (`/ore-distribution`) & NBT to Components (`/nbt-to-components`)** *(2026-07-30)*.
- **Custom Mob Variant Builder (`/custom-mob-variant-builder`)** *(2026-07-29)* & **Stronghold Triangulator (`/stronghold-triangulator`)** *(2026-07-26)*.
- **Cape Pack Builder (`/cape-pack-builder`)** *(2026-07-19)*.
- **Block Palette, Potion Chart, Structures Locate & Stack Calculator** *(2026-07-14)*.
- **Villager Trades Database (`/villager-trades`)** *(2026-07-12)* alongside the full **Server & File Tools**, **Creative Text**, and **Skin Tool** suites.
- **Custom Totem Generator (`/custom-totem`)** *(2026-07-04)* & **Player Heads Generator (`/player-heads`)** *(2026-07-03)*.

### Improvements & Fixes
- **Music Disc Maker** *(2026-07-16)*: Added browser-side MP3/WAV audio conversion support.
- **Seed Map** *(2026-07-16)*: Added relief tiles and `26.3` structure updates.
- **Banner & Firework Generators** *(2026-07-30)*: Redesigned banner/shield maker and expanded firework options.

---

## 2026-06

### New Tools
- **Minecraft Armor Trim Viewer (`/minecraft-armor-trim`)** *(2026-06-30)*: Interactive trim pattern and material previewer with command output.
- **Minecraft Papercraft Generators (`/minecraft-papercraft`)** *(2026-06-30)*: Printable character and block papercraft sheets.
- **Custom Paintings Maker (`/custom-paintings`)** *(2026-06-29)*: Convert images into custom Minecraft painting resource packs.
- **ZIP to MRPACK Converter (`/zip-to-mrpack`), Pack Converter (`/pack-converter`) & Pack Merger (`/pack-merger`)** *(2026-06-29)*.

---

## 2026-04 — Initial Launch

### Core Tools Released
- **MRPack to ZIP Converter (`/mrpack-to-zip`)** *(2026-04-15)*.
- **Crafting Table Recipe Browser (`/crafting`) & Mob Spawner Generator (`/spawner`)** *(2026-04-14)*.
- **3D Skin Editor & Studio (`/edit-skin`)** *(2026-04-13 – 2026-04-18)*: Floating studio panels, autosave, grid shortcuts, and mobile touch controls.
- **Texture Maker (`/texture-maker`)** *(2026-04-09)*: Pixel editor with undo/redo, grid toggle, and ZIP export.
- **Circle Generator (`/circle`) & Sphere Generator (`/sphere`)** *(2026-04-08)*.
- **MOTD Generator (`/motd`), MiniMessage Viewer (`/minimessage`) & Seed Map (`/seed-map`)** *(2026-04-06)*: Initial public launch with shareable URLs and live previews.
