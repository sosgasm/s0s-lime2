# Homeserver with Olimex Lime2 A20

## It's 2024 and the Olimex board is still working. Mostly used as a webserver.

<img src="/lime.jpg?raw=true" width="500px">

## Getting Started
So, I got myself a superb quality singleboard computer and turned it into a project.
I use this server for multiple purposes: Sandbox, storage, webserver, and I've got Irssi running 24/7..etc. 

e.g. : A friend got me a nfc reader + card. The best thing I could come up with, was connect it to my DIY server and make it run a script that sends an email.
The best thing about this device is that I added a lithium battery that I can switch on whenever the Lime is unplugged from it's main power supply. The server doesn't lose it's power for a while. 

### Prerequisites

```
I've found most parts at my local hackerspace, so check your surroundings, ask friends. 

Hardware:
* Olimex Lime2 A20
* 32GB MicroSD card
* An old server power supply rack
* Lithium Ion battery 3000mAh
```

```
* 3mm thick piece of plywood (Size depends on the size of the power supply rack)
* White paint to decorate plywood
* Computer to flash your SD card with
* 500GB SSD
* A switch to power on/off the Lithium battery
* Wifi Dongle
* Olimex Lime2 A20 Manual
```

```
Cables:
* Jumper Wires
* Power supply (5V)
* SATA (data cable) and power cable. Please follow the link below:
```
[Olimex SATA cable](https://www.olimex.com/Products/Components/Cables/SATA-CABLE-SET)

```
I installed an unofficial Armbian image which works fine, but is now unsupported. You will find an archive of Armbian images for this board, on their website.  
OS:
* Armbian Focal (https://www.armbian.com/download/?tx_maker=olimex)
[Latest Armbian OS (Unofficial)](https://armbian.systemonachip.net/archive/lime2/archive/)
```
