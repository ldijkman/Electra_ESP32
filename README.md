# Electra_ESP32

Electra_ESP32

https://ldijkman.github.io/Electra/

Saw this video https://youtu.be/0poh_2rBq7E

and now trying visual studio platform io  https://platformio.org/install/ide?install=vscode

hmm runs ok on raspberry pi 400

Help me Please?!

https://ldijkman.github.io/Electra/




well it doe something on check code

but i have no idea yet

```
how do i get a better lib_deps for wifi

arduino says Using library WiFi at version 1.0 in folder: /home/pi/.arduino15/packages/esp32/hardware/esp32/1.0.6/libraries/WiFi 

[env:esp32dev]
platform = espressif32
board = esp32dev
framework = arduino
lib_extra_dirs = /home/pi/Arduino/libraries
lib_deps =lorol/LittleFS_esp32@^1.0.6, /home/pi/.arduino15/packages/esp32/hardware/esp32/1.0.6/libraries/WiFi/



arduino librarys use

python /home/pi/.arduino15/packages/esp32/tools/esptool_py/3.0.0/esptool.py --chip esp32 elf2image --flash_mode dio --flash_freq 80m --flash_size 4MB -o /tmp/arduino_build_758462/ESP32-LittleFS-wifi-manager_with_editor.ino.bin /tmp/arduino_build_758462/ESP32-LittleFS-wifi-manager_with_editor.ino.elf
esptool.py v3.0-dev
python /home/pi/.arduino15/packages/esp32/hardware/esp32/1.0.6/tools/gen_esp32part.py -q /tmp/arduino_build_758462/partitions.csv /tmp/arduino_build_758462/ESP32-LittleFS-wifi-manager_with_editor.ino.partitions.bin
Multiple libraries were found for "SD.h"
 Used: /home/pi/.arduino15/packages/esp32/hardware/esp32/1.0.6/libraries/SD
 Not used: /home/pi/arduino-1.8.19/libraries/SD
Multiple libraries were found for "Timezone.h"
 Used: /home/pi/Arduino/libraries/Timezone
 Not used: /home/pi/Arduino/libraries/Timezone-master
Multiple libraries were found for "WiFi.h"
 Used: /home/pi/.arduino15/packages/esp32/hardware/esp32/1.0.6/libraries/WiFi
 Not used: /home/pi/arduino-1.8.19/libraries/WiFi
 Not used: /home/pi/Arduino/libraries/WiFi
Multiple libraries were found for "SPIFFSEditor.h"
 Used: /home/pi/Arduino/libraries/ESPAsyncWebServer-master
 Not used: /home/pi/Arduino/libraries/oldESPAsyncWebServer-master
Using library Timezone at version 1.2.3 in folder: /home/pi/Arduino/libraries/Timezone 
Using library Time-master at version 1.6 in folder: /home/pi/Arduino/libraries/Time-master 
Using library Wire at version 1.0.1 in folder: /home/pi/.arduino15/packages/esp32/hardware/esp32/1.0.6/libraries/Wire 
Using library Adafruit_Sensor-master at version 1.1.4 in folder: /home/pi/Arduino/libraries/Adafruit_Sensor-master 
Using library Adafruit_BME280_Library-master at version 2.1.2 in folder: /home/pi/Arduino/libraries/Adafruit_BME280_Library-master 
Using library SPI at version 1.0 in folder: /home/pi/.arduino15/packages/esp32/hardware/esp32/1.0.6/libraries/SPI 
Using library WiFi at version 1.0 in folder: /home/pi/.arduino15/packages/esp32/hardware/esp32/1.0.6/libraries/WiFi 
Using library AsyncTCP-master at version 1.1.1 in folder: /home/pi/Arduino/libraries/AsyncTCP-master 
Using library ESPmDNS at version 1.0 in folder: /home/pi/.arduino15/packages/esp32/hardware/esp32/1.0.6/libraries/ESPmDNS 
Using library FS at version 1.0 in folder: /home/pi/.arduino15/packages/esp32/hardware/esp32/1.0.6/libraries/FS 
Using library LITTLEFS-master at version 1.0.6 in folder: /home/pi/arduino-1.8.19/libraries/LITTLEFS-master 
Using library ESPAsyncWebServer-master at version 1.2.4 in folder: /home/pi/Arduino/libraries/ESPAsyncWebServer-master 
Using library ArduinoJson at version 6.19.2 in folder: /home/pi/Arduino/libraries/ArduinoJson 
Using library NTPClient-master at version 3.2.0 in folder: /home/pi/Arduino/libraries/NTPClient-master 
Using library TFT_eSPI at version 2.4.44 in folder: /home/pi/Arduino/libraries/TFT_eSPI 
Using library SPIFFS at version 1.0 in folder: /home/pi/.arduino15/packages/esp32/hardware/esp32/1.0.6/libraries/SPIFFS 
Using library TJpg_Decoder-master at version 1.0.5 in folder: /home/pi/Arduino/libraries/TJpg_Decoder-master 
Using library SD at version 1.0.5 in folder: /home/pi/.arduino15/packages/esp32/hardware/esp32/1.0.6/libraries/SD 
Using library JSON_Decoder-master at version 0.1.1 in folder: /home/pi/Arduino/libraries/JSON_Decoder-master 
Using library OpenWeather-master at version 0.2.5 in folder: /home/pi/Arduino/libraries/OpenWeather-master 
Using library WiFiClientSecure at version 1.0 in folder: /home/pi/.arduino15/packages/esp32/hardware/esp32/1.0.6/libraries/WiFiClientSecure 
/home/pi/.arduino15/packages/esp32/tools/xtensa-esp32-elf-gcc/1.22.0-97-gc752ad5-5.2.0/bin/xtensa-esp32-elf-size -A /tmp/arduino_build_758462/ESP32-LittleFS-wifi-manager_with_editor.ino.elf
Sketch uses 1023018 bytes (48%) of program storage space. Maximum is 2097152 bytes.
Global variables use 48004 bytes (14%) of dynamic memory, leaving 279676 bytes for local variables. Maximum is 327680 bytes.
```
