# FlexiaGloves
![3d_model](https://user-images.githubusercontent.com/2058899/154548240-75b58b25-c28c-4187-bc41-99eefaa2e872.png)
![assembled_finger](https://user-images.githubusercontent.com/2058899/154548257-2d27b0bf-02bb-4453-a536-e678e75ac065.jpg)

This is a fork of the popular project [LucidGloves](https://github.com/LucidVR/lucidgloves). This project aims to build a compact and OpenGlove compatible, flex sensor based VR glove. The hardware is a complete departure from the orignal LucidGlove.

# Firmware
The firmware can be found here: https://github.com/JohnRThomas/OpenGlove-Firmware

# Hardware
The hardware of this project differs from LucidGlove because it relies on flex sensors instead potentiometers for finger curl tracking.

## Glove parts
* 3D printed parts in the hardware folder
* 2mm wide nylon zipties | [Amazon](https://www.amazon.com/gp/product/B083ZXC71B)
* 0.4mm spring steel wire | [Amazon](https://www.amazon.com/gp/product/B096X52958)
* MG90 Servos | [Amazon](https://www.amazon.com/s?k=mg90+servo)
* Blue breadboard potentiometers | [Amazon](https://www.amazon.com/HUAREW-Adjustable-Resistance-Potentiometer-Assortment/dp/B0877BKG4R)
* ESP32 WROOM Board | [Amazon](https://www.amazon.com/s?k=esp32)
* 1000 grit sandpaper | [Amazon](https://www.amazon.com/s?k=1000+grit+sandpaper)
* Super Glue | [Amazon](https://www.amazon.com/s?k=super+glue)
* 1/2in Velcro strap | [Amazon](https://www.amazon.com/Fasten-Management-Organizer-Reusable-Gripping/dp/B07GTV7PJK)
* Iron-on fabric patch | [Amazon](https://www.amazon.com/Bondex-Iron-Patches-X7-Pkg-Black/dp/B005UT628U)
* Copper Foil Tape | [Amazon](https://www.amazon.com/gp/product/B09C1ZLFZF)
* AdaFruit Velostat | [Adafruit](https://www.adafruit.com/product/1361)

**Amazon Links are simply examples and other sources/parts may be used**

The 3D printable parts. Both STL and Fusion360 files are available for ease of modification.

# Printing Guide
All measurements for the design of FlexiaGloves were based off the size of a single hand, however all hands are different; More than likely every part of the glove will need to be tailored the size of the target hand.

## Sizing
### Finger Guides
The length of each finger guide should be configured to match length of each segment of the target fingers. The width of the guide should be adjusted to accommodate the size of the homemade flex sensors.

### Baseplate
The length, width, finger spacing, and wrist width of the baseplate should be configured to be comfortable on the target hand.

### Force Feed Back Module
The length of each module should be configured to accommodate the total range of motion for each finger. The back portion of the module can be extended or shrunk based on the length of spring wire that is required.

