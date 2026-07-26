# Hydra Studio Opti-Modpack

**El modpack de optimización definitivo para Minecraft Fabric.** 38 mods cuidadosamente seleccionados para maximizar FPS, reducir lag, y mejorar la experiencia de juego sin sacrificar compatibilidad.

Desarrollado por **Hydra Studio** — Inspirado en servidores de eventos como Eufalia Studio, diseñado para rendimiento extremo enPCs de gama baja, media y alta.

---

## ¿Qué incluye?

### ⚡ Optimización Central (Core Performance)

| Mod | Descripción | Impacto |
|-----|-------------|---------|
| **Sodium** | Motor de rendering reescrito desde cero. Reemplaza el renderer de Minecraft con uno muchomás rápido. Reduce el uso de CPU y GPU dramaticamente. | +200-400% FPS |
| **Sodium Extra** | Configuraciones adicionales para Sodium como límites de FPS, VSync, y opciones avanzadas de rendering. | Configuración extra |
| **Reese's Sodium Options** | Interfaz mejorada para las opciones de Sodium. Más fácil de configurar y entender. | Mejor UX |
| **Lithium** | Optimiza la lógica del juego: pathfinding, redstone, tick entities, worldgen. Sin cambios visuales. | +30-100% TPS |
| **FerriteCore** | Reduce el uso de memoria del juego comprimiendo datos de bloques y chunks. Ideal para PCs con poca RAM. | -30-50% RAM |
| **EntityCulling** | No renderiza entidades que están fuera de la pantalla. Ahorra CPU y GPU innecesariamente. | +15-40% FPS |
| **MoreCulling** | Extiende el culling a más objetos: item frames, armor stands, mobs con la misma textura. | +10-25% FPS |
| **C2ME** | Paraleliza la carga de chunks, reduciendo el stuttering al explorar el mundo. | -50% Stuttering |
| **ScalableLux** | Motor de iluminación optimizado. Reduce el tiempo de cálculo de luz sin errores visuales. | +10-20% FPS |
| **Dynamic FPS** | Reduce los FPS cuando Minecraft está en segundo plano o minimizado. Ahorra batería y CPU. | -50% CPU idle |
| **BadOptimizations** | Corrige múltiples problemas de rendimiento que Mojang no ha resuelto. | Variable |
| **Ksyxis** | Optimiza la carga de chunks evitando cargas innecesarias. Mundo más fluido. | +15-30% FPS |
| **Alternate Current** | Reemplaza el sistema de redstone con uno much más rápido y eficiente. | +50-200% Redstone |
| **LY Clumps** | Agrupa entidades para reducir el número de draw calls. Ideal para granjas. | +10-30% FPS |
| **ImmediatelyFast** | Rendering inmediato para elementos de UI y texto. Reduce el lag en inventarios. | +20-40% FPS |
| **Debugify** | Corrige bugs del cliente que afectan el rendimiento. Mantenido por la comunidad. | Variable |
| **Spark** | Profiler de rendimiento. Identifica cuellos de botella en tu juego. | Diagnóstico |

### 🎨 Rendering y Visual

| Mod | Descripción |
|-----|-------------|
| **Iris Shaders** | Soporte completo para shaders OptiFine. Compatibilidad con Sodium para máximo rendimiento. |
| **LambDynamicLights** | Luces dinámicas: las antorchas, linternas y entidades iluminan el entorno al moverse. |
| **Continuity** | Texturas conectadas (glass panes,书架s, etc). Opcional, se puede desactivar. |
| **BetterGrassify** | Mejora la apariencia de la hierba y otros bloques naturales. |
| **Entity Model Features** | Modelos de entidad mejorados para resource packs. |
| **Entity Texture Features** | Texturas de entidad mejoradas: emissive textures, custom colors, etc. |

### 🛠️ Utilidad e Información

| Mod | Descripción |
|-----|-------------|
| **BetterF3** | Pantalla de debug mejorada y más legible. Colores, layout organizado. |
| **Mod Menu** | Menú de mods completo. Configura todos los mods desde un solo lugar. |
| **Ok Zoomer** | Función de zoom con tecla configurable. Reemplaza OptiFine zoom. |
| **Shoulder Surfing** | Tercera persona mejorada: vista lateral, ángulo personalizable. |
| **Simple Voice Chat** | Chat de voz proximity. Habla con jugadores cercanos sin Discord. |
| **ViaFabric** | Conéctate a servidores de versiones anteriores sin cambiar de MC. |

