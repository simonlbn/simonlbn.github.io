---
title: Sensors
---

# Temperature and Humidity Sensors

| Sensor  | Price | Voltage | Range        | T Typ | T Max | Hum Typ | Hum Max |
| ------- | ----- | ------- | ------------ | ----- | ----- | ------- | ------- |
| BME280  | 19.90 | 1.7-3.6 |   0C to 60C  | 0.50C*| 1.00C |         | 3.0     |
| DHT11   |  5.00 | 3.5-5.5 | -40C to 80C  |       | 2.00C | 4.0     | 5.0     |
| DHT22   |  9.95 | 3.3-6.0 | -40C to 80C  | 0.50C |       | 2.0     | 5.0     |
| DS18B20 |  3.00 |         | -10C to 85C  | 0.50C | 0.50C | N/A     | N/A     |
| HDC1010 | 11.95 |         |   5C to 60C  | 0.20C | 0.40C | 2.0     | 3.0     |
| HDC1080 | 10.95 |         |   5C to 60C  | 0.20C | 0.40C | 2.0     | 4.0     |
| HTU21D  |       |  	    |   5C to 60C  | 0.30C | 0.40C | 2.0     | 3.0     |
| SHT30-D |       | 2.4-5.5 |   0C to 76C  | 0.20C |       | 2.0     | 8.0     |
| SHT31-D | 12.95 | 2.4-5.5 |   0C to 90C  | 0.20C |       | 2.0     | 3.5     |
| SHT35-D | 17.95 | 2.4-5.5 |  20C to 60C  | 0.10C |       | 1.5     | 3.0     |
| Si7021  |  6.95 | 1.9-3.6 |  10C to 85V  | 0.30C | 0.04C | 2.0     | 3.0     |
| Si7051  |  8.95 |         |  20C to 70C  | 0.13C | 0.13C | N/A     | N/A     |
| Si7055  |  4.95 |         | -40C to 125C | 0.40C | 0.50C | N/A     | N/A     |

Price is in USD and what can readaily be found available as either
breakout board or something with sane pins.

* T Typ = Temperature Typical &plusmn;
* T Max = Temperature Max &plusmn;
* Hum Typ = Humidity Typical &plusmn;
* Hum Max = Humidity Max &plusmn;

## BME280

* [Datasheet](https://ae-bst.resource.bosch.com/media/_tech/media/datasheets/BST-BME280_DS001-11.pdf)
* NOTE: "Temperature measured by the internal temperature sensor. This temperature value depends
on the PCB temperature, sensor element self-heating and ambient temperature and is typically
above ambient temperature."

## DHT11

* [Adafruit](https://www.adafruit.com/product/386) $5.

## DHT22

* [Adafruit](https://www.adafruit.com/product/385) $9.95.
* [Hobbycomponents](http://hobbycomponents.com/sensors/167-dht22-digital-temperature-humidity-sensor-module) 4.99 GBP.

## HDC1010

* [Closedcube](https://www.tindie.com/products/closedcube/hdc1010-high-accuracy-humiditytemperature-sensor/)

## HDC1080

* [Closedcube](https://www.tindie.com/products/closedcube/hdc1080-high-accuracy-humiditytemperature-sensor/)

## SHT30-D

* [Wemos](https://www.aliexpress.com/store/product/SHT30-Shield-for-WeMos-D1-mini-SHT30-I2C-digital-temperature-and-humidity-sensor-module/1331105_32762136940.html) [Aliexpress](https://www.wemos.cc/blog/sht30-shield-release.html)

## SHT31-D

* [Adafruit](https://www.adafruit.com/product/2857)
* [Closedcube](https://www.tindie.com/products/closedcube/sht31-d-digital-humidity-and-temperature-sensor/)

## SHT35-D

* [Closedcube](https://www.tindie.com/products/closedcube/sht35-d-digital-humidity-and-temperature-sensor/)

## Si7021

* [Adafruit](https://www.adafruit.com/product/3251)
* [Blkbox](https://www.tindie.com/products/blkbox/si7021-digital-humidity-sensor-module/)
* [Datasheet](http://www.silabs.com/documents/public/data-sheets/Si7021-A20.pdf)

## Si7051

* [Closedcube](https://www.tindie.com/products/closedcube/si7051-01c-max-digital-temperature-sensor/)

### Accuracy

* 0.1C:  +35.8C to +41C
* 0.13C: +20C to +70C
* 0.25C: -40C to +125C

## Si7055

* [Closedcube](https://www.tindie.com/products/closedcube/si7055-05c-max-digital-temperature-sensor/)

## HTU21D(F)

* [Datasheet](http://www.te.com/commerce/DocumentDelivery/DDEController?Action=showdoc&DocId=Data+Sheet%7FHPC199_6%7FA%7Fpdf%7FEnglish%7FENG_DS_HPC199_6_A.pdf%7FCAT-HSC0004)
* Humid range of specified accuracy 20-80 %RH
* [Adafrui](https://www.adafruit.com/product/1899)
* [Blkbox](https://www.tindie.com/products/blkbox/htu21d-digital-humidity-sensor-module/)
