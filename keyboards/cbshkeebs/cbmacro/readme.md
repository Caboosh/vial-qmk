# cbshkeebs/cbmacro

![cbshkeebs/cbmacro]()

*The CB-Macro is an 18 key macropad that can be used to control whatever you want on your computer, it has an OLED screen to help keep track of what layer you are in, as well as other feedback.*

* Keyboard Maintainer: [Cameron Miller](https://github.com/Caboosh)
* Hardware Supported: *ATMega32U4*
* Hardware Availability: [Amazon](https://www.amazon.co.uk/s?k=arduino+pro+micro+atmega32u4&crid=1GY9HRAYFW9YX&sprefix=arduino+pro+micro+atmega32u4%2Caps%2C51&ref=nb_sb_noss_1)

Make example for this keyboard (after setting up your build environment):

    make cbshkeebs/cbmacro:default

Flashing example for this keyboard:

    make cbshkeebs/cbmacro:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
