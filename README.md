# Starlink - 60 FPS Mod - Switch

Surprised to see that nobody made this for our Starfox crew. Since you only get the Starfox storyline from the Switch version.
<br/>Trying to play this at an unstable 30fps is such an eyesore, so I made this mod for emulators and the console.

## Requirements
- Base Game
- Game update 1.0.6
- Switch Emulator Ryujinx <ins>or</ins> Modded Switch Console

### Notes
- Ryujinx stutters and crashes randomly, most often while in space flying between planets, but the game autosaves after each objective
- Yuzu/Suyu has tons of rendering issues & randomly crashes, don't recommend
- Switch Console overclocking will destroy your battery power, stay on official charger while playing

# Install Ryujinx
(Tested on Ryujinx 1.3.1 / Canary 1.3.37)
1. Download & Install Ryujinx: https://github.com/Ryubing/Stable-Releases/releases
2. After firmware/keys setup, right-click the game, Manage Title Updates and add update version 1.0.6
3. Download and Unzip my mod for Ryujinx
4. Right-click Game > Manage Mods > Select the unziped folder 
<br/>   `..\Ryujinx\mods\contents\01002cc003fe6000\60FPS (1.0.6) Shadsterwolf`
5. (Recommended) Right-click Game > Create Custom Configuration > CPU tab > Uncheck the box "PPTC"
6. (Recommended) Right-click Game > Create Custom Configuration > CPU tab > Change CPU Mode to "Host (Fast)"

# Install Switch
<sub>(Tested on 18.0.0 Firmware, Atmosphere 1.8.0, Hekate 6.2.2)</sub>
1. Use SD card reader or FTPD
3. Drag and drop Atmosphere folder on root of SD card
<br/>   `S:\atmosphere\exefs_patches\60fpsStarlink`
