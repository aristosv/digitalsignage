# Raspberry Pi Digital Signage System

This is a simple way to use a Raspberry Pi as a digital signage system. No need for a graphical user interface, no need to install a desktop. Just download the [Raspberry Pi OS Lite](https://www.raspberrypi.com/software/operating-systems/) image, burn it on an SD card and boot your Raspberry Pi to the operating system. This has been tested on a Raspberry Pi 4 Model B with 4GB of RAM, but it will probably run just fine on older models also.

Check out the [Credits](https://github.com/aristosv/digitalsignage/blob/main/CREDITS.md). Without these people, this project would not be possible.

## install
```
bash <(wget -qO- https://raw.githubusercontent.com/aristosv/digitalsignage/main/operations/install)
```
## access signage
```
http://raspberrypi_ip:1337
```
## access files
```
http://raspberrypi_ip:8080
```
## update
```
bash <(wget -qO- https://raw.githubusercontent.com/aristosv/digitalsignage/main/operations/update)
```
## logs
- log files for install and update are located in /tmp

## screenshots
<p align="center">
  <img width="600" height="487" src="https://raw.githubusercontent.com/aristosv/digitalsignage/main/media/logo/logo.png">
  
  <img width="370" height="800" src="https://raw.githubusercontent.com/aristosv/digitalsignage/main/screenshots/mobile_olivetin_1.png"> <img width="370" height="800" src="https://raw.githubusercontent.com/aristosv/digitalsignage/main/screenshots/mobile_filebrowser_1.png">
</p>
