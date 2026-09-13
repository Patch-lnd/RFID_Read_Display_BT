# RFID_Read_Display_BT

#This Represents a pseudo Server for NFC Card system done with a Phone Through Bluetooth Communication
 RFID module reads an NFC card, trnasmits the information to a  phone via the Bluetooth Module HC-05.
 The phone then which represents a pseudo server, gets the data in the card , and if after treatment everything is okay, 
 we type "ok" through the phone to represent a confirmation within a period of 10 seconds. 
 
 Which is counted by the Arduino to avoid being delayed by a server not responding.
 The phone sends a  message and then the Arduino reveives it ans the LCD I2C displays "Operation Sucess".
 The card is released and the RFID awaits for a new card 
