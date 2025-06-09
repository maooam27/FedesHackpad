# FedesHackpad

The FedesHackpad is my first real electric project, designed by me with the help of Hack Club during the Highway to Undercity event. It has 6 buttons customizable with several macros through its firmware in KMK and 2 LEDs. It will probably be improved, especially its firmware.

## Features
- Nice case made out of pure programmer tears
- 2 rgb LEDs SK6812
- 6 programmable keys

## CAD Model:
The model was made using Fusion360, it was my first time using this tool too and it is made by two main pieces, the top and the bottom one.
The top piece leaves space to cool down and see both the microcontroller and the LEDs.... it is not poor design :(

![cad](https://github.com/user-attachments/assets/1190266e-07df-4dbf-ae2d-112b8eabf53a)
See! lovely <3

## PCB
The PCB was made in KiCad. I needed to import the OPL library.

Schematic:
![Schematic](https://github.com/user-attachments/assets/1a2bd3f3-ceea-43c3-b971-cbdc2464bc62)

PCB:
![PCB](https://github.com/user-attachments/assets/f1b80b61-34ea-4569-ab69-e056a9bc45e3)

## Firmware
For the firmware I used KMK in python, however it's not perfect, I have to improve it, it's the first time I write one.
The desired functioning is:
- random rgb lights every now and then
- macros when pressing keys
- random rgb lights also when pressing keys

## BOM:
List with everything you would need to rebuild this hackpad:
- 1x XIAO RP2040
- 4x Cherry MX Switches
- 4x Cherry MX Keycaps
- 2x SK6812 mini RGB LEDs
- 1x 3D printed case (top and bottom parts)
- 4x nuts and bolts to keep the case closed

## Extra stuff
Well I might just say thank you Hack Club, I'm now 18 and during the last 2 years, I really loved coding and practicing my skills with all of the community around the world. Big thanks and love from Italy <3
