# Open Source Raspberry Pi Digital Signage System

[![aristosv - digitalsignage](https://img.shields.io/static/v1?label=aristosv&message=digitalsignage&color=blue&logo=github)](https://github.com/aristosv/digitalsignage "Go to GitHub repo")
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/aristosv/digitalsignage?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/aristosv/digitalsignage?style=plastic)
[![License](https://img.shields.io/badge/License-GPL_v3.0-blue)](#license)
[![stars - digitalsignage](https://img.shields.io/github/stars/aristosv/digitalsignage?style=plastic)](https://github.com/aristosv/digitalsignage)
[![forks - digitalsignage](https://img.shields.io/github/forks/aristosv/digitalsignage?style=plastic)](https://github.com/aristosv/digitalsignage)
[![view - Documentation](https://img.shields.io/badge/view-Documentation-blue?style=plastic)](/docs/ "Go to project documentation")
![maintained - yes](https://img.shields.io/badge/maintained-yes-blue)
[![contributions - welcome](https://img.shields.io/badge/contributions-welcome-blue)](/CONTRIBUTING.md "Go to contributions doc")
[![OS - Linux](https://img.shields.io/badge/OS-Linux-blue?logo=linux&logoColor=white)](https://www.linux.org/ "Go to Linux homepage")
[![Hosted with GH Pages](https://img.shields.io/badge/Hosted_with-GitHub_Pages-blue?logo=github&logoColor=white)](https://pages.github.com/ "Go to GitHub Pages homepage")
[![Made with Bash](https://img.shields.io/badge/Bash->=3-blue?logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/ "Go to Bash homepage")

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