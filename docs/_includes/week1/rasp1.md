[More Info on How to Install](https://www.raspberrypi.org/documentation/installation/installing-images/README.md)
### Required Hardware

 - 8GB Micro SD card
 - MicroSD to USB converter (image 2.1)
 - Connect Keyboard, mouse, monitor (HDMI), speakers, ethernet cable

### Required software 

Archive Extractor  - Pre installed in Windows
Image-to-SD tool - Win32 Disk Imager [Download Here](https://www.portablefreeware.com/?id=2018)
Download Image from [Here](https://www.raspberrypi.org/downloads/)

### Steps (Image to MicroSD)

 1. Image MicroSD into MicroSD-to-USB converter. Insert MicroSD-to-USB converter into computer, wait for drive letter to appear.
 2. Ensure that the device is loaded, this can be checked by right clicking the device and going to properties and go to storage. Ensure the number matches the size of your MicroSD card.
 3. Make a note of the "Drive letter" which appears next to a device name once its plugged into a computer.
 4. Launch the program Win32 Disk Imager (That you downloaded before starting).
 5. Now you will write image to SD card. Select the Image, Select drive letter (Again Name of the MicroSD card), write, confirm write, wait till finished (est 5min).
 6. Eject MicroSD-to-USB from PC, remove MicroSD from converter.
 7. Connect Keyboard, mouse, monitor (HDMI), speakers, ethernet cable.
 8. Plug in MicroSD into RPi
 9. Plug in power cord and power on the RPi once everything in plugged in
 10. Wait for it to boot up and a Login interface will appear
 11. The Username is: pi (lowercase) Password: raspberry (image 2.2)
 12. Type into the command line following
	 a. sudo apt-get update
	 b. sudo apt-get upgrade
	 c. reboot
