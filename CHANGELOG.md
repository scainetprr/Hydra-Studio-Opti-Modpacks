# Changelog

All notable changes to **Hydra Studio Opti-Modpack** are documented here.

Format follows [Keep a Changelog](https://keepachangelog.com/) principles. Versions use the same number across all supported Minecraft versions unless noted.

---

## [1.1.1] - 2026-10-14

### Added
- **Crash Assistant** on all versions (automatic crash diagnostics)
- **New builds:** 1.20, 1.20.1, 1.20.2, 1.20.3, 1.20.4, 1.20.5, 1.20.6, 1.21, 1.21.2, 1.21.3, 1.21.4, 1.21.5, 1.21.6, 1.21.7, 1.21.8, 1.21.9, 26.1, 26.1.1
- **Server files** for every supported version (Lithium, C2ME, Krypton, Spark, FerriteCore, Alternate Current, Voice Chat)

### Fixed
- **MC 1.21.11:** Cull Leaves startup crash (`cullRoots` identifier bug) - jar shipped patched in overrides
- **MC 26.1 / 26.1.1 / 26.1.2:** ViaFabric incompatible nested module (`viafabric-mc26-2` removed)
- **MC 26.2:** ViaFabric incompatible nested module (`viafabric-mc26-1` removed)
- **MC 26.3:**
  - ViaFabric incompatible nested module (`viafabric-mc26-1` removed)
  - Sodium downgraded from `0.9.3-alpha.1` to `0.9.2` (required by Reese's Sodium Options 2.2.5)
  - Added `fabric-language-kotlin` 1.14.2 (required by OptiGUI)

### Removed
- Broken 1.1.0 builds for 1.21.11 and 26.3 (replaced by 1.1.1)

### Changed
- Project page rewritten in English
- Version support expanded from 6 to 24 Minecraft versions (1.20 - 26.3)

---

## [1.1.0]

### Added
- **6 new performance mods** across all versions: Krypton, BetterRenderDistance, CullLeaves, Fast IP Ping, C2ME (async chunks)

### Updated
- Sodium, Lithium, Fabric API, Cloth Config, YACL, ImmediatelyFast, Dynamic FPS, EntityCulling, MoreCulling, ScalableLux, BadOptimizations, Ksyxis, Alternate Current, LambDynamicLights, Continuity, BetterGrassify, BetterF3, Mod Menu, Ok Zoomer, Shoulder Surfing, Litematica, MiniHUD, Tweakeroo, Spark, Debugify

### Changed
- Iris Shaders moved to optional folder (disabled by default)
- Render distance default set to 8 chunks
- Optimized video settings via options.txt

### Notes
- MC 26.3: some mods pending 26.3 builds at release time (FerriteCore, Architectury API, Simple Voice Chat, Shoulder Surfing, Entity Model/Texture Features, Puzzles Lib)

---

## [1.0.6]

- Early stable build for MC 26.2
- Baseline optimization pack (Sodium, Lithium, FerriteCore, and core performance suite)

---

## Links

- Modrinth: https://modrinth.com/modpack/hydra-studio-opti-modpack
- Discord: https://discord.gg/dkZpFtXXCj
- Ko-fi: https://ko-fi.com/scainetprr
