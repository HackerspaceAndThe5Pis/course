[More Info on How to Install](https://www.raspberrypi.org/documentation/installation/installing-images/README.md)

### Steps (Image to MicroSD)
  13. You will need to login again with the Username and Password
  14. Enter: raspi-config
  15. Scroll down to option 8: (Update) and press Enter <a data-lightbox="rasp-1" data-title="Update tool menu option" href="{{ site.baseurl }}/assets/img/raspbian/2.3-Option8-UpdateToolMenuOption.png">Image</a>
  16. [Write Steps to Get To Step 17 if Update does not return to Main Menu]
  17. Scroll down to option 2: (Network options) <a data-lightbox="rasp-1" data-title="Network menu option" href="{{ site.baseurl }}/assets/img/raspbian/2.4-Option2-NetworkMenuOption.png">Image</a> and press Enter
  18. Network Menu Screenshot
  19. Scroll down to option 4 (Localisation) <a data-lightbox="rasp-1" data-title="Localisation Menu Option" href="{{ site.baseurl }}/assets/img/raspbian/2.5-Option4-LocalisationMenuOption.png">Image</a>
  20. Set the Timezone to: Australia, Melbourne <a data-lightbox="rasp-1" data-title="Localisation Timezone" href="{{ site.baseurl }}/assets/img/raspbian/2.6-Option4-Localisation-Timezone.png">Image</a>
  21. Set the Wifi Country to: Australia, Melbourne <a data-lightbox="rasp-1" data-title="Localisation Wifi Country" href="{{ site.baseurl }}/assets/img/raspbian/2.7-Option4-Localisation-WifiCountry.png">Image</a>
  22. Scroll down to option 7(advanced options)
  23. Advance Options Interface Screenshot <a data-lightbox="rasp-1" data-title="Advanced Options" href="{{ site.baseurl }}/assets/img/raspbian/2.8-Option7-AdvancedOptions.png">Image</a>
  24. Select A1 Expand filesystem to usb all available space on MicroSD and press Enter then scroll down to back and press enter <a data-lightbox="rasp-1" data-title="Advanced Options Expand Filesystem" href="{{ site.baseurl }}/assets/img/raspbian/2.9-Option7-AdvancedOptions-ExpandFilesystem.png">Image</a>
  25. Scroll down to finish and this will return you to the command line
  26. Enter: reboot
  27. Enter your Username and Password (pi / raspberry)
  28. Enter: df -H <a data-lightbox="rasp-1" data-title="File system expanded - checkspace" href="{{ site.baseurl }}/assets/img/raspbian/2.10-FilesystemExpanded-CheckSpace.png">Image</a>
  29. This will show you available space (should be around 6GB)
