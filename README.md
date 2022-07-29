# Spiritualized GBA 
GBA core for openFPGA on Analogue Pocket
-

Almost everything should be supported by this core.  

Be sure your gba_bios.bin file is in /assets/gba/common/ before using!

Note that the link port is fully supported, and rumble is supported too
if you plug in a DS rumble pak!  Currently Drilldozer is fully supported
this way.  Warioware Twisted would be if there was a usable accelerometer...

Enjoy

This core is for the [Analogue Pocket](https://www.analogue.co/pocket) via [openFPGA](https://www.analogue.co/developer).

## Release Notes

* First public release
* Supports sleep and wake and memories

## Installation
To play Game Boy Advance on your Pocket follow these instructions. 
1. Download and install the latest Pocket firmware here https://analogue.link/pocket-firmware
2. Unzip the contents onto the root of your Pocket SD Card in the appropriate folders. 
3. You will need to add a GBA bios to your sd card. Name the gba bios file "gba_bios.bin" and place it in the assets/gba/common folder.
4. Place rom files in the assets/gba/common folder.
5. Power on Pocket and select openFPGA to run the core.
