1. Spotify Installer

https://upgrade.scdn.co/upgrade/client/win32-x86/spotify_installer-1.1.73.517.gbef50fdb-23.exe

2. Script 

```ps1
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; (iwr -useb 'https://raw.githubusercontent.com/wellvibes/SpotX/main/Install.ps1').Content | iex
```

3. Config

```ps1
╔══════════════════════════════╗
║ Welcome to SpotX for Windows ║
╚══════════════════════════════╝

Your Spotify 1.1.73.517 version is outdated, it is recommended to upgrade to 1.2.1.968
Want to update ? [Y/N]: N

Do you want to disable podcasts, episodes and audiobooks from the main page? [Y/N]: Y

Want to block Spotify updates? [Y/N]
It is recommended to block because Spotify was downgraded: Y

Want to set up automatic cache cleanup? [Y/N]: Y

Cache older: XX days to be cleared
Enter the number of days from 1 to 100: 1

Patching Spotify...

Didn't find variable patches.json.free.connectnew in xpui.js
Didn't find variable patches.json.exp.similarplaylist in xpui.js
Didn't find variable patches.json.exp.ignorrec in xpui.js
Didn't find variable patches.json.exp.prod in xpui.js
Didn't find variable patches.json.exp.newlyrics in xpui.js
Didn't find variable patches.json.exp.showingballoons in xpui.js
Didn't find variable patches.json.exp.enhanceliked in xpui.js
Didn't find variable patches.json.exp.enhanceplaylist in xpui.js
Didn't find variable patches.json.exp.disographyartist in xpui.js
Didn't find variable patches.json.exp.lyricsmatch in xpui.js
Didn't find variable patches.json.exp.equalizer in xpui.js
Didn't find variable patches.json.exp.searchbox in xpui.js
Didn't find variable patches.json.exp.audiobooks in xpui.js
Didn't find variable patches.json.others.fix-old-theme in xpui.css
installation completed
```