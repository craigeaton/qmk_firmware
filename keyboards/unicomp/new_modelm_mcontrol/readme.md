# unicomp_new_modelm_mcontrol

![unicomp_new_modelm_mcontrol](imgur.com image replace me!)

*A short description of the keyboard/project*

* Keyboard Maintainer: [Craig Eaton](https://github.com/craigeaton)
* Hardware Supported: *The PCBs, controllers supported*
* Hardware Availability: *Links to where you can find this hardware*

Make example for this keyboard (after setting up your build environment):

    make unicomp/new_modelm_mcontrol:uf2

Flashing example for this keyboard:

    make unicomp_new_modelm_mcontrol:uf2
    Enter bootloader mode (see below), copy .build/unicomp_new_modelm_mcontrol_modern.uf2 to keyboard's flash mode USB drive

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (Escape on this keyboard) and plug in the keyboard
* **Physical reset button**: Short the "BOOTSEL" solder pads on the controller with a paperclip or wire, and plug in the keyboard
* **Keycode in layout**: Press the key mapped to `RESET` if it is available in selected keymap
