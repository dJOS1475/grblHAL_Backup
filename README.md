# grblHAL_Backup
My grblHAL Config Backup for the MKS DLC32 v2.x. This firmware versrion is WiFi enabled.

Im using a4988 Stepper Drivers with 1.8 degree Stepper motors from LDO and a grbl_spd spindle controller running a Makita Router.

To flash the firmware, use the MKS Laser Tool and a USB cable to flash my "mks_dlc32_gh_fw.bin" file. 

NOTE: When flashing the DLC32, you must remove the MKS touch-screen if you have one. It will prevent you from flashing the board and the board from booting with non-OEM firmware. 

The "MKS Laser Tool" is the best flashing software I've found, and I've copied it to my GitHub repo as it's a PITA to locate.
You can also find it here: https://github.com/makerbase-mks/MKS-DLC32/tree/main/MKS-DLC32-main/firmware/tool

The rest of the config is the same as any other board:
https://github.com/grblHAL/core/wiki/First-Run-Grbl-Settings

The best software to configure grblHAL is IoSender. It will let you configure the wifi settings and all the other settings very easily. It works via USB and also Wifi once that is configured.
https://github.com/terjeio/ioSender

My 3018 CNC mods can be found on Printables:
https://www.printables.com/@djos_1475_171511/models?query=cnc

My CNC machine making something:
https://youtu.be/gauJ4TA8BZ8
