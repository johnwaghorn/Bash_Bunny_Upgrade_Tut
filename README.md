# BashBunny-Upgrade-tut

This an extension of the https://bashbunny.com/downloads upgrade guide.

Upgrade Bash Bunny Firmware on Ubuntu/Debian – Noob Guide [12/07/17]
1.	Download the latest version of the Bash Bunny firmware from https://bashbunny.com/downloads<br>
    •	Example: ch_fw_1.3_264_tar.gz file
    
2.	Verify that the SHA256 checksum of the downloaded firmware files matches the checksum listed at https://bashbunny.com/downloads<br>
    •	Change Directory(cd) to downloaded ch_fw_1.3_264_tar.gz<br>
    •	Run Command: sha256sum ch_fw_1.3_264_tar.gz<br>
    •	Check/match output with downloads page<br>
    •	Example output: fe260b0a5f68c3b2c721fae111e970beaba3a47184df630b1c5bca1e567e4a81 *ch_fw_1.3_264_tar.gz
    
3.	Slide the Bash Bunny switch into Arming Mode (closest to the USB plug) and plug the Bash Bunny into your computer<br>
    •	You will see the LED flash green for a second and then it will flash blue continuously.<br>
    •	You will see the USB ICON appear on your Ubuntu Launcher.
    
4.	Open Bash Bunny USB icon on Ubuntu

5.	THIS IS THE ROOT OF THE BASH BUNNY FLASH DRIVE (NOT THE LINUX ROOT ACCESSED BY SCREEN/SSH)

6.	Copy the firmware upgrade file downloaded in step 1 to the root of the Bash Bunny flash drive.<br>
    •	Copy the ch_fw_1.3_264_tar.gz file (Don’t extract it)
    
7.	Safely eject the Bash Bunny flash drive (IMPORTANT)<br>
    •	Right click eject
    
8.	With the switch still in Arming Mode, plug the Bash Bunny back into your computer and wait 10 minutes.<br>
    •	The USB will flash red for a while (could be 10mintes, could be less)<br>
    •	Once it is flashing blue again, the upgrade should be complete<br>
    •	Check version.txt in the root of the flash drive. 
    
9.	Enjoy :-) 
