# grblHAL_Backup
My grblHAL Config Backup for the MKS DLC32 v2.x. This firmware versrion is WiFi enabled.

Im using a4988 Stepper Drivers with 1.8 degree Stepper motors from LDO and a grbl_spd spindle controller running a Makita Router.

# Flashing the firmware
To flash the firmware, use the MKS Laser Tool and a USB cable to flash my "mks_dlc32_gh_fw.bin" file. 

The settings for MKS Laser Tool are as follows:
<p align="left">
  <a>
    <img src="https://raw.githubusercontent.com/dJOS1475/grblHAL_Backup/main/MKS%20Laser%20Tool%2001.png" height="467">
    <img src="https://raw.githubusercontent.com/dJOS1475/grblHAL_Backup/main/MKS%20Laser%20Tool%2002.png" height="662">
  </a>
</p>

NOTE: When flashing the DLC32, you must remove the MKS touch-screen if you have one. It will prevent you from flashing the board and the board from booting with non-OEM firmware. 

The "MKS Laser Tool" is the best flashing software I've found, and I've copied it to my GitHub repo as it's a PITA to locate.

You can also find it here: https://github.com/makerbase-mks/MKS-DLC32/tree/main/MKS-DLC32-main/firmware/tool

The rest of the config is the same as any other board:
https://github.com/grblHAL/core/wiki/First-Run-Grbl-Settings

# Create your own grblHAL Firmware
If you wish to compile your own custom grblHAL firmware, or just update to a newer version, you can use the grblHAL Web Builder here:
http://svn.io-engineering.com:8080

And then you will need to use the “CombineBin” function in the "ESP32 Download tool" to join the 3 files into a single binary using the settings as shown:

<p align="left">
  <a>
    <img src="https://raw.githubusercontent.com/dJOS1475/grblHAL_Backup/main/IMG_1040.png" height="847">
  </a>
</p>

# Configure grblHAL
The best software to configure grblHAL is IoSender. It will let you configure the wifi settings and all the other settings very easily. It works via USB and also Wifi once that is configured.
https://github.com/terjeio/ioSender

# My 3018 CNC mods can be found on Printables:
https://www.printables.com/@djos_1475_171511/models?query=cnc

# My CNC machine making something:
https://youtu.be/gauJ4TA8BZ8
<p align="left">
  <a>
    <video src="https://youtu.be/gauJ4TA8BZ8" height="480">
  </a>
</p>
