# kbd_ortho_12x4_proton (cerkit48)
 12x4 Ortholinear with integrated [Proton C](https://qmk.fm/proton-c/)

 This is my second keyboard design. After finishing my [first design](https://github.com/cerkit/kbd_ortho_12x4), I decided to integrate the [microcontroller](https://qmk.fm/proton-c/) into the board to reduce the amount of wires everywhere and make it more complete.

 This hasn't been tested.

 It has a pin header for I2C integration at the top of the board. It's connected to the I2C1 pins on B8 and B9 of the Proton.

 There's a reset button on the right side of the board.

 [Reset button](https://omronfs.omron.com/en_US/ecb/products/pdf/en-b3f.pdf)

Here are the pin connections:

* Row 0: B13
* Row 1: B14
* Row 2: B15
* Row 3: B10
* Col 0: B7
* Col 1: B6
* Col 2: B5
* Col 3: B4
* Col 4: B3
* Col 5: B2
* Col 6: B1
* Col 7: B0
* Col 8: A6
* Col 9: A7
* Col 10: A8
* Col 11: A15

I've created the board firmware as [cerkit48 in my GitHub branch for qmk_firmware](https://github.com/cerkit/qmk_firmware)

Make example for this keyboard (after setting up your build environment):

    make cerkit48:default
    
The copper fill is the ground plane.

Special thanks to [@tzarc](https://github.com/tzarc), [D3vastat0r](https://github.com/covah901), and [zvecr](https://github.com/zvecr) for answering my questions on the QMK Discord.

![cerkit48 schematic](https://github.com/cerkit/kbd_ortho_12x4_proton/blob/master/cerkit48_schematic.png?raw=true)

![cerkit48 front](https://github.com/cerkit/kbd_ortho_12x4_proton/blob/master/cerkit48_front_copper.png?raw=true)

![cerkit48 back](https://github.com/cerkit/kbd_ortho_12x4_proton/blob/master/cerkit48_back_copper.png?raw=true)
