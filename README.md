# Raspberry Pi Digital Signage System

This is a simple way to use a Raspberry Pi as a digital signage system. No need for a graphical user interface, no need to install a desktop. Just download the [Raspberry Pi OS Lite](https://www.raspberrypi.com/software/operating-systems/) image, burn it on an SD card and boot your Raspberry Pi to the operating system. This has been tested on a Raspberry Pi 4 Model B with 4GB of RAM, but it will probably run just fine on older models also.

## install
1. clone repository - git clone https://<span></span>github.com/aristosv/digitalsignage.git /home/pi/digitalsignage
2. run install script - bash /home/pi/digitalsignage/operations/install

## access
- OliveTin - http://raspberrypi_ip:1337
- FileBrowser - http://raspberrypi_ip:8080

## update
- run update script - bash /home/pi/digitalsignage/operations/update

## screenshots
<p align="center">
  <img width="600" height="487" src="https://raw.githubusercontent.com/aristosv/digitalsignage/main/media/logo/logo.png">
</p>
 
<p align="center">  
  <img width="370" height="800" src="https://raw.githubusercontent.com/aristosv/digitalsignage/main/screenshots/mobile_olivetin_1.png"> <img width="370" height="800" src="https://raw.githubusercontent.com/aristosv/digitalsignage/main/screenshots/mobile_filebrowser_1.png">
</p>

## monitoring (optional)
- enable cpu/disk/memory/temperature monitoring - bash /home/pi/digitalsignage/monitoring/install

## tunnel (optional)
- enable tunnel access to your raspberry pi through an ssh server - bash /home/pi/digitalsignage/tunnel/install