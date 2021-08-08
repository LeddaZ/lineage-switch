# android-switch
Unofficial Android builds (currently LineageOS 17.1 and crDroid 6.XX, based on Android 10) for the Nintendo Switch. Official Switchroot Android 10 builds are available [here](https://forum.xda-developers.com/t/rom-unofficial-switchroot-android-10.4229761/).

LineageOS builds are signed with my own keys, so a clean flash is required if coming from/to official/other builds.

## Steps
- Download the desired ROM from the [table](https://github.com/LeddaZ/android-switch/blob/main/README.md#rom-links) below.
- For standard Android, extract `tab.zip` to the SD card root and copy `lineage-17.1-XXXXXXXX-UNOFFICIAL-icosa_sr-signed.zip` (`lineage-17.1-XXXXXXXX-UNOFFICIAL-foster_tab-signed.zip` for build 20210518) or `crDroidAndroid-10.0-XXXXXXXX-icosa_sr-6.XX.zip` to the same location.
- For Android TV (LineageOS only), extract `atv.zip` to the SD card root and copy `lineage-17.1-XXXXXXXX-UNOFFICIAL-icosa_tv_sr-signed.zip` (`lineage-17.1-XXXXXXXX-UNOFFICIAL-foster-signed.zip` for build 20210518) to the same location.
- If you want GApps, I recommend [OpenGApps](https://opengapps.org/) (use ARM64 10.0 pico) for LineageOS and [WeebGApps](https://t.me/WeebGAppsChannel) (use arm-arm64-10.0) for crDroid; OpenGApps on crDroid will force you to setup face unlock, and you'll get stuck in a loop because the Switch doesn't have a camera.
- If you want root, download the latest version of [Magisk](https://github.com/topjohnwu/Magisk/releases/latest).
- Follow the flashing instructions in the official XDA thread above.

## RAM OC
If you want to overclock the RAM to 1862MHz, download [this](https://raw.githubusercontent.com/LeddaZ/android-switch/main/coreboot_oc.rom) coreboot, copy it to `/switchroot/android` in your SD card and rename it to `coreboot.rom`. You'll have to redo these steps every time you flash a ROM zip.

## ROM Links
Latest build is at the top, first build at the bottom.

| LineageOS | crDroid |
| :-: | :-: |
| [20210807](https://github.com/LeddaZ/android-switch/releases/tag/20210807-lineage) | |
| [20210712](https://github.com/LeddaZ/android-switch/releases/tag/20210712) | [20210723](https://github.com/LeddaZ/android-switch/releases/tag/20210723-cr) |
| [20210518](https://github.com/LeddaZ/android-switch/releases/tag/20210518) | |

# Credits
- The [Switchroot](https://gitlab.com/switchroot) team for making all of this possible
- [ZachyCatGames](https://gitlab.com/ZachyCatGames) for making a great [guide](https://gitlab.com/ZachyCatGames/q-tips-guide) (from which I also got the OC coreboot)
