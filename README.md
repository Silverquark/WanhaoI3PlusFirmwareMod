# Mods implemented:

LCD Firmware:
- access to sd/print menu without sdcard inserted

Printer Firmware:
- Diagonal leveling assistant

All changes made so far are independent from the other firmware.
So you can install only printer firmware mod to get sdmenu mod or only printer firmware for diagonal leveling. Or both.

# Mods Planned:
- Multiple preheat profiles with different temperatures (hotend/bed)
- Subfolder support for sdcard
- [Complete menu redesign](http://imgur.com/VQiZ4BC) (Will require removal of chinese translation for space reasons)

# Installation:

LCD Firmware:

http://www.wanhao3dprinter.com/FAQ/ShowArticle.asp?ArticleID=79

Printer Firmware:

Download Arduino 1.6.4 from the [arduino website](https://www.arduino.cc/en/main/OldSoftwareReleases).
Connect printer to pc. If you have trouble with drivers look [here](http://3dprinterwiki.info/wiki/wanhao-duplicator-i3-plus/wanhao-i3-plus-documentation-factory-files/ch340x-driver-information/).
Load Marlin.ino with Arduino. Select Arduino Mega under Tools->Boards.
Check the sketch with the ✔ button. If no errors show up upload the sketch to your printer.

# Usefull development links:

Marlin changes for LCD:

http://3dprinterwiki.info/wiki/wanhao-duplicator-i3-plus/wanhao-i3-plus-firmware-description/

LCD Manufraturer (contains sdk, datasheets, drivers and more):

http://dwin.com.cn/english/products/bt-72876584214435.html


# Things i noticed:

It looks like there are different versions of the screen in circulation. Mine is "DMT48270M050_06W". [But i found screenshots of others with different versions](https://i2.wp.com/3dprinterwiki.info/wp-content/uploads/2016/09/IMG_8041.jpeg). I think they should all be compatible, but if it's not working on your screen, this may or may not be the cause.
