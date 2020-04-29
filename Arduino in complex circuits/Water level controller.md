Water Level Controller:

  The aim is to switch the motor on when the level of the water drops below certain point, and the motor is also gets switched off when
  the tank becomes full.
  
  The water level and other important data are displayed on a 16×2 LCD display.
  
  The circuit also monitors the level of water in the sump tank (source tank).
  
  If the level in side the sump tank is low, the motor will not be switched ON and this protects the motor from dry running.
  
  A beep sound is generated when the level in the sump tank is low or if there is any fault with the sensors.
  
  The requirements are Arduino, LCD display, Buzzer, diode, transistors and a relay.
  
  The circuit is:
  ![](http://www.circuitstoday.com/wp-content/uploads/2014/10/water-level-controller-arduino.png)
  
  Digital pin 7 of the Arduino controls the buzzer and digital pin 8 controls the motor.
