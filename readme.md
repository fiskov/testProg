﻿#набор тестовых программ

Различные программы, чтобы не потерять 

## test_bxCAN 
Приложение для тестирования CAN-шины, загружается в демоплату stm32f4-discovery 

CAN-трансивер подключается к выводам CAN1 - PB8=TX и RB9=RX 
 
Скорость 250кГц.   
STM32CubeMX 6.01, Keil 5.27   
К компьютеру подключается по USB - будет создан виртуальный COM-порт  
Формат передачи (по байтам): **addrHi, addrLo, Length, b0, b1, b2, b3, b4, b5, b6, b7**
  
**addrHi addrLo** - 16-битный адрес
**Length** - кол-во передаваемых байт данных
**b0-b7** - байты данных 

## test_bxCAN_win 
Приложение на C# для тестирования XXXXX через шину CAN. 
Работает только с приложением test_bxCAN 

## SpeedCAN.htm 
Небольшой скрипт на javascript для поиска регистров модуля bxCAN процессоров stm32 