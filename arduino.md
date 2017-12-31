# Install Drivers (optional)
If you are using a Windows machine you will need to install drivers. 
Look on the base of the NodeCMU and install the appropriate drivers, the university machines should have the drivers pre-installed.

  CP2102 - https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers
  CH340G - https://github.com/nodemcu/nodemcu-devkit/tree/master/Drivers

# Install Arduino IDE (optional)
Download and install the Arduino IDE, the university machines should have the software already installed or installable through AppsAnywhere.
https://www.arduino.cc/en/Main/Software

## Configure Arduino IDE
Open the Arduino IDE.

Choose the Arduino > Preferences menu

Paste the following into the Additional Boards Manager box.
http://arduino.esp8266.com/stable/package_esp8266com_index.json
Click on OK to close the Preferences window

Open the Tools > Boards > Board manager menu.
find esp8266 by esp8266 community and install.

Before compiling and flashing to the microcontroller open the Tools > Board menu:
choose the NodeMCU 1.0 (ESP12-E Module)

As soon as the sketch has been flashed, open the Tools > Serial monitor and change the baud rate to match that in the sketch (typically 115,200).
