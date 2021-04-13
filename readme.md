This project is written for heltec_wifi_lora32_board. this is GPS code(AIR530). it connect with the board's uart.



please make sure you have install these projects:

https://github.com/Heltec-Aaron-Lee/WiFi_Kit_series

https://github.com/HelTecAutomation/Heltec_ESP32

## How to use this lib?

1. add this file(`printGPSInfo_ESP32`) to this location on your computer `C:\Users\USERNAME\Documents\Arduino\libraries\Heltec_ESP32\examples`

2. add this file (`folder`) to this location on your computer:

   `C:\Users\USERNAME\Documents\Arduino\libraries\Heltec_ESP32\src`

3. Add this Statement `extern HardwareSerial GPSSerial;`on this file

   `C:\Users\username\Documents\Arduino\hardware\heltec\esp32\cores\esp32\HardwareSerial.h`

4.  Add this Statement `HardwareSerial GPSSerial(2);`on this file 29 line

   `C:\Users\username\Documents\Arduino\hardware\heltec\esp32\cores\esp32\HardwareSerial.cpp`