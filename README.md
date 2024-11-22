# SuyuSSBUOptimized

<div align="center">
  <img src="media/suyu-banner.png" alt="Suyu Banner" style="width: 75%;">
</div>

## Linux Alternative to saad-script's Yuzu SSBU optimizer
SuyuSSBUOptimized provides a portable Suyu AppImage setup for Super Smash Bros. Ultimate (SSBU), pre-configured with the same mods as the [yuzu-ssbu-optimizer](https://github.com/saad-script/yuzu-ssbu-optimizer). When launched using `suyu-ssbu-optimized.sh`, the AppImage uses **/SuyuSSBUOptimized/home/** as its home folder, making it a fully isolated Suyu instance for online play. You can place the base directory **SuyuSSBUOptimized** anywhere, but the launcher script uses relative paths so its contents need to maintain the same position relative to the base directory.

## Manual Install to Pre-existing Yuzu/Suyu
To install the mods manually to your existing emulator, your sdmc folder needs to be replaced by the one in sdmc.zip. 
- AppImage sdmc path: `~/.local/share/yuzu/sdmc`
- Flatpak: sdmc path: `/.var/app/org.yuzu_emu.yuzu/data/sdmc`
