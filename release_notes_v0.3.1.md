## Skies of Arcadia Legends — HD Texture Pack (v0.3.1)

Curator & Maintainer: **Shoopkid**  
Originally by **Bighead & frozenwings**

---

### Highlights in v0.3.1

Version 0.3.1 is a cumulative patch update addressing visual inconsistencies, transparency clipping, and character models across the game, alongside a complete modular reorganization of character and UI assets.

---

### Characters & NPCs

* **Albatross Crew & Pirate Isle Citizens**:
  * Remastered facial expressions and features for Dyne, Briggs, Timmus, Patch, Boris, Alan, Lindsi, Peter, Luke, Mabel, and Martha using Japanese Dreamcast master textures.
  * Reorganized loose character dumps into dedicated individual folders for all 11 Albatross crew members and 11 Pirate Isle citizens.
* **Party Members**:
  * Upgraded low-resolution facial expression textures for Vyse, Aika, and Fina to match high-resolution source art.
  * Restored Vyse's belt buckle geometry and cleaned costume accessories.
  * Re-upscaled Vyse's scarf textures to match original GameCube color and highlight curves.
* **Armada**:
  * Cleaned up Alfonso's smiling face texture.
  * Fixed Galcian’s uniform: removed erroneous transparency causing see-through mesh on his coat, restored clipped gold trim edges, and cleaned medallion decals.
  * Tightened visor slots on Valuan Soldier helmets and restored the copilot's face.

---

### Combat & UI

* **Combat Portraits**:
  * Updated battle portraits for early-game enemies and bosses (Sentinel, Flestik, Grouder, Antonio) and party members.
  * Neutralized background white bleed under transparent pixels across all portraits to eliminate edge halos during combat.
  * Set 2D UI portrait badges to single-level mipmaps to keep them sharp on high-resolution displays.
  * Realigned all combat portraits out of character folders into dedicated UI directories (`07\Combat Portraits\`).

---

### Visual Effects & Cutscenes

* **Intro Movie**:
  * Removed the halo border around the Green Moon and cleaned cloud edges over Ixa’taka.
* **Valuan Boarding Cutscenes**:
  * Restored the Valuan flagship crest and flag; cleaned up smoke, flare, and particle textures.
* **Ship Interiors**:
  * Cleaned Albatross wall rivets (-96.8% artificial drop shadow haze) and repaired crackled circular viewport glass.
* **Ships**:
  * Relocated the Blue Rogue Sloop (20 textures) out of character dumps to its canonical ship directory.
* **Towns & Dungeons**:
  * Added 15 runtime arb textures for the Pirate Isle Underground Base.
  * Repaired Pirate Isle skybox clouds, hatch opening chain, and Serpent cutscene banners.
  * Added smoothed steam and evaporation haze textures in Temple of Pyrynn Area 2 (`109c`).

---

### Transparency & Performance

* **Fringe & Halo Cleanup**:
  * Cleaned low-alpha fringes and background color bleed across over 500 textures (magic spells, boss decals, foliage, lanterns, and ironwork) to eliminate square outlines and glowing borders against the sky.

---

### Installation Note

Several character and UI folders have been reorganized into dedicated subfolders for consistency. When updating from v0.3.0, please delete your existing `GEA/01` (Characters) and `GEA/07` (UI) folders before extracting the v0.3.1 archives to prevent duplicate files.

---

### Downloads & Package Breakdown

Every package extracts into a top-level `GEA` folder for drag-and-drop installation into Dolphin's `Load/Textures/` directory:

| Package | Archive | Compressed Size | Scope |
| :--- | :--- | :---: | :--- |
| **01. Characters & Enemies** | `01_SoAL_HD_Characters_and_Enemies_v0.3.1.7z` | 1.38 GB | Playable party members, battle costumes, weapons, Admirals, NPCs, enemies, Gigas, bosses |
| **02a. Towns & Ports (Part 1)** | `02a_SoAL_HD_Towns_and_Ports_Part1_v0.3.1.7z` | 1.28 GB | Pirate Isle, Sailor's Island, Lower City Valua, Maramba City, Horteka, Nasrad |
| **02b. Towns & Ports (Part 2)** | `02b_SoAL_HD_Towns_and_Ports_Part2_v0.3.1.7z` | 1.33 GB | Crescent Isle HQ, Esperanza, Yafutoma, Tenkou Island, Great Silver Shrine |
| **03a. Dungeons & Ruins (Part 1)** | `03a_SoAL_HD_Dungeons_and_Ruins_Part1_v0.3.1.7z` | 1.15 GB | Alfonso's Ship, Shrine Island, Catacombs, Upper City, Pyrynn, Moonstone Mtn, Rixis, Daccat |
| **03b. Dungeons & Ruins (Part 2)** | `03b_SoAL_HD_Dungeons_and_Ruins_Part2_v0.3.1.7z` | 1.44 GB | Grand Fortress, Mt. Kazai, Dark Rift, Glacia, Tartas, Dangral Island, Vortex, Hydra, Soltis |
| **04. Ships & Ship Battles** | `04_SoAL_HD_Ships_and_Ship_Battles_v0.3.1.7z` | 607 MB | Delphinus, Little Jack, Albatross, Armada vessels, bridge interiors, combat stages |
| **05. Overworld** | `05_SoAL_HD_Overworld_v0.3.1.7z` | 143 MB | Skyboxes, cloud layers, landmasses, floating islands, discoveries, rifts |
| **06. Battle Arenas & Effects** | `06_SoAL_HD_Battle_Arenas_and_Effects_v0.3.1.7z` | 945 MB | Combat stages, Moon magic (all 6 elements), S-Crafts, weapon trails, particles |
| **07. UI, Menus & Fonts** | `07_SoAL_HD_UI_Menus_and_Fonts_v0.3.1.7z` | 46.3 MB | Dialogue fonts, compass, HUD command wheels, party status screens, crew cards, combat portraits |
| **08. Cutscenes & Ending** | `08_SoAL_HD_Cutscenes_and_Ending_v0.3.1.7z` | 815 MB | Intro Movies A & B, story flashback artwork, mid-ocean events, endgame, epilogue |

**Total Installed Footprint**: ~11.8 GB (BC7 DDS)  
**Total Download Footprint**: 9.07 GB across 10 modular archives

---

### Installation Instructions
1. Download desired `.7z` packages.
2. Extract using **7-Zip** (`Extract Here`). All archives extract into a unified `GEA` directory.
3. Place `GEA` into Dolphin's texture directory: `Load/Textures/GEA`.
4. In Dolphin:
   - **Graphics -> Advanced**: Enable **Load Custom Textures** and **Prefetch Custom Textures**.
   - **Graphics -> Enhancements**: Internal Resolution 3x (1080p) or 4x (1440p); Anisotropic Filtering 16x; Enable **Arbitrary Mipmap Detection** and **Force 24-Bit Color**; Uncheck **Disable Fog**.
