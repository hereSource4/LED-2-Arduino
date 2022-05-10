# LED-2-Arduino
Connecting individually addressable LED strip lights (WS2812B) to Arduino Uno with Processing 

LIBRARIES: 
I used several free libraries to connect the LEDs, Arduino, and Processing together, this is mentioned in each code file. 

For Arduino: 
- FastLED, which allows makes coding palettes & effects much eaier with addressesable LEDs  https://github.com/FastLED/FastLED

For Processing:
- ControlIP5, which creates controllers easier in a seperate window & render graphics 
https://github.com/sojamo/controlp5
- Processing.Serial, which reads & write data from devices & other programs (like Arduino in our case) 
https://processing.org/reference/libraries/serial/index.html
