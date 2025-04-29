# Starlink : Battle for Atlas - 60 FPS Mod - Switch

Surprised to see that nobody made this for our Starfox crew. Since you only get the Starfox storyline from the Switch version.
<br/>Trying to play this at an unstable 30fps is such an eyesore, so I made this mod for emulators and the console.

## Requirements
- Base Game
- Game update 1.0.6
- Switch Emulator Ryujinx <ins>or</ins> Modded Switch Console
- (Recommended) All DLC packs

### Notes
- Ryujinx sometimes stutters and crashes randomly, but game autosaves after every objective
- Yuzu/Suyu has tons of rendering issues & randomly crashes, not recommended
- Switch Console overclocking will destroy your battery, stay on official charger while playing

# Install Ryujinx
<sub>(Tested on Ryujinx 1.3.1 / Canary 1.3.37)</sub>
1. Download & Install Ryujinx: https://github.com/Ryubing/Stable-Releases/releases
2. After firmware/keys setup, Right-click Game, Manage Title Updates > Add > Select version 1.0.6
3. Download and Unzip my mod for Ryujinx
4. Right-click Game > Manage Mods > Select the unziped folder 
<br/>   `..\Ryujinx\mods\contents\01002cc003fe6000\60FPS (1.0.6) Shadsterwolf`
5. (Recommended) Right-click Game > Create Custom Configuration > CPU tab > Uncheck the box "PPTC"
<br/>  _(Removes caching issues for this game)_
7. (Recommended) Right-click Game > Create Custom Configuration > CPU tab > Change CPU Mode to "Host (Fast)"
<br/>  _(Reduces stuttering and crashing)_

# Install Modded Switch
<sub>(Tested on first gen Switch, 18.0.0 Firmware, Atmosphere 1.8.0, Hekate 6.2.2)</sub>
1. Drag and drop 'atmosphere' folder on root of SD card
<br/>   `S:\atmosphere\exefs_patches\60fpsStarlink`
2. Download & Add to SD card - Sys-Clk: https://github.com/retronx-team/sys-clk/releases
<br/>  _(Overclock sysmodule, Needed to reach higher than 30fps)_
4. Download & Add to SD card - ReverseNX-Tool: https://github.com/masagrator/ReverseNX-Tool/releases
<br/>  _(Handheld/Docked override, Needed to reach 60fps)_
6. (Optional) Download & Add to SD card - Tesla-Menu: https://github.com/WerWolv/Tesla-Menu/releases 
<br/>  _(Overlay menu sysmodule core, convenient to have)_
7. (Optional) Download & Add to SD card - ReverseNX-RT: https://github.com/masagrator/ReverseNX-RT/releases
<br/>  _(Overlay menu for ReverseNX, can toggle handheld/docked while in game)_
9. (Optional) Download & Add to SD card - Status-Monitor-Overlay: https://github.com/masagrator/Status-Monitor-Overlay/releases
<br/>  _(Overlay menu for clock speed status & FPS)_
11. (Optional) Download & Add to SD card - Salty-NX: https://github.com/masagrator/SaltyNX/releases/tag/1.1.1
<br/>  _(Background process to support overlay menus & FPS monitor)_
