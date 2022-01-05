# IOT-smart-street-light
An IOT smart lighting system using LDR, IR and nodeMCU. 
We use LDR for brightness value from the surrounding,
IR for motion detection, and nodemcu because it is an open source platform based on ESP8266 which can connect objects and let data transfer using the Wi-Fi protocol.


Download and install the libraries by following the below links:
Go to files->Preference.
pate ' https://dl.espressif.com/dl/package_esp32_index.json,http://arduino.esp8266.com/stable/package_esp8266com_index.json ' in Additional Board Manager URLs: 
then go to library manager and
add esp8266 by ESP8266 Community version 2.7.4
download the zip file from the below links and add it in the libraries
https://github.com/FirebaseExtended/firebase-arduino/blob/master/src/Firebase.h    vesion 2.7.5
https://github.com/bblanchon/ArduinoJson   version 5.13.5

If it isn't updating on firbase
-> Copy your firbase host url
-> Paste the url and get hexadecimal from, https://www.grc.com/fingerprints.htm
-> Open your firebase-arduino-master folder and go to firbaseHTTPClient.h
-> Open it using notepad and chnage the hex value at the bottom of the file.
