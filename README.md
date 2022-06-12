# Electra_ESP32

Electra_ESP32

https://ldijkman.github.io/Electra/

Saw this video https://youtu.be/0poh_2rBq7E

and now trying visual studio platform io  https://platformio.org/install/ide?install=vscode

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







> Executing task in folder 220612-104357-esp32dev: platformio run <

Processing esp32dev (platform: espressif32; board: esp32dev; framework: arduino)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Verbose mode can be enabled via `-v, --verbose` option
CONFIGURATION: https://docs.platformio.org/page/boards/espressif32/esp32dev.html
PLATFORM: Espressif 32 (4.4.0) > Espressif ESP32 Dev Module
HARDWARE: ESP32 240MHz, 320KB RAM, 4MB Flash
DEBUG: Current (cmsis-dap) External (cmsis-dap, esp-prog, iot-bus-jtag, jlink, minimodule, olimex-arm-usb-ocd, olimex-arm-usb-ocd-h, olimex-arm-usb-tiny-h, olimex-jtag-tiny, tumpa)
PACKAGES: 
 - framework-arduinoespressif32 @ 3.20003.0 (2.0.3) 
 - tool-esptoolpy @ 1.30300.0 (3.3.0) 
 - toolchain-xtensa-esp32 @ 8.4.0+2021r2-patch3
Converting MoonPhase.ino
LDF: Library Dependency Finder -> https://bit.ly/configure-pio-ldf
LDF Modes: Finder ~ chain, Compatibility ~ soft
Warning! Ignoring broken library manifest in /home/pi/Arduino/libraries/ESP_DoubleResetDetector
Warning! Ignoring broken library manifest in /home/pi/Arduino/libraries/JSON_Decoder-master
Library Manager: Could not parse manifest -> Expecting ',' delimiter: line 27 column 5 (char 769)
Library Manager: Could not parse manifest -> Expecting property name enclosed in double quotes: line 14 column 3 (char 349)
Found 84 compatible libraries
Scanning dependencies...
Library Manager: Could not parse manifest -> Expecting ',' delimiter: line 27 column 5 (char 769)
Library Manager: Could not parse manifest -> Expecting property name enclosed in double quotes: line 14 column 3 (char 349)
Dependency Graph
|-- LittleFS_esp32 @ 1.0.6
|   |-- FS @ 2.0.0
|-- Adafruit BME280 Library @ 2.1.2
|   |-- Adafruit Unified Sensor @ 1.1.4
|   |-- SPI @ 2.0.0
|   |-- Wire @ 2.0.0
|-- Adafruit Unified Sensor @ 1.1.4
|-- ArduinoJson @ 6.19.2
|-- AsyncTCP @ 1.1.1
|-- ESP Async WebServer @ 1.2.4
|   |-- AsyncTCP @ 1.1.1
|   |-- AsyncElegantOTA @ 2.2.6
|   |   |-- AsyncTCP @ 1.1.1
|   |   |-- FS @ 2.0.0
|   |   |-- WiFi @ 1.2.7
|   |   |   |-- SPI @ 2.0.0
|   |-- FS @ 2.0.0
|   |-- WiFi @ 1.2.7
|   |   |-- SPI @ 2.0.0
|   |-- ArduinoJson @ 6.19.2
|-- ESPmDNS @ 2.0.0
|   |-- WiFi @ 1.2.7
|   |   |-- SPI @ 2.0.0
|-- FS @ 2.0.0
|-- JSON_Decoder-master
|-- NTPClient @ 3.1.0
|-- OpenWeather @ 0.2.5
|   |-- JSON_Decoder-master
|   |-- WiFi @ 1.2.7
|   |   |-- SPI @ 2.0.0
|   |-- WiFiClientSecure @ 2.0.0
|   |   |-- WiFi @ 1.2.7
|   |   |   |-- SPI @ 2.0.0
|-- SPI @ 2.0.0
|-- TFT_eSPI @ 2.4.44
|   |-- SPIFFS @ 2.0.0
|   |   |-- FS @ 2.0.0
|   |-- FS @ 2.0.0
|   |-- LittleFS @ 2.0.0
|   |   |-- FS @ 2.0.0
|   |   |-- LittleFS_esp32 @ 1.0.6
|   |   |   |-- FS @ 2.0.0
|   |-- SPI @ 2.0.0
|-- Timezone @ 1.2.3
|   |-- Time @ 1.6
|-- WiFi @ 1.2.7
|   |-- SPI @ 2.0.0
|-- Wire @ 2.0.0
|-- TJpg_Decoder @ 1.0.5
|   |-- LittleFS_esp32 @ 1.0.6
|   |   |-- FS @ 2.0.0
|   |-- SPIFFS @ 2.0.0
|   |   |-- FS @ 2.0.0
|   |-- FS @ 2.0.0
|   |-- LittleFS @ 2.0.0
|   |   |-- FS @ 2.0.0
|   |   |-- LittleFS_esp32 @ 1.0.6
|   |   |   |-- FS @ 2.0.0
|   |-- SD @ 2.0.0
|   |   |-- FS @ 2.0.0
|   |   |-- SPI @ 2.0.0
|-- SPIFFS @ 2.0.0
|   |-- FS @ 2.0.0
|-- LittleFS @ 2.0.0
|   |-- FS @ 2.0.0
|   |-- LittleFS_esp32 @ 1.0.6
|   |   |-- FS @ 2.0.0
|-- SD @ 2.0.0
|   |-- FS @ 2.0.0
|   |-- SPI @ 2.0.0
Building in release mode
Compiling .pio/build/esp32dev/src/Electra_ESP32.cpp.o
Compiling .pio/build/esp32dev/src/GfxUi.cpp.o
Compiling .pio/build/esp32dev/src/MoonPhase.ino.cpp.o
Generating partitions .pio/build/esp32dev/partitions.bin
Compiling .pio/build/esp32dev/lib1e0/FS/FS.cpp.o
Compiling .pio/build/esp32dev/lib1e0/FS/vfs_api.cpp.o
src/Electra_ESP32.cpp: In function 'bool initWiFi()':
src/Electra_ESP32.cpp:527:8: error: 'class WiFiClass' has no member named 'mode'
   WiFi.mode(WIFI_STA);
        ^~~~
