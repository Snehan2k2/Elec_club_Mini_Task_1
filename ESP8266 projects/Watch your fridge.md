Watch your fridge:

  This device check how many times and for how long you open your door fridge, then every 30 minutes, it sends that data to the IoT platform Adafruit IO.
  
  The requirements are ESP-01, door magnetic sensor and a LED.
  
  The circuit diagram is: https://hackster.imgix.net/uploads/attachments/1105238/diagrama_ingles_JVffclxr1h.png
  
  The device is based in the ESP-01 which is able to connect via wifi to an Internet network. 
  
  It has a door magnetic sensor. When the door is open, the device increase a count an gets the ESP-01 clock time, and also the LED is switched on.
  
  Then after the door is closed, it gets the ESP-01 clock time and makes a subtraction. That time is stored in a variable and send every 30 minutes.
  
