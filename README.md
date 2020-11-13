# 1x4_card

This is Fun Project with contact info that is also a macro pad

# Parts

•	1 PCB

•	1 Pro Micro (or compatible controller)

•	2 Pro Micro pins (optional & usually included when buying a Pro Micro)

•	4 switches

•	4 keycaps

•	4 M2 standoffs (optional)

•	1 piezo (optional) & (if used please install from below with standoffs)

•	1 tactile button 

 

# Build

Solder the Pro Micro face down onto the PCB with standoffs.

Solder the switches


# Firmware
The card uses QMK as the firmware. To setup QMK, please referee to https://docs.qmk.fm/#/

you can download the keyboard files from:
https://github.com/ramixp1/qmk_firmware/tree/ramixp1/keyboards/1x4_card

<p><code> # make 1x4_card:default:avrdude</code></p>

To reset the Pro Micro, short the RESET pin to ground by pressing the reset button or short manually.


