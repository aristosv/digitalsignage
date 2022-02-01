# BeatBox Digital Signage

This is a simple way to use a Raspberry Pi as a digital signage system. No need for a graphical user interface, no need to install a desktop. Just download the [Raspberry Pi OS Lite](https://www.raspberrypi.com/software/operating-systems/) image, burn it on an SD card and boot your Raspberry Pi to the operating system. This has been tested on a Raspberry Pi 4 Model B with 4GB of RAM (PCB Revision 1.1), but it will probably run just fine on older models also.

## Step 1: Install the prerequisites by running the command below.

---
install prerequisites
```
bash <(wget -qO- https://raw.githubusercontent.com/aristosv/BeatBox-Digital-Signage/main/install_prerequisites)
```
---

## Step 2: Choose any of the commands below.

---
show logo
```
bash <(wget -qO- https://raw.githubusercontent.com/aristosv/BeatBox-Digital-Signage/main/signage_logo)
```
---
play video files from /home/pi/media/video
```
bash <(wget -qO- https://raw.githubusercontent.com/aristosv/BeatBox-Digital-Signage/main/signage_video)
```
---
play audio files from /home/pi/media/audio
```
bash <(wget -qO- https://raw.githubusercontent.com/aristosv/BeatBox-Digital-Signage/main/signage_audio)
```
---
show images from /home/pi/media/images
```
bash <(wget -qO- https://raw.githubusercontent.com/aristosv/BeatBox-Digital-Signage/main/signage_images)
```
---
show a website
```
bash <(wget -qO- https://raw.githubusercontent.com/aristosv/BeatBox-Digital-Signage/main/signage_browser)
```
---
download & play youtube video
```
bash <(wget -qO- https://raw.githubusercontent.com/aristosv/BeatBox-Digital-Signage/main/signage_youtube_local)
```
---
stream youtube video
```
bash <(wget -qO- https://raw.githubusercontent.com/aristosv/BeatBox-Digital-Signage/main/signage_youtube_stream)
```
