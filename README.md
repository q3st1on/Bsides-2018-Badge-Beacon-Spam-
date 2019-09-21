# ESP8266 Beacon Spam


<p align="center"><img alt="project-logo" width="300" src="https://raw.githubusercontent.com/spacehuhn/esp8266_beaconSpam/master/img/beacon_spam.png"></p>
 
 ## What is this?
 
 This is a <a href="https://github.com/BsidesPerth/Badge2018/">Bsides Perth 2018 badge hack<a> (Ironically made in at the 2019 event as the 2019 badges hadn't arrived on the saturday). It Uses Spacehuhn's Beacon Spammer Code and prints the Ap names that it is broadcasting on the screen in a loop 
 
(Im lazy and so this code only works with the AP's provided (you have to change the values of the nested if statements at the bottom of loop for it to work in other scenarios) and if it is compiled on a windows 10 machine with a 5 character long user)
 
 ## SPACEHUHN'S SOCIALS
 
<p align="center">
🐦 <a href="https://twitter.com/spacehuhn">Twitter</a>
| 📺 <a href="https://www.youtube.com/channel/UCFmjA6dnjv-phqrFACyI8tw">YouTube</a>
| 🌍 <a href="https://spacehuhn.de">spacehuhn.de</a><br/>


## Installation

- First get an ESP8266 development board! If you don't know which one, have a look at the [supported devices](https://github.com/spacehuhn/esp8266_deauther/wiki/Supported-Devices) page from the Deauther wiki. It's for a different project, but the requirements are the same.
- Install [Arduino](https://www.arduino.cc/en/Main/software)
- Install the [ESP8266 Arduino Core](https://github.com/esp8266/Arduino#installing-with-boards-manager) version 2.0.0 or newer (no more changes are required)
- Download [this project](https://github.com/spacehuhn/esp8266_beaconSpam/archive/master.zip)
- Extract the .zip file somewhere and open the `esp8266_beaconSpam/esp8266_beaconSpam.ino` file with Arduino
- Edit the SSIDs if you want
- Select the correct Board under Tools > Board, the serial (COM) port your device is using and hit upload!

If you have trouble uploading, have a look at the [installation guide](https://github.com/spacehuhn/esp8266_deauther/wiki/Installation#drivers-and-com-port) on the Deauther Wiki. There you will also find drivers for the most common USB-Serial chips.  
Again, this is for the Deauther and not for this project, but the hardware (ESP8266) is the same and you will find a lot of trouble-shooting info on the Wiki there! :)  

## License

This project is licensed under the MIT License - see the [license file](LICENSE) file for details
