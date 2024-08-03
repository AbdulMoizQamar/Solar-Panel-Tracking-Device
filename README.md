# Solar-Panel-Tracking-Device
This project aims to create an efficient solar panel tracking system that optimizes energy generation by adjusting the panel’s orientation based on the sun’s position. Using light sensors and servo motors, the device ensures that solar panels always face the sun, maximizing energy output. 


**Components Needed**:
Arduino board (e.g., Arduino Uno)
Two LDR (Light Dependent Resistor) sensors
Two 10kΩ resistors (for LDR voltage divider)
Servo motor
Jumper wires
Breadboard (optional)


**LDR Wiring**:
**LDR1:**
Connect one terminal of LDR1 to 5V on the Arduino.
Connect the other terminal to A0 (analog pin) and also to one terminal of a 10kΩ resistor.
Connect the other terminal of the resistor to GND.
**LDR2:**
Connect one terminal of LDR2 to 5V on the Arduino.
Connect the other terminal to A1 (analog pin) and also to one terminal of another 10kΩ resistor.
Connect the other terminal of the resistor to GND.
Servo Motor Wiring
Connect the control wire (usually yellow or white) of the servo motor to digital pin 11 on the Arduino.
Connect the power wire (usually red) of the servo to 5V on the Arduino.
Connect the ground wire (usually black or brown) of the servo to GND on the Arduino.




