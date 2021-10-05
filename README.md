# PsOne_LEDBoard
Simple switch board for PsOne LCD LED mods. 

Connects 4 LED's in a 2x2 configuration (2 parallel sets of 2 diodes in series) to the main board's 7.5V rail, which is then controlled by the AV port 5V supply, so that it only turns on when you press the power button on the system.

Parts are indicated on the schematic PDF - BJT gate resistors are 0603 size and the collector resistor is 1210/1206. The LED's I used are also indicated, but are ultimately up to the user. Just make sure to account for diode voltage drop and resize your resistor accordingly.
