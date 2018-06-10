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

Line 181-->#define _TTNSERVER "router name", configure ttn router name "router name"

Lines 197 to 202: Network Parameters TTN

                  define _DESCRIPTION "description"
                  
                  define _EMAIL "email"
                  
                  define _PLATFORM "ESP32"
                  
                  define _LAT 
                  
                  define _LON 
                  
                  define _ALT 8
                  
            
Line257: { "YOUR WIFI SSID", "YOUR WIFI SSID PASSWORD" } , Insert wifi ssid and wifi password

                                     In the file: loraModem.h

Line 31 to 46--> Select the frequency

                  uint32_t  freq = freqs[9];
                  uint8_t	 ifreq = 9;
    
