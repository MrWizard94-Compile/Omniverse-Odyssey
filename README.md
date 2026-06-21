# Omniverse Odyssey

> From humble dirt-hut survivor to dimension-hopping, spell-casting, factory-building god of the cosmos — four eras of FTB-Quests-guided progression ending in rockets to Mars.

**Minecraft 1.20.1 · Forge 47.x · CurseForge-format modpack**

## Overview

| Spec | Detail |
|------|--------|
| Title | Omniverse Odyssey |
| Version | Minecraft 1.20.1 |
| Loader | Forge 47.x |
| Primary focus | Grand-arc progression (survival → galactic ascension) |
| Difficulty | Slow-burn automation + high-stakes RPG bosses |
| Pack version | 0.1.0 (foundation) |

### The four eras (FTB Quests)

| Era | Focus | Key mods |
|-----|-------|----------|
| I. Survival & Foundation | Food, storage, surviving upgraded nights | Farmer's Delight, Better Combat, Macaw's |
| II. Industrial Awakening | Kinetic energy, trains, early spellbooks | Create, Ars Nouveau, Iron's Spells |
| III. High-Tech & Dimensional | Digital storage, bosses, magical realms | AE2, Cataclysm, Twilight Forest |
| IV. Galactic Ascension | Fusion, MekaSuit, rockets | Mekanism, Ad Astra, Apotheosis |

## Repository layout

| Path | Purpose |
|------|---------|
| `manifest/manifest.json` | CurseForge manifest (Forge 1.20.1). `files[]` resolved at packaging time. |
| `overrides/config/` | Pack configs (committed) |
| `overrides/mods/` | Local mod jars (gitignored; `.gitkeep` tracked) |
| `docs/CONCEPT.md` | Original design vision (incl. progression loop) |
| `docs/MODLIST.md` | Curated, categorized mod roster + Forge 1.20.1 availability notes |

## Status

🌱 **Foundation scaffolded.** Structure, manifest, and curated roster in place. Mod `files[]` not yet resolved to CurseForge IDs — see `docs/MODLIST.md`. FTB Quests chapters per era are authored under `overrides/config/ftbquests/`.

## Building / CurseForge export

1. Drop mod jars into `overrides/mods/` to test in a local Forge 1.20.1 instance.
2. Resolve each mod's `projectID` / `fileID` into `manifest/manifest.json` `files[]`.
3. Zip `manifest.json` + `overrides/` per the CurseForge modpack spec; publish via the CurseForge author dashboard.

## Related

- [JanusPrime orchestration](https://github.com/MrWizard94-Compile/JanusPrime)
- Sibling concept packs: Aethelgard, Aetheria, Aetherial Convergence, Chronicles of the Shattered Cosmos
