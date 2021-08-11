# esphome-sensor

This Project is a sensor that is something I was using but wanted to make it less ugly and no breadboards for people who didn't like breadboard wires and such. 

First the board is layed out to have a ESP8622 Board specifially the D1 Mini.

Compoents are: 
* D1 Mini
* DHT Tempature Sensor (DHT11, DHT22 or a AM2302 Sensor) 
* BH1750 Light Sensor


![](https://github.com/sjhilt/esphome-sensor/blob/main/Screen%20Shot%202021-07-27%20at%209.51.41%20AM.png)

In the case of the DHT Sensor it is designed to use the 4 pin, or 3 pin types as shown in the images below. if you are using 4 pins which means its just the sensor without the addon board you will need to use a resistor which is what you put on R1. Example is this is what you buy on Adafruit with the extras. [Adafruit DHT11](https://www.adafruit.com/product/386)

![DHT11](https://github.com/sjhilt/esphome-sensor/blob/main/IMG_16022.png)

![AM2302](https://github.com/sjhilt/esphome-sensor/blob/main/IMG_1608.png)

