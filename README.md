<p align="center">
  <img 
    width=50%
    height=50%
    src="https://i.imgur.com/b04QAsB.png"
  >
</p>

# Raspberry Pi network-attached storage (NAS) Server—4th  Part
### Raspberry-PI-OLED-STATS-DISPLAY



![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)![Raspberry Pi](https://img.shields.io/badge/-RaspberryPi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)![Mac OS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)![IOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white)![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

This Tutorial is a Part of RPI NAS Server. 

In this tutorial I am going to add I2C OLED  display to raspberry. I am using it for stats display, which will show CPU usage, Memory usage, Disk usage and IP address. In here I am using 128x64 I2C OLED. 
 Product Link:
 - [amzazon link](https://www.amazon.in/s?k=I2C+OLED+128+64&crid=8PDQTRB2B5KH&sprefix=i2c+oled+128+64+%2Caps%2C195&ref=nb_sb_noss_2 )
 - [Robu.in](https://robu.in/product/1-3-inch-i2c-iic-oled-lcd-module-4pin-with-vcc-gnd-white/)

If you do not want to solder the display, I reccomend to use female to female jumper cables.
 Product Link:
 - [amzazon link](https://www.amazon.in/s?k=female+to+female+jumper+cables&crid=1MDSATN53AINJ&sprefix=female+to+female+jumper+cables%2Caps%2C210&ref=nb_sb_noss_1)
 
![This is image](https://i.imgur.com/X0JSGas.png)

<p align="center">
  <img 
       src="https://i.imgur.com/tCJdn9nm.jpg"
  >
</p>

## Connecting Your OLED Stats Display To Your Raspberry Pi
 1. The OLED display’s terminals are labelled on the front
 
![This is image](https://i.imgur.com/Oe38PuP.png)

2. These are  GND, VCC, SCL, and SDA

| | Description|
| --- | --- | 
| GND |Ground Voltage|
| VCC | Voltage Common Collector|
|SCL | The line that carries the clock signal|
|SDA| The line for the master and slave to send and receive data|
