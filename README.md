# CRT-VR-Headset-Driver
SteamVR driver for CRT VR Headset

This is based on the driver for [Relativty](https://github.com/relativty/Relativty/). Changes were made to have more flexibility with having a separate display for each eye and adding some additional initialization code that allows it to work in more games including VRChat. 

Installation instructions:
1. Copy the "Relativty" folder from the releases to the SteamVR drivers folder (by default, it's in C:\Program Files (x86)\Steam\steamapps\common\SteamVR\drivers).
2. Open default.vrsettings in "Relativty\resources\settings" in a text editor. Change the "WindowX" and "WindowY" settings to match the origin (upper left corner) of the display. For example, if your main monitor is 1920x1080, and Windows Display Settings shows the VR headset monitor to the right of it with the top edge aligned, "WindowX" should be 1920 and "WindowY" should be 0. For more details, see the instructions in the readme for Relativty. 

Other settings you might want to change in default.vrsettings include "IPDmeters", "FocalLengthMeters", "DisplayHeightMeters", "DisplayWidthMeters", and "DisplayOffsetMeters". These settings affect the projection for each eye and might need to be adjusted depending on the size and placement of the displays. 
