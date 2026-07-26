# Hydra Studio Opti-Modpack

![Fabric](https://img.shields.io/badge/Loader-Fabric-green)
![Minecraft](https://img.shields.io/badge/MC-1.21.x%20%7C%2026.x-blue)
![Mods](https://img.shields.io/badge/Mods-36--39-orange)
![License](https://img.shields.io/badge/License-ARR-red)

**The ultimate optimization modpack for Minecraft Fabric.** 36-39 carefully selected mods to maximize FPS, reduce lag, and improve the gaming experience without sacrificing compatibility.

Developed by **Hydra Studio & HyperHard Network** — Inspired by the gaming community that has many technical limitations, designed for extreme performance on low-end, mid-range, and high-end PCs.

---

## What's included?

### ⚡ Core Performance Optimization

| Mod | Description | Impact |
|-----|-------------|--------|
| **Sodium** | Rendering engine rewritten from scratch. Replaces Minecraft's renderer with a much faster one. Dramatically reduces CPU and GPU usage. | +200-400% FPS |
| **Sodium Extra** | Additional configurations for Sodium such as FPS limits, VSync, and advanced rendering options. | Extra configuration |
| **Reese's Sodium Options** | Improved interface for Sodium options. Easier to configure and understand. | Better UX |
| **Lithium** | Optimizes game logic: pathfinding, redstone, entity ticks, worldgen. No visual changes. | +30-100% TPS |
| **FerriteCore** | Reduces game memory usage by compressing block and chunk data. Ideal for low-RAM PCs. | -30-50% RAM |
| **EntityCulling** | Doesn't render entities that are off-screen. Saves unnecessary CPU and GPU usage. | +15-40% FPS |
| **MoreCulling** | Extends culling to more objects: item frames, armor stands, mobs with the same texture. | +10-25% FPS |
| **ScalableLux** | Optimized lighting engine. Reduces light calculation time without visual errors. | +10-20% FPS |
| **Dynamic FPS** | Reduces FPS when Minecraft is in the background or minimized. Saves battery and CPU. | -50% CPU idle |
| **BadOptimizations** | Fixes multiple performance issues that Mojang hasn't resolved. | Variable |
| **Ksyxis** | Optimizes chunk loading by avoiding unnecessary loads. Smoother world. | +15-30% FPS |
| **Alternate Current** | Replaces the redstone system with a much faster and more efficient one. | +50-200% Redstone |
| **LY Clumps** | Groups entities to reduce draw calls. Ideal for farms. | +10-30% FPS |
| **ImmediatelyFast** | Immediate rendering for UI and text elements. Reduces lag in inventories. | +20-40% FPS |
| **Debugify** | Fixes client bugs that affect performance. Maintained by the community. | Variable |
| **Spark** | Performance profiler. Identifies bottlenecks in your game. | Diagnostics |

### 🎨 Rendering & Visuals

| Mod | Description |
|-----|-------------|
| **Iris Shaders** | Full OptiFine shader support. Compatible with Sodium for maximum performance. |
| **LambDynamicLights** | Dynamic lights: torches, lanterns, and entities illuminate the environment as they move. |
| **Continuity** | Connected textures (glass panes, bookshelves, etc). Optional, can be disabled. |
| **BetterGrassify** | Improves the appearance of grass and other natural blocks. |
| **Entity Model Features** | Improved entity models for resource packs. |
| **Entity Texture Features** | Improved entity textures: emissive textures, custom colors, etc. |

### 🛠️ Utility & Information

| Mod | Description |
|-----|-------------|
| **BetterF3** | Improved and more readable debug screen. Colors, organized layout. |
| **Mod Menu** | Complete mod menu. Configure all mods from one place. |
| **Ok Zoomer** | Zoom function with configurable key. Replaces OptiFine zoom. |
| **Shoulder Surfing** | Improved third person: side view, customizable angle. |
| **Simple Voice Chat** | Proximity voice chat. Talk to nearby players without Discord. |

### 🔧 Tools (Builders/Technical)

| Mod | Description |
|-----|-------------|
| **Litematica** | Schematic mod. Copy builds between worlds or servers. |
| **MaLiLib** | Library for Litematica, MiniHUD, and Tweakeroo. |
| **MiniHUD** | Mini HUD with coordinates, biome, light, and more info on screen. |
| **Tweakeroo** | Client tweaks: auto-fish, scaffold, tweak placing, and more. |

### 📚 Libraries

| Mod | Description |
|-----|-------------|
| **Fabric API** | Official Fabric API. Required by most mods. |
| **Cloth Config** | Configuration library. Used by many mods for their options. |
| **YACL** | Yet Another Config Lib. Modern and elegant configuration. |
| **Forge Config API Port** | Bridge between Forge and Fabric configurations. |
| **Puzzles Lib** | Shared library between Fabric mods. |
| **Architectury API** | Cross-platform API for multi-loader mods. |

---

## Compatibility

| Version | Status | Mods | Size |
|---------|--------|------|------|
| MC 26.2 | ✅ Complete | 39 mods | 41 MB |
| MC 26.1.2 | ✅ Complete | 39 mods | 41 MB |
| MC 1.21.11 | ✅ Complete | 36 mods | 32 MB |
| MC 1.21.10 | ✅ Complete | 39 mods | 43 MB |
| MC 1.21.1 | ✅ Complete | 38 mods | 40 MB |

**Loader:** Fabric (all mods are Fabric)

---

## Installation

### Step 1: Install Fabric Loader
1. Go to [fabricmc.net](https://fabricmc.net)
2. Download Fabric Loader for your MC version
3. Run the installer and select your MC version
4. Open Minecraft Launcher — you should see a `fabric-loader` profile

### Step 2: Download the Modpack
1. Go to [Releases](../../releases) or download the `.rar` for your version
2. Extract the `.rar` file using WinRAR or 7-Zip

### Step 3: Install Mods
1. Open the extracted `mods` folder
2. Select **ALL** `.jar` files inside
3. Copy them (`Ctrl+C`)
4. Navigate to: `%appdata%\.minecraft\mods\`
5. Paste all `.jar` files here (`Ctrl+V`)

### Step 4: Apply Optimized Settings
1. Copy the `options.txt` file from the modpack
2. Navigate to: `%appdata%\.minecraft\`
3. Paste `options.txt` here (overwrite if asked)

### Step 5: Launch
1. Select the `fabric-loader` profile in Minecraft Launcher
2. Click "Play"
3. Enjoy **+30-400% FPS!**

---

## Video Settings (Applied by options.txt)

| Setting | Value |
|---------|-------|
| Render Distance | 8 chunks |
| Simulation Distance | 8 chunks |
| Graphics | Fast |
| VSync | Off |
| Max FPS | Unlimited |
| Clouds | Off |
| Particles | Minimal |
| Smooth Lighting | Minimum |
| Mipmap Levels | 2 |
| Entity Distance | 50% |

---

## Troubleshooting

**"Incompatible mods found"**
→ Make sure you're using the CORRECT version. Each modpack is for a specific MC version only.

**Game crashes on startup**
→ Make sure Fabric Loader is installed. Make sure you copied ALL .jar files to `.minecraft\mods\`.

**How to allocate more RAM?**
→ Minecraft Launcher > Installations > Edit your profile > More Options > JVM Arguments > Change `-Xmx2G` to `-Xmx4G`

---

## Server Hosting

Our recommended server hosting: **SuperCores Hosting** — Miami, Florida & Latam

- 🌐 Web: [supercores.host](https://supercores.host/)
- 💬 Discord: [Join](https://discord.gg/q3Zv8sv3N3)

**MC Server:** mc.hyperhard.space

---

## Discord

Join our community for support, suggestions, and updates:

[![Discord](https://img.shields.io/badge/Discord-Join-7289da?logo=discord&logoColor=white)](https://discord.gg/dkZpFtXXCj)

---

## Links

- **Modrinth:** [hydra-studio-opti-modpack](https://modrinth.com/modpack/hydra-studio-opti-modpack)
- **GitHub:** [Hydra-Studio-Opti-Modpacks](https://github.com/scainetprr/Hydra-Studio-Opti-Modpacks)
- **Discord:** [Hydra Studio](https://discord.gg/dkZpFtXXCj)
- **Server:** mc.hyperhard.space

---

## Credits

Developed by **Hydra Studio**

Inspired by optimizations from: Sodium, Lithium, FerriteCore, C2ME, and the entire Fabric community.

---

*Version 1.0 — July 2026*
*Fabric | Multi-version | Extreme optimization*
