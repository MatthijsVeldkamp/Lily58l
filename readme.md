# Lily58L
<img src="https://keycapsss.com/media/image/21/2b/68/lily58l-split-keyboard-rgb-led-1.jpg" width="400">

A modified Lily58 pcb, with underglow, per key rgb light and rotary encoder support.
- SK6812 Mini-E per key led's (58x) for easy soldering
- 6x SK6812 Mini led's per side for underglow
- Support for 1 rotary encoder on each side

# Flashing this keymap
- Install QMK MSYS https://msys.qmk.fm/
- Clone this repo
- Save it to:
    C:\Users\USERNAME\qmk_firmware\keyboards\lily58\keymaps\Lily58l

You can then run the following command to flash the firmware to the left microcontroller:
```bash
qmk flash -kb lily58/rev1 -km lily58l -eCONVERT_TO=helio
```
