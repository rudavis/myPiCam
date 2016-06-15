My Pi Cam
=========

Modified the Adafruit Pi Camera + PiTFT tutorial to work with my Raspberry Pi B+ and 3.5" (480x320) PiTFT touch screen.

Setup and Config Raspberry Pi
===================
I used the "easy install" from here:  https://learn.adafruit.com/adafruit-pitft-3-dot-5-touch-screen-for-raspberry-pi

1. Download, unzip and install Raspian image (Jessie Full):  https://adafruit-download.s3.amazonaws.com/2016-03-25_Jessie_PiTFT35r.zip
2. Configure OS,  See https://learn.adafruit.com/diy-wifi-raspberry-pi-touch-cam/pi-setup
* Expand File system, Enable Camera, Set Locale, Timezone, keyboard, SSH, etc
3. IMPORTANT!!  Ensure you're running SDL 1.2.  Instructions here: https://learn.adafruit.com/adafruit-pitft-28-inch-resistive-touchscreen-display-raspberry-pi/pitft-pygame-tips#ensure-you-are-running-sdl-1-dot-2
4. Setup and configure Dropbox
* Created a Dropbox dev app
* Install and configure Dropbox_uploader: https://github.com/andreafabrizi/Dropbox-Uploader

Running
=======
1. git clone https://github.com/rudavis/myPiCam.git
2. cd myPiCam
3. sudo python cam.py


Reference
=========
Original Camera project for Raspberry Pi + camera + Adafruit PiTFT
By PaintYourDragon (Phil B) for Adafruit Industries

http://learn.adafruit.com/diy-wifi-raspberry-pi-touch-cam
