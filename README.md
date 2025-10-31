# VL53L1X Distance Sensor

The VL53L1X by STMicroelectronics is a Time-of-Flight (ToF) distance sensor capable of measuring distances up to 4 meters with high accuracy. 
It communicates via I²C and is well-suited for applications such as robotics, drones, and proximity detection. 
[More information](https://www.st.com/en/imaging-and-photonics-solutions/vl53l1x.html#overview)

**ST provides [official drivers API](https://www.st.com/en/imaging-and-photonics-solutions/vl53l1x.html#tools-software) for easy integration, while users are required to implement their own platform layer.** 

***This repository includes the Ultra Lite Driver (ULD) and platform files for STM32:***
* [platform.c](https://github.com/Phat-sv/VL53L1X_sensor_STM32/blob/main/vl53l1_platform.c)
* [platform.h](https://github.com/Phat-sv/VL53L1X_sensor_STM32/blob/main/vl53l1_platform.h)

You can use these files by **downloading and including them in your STM32 project.**
Configure your project with a valid **I²C channel**, and update **the pin and port definitions** in [platform.h](https://github.com/Phat-sv/VL53L1X_sensor_STM32/blob/main/vl53l1_platform.h), along with other parameters in **public define area**
![VL53L1X Config](images/Define_example.jpg)





