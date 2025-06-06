<h1 align="center">C3Mini-BlueJammer - by @emensta</h1>
<h1 align="center">Early Stage!</h1>
<div align="center">
  <h4 align="center">Picture soon!</h3>
  <h3 align="center">Jamming is ILLEGAL! Educational purposes only!</h3>
</div>

<div align="center">
<a href="https://github.com/EmenstaNougat/C3Mini-BlueJammer" title="Go to GitHub repo">
  <img src="https://img.shields.io/static/v1?label=EmenstaNougat&message=C3Mini-BlueJammer&color=purple&logo=github" alt="EmenstaNougat - C3Mini-BlueJammer">
</a>
<a href="https://github.com/EmenstaNougat/C3Mini-BlueJammer">
  <img src="https://img.shields.io/github/stars/EmenstaNougat/C3Mini-BlueJammer?style=social" alt="stars - C3Mini-BlueJammer">
</a>
<a href="https://github.com/EmenstaNougat/C3Mini-BlueJammer">
  <img src="https://img.shields.io/github/forks/EmenstaNougat/C3Mini-BlueJammer?style=social" alt="forks - C3Mini-BlueJammer">
</a>
</div>


<h4 align="center">
  <a href="https://github.com/EmenstaNougat/C3Mini-BlueJammer/edit/main/README.md#hardware---make-your-own-c3mini-bluejammer">Make your own</a>
    <span> | </span>
  <a href="https://github.com/EmenstaNougat/C3Mini-BlueJammer/edit/main/README.md#c3mini-gt24-mini-pinout--battery-mod">Schematics</a>
    <span> | </span>
  <a href="https://github.com/EmenstaNougat/C3Mini-BlueJammer/edit/main/README.md#pcbs-with-c3mini-and-rf-module-capability---elecrow">PCB's</a>
    <span> | </span>
  <a href="https://github.com/EmenstaNougat/C3Mini-BlueJammer#video-tutorials-and-demonstrations">Demos</a>
    <span> | </span>
  <a href="https://github.com/EmenstaNougat/C3Mini-BlueJammer#operation-channels">Channels</a>
    <span> | </span>
  <a href="https://github.com/EmenstaNougat/C3Mini-BlueJammer?tab=readme-ov-file#flashing-the-firmware">Flashing</a>
    <span> | </span>
  <a href="https://github.com/EmenstaNougat/C3Mini-BlueJammer/edit/main/README.md#about">About</a>
    <span> | </span>
  <a href="https://emensta.pages.dev">Website</a>
</h4>

## C3Mini-BlueJammer
The C3Mini-BlueJammer (Bluetooth jammer, BLE jammer, WiFi jammer, RC jammer) disrupts various devices using an C3Mini and nRF24 modules, causing plenty of noise and sending unnecessary packets (DoS) but in a super mini form factor!.              
                                                                    
It interrupts:  
**The whole 2.4GHz broadband!** Everything that works on 2.4GHz is being interfered, like:                                                       
audio in speakers being transmitted over bluetooth, microphones on 2.4GHz, smartphone connections, WiFi, RC Drones (etc.), IoT devices, smart gadgets, wireless keyboard & mouse, just anything on 2.4GHz!

Ideal for controlled disruption and security testing. Based on 2,4GHz communication in a mini and stealthy way.

It has a big range (over 30Meters+ - may vary on your antenna and hardware setup!) on newest Bluetooth versions with casual 2.4GHz antennas, you can easily increase this aswell by taking some simple "bigger" router antennas.
An amplifier (2.4GHz) may be an good option too, yet it won't be that "Mini" anymore!

Remember that jamming is illegal and should not be used with malicious intent!



Notice!
This is a fresh firmware.
Everything is working, except the 0.42" OLED on the ESP32-C3, this feature will be added soon!



## PCB's with C3Mini and RF-module capability - [Elecrow](https://www.elecrow.com/c3mini-rf-by-atemensta.html)
**C3Mini-RF PCB:**  "C3Mini-RF"  
This PCB can fit an C3Mini and 2 GT24-Mini modules to create several things you'd like.  
***Remember: It is not intended for illegal use, neither for my project!***  
For this one, all you need is listed below:  

