# Please read

This repository is an archive of FBI, which is a file manager for 3DS systems.

The original creator's Github account (Steveice10) was terminated on March 5th 2024, which is likely due to their involvement in the development of **[3DS emulator that is now unavailable]**.

For preservation purposes, and to prevent the 3DS modding scene from (ever) fading, I have decided to reupload the repository as it stood a day before it was gone.

**Piracy is, was, and always will be illegal.**

**The use of FBI to pirate titles will NEVER be condoned or supported.**

# FBI

FBI is an open source title manager for the 3DS.

Download: https://github.com/commandcontrolQ/FBI/releases

Requires [devkitARM](https://devkitpro.org/wiki/Getting_Started), along with 3ds-curl, 3ds-zlib, and 3ds-jansson from the devkitPro pacman repository, to build.

# Features

* Browse and modify the SD card, TWL photos, TWL sounds, save data, and ext save data.
* Export, import, and erase save data from DS cartridges.
* Export, import, and delete save data secure values.
* Install titles/tickets from a file system, over a local network, or over the Internet with a URL or QR code.
  * Automatically imports title seeds on installation, either from the Internet or the SD card.
* Browse and delete pending titles (downloaded updates, in-progress eShop titles, etc).
* Customize appearance by placing replacements for RomFS resources in "sdmc:/fbi/theme/".

* Only available when run from a CIA, 3DS, or a 3DSX under Luma3DS:
  * Browse and modify CTR NAND, TWL NAND, and system save data.
  * Dump the raw NAND image to the SD card.
  * Launch titles installed to the system.

# Credit

Banner: Originally created by [OctopusRift](https://gbatemp.net/members/octopusrift.356526/), touched up by [Apache Thunder](https://gbatemp.net/members/apache-thunder.105648/), updated for new logo by [PabloMK7](https://gbatemp.net/members/pablomk7.345712/).

Logo: [PabloMK7](https://gbatemp.net/members/pablomk7.345712/)

SPI Protocol Information: [TuxSH](https://github.com/TuxSH/) ([TWLSaveTool](https://github.com/TuxSH/TWLSaveTool))
