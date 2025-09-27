# Pokémon Saves Backup 📂

A collection of Pokémon save files across multiple generations.  

These saves are provided so players can:  
- Access version-exclusive Pokémon.  
- Skip trade evolutions.  
- Jump to key checkpoints (before legendaries, gyms, or the Elite Four).  

All saves in this repo are stored as **`.sav` backups**.  
👉 You may need to **rename them** depending on the emulator or hardware you’re using.

---

## 🎮 Recommended Emulators

| Platform          | Emulator   | Link |
|-------------------|------------|------|
| Game Boy / Color / Advance | **mGBA** | [https://mgba.io](https://mgba.io) |
| Nintendo DS       | **melonDS** | [https://melonds.kuribo64.net](https://melonds.kuribo64.net) |
| Nintendo 3DS      | **Azahar** | [https://github.com/AzaharEmu/Azahar](https://github.com/AzaharEmu/Azahar) |
| Nintendo GameCube | **Dolphin** | [https://dolphin-emu.org](https://dolphin-emu.org) |

---

## 📥 How to Use These Saves

### In Emulators

#### Game Boy / GBC / GBA (mGBA)
1. Download a save from this repo (`.sav / .gci / *`).
2. please note 3ds save files are called "main". the archived saves are named "ddmmyyyyhhmm".  
3. Rename the file to match your ROM’s name (e.g., `Pokemon-Emerald.sav`).  
4. Place it in the same folder as your ROM.  
5. mGBA will automatically load the save.  

---

#### Nintendo DS (melonDS)
1. Download a `.sav` file.  
2. Rename it to match your ROM name (e.g., `Pokemon-Black.sav`).  
3. Place it in the same folder as your ROM.  
4. melonDS will load the save automatically.  

---

#### Nintendo 3DS (Azahar)
1. Launch the game once in Azahar to generate a save file.  
2. Right-click the game in Azahar and choose **Open Save Location**.  
3. Delete the existing `main` file.  
4. Download a `ddmmyyyyhhmm` file from this repo and rename it to `main` (no extension).  
5. Place it in the folder you just opened, replacing the existing "main".  
6. Restart the game in Azahar — your save should load.  

---

#### Nintendo GameCube (Dolphin)
1. Run the game once in Dolphin to generate a memory card save file.  
2. Download the `.gci` from this repo.  
3. Rename it to match Dolphin’s `.gci` format (e.g., `01-GC6E-pokemon_colosseum.gci`).  
   - Tip: check inside Dolphin’s memory card folder to see the correct filename.  
4. Place it in your `User/GC/USA/Card A/` folder (or equivalent).  
5. Launch the game in Dolphin — your save will appear.  

---

### On Real Hardware

#### Game Boy / GBC / GBA
- Requires a **cartridge reader/writer** (like GBxCart RW) or a **DS flash cart**.  
1. Copy the `.sav` file to your PC.  
2. Use the hardware’s software to flash it to your physical cartridge.  

---

#### Nintendo DS
Two main methods:  

- **Checkpoint (via homebrewed 3DS):**  
  1. Place the `.sav` on your SD card under `/3ds/Checkpoint/saves/<TitleID>/`.  
  2. Use Checkpoint to **Restore Save** onto your DS cart.  

- **DS Flash Cart:**  
  1. Use the flash cart’s save manager to inject the `.sav`.  
  2. Start the game on your DS — the save will load.  

---

#### Nintendo 3DS
- **Checkpoint (homebrewed 3DS only):**  
  1. Copy the save file from this repo.  
  2. Rename it to `main`.  
  3. Place it inside `/3ds/Checkpoint/saves/<TitleID>/`.  
  4. Use Checkpoint’s **Restore Save** option to inject it back into the cart or digital copy.  

---

#### Nintendo GameCube
- Requires a **homebrewed Wii with GCMM (GameCube Memory Manager)**.  
1. Place the `.gci` file on your SD card under `/MCBACKUP/`.  
2. Run GCMM on your Wii/GameCube.  
3. Restore the save to your physical memory card.  

---

## ⚠️ Disclaimer
These saves are provided **for preservation and personal use only**.  
Do not use them for cheating in online battles or competitions.  
