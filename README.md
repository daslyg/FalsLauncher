# FalsLauncher

Can be used as a shortcut directly to Vintagestory.exe, when run, it will create a directory in %TEMP% containing a batch script that waits for you to start a singleplayer world. It will wait for file extensions .vcdbs-wal or .vcdbs-shm to appear in your saves directory, and will then wait for them to disappear in order to create a backup .zip of the corresponding world. Once Vintage Story has been closed it will also save your user settings, logs, and mods.

See also: [FauxLauncher (Minecraft)](https://github.com/daslyg/FauxLauncher)
