[More Info on How to Install](https://www.raspberrypi.org/documentation/installation/installing-images/README.md)

### Steps (Image to MicroSD)
  13. You will need to login again with the Username and Password
  14. Enter: raspi-config
  15. Scroll down to option 8: (Update) and press Enter (image 2.3)
  16. [Write Steps to Get To Step 17 if Update does not return to Main Menu]
  17. Scroll down to option 2: (Network options)(image 2.4) and press Enter
  18. Network Menu Screenshot
  19. Scroll down to option 4 (Localisation) (image 2.5)
  20. Set the Timezone to: Australia, Melbourne (image 2.6)
  21. Set the Wifi Country to: Australia, Melbourne(image 2.7)
  22. Scroll down to option 7(advanced options)
  23. Advance Options Interface Screenshot (image 2.8)
  24. Select A1 Expand filesystem to usb all available space on MicroSD and press Enter then scroll down to back and press enter (image 2.9)
  25. Scroll down to finish and this will return you to the command line
  26. Enter: reboot
  27. Now Enter your Username and Password (pi / raspberry)
  28. Enter: df -H
  29. This will show you available space (should be around 6GB)
