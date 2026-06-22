# ESP Home Configs

Here are a bunch of configs for various boards, in various configurations/usages, used around my house.

## Boards

### In Use

* Waveshare GEEK ESP32-C6
  * Home Assistant BLE Proxy
  * Display shows climate info from around the house
    * A few pages, including pool/outdoors, indoors, WiFi/HASS connection info
  * BME280 over I2C
    * May change to SHT41 & SPA06 over I2C


* Waveshare ePaper 1.54" ESP32-S3
  * Home Assistant BLE Proxy
  * ePaper shows pool and outside climate info
    * On the back porch for pool proximity
  * Using the "USB" always-plugged-in config:
    * Allows it to be a BLE proxy for outdoor sensors
  * Reports climate data from internal SHT41 sensor
    * But not used because it's in the case and not very accurate


* ABRobot SuperMini OLED ESP32-C3
  * Home Assistant BLE Proxy
  * Display shows its own local climate info
  * BME280 over I2C
    * Some need adjustments to account for high temperature reporting
      * Handled in the ESPHome config
      * Got too hot when soldering?
  * Two matching configs spread around the house
    * One other config for testing on a breadboard
  * (Sold as "Teyleten", but factory firmware says "ABRobot" at boot)

### Next

* Waveshare Touch LCD 1.54" ESP32-S3
  * Clone of ESP32-S3-BOX example Voice Assistant config
  * Display shows VA status and responses
  * Needs some tweaking, the VA response is inconsistent


* Adafruit Mag-Tag ESP32-S3
  * ePaper shows forecast and local climate data
  * Needs tweaking for battery life
  * May attach another climate sensor, can't have too many!
    * ?SHT41 & SPA06 over I2C?


* Waveshare Touch LCD 1.47" ESP32-C6
  * Display needs some tweaking, sometimes doesn't boot correctly
  * Home Assistant BLE Proxy
  * Display Shows climate info from around the house
  * May attach another climate sensor, can't have too many!

### Others

Adafruit QT Py ESP32-S3
  * ~~BME280 over I2C~~
  * SHT41 & SPA06 over I2C
  * Home Assistant BLE Proxy
  * replaced by SuperMini and Geek boards, so the more powerful S3 can be used for something else
