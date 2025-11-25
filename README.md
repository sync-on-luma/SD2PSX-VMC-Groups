# SD2PSX-VMC-Groups
A set of VMC group definitons for [SD2PSX](https://github.com/sd2psx) based memory cards. These groups are designed to facilitate cross-game save interactions when using an SD2PSX based memory card. See [here](https://github.com/sync-on-luma/xebplus-neutrino-loader-plugin/wiki/Memory-Card-Groups) for more details about these features.

An SD2PSX based memory card running the [SD2PSXTD firmare](https://sd2psxtd.github.io/) is required to make use of these files.

## Usage:
* Download the version of `VMC_Groups.zip` that is approriate for your use case. If you are unsure of which version to use, the standard version is reccomended.
* Extract the contents of `VMC_Groups.zip` to the root of your SD2PSX SD card. You may need to enbale *Show Hiddin Files* in your file manager.
* Done! Place the SD card back into your SD2PSX, and save files should now automacially be saved to the correct VMC when starting a game.

## Standard VS Legacy:
`VMC_Groups.zip` is avalible in two versions: Standard and Legacy. The standard version provides human readable names for grouped VMCs, and is reccomenced for new SD2PSX users, as well as those using outdated backup loaders or physical discs. 

The Legacy version is inteded for those who have previosuly used a modern backup loader, such as the XEB+ neutrino Launcher, OSDXMB, and recent beta version of OPL, in conjunction with an SD2PSX. These loaders are capable of handling VMC groupung internally, and passing that information to an SD2PSX via a custom Group ID. The Legacy version of `VMC_Groups.zip` retains this group ID naming scheme, so that any previosuly created group VMC files will continue to be used.

## Known Issues and Limitations:
* Group VMCs that were previously created by a backup loader will not be accessable when using the standard version of `VMC_Groups.zip`.
* Save grouping for PS2 games requires either a phsycial disc or a backup loader that supports title ID detection.
* Save grouping for PS1 games requires an orignal PlayStation console that has been modified with a cutom BIOS or ODE that supports title ID detection, or a PS2 based backup loader that supports the same.
* PS1 memory cards have a hard limit of 128KB. As such, it is possible to run out of space if playing a lot of games in one of the larger VMC groups. If this happens, the SD2PSX channel switching feature can be used as a workaround, though this may break some corss-game interactions.
