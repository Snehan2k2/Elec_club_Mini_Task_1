# Task1
1.Automatic Dustbin:
  The requirements are Arduino board, Ultrasonic distance sensor and a servo motor.
  So, the waste material is shown in front of the dustbin, wherein there is an Ultrasonic sensor.
  So, this sensor detects the material, and as per the Arduino code, the servo motor whose blades are placed on the pedal of the dustbin     gets rotated, hence making the lid open.
  After sometime, the lid gets closed, when the code moves the servo accordingly.
  
2.Arduino Color Sorter:
  The Mechanical model of the Sorter is:
  https://howtomechatronics.com/wp-content/uploads/2016/07/Color-Sorting-Machine-Arduino-Project-Solidworks-Model.jpg
  The requirements are Arduino Nano board, two servo motors, TCS230 TCS3200 Color Sensor, switch and a power jack.
  The connections for the sorter is:
  https://howtomechatronics.com/wp-content/uploads/2016/07/Arduino-Color-Sorting-Machine-Circuit-Schematic.png
  So, there are two servos, let us say they are top and bottom servos.
  The top servo helps us to move the coloured pebble from the container to under the color sensor, which detects the color.
  Based on the color detected, the bottom servo rotates the guide rail into the box of a particular color.
  
3.Social distancing device:
  The requirements are Arduino board, an Ultrasonic sensor and a buzzer.
  So, as the name suggests, the device is very simple.
  The device starts beeping, when a person comes within a range of 1m. 
  The ultrasonic sensor detects the person when he/she comes in on closer than a meter, the buzzer gets operated with the help of the         Arduino code1.
 
4.Automated Dino Game:
  The setup looks like:
  https://hackster.imgix.net/uploads/attachments/1100829/automated_dino_game_using_arduino_2_DnU8h6L3fU.jpg?auto=compress%2Cformat&w=740&h=555&fit=max
  The requirements are Arduino board, LDR and a servo motor.
  The circuit is:
  https://hackster.imgix.net/uploads/attachments/1100839/arduino_dino_game_mNFSPFDLyT.jpg?auto=compress%2Cformat&w=740&h=555&fit=max
  So, when the dino encounters the realtively dark, the LDR recognises it and therefore the analog voltage (A1) changes.
  If the value of the voltage at A1 is less than some threshold value, then the keyboard is pressed with the help of a servo motor, as
  coded.
  
5.Water Level Controller:
  The aim is to switch the motor on when the level of the water drops below certain point, and the motor is also gets switched off when
  the tank becomes full.
  The water level and other important data are displayed on a 16×2 LCD display. 
  The circuit also monitors the level of water in the sump tank (source tank). 
  If the level in side the sump tank is low, the motor will not be switched ON and this protects the motor from dry running. 
  A beep sound is generated when the level in the sump tank is low or if there is any fault with the sensors.
  The requirements are Arduino, LCD display, Buzzer, diode, transistors and a relay.
  The circuit is:
  http://www.circuitstoday.com/wp-content/uploads/2014/10/water-level-controller-arduino.png
  Digital pin 7 of the Arduino controls the buzzer and digital pin 8 controls the motor.
  
6.Wireless Doorbell:
  The circuit diagram for the Transmitter part is:
  https://www.electronicshub.org/wp-content/uploads/2017/03/Wireless-Doorbell-Transmitter.jpg
  The requirements for the Transmitter part are 434 MHz RF Transmitter, HT-12E Encoder IC and a button.
  The circuit diagram for the Reciever part is:
  https://www.electronicshub.org/wp-content/uploads/2017/03/Wireless-Doorbell-Receiver.jpg
  The requirements for the Reciever part are Arduino, HT-12D Decoder IC, 434 MHz RF Reciever module and a buzzer.
  Whenever, the button on the transmitter side is pressed on, the buzzer on the reciever side is turned on wirelessly.
  
7.
