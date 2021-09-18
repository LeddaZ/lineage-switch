# lineage-switch
Unofficial LineageOS 17.1 builds (based on Android 10) for the Nintendo Switch. Official Switchroot Android 10 builds are available [here](https://forum.xda-developers.com/t/rom-unofficial-switchroot-android-10.4229761/).

Builds are signed with my own keys, so a clean flash is required if coming from/to official/other builds.

## Steps
- Download the ROM from the [Releases](https://github.com/LeddaZ/lineage-switch/releases/latest) section.
- For standard Android, extract `tab.zip` to the SD card root and copy `lineage-17.1-XXXXXXXX-UNOFFICIAL-icosa_sr-signed.zip` to the same location.
- For Android TV, extract `atv.zip` to the SD card root and copy `lineage-17.1-XXXXXXXX-UNOFFICIAL-icosa_tv_sr-signed.zip` to the same location.
- If you want GApps, I recommend [OpenGApps](https://opengapps.org/) (use ARM64 10.0 pico).
- If you want root, download the latest version of [Magisk](https://github.com/topjohnwu/Magisk/releases/latest).
- Follow the flashing instructions in the official XDA thread above.

To update just flash the zip in TWRP, or update from Settings (supported on September 2021 builds and newer).

## RAM OC
If you want to overclock the RAM to 1862MHz, download [this](https://raw.githubusercontent.com/LeddaZ/android-switch/main/coreboot_oc.rom) coreboot, copy it to `/switchroot/android` in your SD card and rename it to `coreboot.rom`. You'll have to redo these steps every time you flash a ROM zip.

# Credits
- The [Switchroot](https://gitlab.com/switchroot) team for making all of this possible
- [ZachyCatGames](https://gitlab.com/ZachyCatGames) for making a great [guide](https://gitlab.com/ZachyCatGames/q-tips-guide) (from which I also got the OC coreboot)
