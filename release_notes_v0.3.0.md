## Skies of Arcadia Legends — HD Texture Pack (v0.3.0)

Curator & Maintainer: **Shoopkid**  
Originally by **Bighead & frozenwings**

---

### Highlights: The 100% ISO Remaster
Version 0.3.0 achieves complete 100% coverage across all **31,010 textures** extracted directly from the internal `.mld` and `.mlk` archives of the GameCube disc image.

All textures are provided in Microsoft DirectX **BC7 DDS** format with hardware mipmaps (`-m 0` / `-m 1`). Using BC7 DDS bypasses CPU decoding overhead entirely and streams directly into GPU VRAM using Dolphin's custom texture prefetch engine, eliminating in-game frame-time spikes and micro-stuttering.

---

### Key Technical Improvements
1. **Full ISO Coverage (31,010 Textures)**:
   - Full 4x upscale and curation across all game files dumped directly from the raw disc image.
   - Comprehensive coverage across all characters, airships, towns, dungeons, overworld, combat stages, visual effects, and cutscenes.
2. **Alpha Channel & Ghost Haze Elimination**:
   - Audited the entire library to purge low-alpha edge fringing ($1 \le \alpha \le 25$), eliminating gray outline artifacts on character cutouts and foliage.
3. **Standardized Atmospheric Pipeline**:
   - Transparent overlays (clouds, smoke, mist, fog, and heat haze) upscaled with proportional Gaussian blur applied strictly to the alpha channel to preserve soft gradients without pixel stair-stepping.
4. **Scene Corrections**:
   - **Mid-Ocean Rhaknam Cutscene (`205ab01`)**: Restored correct atmospheric mist density; resolved screen occlusion bug.
   - **Temple of Pyrynn Area 2 (`109c`)**: Purged solid-opaque hash-colliding textures causing white screen washouts.
   - **Galcian Cutscenes & Combat**: Corrected eye and cape alpha masks; removed bounding box outlines.
   - **Delphinus Bridge Flag Shadow (`034ab`)**: Standardized to canonical alpha gradient; removed redundant duplicates.
5. **Runtime GPU Textures**:
   - Extracted and remastered dynamic Format 8 (C4, 4-bit paletted) runtime textures from endgame boss gauntlets, ship combat, and Intro Movie A with dual `_arb.dds` compatibility aliases.

---

### Downloads & Package Breakdown

Every package extracts into a top-level `GEA` folder for drag-and-drop installation into Dolphin's `Load/Textures/` directory:

| Package | Archive | Compressed Size | Scope |
| :--- | :--- | :---: | :--- |
| **01. Characters & Enemies** | `01_SoAL_HD_Characters_and_Enemies_v0.3.0.7z` | 1.17 GB | Playable party members, costumes, weapons, Admirals, NPCs, enemies, Gigas, bosses |
| **02a. Towns & Ports (Part 1)** | `02a_SoAL_HD_Towns_and_Ports_Part1_v0.3.0.7z` | 1.26 GB | Pirate Isle, Sailor's Island, Lower City Valua, Maramba City, Horteka, Nasrad |
| **02b. Towns & Ports (Part 2)** | `02b_SoAL_HD_Towns_and_Ports_Part2_v0.3.0.7z` | 1.30 GB | Crescent Isle HQ, Esperanza, Yafutoma, Tenkou Island, Great Silver Shrine |
| **03a. Dungeons & Ruins (Part 1)** | `03a_SoAL_HD_Dungeons_and_Ruins_Part1_v0.3.0.7z` | 1.12 GB | Alfonso's Ship, Shrine Island, Catacombs, Upper City, Pyrynn, Moonstone Mtn, Rixis, Daccat |
| **03b. Dungeons & Ruins (Part 2)** | `03b_SoAL_HD_Dungeons_and_Ruins_Part2_v0.3.0.7z` | 1.40 GB | Grand Fortress, Mt. Kazai, Dark Rift, Glacia, Tartas, Dangral Island, Vortex, Hydra, Soltis |
| **04. Ships & Ship Battles** | `04_SoAL_HD_Ships_and_Ship_Battles_v0.3.0.7z` | 597.3 MB | Delphinus, Little Jack, Albatross, Armada vessels, bridge interiors, combat stages |
| **05. Overworld** | `05_SoAL_HD_Overworld_v0.3.0.7z` | 141.9 MB | Skyboxes, cloud layers, landmasses, floating islands, discoveries, rifts |
| **06. Battle Arenas & Effects** | `06_SoAL_HD_Battle_Arenas_and_Effects_v0.3.0.7z` | 940.7 MB | Combat stages, Moon magic (all 6 elements), S-Crafts, weapon trails, particles |
| **07. UI, Menus & Fonts** | `07_SoAL_HD_UI_Menus_and_Fonts_v0.3.0.7z` | 40.6 MB | Dialogue fonts, compass, HUD command wheels, party status screens, crew cards |
| **08. Cutscenes & Ending** | `08_SoAL_HD_Cutscenes_and_Ending_v0.3.0.7z` | 811.1 MB | Intro Movies A & B, story flashback artwork, mid-ocean events, endgame, epilogue |

**Total Installed Footprint**: ~11.65 GB (BC7 DDS)  
**Total Download Footprint**: 8.71 GB across 10 modular archives

---

### Installation Instructions
1. Download desired `.7z` packages.
2. Extract using **7-Zip** (`Extract Here`). All archives extract into a unified `GEA` directory.
3. Place `GEA` into Dolphin's texture directory: `Load/Textures/GEA`.
4. In Dolphin:
   - **Graphics $\rightarrow$ Advanced**: Enable **Load Custom Textures** and **Prefetch Custom Textures**.
   - **Graphics $\rightarrow$ Enhancements**: Internal Resolution 3x (1080p) or 4x (1440p); Anisotropic Filtering 16x; Enable **Arbitrary Mipmap Detection** and **Force 24-Bit Color**; Uncheck **Disable Fog**.
