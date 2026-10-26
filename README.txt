======================================================================
SKIES OF ARCADIA LEGENDS - HD TEXTURE PACK (DOLPHIN MOD)
Version: 0.2.0 (BC7 DDS Release)
Curator & Maintainer: Shoopkid
Originally by Bighead & frozenwings
======================================================================

OVERVIEW
--------
This pack aims to provide a clean, high-quality replacement for uncurated 
"AI slop" texture packs that have circulated the community, prioritizing 
careful manual curation over raw, unchecked batch generation.

Crucially, all textures have been fully converted into Microsoft DirectX 
BC7 DDS format. Unlike standard PNG texture packs that cause micro-stutters 
and consume large amounts of RAM while your CPU decodes them, these DDS files 
bypass the CPU completely and stream instantly into your GPU's VRAM with 
Dolphin prefetching.

The result is a visually stunning experience with ZERO STUTTERING and highly 
efficient performance.


MODULAR PACKAGES (AVAILABLE ON GITHUB RELEASES)
-----------------------------------------------
Download from: https://github.com/shoopkid/Skies-of-Arcadia-Legends-HD-Textures-Pack/releases

01. UI (25 MB)
    Menus, text fonts, HUD command wheels, compass, crew portraits, dialogue boxes.

02. Characters (1.00 GB)
    All party members, costumes, weapons, NPCs, Armada, enemies, bosses, and Gigas.

03a. Environment -- World & Ships (801 MB)
     Airships (Delphinus, Little Jack, etc.), skyboxes, weather, moons, discoveries, battle arenas.

03b. Environment -- Locations (Disc 1, Part 1) (1.77 GB)
     Pirate Isle, Shrine Island, Sailor's Island, Valua City/Catacombs, Maramba, Pyrynn, Horteka, Rixis.

03c. Environment -- Locations (Disc 1, Part 2) (1.58 GB)
     Nasrad, Daccat's Island, Grand Fortress, Dark Rift, Yafutoma, Mt. Kazai, World Flight.

03d. Environment -- Locations (Disc 2) (1.35 GB)
     Crescent Isle HQ upgrades, Lands of Ice, Glacia, Great Silver Shrine, Hydra, Soltis.

04. Special Effects (208 MB)
    Magic spells (all 6 elements), explosions, particle flares, weapon trails, hit sparks.

05. Cutscene Artwork (38 MB)
    Full-screen story illustrations, Silvite flashbacks, opening sequence paintings.


HOW TO INSTALL ON DOLPHIN EMULATOR
----------------------------------
1. Download & Extract:
   - Download your desired .7z packages from the Releases page.
   - Select all downloaded .7z files, right-click, and choose 7-Zip -> Extract Here.
   - You will see a single folder named "GEA" (the GameCube ID for Skies of Arcadia Legends).

2. Move to Dolphin's Textures Directory:
   Copy the extracted "GEA" folder and paste it into Dolphin's custom textures directory:
   - Windows: Documents\Dolphin Emulator\Load\Textures\
   - macOS: ~/Library/Application Support/Dolphin/Load/Textures/
   - Linux: ~/.local/share/dolphin-emu/Load/Textures/

   The final path must look like:
   Load/Textures/GEA/
     ├── Characters/
     ├── Cutscene Artwork/
     ├── Environment/
     ├── Special Effects/
     └── UI/

3. Enable Settings in Dolphin:
   - Open Dolphin and click "Graphics" -> "Advanced" tab.
   - Under Utility, check "Load Custom Textures".
   - Under Utility, check "Prefetch Custom Textures" (Crucial for zero stutter).

4. Recommended Enhancements:
   - Graphics -> General: Backend set to Vulkan or Direct3D 12.
   - Graphics -> Enhancements: Internal Resolution set to 3x (1080p) or 4x (1440p).
   - Graphics -> Enhancements: Anisotropic Filtering set to 8x or 16x.


CREDITS & THANKS
----------------
- SEGA & Overworks: For creating the timeless masterpiece that is Skies of Arcadia.
- Bighead & frozenwings: For creating the original, foundational Dolphin HD texture project:
  https://forums.dolphin-emu.org/Thread-skies-of-arcadia-hd-v0-06-june-27-2020
- Continued, expanded, curated, and optimized into BC7 DDS by Shoopkid.
- Dolphin Emulator Development Team: For the industry-leading emulator and custom texture engine.
======================================================================
