# NodeMcu

The NodeMCU is an open source IoT platform built around the popular ESP8266 Wifi chip.


The ESP8266 is available in a variety of different form factors and multiple commercial products. One of the most significant features of the ESP8266 is the ease with which new firmwares can be uploaded on to it which makes development and customization easy.


These include pre-existing platforms such as ESPEasy - https://www.letscontrolit.com/wiki/index.php/ESPEasy

Or the ability to develop your own programs in either...

    MicroPython - https://docs.micropython.org/en/latest/esp8266/esp8266/tutorial/intro.html
    
    Arduino C - https://github.com/esp8266/Arduino
    
    or LUA - https://nodemcu.readthedocs.io/en/master/en/


Additional information about these options is available in the appropriate .md file.

## Coventry University lab machines
In order to use a NodeMCU with the university computers additional drivers are required, you can install these on any university machine by installing the Arduino 1.8.5 software via the AppsAnywhere software portal.

## Personal machines
If you are using a Windows machine you will need to install drivers yourself. If using a V2 board install the <a href="https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers">CP2102 driver</a>, V3 install the <a href="https://github.com/nodemcu/nodemcu-devkit/tree/master/Drivers">CH340G driver</a>.
