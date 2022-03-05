# Open Source Raspberry Pi Digital Signage System

This is a simple way to use a Raspberry Pi as a digital signage system. No need for a graphical user interface, no need to install a desktop. Just download the [Raspberry Pi OS Lite](https://www.raspberrypi.com/software/operating-systems/) image, burn it on an SD card and boot your Raspberry Pi to the operating system. This has been tested on a Raspberry Pi 4 Model B with 4GB of RAM, but it will probably run just fine on older models also.

## install
clone repo & run install
```
git clone https://github.com/aristosv/digitalsignage.git
bash ~/digitalsignage/operations/install
```

## access
```
OliveTin - http://raspberrypi_ip:1337
FileBrowser - http://raspberrypi_ip:8080
```

## update
run update script
```
~/digitalsignage/operations/update
```

## screenshots
<p align="center">
  <img width="600" height="487" src="https://raw.githubusercontent.com/aristosv/digitalsignage/main/media/logo/logo.png">
</p>
 
<p align="center">  
  <img width="370" height="800" src="https://raw.githubusercontent.com/aristosv/digitalsignage/main/screenshots/mobile_olivetin_1.png"> <img width="370" height="800" src="https://raw.githubusercontent.com/aristosv/digitalsignage/main/screenshots/mobile_filebrowser_1.png">
</p>

## optional
enable cpu/disk/memory/temperature monitoring
```
~/digitalsignage/monitor/install
```
enable tunnel access to your raspberry pi via an ssh server
```
~/digitalsignage/tunnel/install
```

[![aristosv - digitalsignage](https://img.shields.io/static/v1?label=aristosv&message=digitalsignage&color=blue&logo=github)](https://github.com/aristosv/digitalsignage "Go to GitHub repo") <a href="https://github.com/aristosv/digitalsignage/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/aristosv/digitalsignage?style=for-the-badge"></a> <a href="https://github.com/aristosv/digitalsignage/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/aristosv/digitalsignage?style=for-the-badge"></a> <a href="https://github.com/aristosv/digitalsignage"><img alt="GitHub license" src="https://img.shields.io/github/license/aristosv/digitalsignage?style=for-the-badge"></a>