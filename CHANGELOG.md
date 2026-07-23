# Changelog

## v1.0.5 — WW2 Mode Picker, Half-Life & Steam Scan

- Added **Counter-Strike WW2** — new game with Google Drive download. Includes an in-launcher mode picker (Normal, Team Death Match, Nazi Zombies, Dogfight Mode, Nazi Zombie: Escape) and graphics selector (Normal / High). Mode switching replicates the original `CS-Launcher.bat` config-file swap logic without opening a command window.
- Added **Half-Life** — downloads the official installer from the launcher via Google Drive and launches it automatically. Use the Locate button afterward to register your installation.
- Updated Counter-Strike Online download link to a new MEGA address.
- Steam scan (`Settings → Scan Steam / Valve`) now checks all subfolders of `C:\Program Files (x86)\Steam\steamapps\common` (and other library paths from the registry) and auto-registers found Valve games.
- New game thumbnail images for Half-Life, Blue Shift, Decay, Opposing Force, Operation Black Mesa, and HellStrike are now auto-matched when those games are added or located.
- Fixed the three-dot (⋯) context menu sometimes appearing off-screen or in the wrong position on game cards.
- Right-clicking an installed game card now opens the same context menu as the three-dot button.

Download the installer and machine-readable checksum metadata from the [v1.0.5 release](https://github.com/AniketSpecter/Counter-Strike-Master-Collection/releases/tag/v1.0.5).

## v1.0.4 — Remote Library Release

- Converted the collection to a lightweight on-demand game launcher.
- Added resumable Google Drive and MEGA downloads with pause, resume, cancel, speed, ETA, transferred bytes, and percentage.
- Added automatic `.7z` verification, extraction, installation-state persistence, repair, move, locate, and uninstall operations.
- Added selectable game libraries and download-cache locations with a recommended `C:\Program Files (x86)\CSMC` default.
- Added support for existing Valve games and mods plus customizable launch executables.
- Configured Counter-Strike Xtreme V7 Beta and Final to prefer `CS-Extreme.exe`.
- Added a Steam-style Downloads page with queue state and sidebar progress.
- Added ten persistent themes, including Cyberpunk and Anime Neon.
- Improved runtime detection and added a permanent reminder opt-out.
- Added launcher preferences for minimize, restore, system information, updates, runtimes, playtime, and online launch targets.
- Added per-game and total playtime tracking.
- Added CSMC window, taskbar, titlebar, shortcut, and installer branding.
- Added Discord, YouTube, update notifications, patch notes, and community messages.
- Added a compact playable Valve Games Evolution mini-player and fixed YouTube Error 153 in Electron.
- Fixed archives containing a wrapper folder, shortcut synchronization, thumbnail re-detection, and transient network retry behavior.

Download the installer and machine-readable checksum metadata from the [v1.0.4 release](https://github.com/AniketSpecter/Counter-Strike-Master-Collection/releases/tag/v1.0.4).
