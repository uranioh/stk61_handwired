# stk61_handwired

![stk61_handwired](imgur.com image replace me!)

*Handwired stk61 using an ATmega32U4 Pro Micro*

* Keyboard Maintainer: [uranioh](https://github.com/uranioh)
* Hardware Supported: *The PCBs, controllers supported*

Make example for this keyboard (after setting up your build environment):

    make stk61_handwired:default

Flashing example for this keyboard:

    make stk61_handwired:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the board *twice* (wired to RST and GND of the Pro Micro)