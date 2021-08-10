Lab3:
2-digit 7-segement dispaly library
Using output multiplexing to reduce the number of Pins needed. To turn on the LED on the 7-segement display, set the shared anode to high and set the unique cathode to low. Also, the LED in different digit, but in the same postion connect to the same pin of MCU. By control the anode to turn on the LED in appropriate digit.

Keypad read library
Using input multiplexing to reduce the number of Pins needed. This library read keypad with 16 bottoms by using 8 pins of MCU. The built-in MCU pull-up resistors will keep pins high by default, unless push the bottom in that pin.
