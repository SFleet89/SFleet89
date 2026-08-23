# Hi, I'm SFleet89 👋

I build practical tools that make tedious, repeatable work safe and reviewable — Python automation and offline single-page web apps. The common thread: **dry-run and offline-first by default** — nothing moves, renames, tags, or leaves your machine without your say-so.

---

## 🎮 Game tools

### [the-tower-unified-tools](https://github.com/SFleet89/the-tower-unified-tools)
A free, **offline, all-in-one companion** for *The Tower – Idle Tower Defense*. One HTML page you open in your browser — no install, no server, no account, and nothing ever leaves your device. Load your `playerInfo.dat` save and it auto-fills every tab.

Lab / UW / Workshop cost calculators · a Farm Run Tracker with analytics · an Income Planner · a **Waves ↔ Hours** farm clock · modules, bots, cards, guardian, relics, perks, and milestones. Values are ported from the game's own data and cross-checked, and the wave-rate model is verified against real save runs — all guarded by a JS regression-test harness.

---

## 🎵 Music tools

### [music-tools](https://github.com/SFleet89/music-tools)
A growing suite of utilities for organising, cleaning, and tagging a music library — with a PySide6 desktop GUI in active development.

**Organisation**
Sort multi-disc albums into CD subfolders · Sort loose albums into artist folders · Sort flat files by artist tag · Move non-music files out of album folders

**Renaming**
Rename album folders by tag · Rename files using a FileBot-style template · Rename to catalogue number format · Fix CD subfolder naming · Undo any rename from a saved report

**Scanning & Fixing**
Flag messy filenames and track cleanup progress · Fix double spaces in filenames · Move featuring credits from Artist tag to Title tag · Scan for missing tags, unreadable files, and encoding issues

**Duplicate Detection**
Compare unsorted downloads against the library using fuzzy matching, metadata, and audio fingerprinting · Find the same track duplicated across multiple artist folders · Full undo support for every move

**MusicBrainz Lookup & Tagging**
Batch look up releases by catalogue number (Anjunabeats, Tiësto / Black Hole, or any label) · Auto-tag files from confirmed lookup results · Undo tags from a backup report · Move folders based on a processed report

**Utilities**
Split a single-file FLAC + CUE sheet into individual tracks · Run multiple tools in sequence as a pipeline · Repair broken paths in .m3u/.m3u8 playlists

### [music-duplicate-finder](https://github.com/SFleet89/music-duplicate-finder)
The original standalone duplicate finder — compare an unsorted collection against an organised library with fuzzy matching, audio fingerprinting, dry-run preview, and full undo support.

---

## 🛠 Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PySide6](https://img.shields.io/badge/PySide6-41CD52?style=flat&logo=qt&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

**Libraries:** `mutagen` · `rapidfuzz` · `tqdm` · `Chromaprint (fpcalc)` · `MusicBrainz API`

---

## 📚 Currently learning

Desktop application development with PySide6 (Qt) · Cybersecurity

---

*Everything I build is dry-run / offline by default — nothing moves, renames, tags, or uploads without your confirmation.*
