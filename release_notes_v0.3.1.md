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
