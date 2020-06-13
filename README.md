# Marlin 1.1.9.1 Firmware for Ender-3

<img align="top" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

This is a modified version of the Marlin 1.1.9.1 release that has been optimised for the Creality Ender-3 with a BLTouch.

Additional documentation can be found at the [Marlin Home Page](http://marlinfw.org/).

## Main Tweaks
- 3x3 Auto Bed Levelling, ideal for a glass bed, but you might want to increase this to 5x5 for buildtak/ magnetic beds.
- Slightly increased ABL second test speed, still performs well
- Removed broken power loss recovery
- Light LCD Menus
- BLTouch/ ABL related menus added
- Negative Z-Offset enabled. 
- Babystepping set to 0.005 - This is really as accurate as you'd ever need.
- All Serial/ SD is working - Tested with Octoprint and direct from Cura 4.6.1
- Tweaked bed size from original config in 1.1.9.1 firmware
- Thermal runaway protection is enabled and tested
- Currently building with 96% of the flash in use so there's room for small extras.
- Fixed home offsets based on most recent release of the (non-pro) Ender 3. 

## Building
You can build this from the Arduino IDE using the many guides available on the internet. 

## License

Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.
