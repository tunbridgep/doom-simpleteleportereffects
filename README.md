# Simple Teleporter Effects #

## About ##

This very simple mod is designed to add particle fountains to all valid teleporters in Doom and any pwads. It can be configured using the teleporter_flats_<color> console commands. Simply add flat names to these lists and they will be handled correctly.

The mod detects teleporters by ensuring at least one linedef on the sector has the Teleport (70) Action Special. This means it should also work for other games like Strife, Hexen etc, however these games already have teleporter effects, so it doesn't really make sense to use them there.

## Installation ##

Premade release versions are ready to go. The repository doesn't contain anything other than the core source files, with all generated/compiled files not included.

If you wish to build it yourself you can do so using the following steps:

1. Create an include file for all files in the zsc directory. Zscript includes are discussed in detail [here](https://zdoom.org/wiki/ZScript)
2. [Zip the contents of the src directory as a pk3](https://zdoom.org/wiki/Using_ZIPs_as_WAD_replacement), then run in GZDoom using the -file parameter or using another method.

Alternatively, for a much quicker build experience, a config file is included for use with my [doom_quickbuild](https://github.com/tunbridgep/doom_quickbuild) utility.
