Custom OpenWRT Firmware
=======================

Attitude Adjustment 12.09.1 for WR1043ND
----------------------------------------

Source
------

https://github.com/gwlim/Attitude_Adjustment_WR1043ND.git

Features
--------

* Customised CFLAGS for mips24kc
* Updated toolchain to latest Linaro GCC 4.8 and Linaro Binutils
* LuCI Interface Tweaks
* 6.5MB Base Image with Installable Modular Packages

Recovery
--------

* Firmware to restore to default TP-Link Software in [Backup Folder](https://github.com/gwlim/Openwrt_Firmware/tree/master/TP-Link_TL-WR1043ND/BackUp_Image)
* Uboot backup partition available
* Art backup partition available

Overclock
---------

* Overclock firmware for WR1043NDv1 is available in [Backup Folder](https://github.com/gwlim/Openwrt_Firmware/tree/master/TP-Link_TL-WR1043ND/BackUp_Image)
* 2 Preset Overclock: 
* 440MHZ CPU Clock, 440MHZ RAM, and 220MHZ AHB
* 420MHZ CPU Clock, 420MHZ RAM, and 210MHZ AHB
* Tested Stable and Working on my WR1043ND
* To use simply sysupgrade to default TP-Link Factory Firmware using the sysupgrade to factory image then upgrade again using the Overclocked Firmware

