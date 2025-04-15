# GMMK Pro Custom Keymap

This repository contains a custom keymap for the GMMK Pro keyboard, modified from the [2Manchu/gmmk-pro-qmk](https://github.com/2Manchu/gmmk-pro-qmk) QMK firmware.

## Overview
The keymap file (`aa_keymap.c`) is tailored for my personal use, based on 2Manchu's QMK configuration for the GMMK Pro. It includes a small change to make the rotary encoder compatible with Voicemeeter Banana's CTRL-F11/F12 Volume hook: Menu - Shortcut Key (Hook) - Hook CTRL-F10,F11,F12 (For Level Output A2)

The compiled bin (`gmmk_pro_rev1_ansi_aa.bin`) is provided for convenience if you want to flash direct. Use at your own risk.

## Modifications
- Changed rotary encoder left/right to be CTRL-F11 and CTRL-F12
- Default layout otherwise besides PrtScr is Home.
    
## Usage
1. Clone this repository or download the keymap file.
2. Place the keymap file in the appropriate directory of your QMK firmware fork (e.g., `qmk_firmware/keyboards/gmmk/pro/keymaps/your_keymap_name`).
3. Compile and flash the firmware using QMK Toolbox or `qmk compile` and `qmk flash`. Refer to the [QMK documentation](https://docs.qmk.fm/) for detailed instructions.
4. Ensure your GMMK Pro is in DFU mode (e.g., press `Fn + \` for 2Manchu’s firmware) before flashing.

## Credits
- Original firmware by [2Manchu](https://github.com/2Manchu/gmmk-pro-qmk).
- Built using the [QMK Firmware](https://github.com/qmk/qmk_firmware) framework.

## Notes
- This keymap is specific to my setup and may require adjustments for other configurations.
- For the full QMK context or to sync with upstream changes, refer to 2Manchu’s original repository.
