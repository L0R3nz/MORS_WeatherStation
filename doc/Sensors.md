
# Sensor Evaluation 

In following document you will find information regarding sensor planned to use in weather station project.
___


For more accurate results, I plan to use multiple sensors for temperature, humidity, and pressure. All of these sensors will be located on separate PCBs to mitigate the influence of other circuit elements that can generate heat and thereby interfere with the measurements. This sensor board should be located in solar radiation shield to minimize direct sunlight which can heat up the sensors, affecting the accuracy of temperature readings


# Sensors Diagram
![SensorDiagram]

## 1. Environment Sensors Group

|Sensor               |[BME680](Datasheets/BME680.pdf)                              |[SHT45](Datasheets/SHT4x.pdf)  |[LPS22HB](Datasheets/LPS22HB.pdf)|
|---------------------|-------------------------------------------------------------|-------------------------------|---------------------------------|
|Temperature          |:white_check_mark:                                           |:white_check_mark:             |:x:                              |
|Humidity             |:white_check_mark:                                           |:white_check_mark:             |:x:                              |
|Pressure             |:white_check_mark:                                           |:x:                            |:white_check_mark:               |
|SPI                  |:white_check_mark:                                           |:x:                            |:white_check_mark:               |
|I2C                  |:white_check_mark:                                           |:white_check_mark:             |:white_check_mark:               |
|Voltage              |1.71 - 3.6                                                   |1.08 - 3.6                     |1.70 - 3.6                       |
|Current Consumption  |12 mA (Active)<br>1 mA (Low Power)<br>90 μA (Ultra Low Power)|2 μA (Average)                 |3 μA (Average)                   |

## 2. Light Sensors Group

|Sensor               |[AS7331](Datasheets/AS7331.pdf)                          |[OPT3004](Datasheets/OPT3004.pdf)                        |
|---------------------|---------------------------------------------------------|---------------------------------------------------------|
|UV (A/B/C)           |:white_check_mark:                                       |:x:                                                      |
|Ambient Light        |:x:                                                      |:white_check_mark:                                       |
|SPI                  |:x:                                                      |:x:                                                      |
|I2C                  |:white_check_mark:                                       |:white_check_mark:                                       |
|Voltage              |2.7 - 3.6                                                |1.6 - 3.6
|Current Consumption  |2 mA (Active)<br>970 μA (Standby)<br>1 μA (Power Down)   |1.8 μA (Typical)

<!-- ## 3. Wind Sensors Group -->
<!-- ## 4. Rain Sensor Group -->

<!-- Images and diagrams -->
[SensorDiagram]: img/Sensors-diagram.svg
