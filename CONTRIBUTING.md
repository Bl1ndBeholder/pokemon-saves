Pokémon Save Collection

A public archive of Pokémon save files across Generations I–VII — free for anyone to download and use.
Useful for: accessing version exclusives, completing trade evolutions, testing, or skipping replay grind.

All saves in this repository are backed up with a .sav prefix for consistency.

Quick reference
Platform	Emulator / Usage	File from repo	Rename / Place in
GBA / DS	mGBA, DeSmuME, melonDS	DDMMYYYYHHMM.sav	Match ROM name, keep .sav
3DS	Azahar / Checkpoint	DDMMYYYYHHMM.sav	Rename to main (no extension)
GameCube	Dolphin	DDMMYYYYHHMM.sav	Rename to .gci using the correct Dolphin-generated filename. Example: 01-GC6E-pokemon_colosseum.gci. Tip: Start the game in Dolphin first to generate the save folder and filename for your game version.

Note: All saves in this repo are .sav.

3DS saves → rename to main (no extension).

GameCube saves → rename to .gci to match Dolphin's generated filename for your version.

Quick usage
GBA / DS (Gen I–V)

Pick a save file.

Rename it to match your ROM filename (keep .sav).

Place it in your emulator’s save folder.

3DS (Gen VI–VII)

Start the game once in Azahar to generate the save folder.

Replace the generated main file with the downloaded one.

On real hardware:
With a homebrewed 3DS and Checkpoint
, you can restore these main saves to physical cartridges or digital titles.

GameCube (XD: Gale of Darkness & Colosseum)

Start the game once in Dolphin to generate the save folder and filename.

Copy the .sav file from this repo and rename it to match Dolphin’s generated filename with .gci.

Example: 01-GC6E-pokemon_colosseum.gci for Colosseum.

Place the renamed .gci in the Dolphin save folder:

Dolphin Emulator/GC/Saves/<GameID>/

Repository structure

Top-level game folders include (non-exhaustive):
alpha-sapphire/, colosseum/, crystal/, emerald/, fire-red/, moon/,
omega-ruby/, red/, ruby/, sun/, ultra-moon/, ultra-sun/,
white/, x/, xd-gale-of-darkness/, y/.

Author saves live directly under each game folder, named with a timestamp:

pokemon-saves/emerald/DDMMYYYYHHMM.sav


GameCube saves .sav → rename to .gci in Dolphin.

3DS saves → rename to main (no extension).

Contributor saves must go inside a subdirectory named after your GitHub username:

pokemon-saves/emerald/joebloggs/DDMMYYYYHHMM.sav
pokemon-saves/xd-gale-of-darkness/joebloggs/DDMMYYYYHHMM.gci
pokemon-saves/omega-ruby/joebloggs/main

Contributing

Add your saves under your GitHub username folder (see above).

Useful checkpoints are encouraged (e.g. before legendaries, Elite Four, trade evolutions).

Open a pull request with a short note describing your save.

⚠️ Disclaimer

Save files may contain in-game personal data (player name, playtime, link codes).
Treat these as public backups. Use responsibly and respect original game copyrights.
ChatGPT said:

Nice — thanks for pasting your README.md. Since your script now keeps the original file type automatically, you no longer need to tell users to rename .sav → .gci or .sav → main.

Here’s an updated version that reflects the new behavior:

Pokémon Save Collection

A public archive of Pokémon save files across Generations I–VII — free for anyone to download and use.
Useful for: accessing version exclusives, completing trade evolutions, testing, or skipping replay grind.

All saves in this repository are backed up with their native save type for accuracy.

Quick reference
Platform	Emulator / Usage	File from repo	Placement / Notes
GB / GBC / GBA / DS	mGBA, DeSmuME, melonDS	DDMMYYYYHHMM.sav	Rename to match ROM name (keep .sav).
3DS	Azahar / Checkpoint	DDMMYYYYHHMM (no extension)	Replace the generated main file.
GameCube	Dolphin	DDMMYYYYHHMM.gci	Place in Dolphin’s memory card folder. Must match the Dolphin-generated filename (e.g. 01-GC6E-pokemon_colosseum.gci).
Quick usage
GBA / DS (Gen I–V)

Pick a save file from the repo.

Rename it to match your ROM filename (keep .sav).

Place it in your emulator’s save folder.

3DS (Gen VI–VII)

Start the game once in Azahar (or on hardware with Checkpoint) to generate the save folder.

Replace the generated main file with the downloaded one (DDMMYYYYHHMM, no extension).

On real hardware:
With a homebrewed 3DS and Checkpoint, you can restore these saves to physical cartridges or digital titles.

GameCube (Colosseum / XD: Gale of Darkness)

Start the game once in Dolphin to generate the save folder and correct .gci filename.

Copy the save file from this repo (DDMMYYYYHHMM.gci).

Rename it to match Dolphin’s generated filename (example: 01-GC6E-pokemon_colosseum.gci).

Place it in Dolphin’s memory card folder:

Dolphin Emulator/GC/Saves/<GameID>/

Repository structure

Top-level game folders include (non-exhaustive):
alpha-sapphire/, colosseum/, crystal/, emerald/, fire-red/, moon/,
omega-ruby/, red/, ruby/, sun/, ultra-moon/, ultra-sun/,
white/, x/, xd-gale-of-darkness/, y/.

Author saves live directly under each game folder, named with a timestamp:

pokemon-saves/emerald/DDMMYYYYHHMM.sav
pokemon-saves/xd-gale-of-darkness/DDMMYYYYHHMM.gci
pokemon-saves/omega-ruby/DDMMYYYYHHMM


Contributor saves must go inside a subdirectory named after your GitHub username:

pokemon-saves/emerald/joebloggs/DDMMYYYYHHMM.sav
pokemon-saves/xd-gale-of-darkness/joebloggs/DDMMYYYYHHMM.gci
pokemon-saves/omega-ruby/joebloggs/DDMMYYYYHHMM
