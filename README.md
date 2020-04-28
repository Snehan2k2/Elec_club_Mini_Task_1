# Task1

  


 
4.Automated Dino Game:
  The setup looks like:
  https://hackster.imgix.net/uploads/attachments/1100829/automated_dino_game_using_arduino_2_DnU8h6L3fU.jpg?auto=compress%2Cformat&w=740&h=555&fit=max.
  The requirements are Arduino board, LDR and a servo motor.
  The circuit is:
  https://hackster.imgix.net/uploads/attachments/1100839/arduino_dino_game_mNFSPFDLyT.jpg?auto=compress%2Cformat&w=740&h=555&fit=max.
  So, when the dino encounters the realtively dark, the LDR recognises it and therefore the analog voltage (A1) changes.
  If the value of the voltage at A1 is less than some threshold value, then the keyboard is pressed with the help of a servo motor, as coded.
  
5.Water Level Controller:
  The aim is to switch the motor on when the level of the water drops below certain point, and the motor is also gets switched off when
  the tank becomes full.
  The water level and other important data are displayed on a 16×2 LCD display. 
  The circuit also monitors the level of water in the sump tank (source tank). 
  If the level in side the sump tank is low, the motor will not be switched ON and this protects the motor from dry running. 
  A beep sound is generated when the level in the sump tank is low or if there is any fault with the sensors.
  The requirements are Arduino, LCD display, Buzzer, diode, transistors and a relay.
  The circuit is:
  http://www.circuitstoday.com/wp-content/uploads/2014/10/water-level-controller-arduino.png.
  Digital pin 7 of the Arduino controls the buzzer and digital pin 8 controls the motor.
  
6.Wireless Doorbell:
  The circuit diagram for the Transmitter part is:
  https://www.electronicshub.org/wp-content/uploads/2017/03/Wireless-Doorbell-Transmitter.jpg.
  The requirements for the Transmitter part are 434 MHz RF Transmitter, HT-12E Encoder IC and a button.
  The circuit diagram for the Reciever part is:
  https://www.electronicshub.org/wp-content/uploads/2017/03/Wireless-Doorbell-Receiver.jpg.
  The requirements for the Reciever part are Arduino, HT-12D Decoder IC, 434 MHz RF Reciever module and a buzzer.
  Whenever, the button on the transmitter side is pressed on, the buzzer on the reciever side is turned on wirelessly.
  
7.Secret Knock detecting door:
  The requirements are Arduino, piezo speaker and a servo motor.
  The peizo speaker takes in sounds of the knock, and the servo motor helps us to open the door.
  Per se, int secretCode[maximumKnocks] = {100, 100, 55, 55, 100, 100, 100, 50, 40, 50, 30};
  then, this is the default knock that it recognizes when you turn it on.
  

