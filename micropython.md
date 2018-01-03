# Installing MicroPython
You will need to install the MicroPython firmware on your ESP8266 device before you go any further.

Download the latest stable ESP8266 firmware from http://micropython.org/download#esp8266

Flash the firmware to the device, there are mutliple ways to do this but I recommend PyFlasher https://github.com/marcelstoer/nodemcu-pyflasher

For a NodeMcu the following settings should work 

Baud rate: 115200, Flash mode: DIO, Erase flash: No

# IDEs
There are a number of IDEs available, pick which ever works best for you...

  - ESPCut - http://espcut.com/ - A portable version of the software is available in the <a href="https://github.com/covcom/NodeMcu/tree/master/tools">tools</a> folder
  
  - uPyCraft - https://github.com/DFRobot/uPyCraft
  
  - ESPlorer - https://esp8266.ru/esplorer/
  
  - EsPy - https://github.com/jungervin/EsPy
  
# Code
You can interact with MicroPython either in interactive mode or use it to run files.

You can upload multiple files to your device but there are two reserved file names:

 - /boot.py - This file is on run immediately on power up/reset and should contain any code for configuring the device. Generally just leave this alone unless you're customizing MicroPython itself.
 - /main.py - This file (if present) is run after boot.py and should contain any code to be executed every time the device is powered on or reset.

Beware of writing code containing infinite loops as if may interfer with your ability to interact with MicroPython.
