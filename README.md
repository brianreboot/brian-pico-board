# Pico Breakout
This a simple Pico breakout PCB based on the Open Stick Foundation.

# Version 2
<img src="https://github.com/brianreboot/brian-pico-breakout/blob/main/Version%202/3D%20Renderings/front.png" height=30% width=30% > <img src="https://github.com/brianreboot/brian-pico-breakout/blob/main/Version%202/3D%20Renderings/back.png" height=30% width=30% >

# Specs
You're going to need two 1206 4.7K Ohm pull-up resisters for the OLED. The 20-pin connector is for the Brook harness. The L3 and R3 pins are optional, I added them to the board because there's a .1% chance that I may actually use them.

# Getting the PCB made.
I get my PCBs made at <https://jlcpcb.com/>. Just upload the gerber zip file. I used the default settings. <br />

<img src="https://github.com/brianreboot/brian-pico-breakout/blob/main/jlcpcb%20pcb%20options/pcb%20options.png" height=30% width=30% >

# Firmware
This board uses a tweaked firmware that is based on the [Open Stick Foundation](https://github.com/OpenStickFoundation/GP2040-CE).<br />
To properly use this board then head over to my github <https://github.com/brianreboot/GP2040-CE/tree/VLX> and check out the VLX tree for the tweaked firmware. It has the same functionality except that the button layout on the OLED has been modified for the HRAP Premium VLX controller.

# License
CERN-OHL-W