src/Electra_ESP32.cpp:527:13: error: 'WIFI_STA' was not declared in this scope
   WiFi.mode(WIFI_STA);
             ^~~~~~~~
src/Electra_ESP32.cpp:527:13: note: suggested alternative: 'WIFI_IF_STA'
   WiFi.mode(WIFI_STA);
             ^~~~~~~~
             WIFI_IF_STA
src/Electra_ESP32.cpp:538:21: error: could not convert 'WiFi.WiFiClass::config(IPAddress(localIP), IPAddress(gatewayIP), IPAddress(subnetMask))' from 'void' to 'bool'
     if (!WiFi.config(localIP, gatewayIP, subnetMask)) {
          ~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
src/Electra_ESP32.cpp:538:52: error: in argument to unary !
     if (!WiFi.config(localIP, gatewayIP, subnetMask)) {
                                                    ^
src/Electra_ESP32.cpp:544:24: error: invalid conversion from 'const char*' to 'char*' [-fpermissive]
   WiFi.begin(ssid.c_str(), pass.c_str());
              ~~~~~~~~~~^~
In file included from src/Electra_ESP32.cpp:201:
/home/pi/Arduino/libraries/WiFi/src/WiFi.h:79:21: note:   initializing argument 1 of 'int WiFiClass::begin(char*, const char*)'
     int begin(char* ssid, const char *passphrase);
               ~~~~~~^~~~
src/Electra_ESP32.cpp: In function 'String processor(const String&)':
src/Electra_ESP32.cpp:627:32: error: 'class WiFiClass' has no member named 'dnsIP'
     mystring += "DNS: " + WiFi.dnsIP().toString() + "<br>";
                                ^~~~~
src/Electra_ESP32.cpp:628:43: error: no matching function for call to 'WiFiClass::macAddress()'
     mystring += "MAC: " + WiFi.macAddress() + "<br>";
                                           ^
In file included from src/Electra_ESP32.cpp:201:
/home/pi/Arduino/libraries/WiFi/src/WiFi.h:137:14: note: candidate: 'uint8_t* WiFiClass::macAddress(uint8_t*)'
     uint8_t* macAddress(uint8_t* mac);
              ^~~~~~~~~~
/home/pi/Arduino/libraries/WiFi/src/WiFi.h:137:14: note:   candidate expects 1 argument, 0 provided
src/Electra_ESP32.cpp: In function 'void setup()':
src/Electra_ESP32.cpp:652:3: error: 'initWebSocket' was not declared in this scope
   initWebSocket();
   ^~~~~~~~~~~~~
src/Electra_ESP32.cpp:652:3: note: suggested alternative: 'AsyncWebSocket'
   initWebSocket();
   ^~~~~~~~~~~~~
   AsyncWebSocket
src/Electra_ESP32.cpp: In lambda function:
src/Electra_ESP32.cpp:850:7: error: 'Relays_ON' was not declared in this scope
       Relays_ON();
       ^~~~~~~~~
Compiling .pio/build/esp32dev/lib852/LittleFS_esp32/LITTLEFS.cpp.o
src/Electra_ESP32.cpp: In lambda function:
src/Electra_ESP32.cpp:859:7: error: 'Relays_OFF' was not declared in this scope
       Relays_OFF();
       ^~~~~~~~~~
src/Electra_ESP32.cpp: In function 'void setup()':
src/Electra_ESP32.cpp:1049:5: error: 'checkpost' was not declared in this scope
     checkpost();   // post submit for AP and STA?
     ^~~~~~~~~
src/Electra_ESP32.cpp:1070:10: error: 'class WiFiClass' has no member named 'softAP'
     WiFi.softAP(broadcastintheair.c_str(), NULL);                                        // i do not know, strings and chars thing drive me nuts
          ^~~~~~
src/Electra_ESP32.cpp:1073:25: error: 'class WiFiClass' has no member named 'softAPIP'
     IPAddress IP = WiFi.softAPIP();
                         ^~~~~~~~
src/Electra_ESP32.cpp:1084:5: error: 'checkpost' was not declared in this scope
     checkpost();   // post submit for AP and STA?
     ^~~~~~~~~
src/Electra_ESP32.cpp: In function 'void loop()':
src/Electra_ESP32.cpp:1154:5: error: 'touch_calibrate' was not declared in this scope
     touch_calibrate();           // calibrate tft touch screen start from html url
     ^~~~~~~~~~~~~~~
src/Electra_ESP32.cpp:1154:5: note: suggested alternative: 'gocalibrate'
     touch_calibrate();           // calibrate tft touch screen start from html url
     ^~~~~~~~~~~~~~~
     gocalibrate
src/Electra_ESP32.cpp:1350:5: error: 'Relays_OFF' was not declared in this scope
     Relays_OFF(); // Turn relaispin OFF
     ^~~~~~~~~~
src/Electra_ESP32.cpp:1357:9: error: 'notifyClients' was not declared in this scope
         notifyClients();                     // send countdown once every half second
         ^~~~~~~~~~~~~
src/Electra_ESP32.cpp:1357:9: note: suggested alternative: 'timeClient'
         notifyClients();                     // send countdown once every half second
         ^~~~~~~~~~~~~
         timeClient
src/Electra_ESP32.cpp:1387:5: error: 'notifyClients' was not declared in this scope
     notifyClients();
     ^~~~~~~~~~~~~
src/Electra_ESP32.cpp:1387:5: note: suggested alternative: 'timeClient'
     notifyClients();
     ^~~~~~~~~~~~~
     timeClient
src/Electra_ESP32.cpp:1398:5: error: 'browseService' was not declared in this scope
     browseService("http", "tcp");           // scan for other mdns devices urls in local network
     ^~~~~~~~~~~~~
Compiling .pio/build/esp32dev/lib852/LittleFS_esp32/esp_littlefs.c.o
src/Electra_ESP32.cpp: In function 'void Relays_ON()':
src/Electra_ESP32.cpp:1622:3: error: 'notifyClients' was not declared in this scope
   notifyClients();
   ^~~~~~~~~~~~~
src/Electra_ESP32.cpp:1622:3: note: suggested alternative: 'timeClient'
   notifyClients();
   ^~~~~~~~~~~~~
   timeClient
src/Electra_ESP32.cpp: In function 'void Relays_OFF()':
src/Electra_ESP32.cpp:1632:3: error: 'notifyClients' was not declared in this scope
   notifyClients();
   ^~~~~~~~~~~~~
src/Electra_ESP32.cpp:1632:3: note: suggested alternative: 'timeClient'
   notifyClients();
   ^~~~~~~~~~~~~
   timeClient
.pio/libdeps/esp32dev/LittleFS_esp32/src/esp_littlefs.c:19:2: warning: #warning ("Use the built-in LITTLEFS library") [-Wcpp]
 #warning("Use the built-in LITTLEFS library")
  ^~~~~~~
src/Electra_ESP32.cpp: In function 'void drawAstronomy()':
src/Electra_ESP32.cpp:2236:18: error: 'moon_phase' was not declared in this scope
   uint8_t icon = moon_phase(y, m, d, h, &ip);
                  ^~~~~~~~~~
src/Electra_ESP32.cpp:2236:18: note: suggested alternative: 'moonPhase'
   uint8_t icon = moon_phase(y, m, d, h, &ip);
                  ^~~~~~~~~~
                  moonPhase
Archiving .pio/build/esp32dev/lib1e0/libFS.a
Indexing .pio/build/esp32dev/lib1e0/libFS.a
Compiling .pio/build/esp32dev/lib852/LittleFS_esp32/lfs.c.o
*** [.pio/build/esp32dev/src/Electra_ESP32.cpp.o] Error 1
.pio/libdeps/esp32dev/LittleFS_esp32/src/LITTLEFS.cpp: In member function 'virtual bool LITTLEFSImpl::exists(const char*)':
.pio/libdeps/esp32dev/LittleFS_esp32/src/LITTLEFS.cpp:44:28: error: no matching function for call to 'LITTLEFSImpl::open(const char*&, const char [2])'
     File f = open(path, "r");
                            ^
In file included from .pio/libdeps/esp32dev/LittleFS_esp32/src/LITTLEFS.cpp:17:
/home/pi/.platformio/packages/framework-arduinoespressif32/libraries/FS/src/vfs_api.h:38:17: note: candidate: 'virtual fs::FileImplPtr VFSImpl::open(const char*, const char*, bool)'
     FileImplPtr open(const char* path, const char* mode, const bool create) override;
                 ^~~~
/home/pi/.platformio/packages/framework-arduinoespressif32/libraries/FS/src/vfs_api.h:38:17: note:   candidate expects 3 arguments, 2 provided
*** [.pio/build/esp32dev/lib852/LittleFS_esp32/LITTLEFS.cpp.o] Error 1
============================================================================ [FAILED] Took 26.68 seconds ============================================================================
The terminal process "platformio 'run'" terminated with exit code: 1.

Terminal will be reused by tasks, press any key to close it.

```
