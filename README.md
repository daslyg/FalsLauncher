# FalsLauncher

## **DISCLAIMER: This executable is self-extracting; scripts are extracted and run upon execution. This can pose a security risk on some systems, most notably those with strict security policies. User discretion is advised.**
See also: [FauxLauncher (Minecraft)](https://github.com/daslyg/FauxLauncher)

Can be used as a shortcut directly to Vintagestory.exe, when run, it will create a directory in %TEMP% containing a batch script (it will run it automatically) that waits for you to start a singleplayer world. It will wait for file extensions .vcdbs-wal or .vcdbs-shm to appear (upon loading a world) in your saves directory, and will then wait for them to disappear (upon unloading of a world) in order to create a backup .zip of the corresponding world. Once Vintage Story has been closed it will also save your user settings, logs, and mods. All backups created by the .exe are in the same directory, so changing your backup folder is as simple as moving the executable. A log is created for debugging purposes.

Warning, .zips may be overwritten if they share the same name in your backup folder when the executable is run.

### **Requirements:**
Windows 11, [Vintage Story](https://www.vintagestory.at/), [7-Zip](https://www.7-zip.org/)—(Only follow links you trust)

Downloads are available in the releases page.
