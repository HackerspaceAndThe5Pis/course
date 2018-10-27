# Installing Raspbian
[More Info on How to Install](https://www.raspberrypi.org/documentation/installation/installing-images/README.md)
## Required Hardware

 - 8GB Micro SD card
 - MicroSD to USB converter (image 2.1)
 - Windows computer, USB Keyboard, USB mouse, monitor (HDMI), speakers, ethernet cable

## Required software 

Archive Extractor  - Pre installed in Windows
Image-to-SD tool - Win32 Disk Imager [Download Here](https://www.portablefreeware.com/?id=2018)
Download Image from [Here](https://www.raspberrypi.org/downloads/)

## Steps (Image to MicroSD)

 1. Insert MicroSD into MicroSD-to-USB converter. Insert MicroSD-to-USB converter into computer, wait for drive letter to appear.
 2. Ensure that the device is loaded, this can be checked by right clicking the device and going to properties and go to storage. Ensure the number matches the size of your MicroSD card.
 3. Make a note of the "Drive letter" which appears next to a device name once its plugged into a computer.
 4. Launch the program Win32 Disk Imager (That you downloaded before starting).
 5. Select the Raspbian Image, Select drive letter (Again Name of the MicroSD card), write, confirm write, wait till finished (est 5min).
 6. Eject MicroSD-to-USB from PC, remove MicroSD from converter.
 7. Connect Keyboard, mouse, monitor (HDMI), speakers, ethernet cable to Raspberry Pi.
 8. Insert MicroSD into RPi.
 9. Insert power cord and power on the RPi once everything in plugged in.
10. Wait for a Login interface to appear.
11. The Username is: pi (lowercase) Password: raspberry (image 2.2) - NOTE: these can be changed later
12. Type into the command line following to update Raspbian with any updates released after the image was created.
	 a. sudo apt-get update
	 b. sudo apt-get upgrade
	 c. reboot
13. You will need to login again with the Username and Password
14. Type: raspi-config
15. Main Menu -> Using the down arrow, Select option 8: (Update) by pressing Enter (image 2.3)
16. [Write Steps to Get To Step 17 if Update does not return to Main Menu]
17. Main Menu -> Select option 2: (Network options)(image 2.4)
18. [Network Menu Screenshot]
19. Main Menu -> Select option 4 (Localisation) (image 2.5)
20. Localisation -> Set the Timezone to: Australia, Melbourne (image 2.6)
21. Localisation -> Set the Wifi Country to: Australia, Melbourne(image 2.7)
22. Return to the Main Menu
23. Main Menu -> Select option 7(advanced options)
24. [Advance Options Interface Screenshot] (image 2.8)
25. Main Menu -> Select A1: Expand filesystem to use all available space on MicroSD, then return to Main Menu (image 2.9)
26. Main Menu -> Select Finish to return to the command line
27. Type: reboot
28. Relogin (username: pi, password: raspberry)
29. Type: df -H  (This will show you available space (should be around 6GB)
