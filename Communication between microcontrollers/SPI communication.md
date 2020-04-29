SPI communication between Arduino and STM32:
  
  Comparing SPI bus in Arduino & STM32F103C8 Blue Pill board, STM32 has 2 SPI bus in it while Arduino Uno has one SPI bus. Arduino Uno has ATMEGA328 microcontroller in it, and STM32F103C8 has ARM Cortex- M3.
  
  The circuit is:
  https://circuitdigest.com/fullimage?i=circuitdiagram_mic/Circuir-Diagram-for-SPI-Communication-in-STM32-Microcontroller.png
  
  The same <SPI.h> library is used in programming STM32F103C8.
  
  Two Potentiometers are also connected with STM32 (PA0) and Arduino (A0) to determine the sending values (0 to 255) from master to slave and slave to master by varying the potentiometer.
  
  Analog input is taken at STM32F10C8 pin PA0 (0 to 3.3V) by rotating the potentiometer. Then this input value is converted into Analog to Digital value (0 to 4096) and this digital value is further mapped to (0 to 255) as we can send only 8-bit (byte) data through SPI communication at once, which is displayed on LCD connected to Arduino.
  
  Similarly in Slave side we take analog input value at Arduino pin A0 from (0 to 5V) by using potentiometer. And again this input value is converted into Analog to Digital value (0 to 1023) and this digital value is further mapped to (0 to 255), which is displayed on LCD connected to STM32.



