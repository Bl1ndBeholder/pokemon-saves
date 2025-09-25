# Pokémon Save Collection

A public archive of Pokémon save files across Generations I–VII — free for anyone to download and use.  
Useful for: accessing version exclusives, completing trade evolutions, testing, or skipping replay grind.

---

## Quick usage

### GBA / DS (Gen I–V)
1. Pick a save file (files are timestamped `DDMMYYYYHHMM.sav`).  
2. Rename it to match your ROM filename (keep the `.sav` extension).  
   - Example: `Pokemon-Emerald.gba` → `Pokemon-Emerald.sav`  
3. Place it in your emulator’s save folder.  
   - Most emulators (mGBA, DeSmuME, melonDS) default to the ROM folder.  

### 3DS (Gen VI–VII)
- Saves are always called **`main`** (no extension).  
- Intended for the **Azahar** emulator.  

To use in Azahar:
1. Start the game once to generate its save directory.  
2. Replace the generated `main` file with the downloaded one.  

On real hardware:  
With a homebrewed 3DS and [Checkpoint](https://github.com/FlagBrew/Checkpoint), you can restore these `main` saves to physical cartridges or digital titles.

---

## Repository structure

Top-level game folders include (non-exhaustive):  
`alpha-sapphire/`, `colosseum/`, `crystal/`, `emerald/`, `fire-red/`, `moon/`,  
`omega-ruby/`, `red/`, `ruby/`, `sun/`, `ultra-moon/`, `ultra-sun/`,  
`white/`, `x/`, `xd-gale-of-darkness/`, `y/`.

**My saves** live directly under each game folder, named with a timestamp:  
pokemon-saves/emerald/DDMMYYYYHHMM.sav


**Contributor saves** must go inside a subdirectory named after your GitHub username:  
pokemon-saves/emerald/joebloggs/DDMMYYYYHHMM.sav


---

## Contributing

- Add your saves under your GitHub username folder (see above).  
- Useful checkpoints are encouraged (e.g. before legendaries, Elite Four, trade evolutions).  
- Open a pull request with a short note describing your save.  

---

### ⚠️ Disclaimer
Save files may contain in-game personal data (player name, playtime, link codes).  
Treat these as public backups. Use responsibly and respect original game copyrights.
If submitting save files - it is recommended to not use your own name on your save.
