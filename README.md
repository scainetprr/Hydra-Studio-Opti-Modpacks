# Hydra Studio Opti-Modpack

![Fabric](https://img.shields.io/badge/Loader-Fabric-green)
![Minecraft](https://img.shields.io/badge/MC-1.20%20%E2%86%92%2026.3-blue)
![Mods](https://img.shields.io/badge/Mods-40--51-orange)
![License](https://img.shields.io/badge/License-ARR-red)

**The ultimate optimization modpack for Minecraft Fabric.** 40-51 carefully selected mods to maximize FPS, reduce lag, and improve the experience without sacrificing compatibility.

Developed by **Hydra Studio & HyperHard Network**. Built for gamers with technical limitations - extreme performance on low-end, mid-range, and high-end PCs.

**90% optimization - 10% lightweight QoL - Built for low-end PCs.**

## Download

- **Modrinth:** [hydra-studio-opti-modpack](https://modrinth.com/modpack/hydra-studio-opti-modpack)
- **Discord:** https://discord.gg/dkZpFtXXCj
- **Donate (Ko-fi):** https://ko-fi.com/scainetprr

## Supported versions

| Minecraft | Client | Server files |
|-----------|--------|--------------|
| 1.20 - 1.20.6 | Yes | Yes |
| 1.21 - 1.21.11 | Yes | Yes |
| 26.1 - 26.3 | Yes | Yes |

All builds use **Fabric Loader**. On older versions (1.20.x) some mods are missing because authors do not publish builds for those MC versions.

## What's inside?

### 90% - Core Performance

| Mod | What it does | Impact |
|-----|--------------|--------|
| **Sodium** | Rendering engine rewritten from scratch | +200-400% FPS |
| **Lithium** | Game logic optimization (pathfinding, redstone, ticks) | +30-100% TPS |
| **FerriteCore** | Memory usage reduction | -30-50% RAM |
| **C2ME** | Async chunk generation and loading | Fewer stutters |
| **EntityCulling** | Does not render what you cannot see | +15-40% FPS |
| **MoreCulling** | Extends culling to item frames, armor stands, and more | +10-25% FPS |
| **ScalableLux** | Optimized lighting engine | +10-20% FPS |
| **ImmediatelyFast** | Fast UI and text rendering | +20-40% FPS |
| **BadOptimizations** | Fixes multiple Mojang performance issues | Variable |
| **Ksyxis** | Optimized chunk loading | +15-30% FPS |
| **Alternate Current** | Efficient redstone | +50-200% redstone speed |
| **Krypton** | Network stack optimization | Better multiplayer |
| **Cull Leaves** | Culls leaf blocks you cannot see | +5-15% FPS |
| **Dynamic FPS** | Reduces FPS when the game is in background | -50% idle CPU |
| **LY Clumps** | Groups XP orbs to reduce entity count | +10-30% FPS |
| **Debugify** | Fixes client bugs that hurt performance | Variable |
| **Spark** | Performance profiler | Diagnostics |

### 10% - Lightweight QoL (no FPS cost)

| Mod | What it does |
|-----|--------------|
| **Mod Menu** | Easy mod configuration UI |
| **BetterF3** | Cleaner debug screen |
| **Ok Zoomer / Zoomify** | Zoom without lag |
| **Simple Voice Chat** | Proximity voice chat |
| **Litematica / MiniHUD / Tweakeroo** | Building tools (Marium's suite) |
| **BetterGrassify** | Connected grass visuals |
| **Continuity** | Connected textures |
| **Shoulder Surfing** | Third-person camera improvements |
| **Controlify** | Controller support |
| **Crash Assistant** | Automatic crash diagnostics |

Iris Shaders ships **optional and disabled** in `_opcional-iris/` (where available). Enable it only if your PC can handle it.

## Default settings (pre-tuned)

- Render distance: **8 chunks**
- Graphics: **Fast**
- VSync: **Off**
- Clouds: **Off**
- Particles: **Minimal**

The pack includes an optimized `options.txt`.

## Installation

### Modrinth App (recommended)
1. Open **Modrinth App**
2. Search **Hydra Studio Opti-Modpack**
3. Pick your Minecraft version
4. **Install** - **Play**

### Manual
1. Install **Fabric Loader** for your MC version at [fabricmc.net](https://fabricmc.net)
2. Download the `.mrpack` from the Modrinth **Versions** tab
3. Import it in Modrinth App / Prism / MultiMC, or extract the mods into `.minecraft/mods/`
4. Copy the included `options.txt`
5. Play with the Fabric profile

### Server
1. Install Fabric Loader on your server
2. Download the **Server Files** version from Modrinth matching your MC version
3. Copy the jars into your server `mods/` folder
4. Start the server - players do not need any of these mods to join

## Repository layout

```
MC-<version>/   # mrpack builds per Minecraft version
CHANGELOG.md    # release history
README.md       # this file
REGLAS.md       # community rules (Spanish)
```

## Feedback

Use the **comments** section on [Modrinth](https://modrinth.com/modpack/hydra-studio-opti-modpack) or our **Discord** to report FPS, suggest mods, or ask for help.

When reporting results, include: **CPU, GPU, RAM, MC version, and average FPS** - it helps others with similar hardware.

## Credits

Developed by **Hydra Studio & HyperHard Network**.

- Hosting: [SuperCores Host](https://supercores.host/) (Miami and Latam)
- Discord: https://discord.gg/q3Zv8sv3N3

Thanks to the Fabric community: Sodium, Lithium, FerriteCore, C2ME, and friends.

---
v1.1.1 - Fabric - MC 1.20 to 26.3 - Extreme optimization
