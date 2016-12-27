# Ardurino-flash backup AT firmware to ESP8266

## How to

Flash AT commands firmware in ESP8266 ESP-01 device

The module comes with AT commands firmware when buy but you can flash other firmware into the module like NodeMCU etc. 
But if we want to reflash Espressif's AT commands firmware again in the Wi-Fi module it is very simple.

Do the following steps to download and Flash AT command firmware into the module:

1. Download Espressif's original ESP8266 Flasher.exe and ESP8266_AT_firmware.bin. Please click here to download.
2. Unzip the zip file.
3. Open ESP8266 flasher and add binary.
4. Connect ESP8266 ESP-01 with USB to serial converter. Connect GPIO0 to ground to put the module into flashing mode.
5. Click to flash the software.
6. Done!

### Sources
http://www.instructables.com/id/Intro-Esp-8266-firmware-update/?ALLSTEPS
http://esp8266internetofthings.blogspot.cz/2015/10/how-to-flash-at-commands-firmware-in.html
