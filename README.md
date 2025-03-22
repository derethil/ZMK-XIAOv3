# ZMK-XIAOv3 Keymap

This repository houses the ZMK build firmware and instructions for flashing my ergonomic keyboard.

## Editing

1. Navigate to [the keymap editor](https://nickcoutsos.github.io/keymap-editor)
2. Set up repository access if needed
3. Make changes
4. Click save to build firmware and publish a new release

## Flashing

1. Delete existing keyboard profiles from PC
2. Download artifacts from the new [release](https://github.com/derethil/ZMK-XIAOv3/releases)
3. Ensure both halves of the keyboard are turned off
4. Flash the left board:
   1.  Plug in either left of the keyboard and enter bootloader mode by double tapping the reset button quickly
   2.  Open the keyboard firmware storage in a file manager (it should show up as a USB device)
   3.  Move the settings reset file into the folder
   4.  Unplug and power cycle the board
   5.  Move the corresponding firmware file into the board
   6.  Unplug the board
11. Similarly, flash the right board
12. Turn both boards on to pair
