# kbd_ortho_12x4_proton
 12x4 Ortholinear with integrated [Proton C](https://qmk.fm/proton-c/)

 This is my second keyboard design. After finishing my [first design](https://github.com/cerkit/kbd_ortho_12x4), I decided to integrate the [microcontroller](https://qmk.fm/proton-c/) into the board to reduce the amount of wires everywhere and make it more complete.

 This hasn't been tested.

 It has a Qwiic connector to the left of the proton. The connector can be purchased from Sparkfun. It's the only surface mount component on the board. It's connected to the I2C1 pins on B6 and B7 of the Proton.

 [Qwiic connector](https://www.sparkfun.com/products/14417)

Here are the pin connections:

* Row 0: B0
* Row 1: B1
* Row 2: B2
* Row 3: B3
* Col 0: A13
* Col 1: A14
* Col 2: B12
* Col 3: B11
* Col 4: B10
* Col 5: B9
* Col 6: B15
* Col 7: B14
* Col 8: B13
* Col 9: B8
* Col 10: A0
* Col 11: A1

I don't have the boards, yet, so I haven't even started the QMK firmware changes.

Special thanks to [@tzarc](https://github.com/tzarc), [D3vastat0r](https://github.com/covah901), and [zvecr](https://github.com/zvecr) for answering my questions on the QMK Discord.

![cerkit ortho with Proton C front](https://github.com/cerkit/kbd_ortho_12x4_proton/blob/master/cerkit_planck_proton_front_copper.png?raw=true)

![cerkit ortho with Proton C back](https://github.com/cerkit/kbd_ortho_12x4_proton/blob/master/cerkit_planck_proton_back_copper.png?raw=true)
