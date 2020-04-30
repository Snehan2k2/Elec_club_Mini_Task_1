Voice controlled lights:
  
  In this project, we will send voice commands from Smart Phone to Raspberry Pi using Bluetooth Module and Raspberry Pi will receive that transmitted signal wirelessly and will perform respective task over the hardware.
  
  Major components used are Raspberry Pi 3, bluetooth module-05, ethernet cable, LED's and AMR voice app in android phone.
  
  The circuit is:
  
  ![](https://circuitdigest.com/sites/default/files/circuitdiagram_mic/voice-controlled-LEDs-using-Raspberry-pi-circuit.jpg)
  
  AMR voice app records this voice and sends it to Google Voice app to convert it into the text string format. 
  
  Now this converted string is sent to Raspberry Pi via Bluetooth module and Raspberry Pi reads this string from UART port and store in a string in the code.
