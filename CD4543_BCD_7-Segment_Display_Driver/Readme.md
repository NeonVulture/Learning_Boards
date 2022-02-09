# CD4543 BCD 7-Segment Display Driver Learning Board

## Version 1.0

#### A learning board to teach 

### Features: 
+ Board can be set to drive both common cathode and common anode displays.

### Component List:
+ 1x Single Digit 7-Segment Display (Common Cathode or Common Anode) 
+ 2x 5x1 Female Row Headers (PCB)
+ 7x 220 - 470 Ohm Resistors 
+ 4x SPDT Switches
+ Breadboard (For Protoyping Only)
+ Jumper Wires (For Prototyping Only)

### Circuit Wiring:

![Schematic](https://github.com/NeonVulture/Learning_Boards/blob/main/CD4543_BCD_7-Segment_Display_Driver/Assests/Schematic.jpg "Schematic")

### Simulation:

#### Truth Table

| Bit 4  | Bit 3 | Bit 2 | Bit 1 | Seg A | Seg B | Seg C | Seg D | Seg E | Seg F | Seg G | Digit |
|--------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|
| 0      | 0     | 0     | 0     | 1     | 1     | 1     | 1     | 1     | 1     | 0     | 0     |
| 0      | 0     | 0     | 1     | 0     | 1     | 1     | 0     | 0     | 0     | 0     | 1     |
| 0      | 0     | 1     | 0     | 1     | 1     | 0     | 1     | 1     | 0     | 1     | 2     |

PCB Design:
