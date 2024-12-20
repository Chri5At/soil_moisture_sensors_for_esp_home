# Wireless Soil moisture sensors for Home Assistant by using ESP Home
Configuration files to integrate soil moisture sensors into Home Assistant by using ESP Home.

> [!NOTE]
> You can find more details about the setups in my videos:<br />
> [Youtube - WSMS#1 - Wireless Sensor to control garden irrigation with ESPHome and Home Assistant](https://youtu.be/qE35_fPxOck) - Different Setups<br />
> [Youtube - WSMS#2 - Best Soil Moisture Sensor for Smart Home Project](https://youtu.be/b9j9IffGZEs) - Results of ESP boards and sensor comparison<br />
> [Youtube - WSMS#3 - Optimize Power Consumption of ESPHome Wireless Sensors](https://youtu.be/vsYwS1WDop8) - Optimize power consumption<br />
> [Youtube - WSMS#4 - Solar Power your Smart Home Sensors](https://youtu.be/zpCm9TAhiMg) - Solar Power the Setup

# #1 Different Setups
Setups with different microcontrollers and soil moisture sensors

## Sparkfun ESP32 Thing with DF Robot Soil Moisture Sensor v.1
<img src="https://github.com/Chri5At/soil_moisture_sensors_for_esp_home/assets/123552852/37ddd91f-7350-46c8-9e30-2a1364078383" alt="Sparkfun ESP32 Thing" width="400" height="auto">

## AZ Delivery ESP32 DevKit v4 with Capacitive Soil Moisture Sensor v.1.2 and AZ Delivery Battery Shield for D1 Mini
To read the battery voltage, the same voltage divider, as used in the setup above, has been added. The output of the voltage divider is connected to GPIO34.

<img src="https://github.com/Chri5At/soil_moisture_sensors_for_esp_home/assets/123552852/ecda39dd-adf9-4904-8db9-e70958d31bf8" alt="AZ Delivery ESP32 DevKit v4" width="370" height="auto">

## DF Robot Firebeetle ESP32 IoT with DF Robot Soil Moistur Sensor v.2
<img src="https://github.com/Chri5At/soil_moisture_sensors_for_esp_home/assets/123552852/1b5b4274-659c-42b6-80a5-81d23edc672b" alt="DFR ESP32" width="300" height="auto">

## DF Robot Firebeetle ESP8266 IoT with DF Robot Soil Moisture Sensor v.2 and INA3221 Board
<img src="https://github.com/Chri5At/soil_moisture_sensors_for_esp_home/assets/123552852/f96620cf-234a-4010-8c70-60297826b371" alt="DFR ESP8266" width="400" height="auto">

# #3 Optimize power consumption
To optimize power consumption, we can power the sensor by using a GPIO Pin. TO be able to measure the consumption, we use a second microcontroller with INA3221.
![06](https://github.com/user-attachments/assets/bacb1cb2-767e-4d9e-a8b1-093ca2ddd6af)

# #4 Solar Power the Setup
To be able to run our sensor indefinitely while also increasing the update rate, we add a solar module to our setup.<br />
## Setup to Comparison of different charge controllers by measuring solar and battery power.
![2024_11_07 Test Setup - fix_1](https://github.com/user-attachments/assets/4f0eb3e7-31d7-4fe1-8930-4aae68cee329)<br />
## Single configurations
![2024_11_07 Setups - fix_1](https://github.com/user-attachments/assets/8b333f77-183f-4e1a-a721-4eeadce97df2)
