# LoRa-Gateway-with-ESP32
 Library required to build a gateway with esp32
 
Original Library
=====================================================

https://github.com/kersing/ESP-1ch-Gateway-v5.0
 
libraries required (Arduino IDE)
=====================================================

1-SPIFFS

2-U8G2
 
Configuratios (Arduino IDE)
===================================================== 

In the file: ESP-sc-gway.h

Line 90--> #define _PIN_OUT 3 , 3 is the configurations for the esp32 pins
Line 181-->#define _TTNSERVER "router name", configure ttn server name
