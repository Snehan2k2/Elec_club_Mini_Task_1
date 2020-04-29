I2C communication between STM32 and Arduino:
  
  Comparing I2C (Inter Integrated Circuits) in STM32F103C8 Blue Pill board with Arduino Uno, then we will see that Arduino has ATMEGA328 microcontroller in it, and STM32F103C8 has ARM Cortex- M3 in it. STM32 has Two I2C bus while Arduino Uno only has one I2C bus and STM32 is faster than Arduino.
  
  I2C pins in STM32 are:
  
  SDA (serial data):  PB7 or PB9, PB11
  
  SCL (serial clock):  PB6 or PB8, PB10
  
  I2C pins in Arduino are:
  
  SDA: A4 pin
  
  SCL: A5 pin
  
  The circuit is:
  https://circuitdigest.com/sites/default/files/circuitdiagram_mic/Circuit-Diagram-for-using-I2C-Communication-in-STM32-Microcontroller.png
  
  When we press the push button at Master STM32, the LED connected to Slave Ardiono turns ON.
  
  Now when we press the push button at Slave side, the LED connected to Master turns ON and when button is released LED turns OFF.
  
  When both the push buttons pressed simultanewolsy, then both the LEDs glow at the same time, and remains ON until the buttons are pressed.
  
