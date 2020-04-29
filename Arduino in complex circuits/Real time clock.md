Arduino Real time clock:
  
  The circuit is:
  ![](https://www.electronicshub.org/wp-content/uploads/2018/01/Arduino-Real-Time-Clock-DS1307-Tutorial-Circuit-3.png)
  
  The requirements are Arduino board, DS1307 RTC and a LCD display.
  
  A special library called “RTClib” is used in the programming.
  
  In order to upload the data and time into the DS1307 RTC IC, we have used a feature available in the RTClib library, where the Arduino will upload the date and time from the computer while uploading the code. 
  
  Also, the RTC Module DS1307 is backed with a battery, it will continue to maintain time even in the event of power fail.  
