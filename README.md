# arduino-light-rtc

ELEMENTS:
  ARDUINO UNO BOARD;
  LED COLD LIGHT BULB;
  RELAY MODULE;
  REAL-TIME CLOCK MODULE;
 
SCHEME:
  ARDUINO->BREAD->RELAY_MODULE->LIGHT_BULB->VCC;GND
           BOARD->REAL-TIME_CLOCK_MODULE
           
RELAY MODULE CONNECTION:
VCC->+5V  IN1->8th PIN  GND->GND

REAL-TIME CLOCK MODULE CONNECTION:
VCC->+5V  GND->GND  SDA->A4  SCL->A5  

LAYOUT TASK:
When time will be 4:30am the light bulb turns on, and will be turn off at 6:00am. Program will reset.

