# simacing_wireless_buttons
Implementation of wireless buttons for a simracing wheel using two HC-05 bluetooth modules and two Teensy microcontrollers

BOM: Buttons, paddle shifters, wires, soldering iron and solder. Something to attatch the buttons to. Two leds with suitable series
resistors and two resistor to get battery voltage monitoring voltage divider circuit working. One 1S Lithium-Polymer battery is required to power up the system at the wheel.

Requires two Teensy microcontrollers connected with two HC-05 (or compatible) bluetooth modules, with Serial connection 
at Teensy pins 0 and 1. Connection status is connected to pin 2. Please adjust the two HC-05 bluetooth modules to pair with 
each other beforehand.