**Required:**  
- **[C3Mini Dev Module](https://s.click.aliexpress.com/e/_oluRXPm)**
- **[GT24-Mini](https://s.click.aliexpress.com/e/_omlnE88)** (2x)

**Additional:**  
- **[TP4056 Charging Module (Micro-USB/Type-C)](https://s.click.aliexpress.com/e/_oCqORHE)**  
- **[JST PH 2.0 Connector](https://s.click.aliexpress.com/e/_ooSOhDd)**  
- **[3.7V Li-Ion Battery](https://s.click.aliexpress.com/e/_on04mQ7)**  
![C3Mini-RF PCB](https://www.elecrow.com/media/catalog/product/cache/b6b9577937e6a96f50e53ddc42983628/d/7/d7b69e85-d16f-48e5-8b3b-1758be470f75.jpg)
[Shop](https://www.elecrow.com/c3mini-rf-by-atemensta.html)



## Video tutorials and demonstrations (ESP32-BlueJammer, works the same!)
[Full DIY assembling video tutorial](https://www.tiktok.com/@emensta/video/7389783018002550049)

[Full DIY assembling video tutorial (if the TikTok is not available for you)](https://www.mediafire.com/file/mgb3wicdifkq1ce/C3Mini-BlueJammerByEmensta-DIYTutorial.mp4/file)

---

[Demonstration](https://vm.tiktok.com/ZGec5Mqg7/)

[Demonstration (if the TikTok is not available for you)](https://www.mediafire.com/file/xgru01ihbw26mfu/C3Mini-BlueJammerByEmensta-Demonstration.mp4/file)

---

[Flashing process](https://www.tiktok.com/@emensta/video/7413509704401292577)

[Flashing process (if the TikTok is not available for you)](https://www.mediafire.com/file/2aj4hmf9zt7w6sw/C3Mini-BlueJammerByEmensta-FlashingProcess.mp4/file)

---

## Operation Channels
- **Bluetooth** = 79CH  
  Frequency Range: 2.402 GHz to 2.480 GHz  
  Channel Width: 1 MHz

- **BLE** = 40CH  
  Frequency Range: 2.400 GHz to 2.4835 GHz  
  Channel Width: 2 MHz

- **WiFi** = 14CH  
  Frequency Range: 2.400 GHz to 2.4835 GHz  
  Channel Width: Typically 20 MHz, but can be 22 MHz or 40 MHz in some cases

- **RC drones, etc.** = 1-125CH  
  Frequency Range: 2.400 GHz to 2.525 GHz  
  Channel Width: 1 MHz



## How to use?
To disrupt various channels on the 2.4GHz band, do the following to enable your C3Mini-BlueJammer:
- Every mode starts right away after powering on the device! There is no additional button to start the attack!  
- It simply jams right away once powered!

### C3MiniOLED-BlueJammer firmware:
- use the "Boot" button on the C3Mini to switch between the channel modes on the Combo-Firmware!
- the 0.42" OLED will display your current operation channel
- the status LED let's you know about the current state you're in:  
1 blink = BT  
2 blinks = BLE  
3 blinks = WiFi  
4 blinks = RC  
- the serial output of your C3Mini-BlueJammer will output the following lines when switching mode:  
State 1: Bluetooth  
State 2: Bluetooth Low Energy  
State 3: WiFi  
State 4: RC  

## Hardware - Make your own C3Mini-BlueJammer
(Aliexpress affilate links to support me-linked to the item names)
### Required:

- **[ESP32-C3 OLED Dev Module](https://s.click.aliexpress.com/e/_oluRXPm)**
- **[GT24-Mini](https://s.click.aliexpress.com/e/_omlnE88)** (2x)
- **[10uF Capacitor](https://s.click.aliexpress.com/e/_oFvFeYX)** (2x) (any voltage above 5V)
- **[Prototype PCB](https://s.click.aliexpress.com/e/_oBtd18j)** (at least 7x9 cm, but you will need to cut it down to fit the 3D-printed case, which fits a size of 7x5,5cm!)

### If you're looking to add a battery:

- **[3.7V Li-Ion Battery](https://s.click.aliexpress.com/e/_on04mQ7)**
- **[JST PH 2.0 Connector](https://s.click.aliexpress.com/e/_ooSOhDd)**
- **[TP4056 Charging Module (Micro-USB/Type-C)](https://s.click.aliexpress.com/e/_oCqORHE)**
- **[Slide Switch](https://s.click.aliexpress.com/e/_oowBkmu)**



## Antennas
Yes, you need at least both antennas for the nRF24's! Why? To have it working on a decent range!
The average range with standard known chinese 2.4GHz antennas is about 20-30meters. Upgrading those antennas will help a lot with getting more range!

2 antennas are for the GT1 and GT2 GT24-Mini modules!



## Flashing the firmware
### via webflasher (Easy)  %NOT READY YET%
![C3Mini-BlueJammerFlasher](https://dwdwpld.pages.dev/C3MiniBlueJammerFlasher.png)                                                                 
I've created a webflasher to make it super easy for you to flash your C3Mini chip with the C3Mini-BlueJammer firmware of your choice!  
- Visit [C3Mini-BlueJammerFlasher](https://C3Mini-bluejammerflasher.pages.dev)
- First, choose the firmware type, "Generic" or "0.96" OLED"
- choose the firmware you want to flash
- Connect your C3Mini via a data USB cable
- Flash the firmware of your choice :D

### Flashing C3Mini via binary files (Advanced yet simple)  
- Download the **.bin files** available on this repository
- Use any flasher of your choice
- Flash it :D

If your C3Mini is not showing up in the device list or won't get recognized you will need to have [THESE DRIVERS INSTALLED](https://www.silabs.com/documents/public/software/CP210x_Windows_Drivers.zip) which can be found on my [Discord server](https://discord.gg/yNGhKxzqUE) too!



## C3Mini-GT24-Mini pinout + battery mod
Here are both pinouts for HSPI and VSPI. You need both nRF24L01 modules connected in order to achieve full capability of the device.                
[GT24-Mini pinout](https://www.tinytronics.nl/image/cache/catalog/products/product-003610/gt-24-mini-wireless-module-nrf24l01-with-pa-and-lna-smd-back-600x600w.jpg)
### GT1
| 1st nRF24L01 module Pin | HSPI Pin (C3Mini) | 10uf capacitor |
|---------------|------------------|--------------------|
| VCC           | 3.3V             | (+) capacitor |
| GND           | GND              | (-) capacitor |
| CE            | GPIO 20  (RX)    |
| CSN           | GPIO 21  (TX)    |
| SCK           | GPIO 4           |
| MOSI          | GPIO 6           |
| MISO          | GPIO 5           |
| IRQ           |                  |

### GT2
| 2nd nRF24L01 module Pin | VSPI Pin (C3Mini) | 10uf capacitor |
|---------------|------------------|--------------------|
| VCC           | 3.3V             | (+) capacitor |
| GND           | GND              | (-) capacitor |
| CE            | GPIO 7           |
| CSN           | GPIO 10          |
| SCK           | GPIO 4           |
| MOSI          | GPIO 6           |
| MISO          | GPIO 5           |
| IRQ           |                  |

### Battery modification (additional)
| 3.7V Li-Ion battery | JST-PH2 connector    | TP4056 Charging Module | Mini Slide Switch | C3Mini |
|---------------------|----------------------|------------------------|-------------------|-------|
| (+) Battery         | (+) JST-PH2          | Bat +                  |                   |       |
| (-) Battery         | (-) JST-PH2          | Bat -                  |                   |       |
|                     |                      | OUT +                  | Switch in         |       |
|                     |                      | OUT -                  |                   |  GND  |
|                     |                      |                        | Switch out        |  3V3  |



### About
  There are several "BLE Jammers" available on GitHub, but they all have limitations in frequency range, channel coverage, and effective distance (around 5 meters). Therefore I decided to develop and code my own firmware for the C3Mini-BlueJammer, aiming for superior performance.
  AND THEY'RE NOT MINI ;)



## Discord
You can join my Discord server [here](https://discord.gg/emensta)!



## Portfolio and all my links
Here you can visit my Portfolio, you'll find everything that you're looking for [here](https://emensta.pages.dev)!



<h1 align="center"> DISCLAIMER </h1>

<h4 align="center">Please note that the use of this tool is entirely at your own risk. It is intended strictly for educational purposes and should not be used for any illegal or unethical activities. Jamming is illegal and can get you in big trouble!</h4>
<h4 align="center">I'm not responsible for your actions! </h4>
