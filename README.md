# Raspberry-Pi-3-Setup - Raspbian Stretch - Headless Setup

## Installation : 
First off, Download Raspian Strech with Desktop for writing to the SD Card from the official website whose link I have attached below :
```
https://www.raspberrypi.org/downloads/raspbian/
```
Before writing on the SD Card to be used for the Raspberry Pi, format it. Preferebly using SD Card Formattter : 
```
https://www.sdcard.org/downloads/formatter_4/
```
Once the download is over, write the image to the SD Card using Win32 Disk Imager :
```
https://sourceforge.net/projects/win32diskimager/files/latest/download
```
Open the Bootable Card and one has to create two new files for headless boot.
I have enclosed the .conf file to be created and create an empty file called "ssh" with no extensions.
Now insert the card into the Raspberry Pi set and connect the set to the Router using Ethernet and find the  IP Address of the Raspberry Pi found under the DHCP Clients list in your Router Page. 
Now connect to the Raspberry Pi using software such as PuTTY available in :
```
http://www.putty.org/
```
Open PuTTY and specify the IP Address and select the Protocol as SSH.
You are all set to use Raspberry Pi Terminal. The usual user ID is pi and password is raspberry 
I'll commit changes soon to view the desktop using software such as VNC. 
