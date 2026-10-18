# Hack Pad

## PCB

Its a keyboard with 4x4 set of keys two rotary encoders and a 128x32 oled display.

<img width="571" height="597" alt="image" src="https://github.com/user-attachments/assets/83f6a574-75d2-4904-9f30-aacb168179a9" />

this project is a stardance mission i tried using only the parts provided from stardamce so my schematic looks like this:

<img width="1164" height="804" alt="image" src="https://github.com/user-attachments/assets/1fa1bb3e-f8fb-4303-8b81-63c6592bc2f7" />

notice that the switches are charlieplexed thats because the provided microcontroller has only 14 pins 11 if you exclude the ground and the power sources the display needs 2 pins
the rotary encoders need 4  that leaves me with 5 I/Os so I charlieplexed them for a total of N × (N - 1) posible swiches witch is 20 in total we got space for 16 switches and for the 2 buttons on the rotary encoder

## CAD

The cad file is split into two parts top and bottom the botom is built to hold the pcb 

<img width="781" height="701" alt="image" src="https://github.com/user-attachments/assets/2f74982b-100a-4c2b-8927-4648fbe68f0e" />

<img width="752" height="636" alt="image" src="https://github.com/user-attachments/assets/289f4d98-70b6-410f-900e-54691e5e4811" />

the top covers the pcb and holds the display which i will connect to the pcb with wires.

<img width="582" height="458" alt="image" src="https://github.com/user-attachments/assets/ab795466-ebe4-4dd9-959a-9493632db1b3" />

<img width="740" height="627" alt="image" src="https://github.com/user-attachments/assets/f782dc94-1972-4277-ad83-fb788e2545fd" />

the knobs are for the rotary encoders they have my logo on them thats two Ms in 180 degrees of rotation between them and they are a bit taller because i like them tall

<img width="596" height="718" alt="image" src="https://github.com/user-attachments/assets/692d6e2d-44ca-48f2-8146-b2bf59391f93" />

### Bill of Materials (BOM):

1. 1 unsoldered Seeed XIAO RP2040

2. 20x through-hole 1N4148 Diodes

3. 16x MX-Style switches

4. 2x EC11E Rotary encoders (with switch!)

5. 1x 0.91 inch OLED display (the pin order is GND-VCC-SCL-SDA, MAKE SURE YOUR PCB MATCHES)

6. 16x white blank DSA keycaps

7. 16x SK6812 MINI-E LEDs

8. 6x M3x16mm screws

9. 6x M3x5mx4mm heatset inserts

10. 1x PCB (fabricated using provided files)

3D Prints
 1x Case Top
 1x Case Bottom
 2x Knob Dials
