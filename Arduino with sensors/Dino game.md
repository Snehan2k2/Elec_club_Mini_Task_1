Automated Dino Game:

  The setup looks like:
  https://hackster.imgix.net/uploads/attachments/1100829/automated_dino_game_using_arduino_2_DnU8h6L3fU.jpg?auto=compress%2Cformat&w=740&h=555&fit=max.
  
  The requirements are Arduino board, LDR and a servo motor.
  
  The circuit is:
  https://hackster.imgix.net/uploads/attachments/1100839/arduino_dino_game_mNFSPFDLyT.jpg?auto=compress%2Cformat&w=740&h=555&fit=max.
  
  So, when the dino encounters the realtively dark, the LDR recognises it and therefore the analog voltage (A1) changes.
  
  If the value of the voltage at A1 is less than some threshold value, then the keyboard is pressed with the help of a servo motor, as coded.
