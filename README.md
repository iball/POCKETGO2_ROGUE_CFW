<p align="center"><img class="center" src =https://raw.githubusercontent.com/Ninoh-FOX/POCKETGO2_ROGUE_CFW/master/logos/logo_gcwzero_clut224.png></p>

# POCKETGO2 ROGUE CFW

Official firmware for Pocketgo 2 handheld!

# update firmware 1.0.2: <br>
https://github.com/Ninoh-FOX/POCKETGO2_ROGUE_CFW/releases/tag/v1.0.2

# update firmware 1.0.1: <br>
https://github.com/Ninoh-FOX/POCKETGO2_ROGUE_CFW/releases/tag/v1.0.1

### 1.0.2:<br>

1. Fixed clock hour reset when powering off the console.
2. Gmenu2x now can show two type of previews (put in /(romsdir)/.previews/).
3. Adjusted the joystick (again).

### 1.0.1:<br>

1. Updated the file system, partition and expansion scripts again.
2. Gmenu2x analog stick control is removed.
3. Adjusted the battery.
4. Updated the stock Clock application with a new redesign. Thanks to Rafa Vico. (https://github.com/RafaVico)
![](https://raw.githubusercontent.com/Ninoh-FOX/POCKETGO2_ROGUE_CFW/master/screenshots/screenshot011.png)
![](https://raw.githubusercontent.com/Ninoh-FOX/POCKETGO2_ROGUE_CFW/master/screenshots/screenshot012.png)
5. Text editor, corrected opk buttons. thanks to Rafa Vico (https://github.com/RafaVico)
6. Added the hardware tester POCKETGO 2. thanks to Rafa Vico (https://github.com/RafaVico)
![](https://raw.githubusercontent.com/Ninoh-FOX/POCKETGO2_ROGUE_CFW/master/screenshots/screenshot008.png)
![](https://raw.githubusercontent.com/Ninoh-FOX/POCKETGO2_ROGUE_CFW/master/screenshots/screenshot009.png)
![](https://raw.githubusercontent.com/Ninoh-FOX/POCKETGO2_ROGUE_CFW/master/screenshots/screenshot010.png)

# features:

1. Support added to allow the second sdcard to be in fat32, exFAT, ntfs, ext4 (recommended) or ext3 formats.

2. Added key combinations with the power button:
+ POWER + VOL + or VOL-: Adjust the brightness of the screen.
+ POWER + SELECT: Close the current application.
+ POWER + START: Restart the console.
+ POWER + B: The analog stick will work as DPAD.
+ POWER + A: Change the aspect ratio with the screen in Hardware mode.
+ POWER + R1: Mouse emulation (Stick is movement and the L2 and R2 buttons the buttons)
+ POWER + DPAD up / dowm: Adjust the sharpness.
+ POWER + X: Take a screenshot.
    
3. In Gmenu2x the power button can turn the screen off or on. (THIS IS NOT A SLEEP FUNCTION!)

4. You can change the CPU to maximum or minimum in gmenu2x for the opk, the same to change the name, description, icon and file filter.

# Installation:

To properly ensure correct installation of this firmware, please make sure you completely remove all previous partions on the micro-SD card and format it to a single FAT32 (Windows/Linux) or exFAT (Windows) partition.  
Then use a quality micro-SD imaging program like Win32DisImager to apply the sd_image.bin to the micro-SD card.  
It's also beneficial to temporarily pause any antivirus programs you may have installed so they don't interfere with the imaging process.  We've seen instances where WIn32DiskImager will create a new partion on the micro-SD card only to have an antivirus software such as Bitdefender immediately start scanning that partition causing WIn32DiskImager to error out.
Just pause your AV software's real-time scanning, image the micro-SD card, and then unpause your AV software to let it run as normal.

https://sourceforge.net/projects/win32diskimager/

https://www.sdcard.org/downloads/formatter/

You can also use the "flasher.opk" file to install this firmware, but it takes much longer.
This being a console that only has the SD1 (TF1) of the system at hand I do not believe it is really necessary but even so, it is being made available for you to use should you wish to go that route.
If you do want to use it, it's advisable to put it in the apps folder of the SD2 (TF2).

For future update releases of this firmware you will only need to use the update.opk, which is used just like any application.
You can use the update OPK in either the apps folder of SD1 (TF1) or SD2 (TF2).
