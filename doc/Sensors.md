
# Sensor Evaluation 

In following document you will find information regading sensor planned to use in weather station project.
___


For more accurate results, I plan to use multiple sensors for temperature, humidity, and pressure. All of these sensors will be located on separate PCBs to mitigate the influence of other circuit elements that can generate heat and thereby interfere with the measurements. This sensor board schould be loceted in solar radiation shield to minimize direct sunlight whitch can heat up the sensors, affecting the accuracy of temperature readings


# Sensors Diagram
![SensorDiagram]

## 1. Enviroment Sensors Group

|Sensor               |[BME680](Datasheets/BME680.pdf)                              |[SHT45](Datasheets/SHT4x.pdf)  |[LPS22HB](Datasheets/LPS22HB.pdf)|
|---------------------|-------------------------------------------------------------|-------------------------------|---------------------------------|
|Temperature          |:white_check_mark:                                           |:white_check_mark:             |:x:                              |
|Humidity             |:white_check_mark:                                           |:white_check_mark:             |:x:                              |
|Pressure             |:white_check_mark:                                           |:x:                            |:white_check_mark:               |
|SPI                  |:white_check_mark:                                           |:x:                            |:white_check_mark:               |
|I2C                  |:white_check_mark:                                           |:white_check_mark:             |:white_check_mark:               |
|Voltage              |1.71 - 3.6                                                   |1.08 - 3.6                     |1.70 - 3.6                       |
|Current Consumption  |12 mA (Active)<br>1 mA (Low Power)<br>90 μA (Ultra Low Power)|2 μA (Average)                 |3 μA (Average)                   |


<!-- Images and diagrams -->
[SensorDiagram]: img/Sensors-diagram.svg
