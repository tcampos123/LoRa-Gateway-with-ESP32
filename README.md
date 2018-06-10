# LoRa-Gateway-with-ESP32
 Library required to build a gateway with esp32
 
 
Original Library
=====================================================
https://github.com/kersing/ESP-1ch-Gateway-v5.0
 
libraries required
=====================================================

1-paho-mqtt 1.3.1:

 pip install paho-mqtt 
 
 https://pypi.org/project/paho-mqtt/

2- json:
 
 pip install json262 
 
 https://pypi.org/project/json262/
 
3- base64:
 
 https://docs.python.org/3/library/base64.html

Comments
========

Data to be inserted in the python code of the ttn network application:

#Application EUI

#Application ID

#ACCESS KEYS

ttn_client.connect ->configure for server you are using

***When running code, the output refers to the sensor data and the EUI of the device in ttn.***
