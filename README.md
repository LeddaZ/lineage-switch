# lineage-switch
Unofficial LineageOS 17.1 (Android 10) builds for the Nintendo Switch. Official Switchroot builds are available [here](https://forum.xda-developers.com/t/rom-unofficial-switchroot-android-10.4229761/).

These builds are signed with my own keys, so a clean flash is required if coming from/to official/other builds.

## Steps
- Go to the [latest release](https://github.com/LeddaZ/lineage-switch/releases/latest)
- For standard Android, extract `tab.zip` to the SD card root and copy `lineage-17.1-XXXXXXXX-UNOFFICIAL-icosa_sr-signed.zip` to the same location
- For Android TV, extract `atv.zip` to the SD card root and copy `lineage-17.1-XXXXXXXX-UNOFFICIAL-icosa_tv_sr-signed.zip` to the same location
- Then follow the instructions in the official XDA thread above

## RAM OC
If you want to overclock the RAM to 1862MHz, download [this](https://raw.githubusercontent.com/LeddaZ/lineage-switch/main/coreboot_oc.rom) coreboot, copy it to `/switchroot/android` in your SD card and rename it to `coreboot.rom`. You'll have to redo these steps every time you flash a LineageOS zip.
