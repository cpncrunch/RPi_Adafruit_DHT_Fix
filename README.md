# RPi_Adafruit_DHT_Fix

Raspberry Pi 4 fix of the Adafruit_DHT library

The Adafruit_DHT library for the DHT22 sensor has been depreciated so it only works up to the Raspberry Pi 3's. This is a simple fix to get it to work with the Raspberry Pi 4.

Just copy this file to the path: /usr/local/lib/python3.7/dist-packages/Adafruit_DHT/platform_detect.py. Overwrite the existing file and it should work.

Good luck!