### 📚 Bibliotecas (Libraries)

| Mod | Descripción |
|-----|-------------|
| **Fabric API** | API oficial de Fabric. Requerida por la mayoría de mods. |
| **Cloth Config** | Biblioteca de configuración. Usada por muchos mods para sus opciones. |
| **YACL** | Yet Another Config Lib. Configuración moderna y elegante. |
| **Forge Config API Port** | Puente entre configuraciones de Forge y Fabric. |
| **Puzzles Lib** | Biblioteca compartida entre mods de Fabric. |
| **Architectury API** | API cross-platform para mods multi-loader. |

### 🔧 Herramientas (Builders/Technical)

| Mod | Descripción |
|-----|-------------|
| **Litematica** | Mod de esquemáticos. Copia construcciones entre mundos o servidores. |
| **MaLiLib** | Biblioteca para Litematica, MiniHUD y Tweakeroo. |
| **MiniHUD** | Mini HUD con coordenadas, biome, luz, y más información en pantalla. |
| **Tweakeroo** | Tweaks del cliente: auto-fish, scaffold, tweak placing, y más. |

---

## Compatibilidad

| Versión | Estado |
|---------|--------|
| MC 26.2 | ✅ Completo (38 mods) |
| MC 26.1.2 | ✅ Completo (39 mods) |
| MC 1.21.1 | ✅ Completo (38 mods) |
| MC 1.21 | ✅ Completo (39 mods) |
| MC 1.21.1 | ✅ Completo (38 mods) |

**Loader:** Fabric (todos los mods son Fabric)

---

## Requisitos

- **Fabric Loader** instalado para tu versión de MC
- **Java 21+** (para MC 1.21+) o **Java 25** (para MC 26.2+)
- **2-4 GB RAM** asignados a Minecraft (recomendado: 4GB)
- **GPU con OpenGL 4.5+** (cualquier GPU moderna)

---

## Instalación

1. Descarga el modpack de tu versión
2. Instala **Fabric Loader** desde https://fabricmc.net
3. Extrae el archivo `.rar`
4. Copia todos los `.jar` de la carpeta `mods` a:
   - **Windows:** `%appdata%\.minecraft\mods\`
   - **Linux:** `~/.minecraft/mods/`
   - **Mac:** `~/Library/Application Support/minecraft/mods/`
5. Inicia Minecraft con el perfil **Fabric**
6. ¡Disfruta de +30-400% FPS!

---

## Optimizaciones incluidas

- **Sodium** — Rendering engine reescrito (+200-400% FPS)
- **Lithium** — Lógica del juego optimizada (+30-100% TPS)
- **FerriteCore** — Uso de memoria reducido (-30-50% RAM)
- **C2ME** — Chunks paralelos (-50% stuttering)
- **EntityCulling** — No renderiza lo que no ves (+15-40% FPS)
- **ScalableLux** — Iluminación optimizada (+10-20% FPS)
- **Alternate Current** — Redstone eficiente (+50-200%)
- **ImmediatelyFast** — UI y texto rápido (+20-40% FPS)
- **Iris Shaders** — Shaders sin lag
- **38 mods** — Todos compatibles entre sí

---

## Créditos

Desarrollado por **Hydra Studio**
Servidor de hosting: **SuperCores Hosting** — Miami, Florida y Latam
- Web: https://supercores.host/
- Discord: https://discord.gg/q3Zv8sv3N3

Inspirado en optimizaciones de: Sodium, Lithium, FerriteCore, C2ME, y toda la comunidad de Fabric.

---

## Links

- **GitHub:** https://github.com/scainetprr/HyperHard-Optimization-ModPack
- **Discord:** https://discord.gg/hydrastudio
- **Servidor MC:** us-1.av.supercores.host

---

*Versión 1.0 — Julio 2026*
*Fabric | Multi-version | Optimización extrema*
