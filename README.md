# retroarch-thumbnail-cleaner
A simple bash script to remove unused thumbnails in RetroArch 🎮️

---
# Usage
In Linux terminal, navigate to the directory that the script is saved. Then:
```
./retroarch-thumbnail-cleaner.sh "<RetroArch's main directory>"
```
For example, RetroArch (Flatpak) on my machine:
```
./retroarch_thumbnail-cleaner.sh "/home/archerallstars/.var/app/org.libretro.RetroArch/config/retroarch"
```
Depending on the size of the playlists, it might take a while to list all unused thumbnails.

---
# Features
- Works with [special characters](https://docs.libretro.com/guides/roms-playlists-thumbnails/#thumbnail-paths-and-filenames).
- Supports all [3 types](https://docs.libretro.com/guides/roms-playlists-thumbnails/#thumbnail-paths-and-filenames) of RetroArch's thumbnail detection (ROM file name, playlist label, short name).
- List unused thumbnails.
- Removal confirmation.

---
# Why
There's a tool for this available on Windows, [Delete-RetroArch-Unneeded-Thumbnails](https://github.com/maforget/Delete-RetroArch-Unneeded-Thumbnails). But it's not on Linux. So, I made this!

