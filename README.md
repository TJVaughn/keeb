# keyboards

## Mapping

- Go to (qmk configurator)[https://config.qmk.fm/#/keebio/foldkb/]
- create your custom keymap
- download json
- compile firmware
- download firmware

## Flashing

- `lsusb` to see usb devices
- reset keyboard
- `lsusb` again
- `Atmel Corp. atmega32u4 DFU bootloader` should be listed
- `dfu-programmer atmega32u4 erase` 
- `dfu-programmer atmega32u4 flash hex-file.hex`
- unplug, and replug in keyboard
