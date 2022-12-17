# carlos-e-piano

## About
My Goal is to read from selfmade keyboard via atmega16 and create an e-piano. Just for fun.

## Layout

### Main-Breadboard

### Keyboard
Each key is connected to the main-breadboard via 5V and GND. A Key is represented by a z-diode. Pressing the key makes the z-diode conducitive, so you measure 0V on that diode when its pressed. 

Each note represents a digital bit, summarized as 7 bytes like shown below:

#### Noterange & Bytes:
- Bytse 0: C-G
- Byte 1: G#-D#
- Byte 2: E-B
- Byte 3: C-G
- Byte 4: G#-D#
- Byte 5: E-B
- Byte 6: C-G
- Byte 7: G#-C (not completly used)
