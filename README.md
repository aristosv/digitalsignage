# Raspberry Pi Digital Signage System

This is a simple way to use a Raspberry Pi as a digital signage system. No need for a graphical user interface, no need to install a desktop. Just download the [Raspberry Pi OS Lite](https://www.raspberrypi.com/software/operating-systems/) image, burn it on an SD card and boot your Raspberry Pi to the operating system. This has been tested on a Raspberry Pi 4 Model B with 4GB of RAM, but it will probably run just fine on older models also.

Check out the [Credits](https://github.com/aristosv/digitalsignage/blob/main/CREDITS.md). Without these people, this project would not be possible.

## install
```
curl -fsSL https://raw.githubusercontent.com/aristosv/digitalsignage/main/prepare/install -o /home/pi/install
bash /home/pi/install
```
## access
```
http://raspberrypi_ip:1337
```
## update
```
cd /home/pi/digitalsignage/
git pull origin main
```
## screenshots
<p align="center">
  <img width="533" height="800" src="https://raw.githubusercontent.com/aristosv/digitalsignage/main/screenshots/mobile.png">
</p>
