Android controlled RGB using Arduino:
  
  The circuit is:
  https://hackster.imgix.net/uploads/attachments/1107823/_ajyeCFDKkf.blob?auto=compress%2Cformat&w=900&h=675&fit=min
  
  The major hardware components are Arduino, HC-05 Bluetooth module, LED strips and MOSFETs.
  
  This LED Strip, for the most part, made up of SMD LEDs.
  
  In the LED strip There are 3 Individual LEDs there are Red, Green, and Blue. 
  
  I will utilize 3 Mosfets for this Project. Each LED is Connected with Each Mosfet.
  
  #include <SoftwareSerial.h> library is used.
