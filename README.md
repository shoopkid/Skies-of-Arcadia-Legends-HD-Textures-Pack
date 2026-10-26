# Skies of Arcadia Legends — HD Texture Pack

[![Release](https://img.shields.io/badge/version-v0.2.0-blue.svg)](https://github.com/Shoopkid/skies-of-arcadia-legends-hd/releases)
[![Platform](https://img.shields.io/badge/platform-Dolphin%20Emulator-0078D7.svg)](https://dolphin-emu.org/)
[![GameCube IDs](https://img.shields.io/badge/GameCube-GEAE01%20%7C%20GEAP8P%20%7C%20GEAJ8P-green.svg)](https://gametdb.com/GameCube/GEAE01)
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](LICENSE)
[![Website](https://img.shields.io/badge/website-skiesofarcadiahd.xyz-blueviolet.svg)](https://skiesofarcadiahd.xyz/)
[![Archive.org](https://img.shields.io/badge/archive.org-v1%20release-black.svg)](https://archive.org/details/skies-of-arcadia-legends-hd-texture-pack-4x-upscaled-dds-v1)

> A faithful, performance-optimized, and hand-curated 4x HD texture overhaul for the GameCube classic *Skies of Arcadia Legends*, tailored specifically for Dolphin Emulator.

---

## Quick Links

* 🌐 **Official Website:** [https://skiesofarcadiahd.xyz/](https://skiesofarcadiahd.xyz/)
* 📦 **GitHub Releases:** [Releases & Downloads](https://github.com/Shoopkid/skies-of-arcadia-legends-hd/releases)
* 🏛️ **Internet Archive Listing:** [archive.org Repository (v1 DDS)](https://archive.org/details/skies-of-arcadia-legends-hd-texture-pack-4x-upscaled-dds-v1)
* 💾 **Google Drive Mirror:** Available through [skiesofarcadiahd.xyz](https://skiesofarcadiahd.xyz/)
* 💬 **Dolphin Forums Project:** [Dolphin Community Thread](https://forums.dolphin-emu.org/Thread-skies-of-arcadia-hd-v0-06-june-27-2020) *(Original work by BigHead & FrozenWings)*

---

## Table of Contents
1. [Overview & Philosophy](#overview--philosophy)
2. [Package Formats (DDS vs 4x PNG vs 1x PNG)](#package-formats)
3. [Version History & Release Timeline](#version-history--release-timeline)
4. [What's New in Version 0.2.0](#whats-new-in-version-020)
5. [Upscale & Curation Methodology](#upscale--curation-methodology)
6. [Installation Guide (Dolphin Emulator)](#installation-guide-dolphin-emulator)
7. [Recommended Dolphin Graphics Settings](#recommended-dolphin-graphics-settings)
8. [Known Limitations & Roadmap](#known-limitations--roadmap)
9. [Contributing & Bug Reports](#contributing--bug-reports)
10. [Legal Disclaimer & Licensing](#legal-disclaimer--licensing)
11. [Credits & Appreciation](#credits--appreciation)

---

## Overview & Philosophy

This project is a dedicated continuation, expansion, and modernization of the pioneering *Skies of Arcadia Legends* HD texture pack originally created by **BigHead** and **FrozenWings** on the Dolphin Emulator forums.

Maintained and curated by **Shoopkid**, this project provides a clean, high-fidelity alternative to uncurated "AI slop" texture packs that have circulated the community. Rather than relying on raw, unchecked batch upscaling that washes out subtle lighting or hallucinates erroneous geometry, every texture family is carefully evaluated, hand-airbrushed in Photoshop, and calibrated against native GameCube rendering to preserve the authentic charm and atmosphere of the original Dreamcast and GameCube art direction.

---

## Package Formats

This release is distributed across three distinct formats tailored to different user needs:

| Package | Format | Primary Use Case | Key Highlights |
| :--- | :--- | :--- | :--- |
| **Characters (BC7 DDS)** | `.dds` (`BC7_UNORM`) | **Recommended for Playing** | • **~63% smaller size & VRAM footprint**<br>• Zero CPU decode stutters during battle swaps<br>• Direct GPU streaming with Dolphin prefetching<br>• Strict single-mip (`-m 1`) compatibility |
| **Characters_4x (PNG)** | Lossless 32/24-bit `.png` ($512\times512+$) | **Archival & Modding Master** | • **First public release** of raw uncompressed 4x master assets<br>• Lossless master textures for texture artists and custom reskins |
| **Characters_1x (PNG)** | Native GameCube `.png` ($128\times128$) | **SD Reference Companion** | • Exact 1:1 SD reference and hash verification<br>• Decompressed directly from retail GameCube PAL ISO (`.mld`) |

---

## Version History & Release Timeline

### **Version 0.1.0 — Initial Public Release (May 19, 2026)**
* Hosted on [Internet Archive](https://archive.org/details/skies-of-arcadia-legends-hd-texture-pack-4x-upscaled-dds-v1) and [skiesofarcadiahd.xyz](https://skiesofarcadiahd.xyz/) across six modular `.7z` packages (~17,000 textures).
* Fully converted to Microsoft DirectX **BC7 DDS** for GPU prefetching.
* *Identified Issues:* Community feedback noted that Fina suffered from color distortion in-game: her hands appeared abnormally dark and sunburned, and her front bangs were rendered in an oversaturated caramel tone that clashed with her blonde crown.
* *Distribution Scope:* Distributed exclusively in BC7 DDS format; source PNGs were not released.

### **Version 0.2.0 — Character Calibration & Source Release (October 2026)**
* Complete visual calibration and color-space restoration for key party members and weapons.
* Resolves all reported issues with Fina's skin tone, hair, and costume.
* Restores missing specular highlights, metal wrap, and dynamic range to Aika's and Vyse's starting weapons.
* Corrects Dolphin DDS mipmap pipeline (`-m 1` on non-mipmapped surfaces).
* **First-Ever Public Release of Source PNG Packs:** Distributes raw 4x master PNGs and 1x native SD companion archives.
* **GitHub Migration:** Project tracking, issue reports, and source releases transitioned to GitHub.

---

## What's New in Version 0.2.0

* **Fina Skin Tone & Hand Correction:**
  * Fixed an issue where Fina's hands rendered with an unnatural dark, sunburned/tanned tint compared to her pale face and shoulders.
  * Rebalanced hand texture (`9b60b97d998b8fe3`) to a soft, living porcelain flesh tone matching her shoulders and chest.
* **Fina Hair Color Calibration:**
  * Eliminated severe two-tone contrast where Fina's front bangs rendered in dark caramel/amber while her crown was light creamy blonde.
  * Re-calibrated across all 12 hair texture hashes (covering battle, village cutscenes, sailing models, and the Pirate Isle dining sequence) with a balanced warm golden-blonde palette matching in-game crown lighting without bleaching.
* **Fina Sleeve & Costume Brightness:**
  * Replaced murky grey and yellowed shadow artifacts on Fina's flared sleeves and upper arm band (`b9f42d7a04cc65dd`) with clean, luminous silk-white matching her dress.
* **Aika Boomerang Handle Restoration:**
  * Resolved a critical bug where Aika's starting Boomerang handle rendered as a solid "pitch-black blob" in-game.
  * Reconstructed handle textures (`afc1f5d226e142c9` / `m_ad27b8959e0382cd`) by transferring original 1x specular amber highlights and warm lighting curves, combined with high-definition 4x pebbled leather grain and sharp silver rivets.
* **Vyse Twin Cutlasses Restoration:**
  * Fixed flat, dull visuals on Vyse's starting twin weapons inherited from legacy forum upscales:
    * **Hilt (`51fdd4ba8ab2addb`):** Restored the missing polished silver/steel handle wrap (which had been mistakenly painted over with flat dark wood), enhanced wire grip metallic shine, and enriched warm wood grain.
    * **Blade (`m_53338d40995df82b`):** Restored glowing blue-white specular cutting edge sheens and bright glints on all silver blade studs.
* **Dolphin DDS Mipmap Fix:**
  * Corrected mipmap level generation across the DDS pack: non-mipmapped surfaces now use strict single-mip flags (`-m 1`) to prevent Dolphin from rejecting replacement textures, while true mipmapped textures (`_m_`) retain full mip chains (`-m 0`).

---

## Upscale & Curation Methodology

Every asset in this pack undergoes a specialized, multi-stage restoration workflow rather than automated batch processing:
* **Character Faces:** Upscaled using Topaz Gigapixel AI generative models (`Redefine` 2x followed by `High fidelity` 2x), followed by careful manual airbrushing in Photoshop to eliminate artifacts and preserve authentic facial expressions.
* **Character Clothing & Costumes:** Upscaled using Topaz Gigapixel AI (`High fidelity` 4x) with manual localized detail recovery and fabric tone matching.
* **Weapons & Props:** Hybrid detail reconstruction combining native GameCube specular maps with 4x micro-surface grain.
* **UI Elements:** Recreated and redrawn from scratch for pixel-perfect sharpness.

---

## Installation Guide (Dolphin Emulator)

### Step 1: Open Dolphin's Texture Directory
Navigate to your Dolphin user directory:
```text
<Dolphin Directory>/Load/Textures/
```
* **Windows Typical Path:** `C:\Users\<YourUsername>\Documents\Dolphin Emulator\Load\Textures\`
* **macOS Typical Path:** `~/Library/Application Support/Dolphin/Load/Textures/`
* **Linux Typical Path:** `~/.local/share/dolphin-emu/Load/Textures/`

### Step 2: Install the Pack
* Create a folder named **`GEA`** (the master GameCube ID for *Skies of Arcadia Legends*).
  * *Note:* If you are playing the PAL European release, you may also name or link the folder as `GEAP8P`; for Japanese, use `GEAJ8P`. Modern Dolphin builds recognize `GEA` universally across regions.
* Copy the contents of your chosen pack (e.g. `Characters`) into that folder:
  ```text
  Load/Textures/GEA/Characters/...
  ```

---

## Recommended Dolphin Graphics Settings

To get the most out of these textures with optimal performance:

1. **Enable Custom Textures:**
   * In Dolphin, go to **Options → Graphics Settings → Advanced**.
   * Under the **Utility** section, check **Load Custom Textures**.
   * *(Crucial for DDS)* Check **Prefetch Custom Textures**. Because BC7 DDS files are pre-compressed for GPU memory, prefetching loads them smoothly on launch without consuming excessive system RAM, completely eliminating in-game stutter.
2. **Recommended Enhancements:**
   * **Backend:** Vulkan or Direct3D 12
   * **Internal Resolution:** 3x (1080p) or 4x (1440p)
   * **Anisotropic Filtering:** 8x or 16x

---

## Known Limitations & Roadmap

1. **Enemy UI Names:**
   * Enemy UI nameplate assets are present in these archives, but only a portion are currently updated to HD quality. Updating and redrawing all remaining enemy UI nameplates is planned as the final milestone of the Character category.
2. **Coverage & Missing Assets:**
   * A small number of obscure character/bounty variants, background NPC assets, or rare cutscene models may not yet be covered in v0.2.0. These will be added incrementally as further environment and area decompilations are completed.

---

## Contributing & Bug Reports

Community feedback and contributions are welcome:
* **Bug Reports:** If you spot an untextured character, a misaligned hash, or a visual lighting artifact, please open an [Issue on GitHub](https://github.com/Shoopkid/skies-of-arcadia-legends-hd/issues) with a screenshot and the relevant texture hash (e.g. `tex1_128x128_...`).
* **Pull Requests:** Improved upscales or missing hash mappings are welcome via GitHub pull requests.

---

## Legal Disclaimer & Licensing

* **Intellectual Property:** *Skies of Arcadia* and *Skies of Arcadia Legends* are registered trademarks and copyright of **SEGA Corporation** and **Overworks**. This is an unofficial, non-commercial fan preservation project not affiliated with or endorsed by SEGA.
* **No Game ISOs:** No copyrighted game ROMs, disc images, or retail executables are included in this repository.
* **Mod License:** Community texture edits, upscaled source files, and scripts are licensed under [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International](LICENSE) (CC BY-NC-ND 4.0).

---

## Credits & Appreciation

* **SEGA & Overworks:** For creating *Skies of Arcadia*, one of the greatest RPGs ever made.
* **BigHead & FrozenWings:** For initiating the original Dolphin HD texture project and contributing foundational upscaled assets.
* **Shoopkid:** Project curation, color-space & specular restorations, native ISO asset extraction, Topaz AI processing, and BC7 DDS conversion.
* **Dolphin Emulator Development Team:** For the industry-leading GameCube/Wii emulation platform and custom texture engine.
* **The Skies of Arcadia Community:** For keeping the skies alive.
