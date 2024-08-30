# nuovotaka/freeadrs32_knob/rev1

![nuovotaka/freeadrs32_knob/rev1](https://imgur.com/a/w6D2VXD)

| Name            | Description                                   |
| :-------------- | :-------------------------------------------- |
| Freeadrs32_knob | Left-handed keyboard with 32 keys and 3 knobs |

- Keyboard Maintainer: [Takahiro Natsume](https://github.com/nuovotaka)
- Hardware Supported: ProMicro like footprint
- Hardware Availability: See [nuovotaka shop](https://nuovotaka-kbd.stores.jp/)

Make example for this keyboard (after setting up your build environment):
make black_hellebore:default
Flashing example for this keyboard:
make black_hellebore:default:flash
There are two keymaps provided at least:

- via - Standard version with [Remap](https://remap-keys.app/) to change keymap
- test - Easy-to-use version for checking operation at build time
- default - Base version for creating your own customized firmware

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

- **Bootmagic reset**: Hold down the key at (0,1) in the matrix (usually the top left key or Escape) and plug in the keyboard
- **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
- **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
