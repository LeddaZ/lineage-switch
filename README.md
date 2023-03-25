# lineage-switch
Unofficial LineageOS 17.1 and 20 builds (based on Android 10 and 13 respectively) for the Nintendo Switch. Official Switchroot Android 10 builds are available [here](https://wiki.switchroot.org/en/Android/Setup-10).

Builds are signed with my own keys, so a clean flash may be required if coming from/to official/other builds.

**Do NOT report any issues you encounter with my builds to the Switchroot team on Discord or other platforms. Only report them issues with their official builds, they can't do anything about unofficial releases.**

**No support will be provided for these builds, as they are for my personal usage. Flash at your own risk.**

```
* Disclaimer 
* I am not responsible for bricked devices, dead SD cards, thermonuclear war, 
* or you getting fired because the alarm app failed. Please do some research 
* if you have any concerns about features included in this ROM
* before flashing it! YOU are choosing to make these modifications, and if
* you blame me in any way for what happens to your device, I will laugh at you.
```

## Steps
- Download `nx_tab-{date}-dev.zip` (standard Android) or `nx-{date}-dev.zip` (Android TV) from the [Releases](https://github.com/LeddaZ/lineage-switch/releases/latest) page.
- Extract the zip file's contents to the SD card root.
- If you want GApps, follow the instructions on the [LineageOS Wiki](https://wiki.lineageos.org/gapps).
- If you want root, download the latest version of [Magisk](https://github.com/topjohnwu/Magisk/releases/latest).
- Dump joycon pairing info, partition the SD card and flash required files by following steps 2 onwards [here](https://wiki.switchroot.org/en/Android/Setup-10#steps).

To update, download `lineage-20.0-{date}-UNOFFICIAL-nx_tab-signed.zip` (standard Android) or `lineage-20.0-{date}-UNOFFICIAL-nx-signed.zip` (Android TV) and flash it in recovery. You can also update from Settings -> System -> Updater.

<details><summary>17.1 steps</summary>

- Download `icosa-tab-XXXXXXXX-dev.zip` (standard Android) or `icosa-atv-XXXXXXXX-dev.zip` (Android TV) from the [Releases](https://github.com/LeddaZ/lineage-switch/releases/tag/20220824) page.
- Extract the zip file's contents to the SD card root.
- If you want GApps, use [MindTheGApps](https://androidfilehost.com/?w=files&flid=322935) (choose `10.0.0-arm64`) for standard Android or [OpenGApps](https://opengapps.org/?arch=arm64&api=10.0&variant=tvmini) for Android TV, as recommended by the LineageOS team (more info [here](https://wiki.lineageos.org/gapps)).
- If you want root, download the latest version of [Magisk](https://github.com/topjohnwu/Magisk/releases/latest).
- Follow the flashing instructions [here](https://wiki.switchroot.org/en/Android/Setup-10#steps) (from step 2 onwards).

To update, download `lineage-17.1-XXXXXXXX-UNOFFICIAL-icosa_sr-signed.zip` (standard Android) or `lineage-17.1-XXXXXXXX-UNOFFICIAL-icosa_tv_sr-signed.zip` (Android TV) and flash it in TWRP. You can also update from Settings -> System -> Updater (supported on September 2021 builds and newer).

</details>

## Credits
- The [Switchroot](https://gitlab.com/switchroot) team for making all of this possible
- [ZachyCatGames](https://gitlab.com/ZachyCatGames) for making a great [guide](https://gitlab.com/ZachyCatGames/q-tips-guide) before the official one came out.
