# Contributing to Pokémon Save Collection

Thank you for wanting to contribute!  
This guide explains how to:

* Dump save files from emulators or physical hardware.
* Submit them to the repository.

> **Before you start:**
>
> * Only contribute your **own save files**.
> * Make sure **Git is installed** (instructions below).
> * Have access to your game saves via emulator or hardware.
> * Submitted saves **must be legitimate**: no cheats, edited saves, or ROM hacks.

---

## 1. How the files work

All saves in this repository are backed up in their **native format**:

* **GB / GBC / GBA / DS:** `.sav`
* **3DS:** no extension (file is always `main`)
* **GameCube:** `.gci`

Each file is timestamped when backed up:

* Format: `DDMMYYYYHHMM`
* Example: `270920251834.sav`

### Platform Reference

| Platform | Backup in repo          | Name to use in emulator                   | Example                         | Emulator / Tool |
| -------- | ----------------------- | ----------------------------------------- | ------------------------------- | --------------- |
| GB / DS  | `DDMMYYYYHHMM.sav`      | Keep `.sav` and match ROM filename        | `Pokemon-Emerald.sav`           | mGBA, melonDS   |
| 3DS      | `DDMMYYYYHHMM` (no ext) | `main` (no extension)                     | `main`                          | Azahar          |
| GameCube | `DDMMYYYYHHMM.gci`      | Rename to `.gci` using Dolphin’s filename | `01-GC6E-pokemon_colosseum.gci` | Dolphin         |

---

## 2. Dumping save files from physical hardware

### 3DS

**Recommended:** Use **Checkpoint** on a homebrewed 3DS.

1. Insert your 3DS cartridge.
2. Open Checkpoint and select **Dump Save**.
3. The save will be written to your SD card at:

```
/3ds/Checkpoint/saves/<TitleID>/
```

* `<TitleID>` example: `00040000001A2C00`
* The save file is called `main` (no extension).

4. Copy `main` to your computer.

---

### Nintendo DS

**Recommended:** Use a 3DS with Checkpoint if available (see above).

**Alternative (if no 3DS is available):** Use a **DS Flashcart** (R4, Acekard, DSTT) with save dumping software.

**Example software for DS Flashcarts:**

* **R4 / R4i:** R4i Save Manager
* **Acekard:** Acekard Save Tool
* **DSTT:** DSTT Save Manager

Steps:

1. Insert the DS cartridge into the Flashcart.
2. Open the save dumping software on the Flashcart.
3. Dump the save to `.sav` format.
4. Copy the `.sav` file to your computer.

---

### Game Boy Advance

If you have a GBA cartridge and a **DS flashcart that supports GBA**:

1. Insert the GBA cartridge into the flashcart.
2. Use the Flashcart’s GBA save dumping software (e.g., **GBA Backup Tool** or **R4i Save Manager**).
3. Dump the save as `.sav`.
4. Copy it to your computer.

---

### Game Boy / Game Boy Color

1. Use a **GB cartridge reader** (e.g., GBxCart RW).
2. Use the software to read the save and save it as `.sav` on your computer.

---

### GameCube

There are two common ways to get a GameCube save:

**1. Using Dolphin emulator (recommended if you have a digital backup):**

1. Run the game once in **Dolphin** to generate a save folder.
2. Copy the `.gci` backup from the repository and rename it to match Dolphin’s `.gci` filename.

**2. Copying a save from a Wii console to an SD card:**

1. Insert the GameCube memory card into your Wii.
2. Go to **Wii System Menu → Data Management → Save Data → GameCube**.
3. Find your game save and **copy it to an SD card**.

   * SD card must be FAT16/FAT32.
4. Insert the SD card into your computer.
5. Rename the save to `.gci` format for Dolphin (example: `01-GC6E-pokemon_colosseum.gci`).

---

## 3. Installing Git

### Windows

1. Download Git: [https://git-scm.com/download/win](https://git-scm.com/download/win)
2. Run installer (keep default options).
3. Open **Git Bash** and type:

```bash
git --version
```

### MacOS

1. Open Terminal.
2. Type:

```bash
git --version
```

3. If Git is missing, follow prompts to install Xcode Command Line Tools.

### Linux

Use your package manager:

**Ubuntu / Debian:**

```bash
sudo apt update
sudo apt install git
```

**Fedora:**

```bash
sudo dnf install git
```

**Arch:**

```bash
sudo pacman -S git
```

**OpenSUSE:**

```bash
sudo zypper in git
```

**Void:**

```bash
sudo xbps-install -S git
```

Verify installation:

```bash
git --version
```

---

## 4. Organizing your save for this repo

Inside the correct game folder, create a folder with your GitHub username and place your saves there.  

Use the **native format**:

* GB/GBC/GBA/NDS → `.sav`
* 3DS → `main` (no extension)
* GameCube → `.gci`

Example folder structure using a local backup:

```
~/Documents/Pokemon/save-backup/emerald/joebloggs/DDMMYYYYHHMM.sav
~/Documents/Pokemon/save-backup/xd-gale-of-darkness/joebloggs/DDMMYYYYHHMM.gci
~/Documents/Pokemon/save-backup/omega-ruby/joebloggs/DDMMYYYYHHMM    <- 3DS backup (main)
```

> **Important:** Do not upload renamed emulator-specific files.  
> Only contribute raw backups in their native format as shown above.

---

## 5. Submitting your save (GitHub Pull Request)

1. **Clone the repository**

```bash
git clone https://github.com/Bl1ndBeholder/pokemon-saves.git
cd pokemon-saves
```

2. **Add your save files**

* Create a folder with your GitHub username in the correct game folder.
* Copy your save files there.

3. **Commit changes**
  
```bash
git add .
git commit -m "<current gamestate>"
example: git commit -m "before the second gym"
```
4. **Push changes**

```bash
git push origin main
```

> Recommended: create a branch first:

```bash
git checkout -b add-my-saves
git push origin add-my-saves
```

5. **Open a Pull Request**

* Go to your fork on GitHub.
* Click **Compare & pull request**.
* Add a short description (e.g., “Added Emerald save by joebloggs before Elite Four”).
* Submit the PR.

---

## 6. Tips for beginners

* Only include your **own saves**.
* Do **not** include any personal information in your save files (e.g., names, friend codes, or other identifiers).
* No ROM Files — only submit **save file data**.
* Submitted saves **must be legitimate**: no cheats, edited saves, or ROM hacks.
* Useful checkpoints: before legendaries, trade evolutions, or Elite Four.
* Double-check that your save works in an emulator.
* Follow folder/naming rules carefully — PRs not following them may be rejected.
