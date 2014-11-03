# Flashing the SD Card using Mac

> [INFO] This part of the guide assumes that you already have [downloaded and extracted](../quick-start/quick-start-guide.md#download-and-extract) the image file

Intro
---------
The SD card will be the home for your unit's Operating System. This installation will flash the RuneOS onto the card, along with formatting the card to a bootable state. This is different than copying the image onto the drive, but similar and almost as easy.

Materials
---------
To begin this procedure, you will require several things.

1. A Micro SD card of 4Gb capacity or greater. 

> [Info] Make sure it is not write protected before starting.

2. A card reader that can connect your SD card to your computer. USB types are cheap and work well.
3. The appropriate RuneAudio image file for your system. Find them on the [Downloads Page](http://www.runeaudio.com/download/).
4. An image flashing tool for a MAC. Several exist, this example uses ApplePi-Baker [http://www.tweaking4all.com/hardware/raspberry-pi/macosx-apple-pi-baker/]. 

Procedure using ApplePi-Baker
---------
 - Insert your card into the card reader, (and the card reader into your USB port). You should see a new USB Device in Finder.

> [Info] You are encouraged to remove all other USB devices at this time to avoid confusion during flashing. Flashing will overwrite the disk.

 - Run ApplePi-Baker. Below is a screenshot of the Application, showing the Drive window and the 4 "main" functions.
 - ******SCREENSHOT SHOULD GO IN HERE, Just need to figure out how :) ***********
 - If you dont see your drive, hit the Refresh button
 - Highlight the correct USB drive by selecting it in the Drives window
 - If you did not extract the Rune image file from the Rune download, do so now.
 - Now select the correct image file (should have .img extension) that you extracted. This is done by selecting the button with the 3 "dots" next to IMG File
 - Once an image is selected, the IMG to SD-Card button should be enabled.
 - Press the button to initiate the flashing of Rune to the SD card. Note: this takes some time depending on size of image, speed of media, etc. but generally 12-15 minutes for Rune 0.3 beta
 - Once complete, ApplePi-Baker will pop-up a prompt telling you its done and to unmount your SD Card properly. This can be done via the OS or from within ApplePi-Baker using the Unmount/Eject button.
 - Remove SD card from reader, put in RaspberryPI....PROFIT!!
 
