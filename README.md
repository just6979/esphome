# ESP Home Configs

Here are a bunch of configs for various boards, in various configurations/usages, used around my house.

## Boards

### In Use

* ABRobot SuperMini ESP32-C3 OLED
  * Home Assistant BLE Proxy
  * Display shows its own local climate info
  * BME280 over I2C
  * Two matching configs spread around the house
    * One other config for testing on a breadboard
  * (Sold as "Teyleten", but factory firmware says "ABRobot" at boot)

* Waveshare ESP32-C6 GEEK
  * Home Assistant BLE Proxy
  * Display shows climate info from around the house
    * A few pages, including WiFi/HASS connection info
  * BME280 over I2C

* Waveshare ESP32-S3 ePaper 1.54
  * Home Assistant BLE Proxy
  * ePaper shows pool and outside climate info
    * On the back porch for pool proximity
  * Using the "USB" config:
    * Always plugged in, to be a BLE proxy for outdoor sensors 

* Waveshare ESP32-S3 Touch LCD 1.54"
  * Clone of ESP32-S3-BOX example Voice Assistant config
  * Display shows VA status and responses
  * Needs some tweaking, the VA response is inconsistent

### Others

* Adafruit Mag-Tag
  * ePaper shows forecast and local climate data
  * Needs tweaking for battery life
  * May attach another climate sensor, can't have too many!

* Waveshare ESP32-C6 Touch LCD 1.47"
  * Display needs some tweaking, sometimes doesn't boot correctly
  * Home Assistant BLE Proxy
  * Display Shows climate info from around the house
    * A few pages, including pool/outdoors, indoors, WiFi/HASS connection info
  * May attach another climate sensor, can't have too many!

Adafruit QT Py ESP32-S3
  * BME280 over I2C
  * Home Assistant BLE Proxy
  * replaced by SuperMini and Geek boards, so the more powerful S3 can be used for something else
