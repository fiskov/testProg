﻿# test_i2c_LCM1602

Тестирование дисплея LCM1602 по i2c на плате stm32f4_discovery 
STM32CubeMX 6.01, Keil 5.27  
На основе проекта из интернета I2CLCD80  

На stm32f103 не заводится - зависает при опросе i2c? 
На nRF52832 (DK 10040) какую-то ерунду выдает (но инициализацию проходит). 
То ли задержки, то ли подтяжки по питанию не те. 

![Подключение](https://github.com/fiskov/testProg/blob/master/test_i2c_LCM1602/test_i2c_lcm1602.jpg)  

