# pewter - tarnished chrome
Pewter is a bundle of an old copy of Chrome Development and an older copy of Adobe Flash Player.  
They're the latest versions that can still view legacy Flash content on the web after Flash's EOL.  
**Be warned that this browser is old and insecure due to Flash usage!**  
**Please use a modern browser for all other purposes!**  
If you'd like to get straight to the downloads, click [here](https://github.com/redbrain/pewter/releases/latest).  
Releases are currently only available for Windows; Mac and Linux builds are coming soon.
## technical info
Pewter uses a Chromium build from the last stable version of v87 (before Flash was completely removed).  
The source of that build is [here](https://commondatastorage.googleapis.com/chromium-browser-snapshots/index.html?prefix=Win_x64/812845/).  
It's bundled with Flash Player 32.0.0.371 the last version before Adobe's 2021 "time bomb" was added.  
That was found in the Internet Archive [here](https://web.archive.org/web/20200524075102/https://fpdownload.adobe.com/pub/flashplayer/pdc/32.0.0.371/install_flash_player_ppapi.exe).  
I plan to switch this to an open SWF player, such as Lightspark, once it's ready for production use.  
For Windows, the appropriate CLI args are given in a batch file, and the installer is created with 7-Zip.
