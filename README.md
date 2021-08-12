Lab3: Keypad read and 7-segement display

2-digit 7-segement dispaly library
Using output multiplexing to reduce the number of Pins needed. To turn on the LED on the 7-segement display, set the shared anode to high and set the unique cathode to low. Also, the LED in different digit, but in the same postion connect to the same pin of MCU. By control the anode to turn on the LED in appropriate digit.

Keypad read library
Using input multiplexing to reduce the number of Pins needed. This library read keypad with 16 bottoms by using 8 pins of MCU. The built-in MCU pull-up resistors will keep pins high by default, unless push the bottom in that pin.


Lab4: Double-click detection

The program include double-Click detection (input capture) and servo-control (output compare). Everytime the system detect a double-click event, the servo will turn to 90 degree and turn back after a time period. 

Lab5: LCD

LCD library
Including the function to write a single command to I2C bus; the function to configure the LCD screen; the function to write the cursor command to LCD (set display position); the functions to print a single character/a string in LCD.
