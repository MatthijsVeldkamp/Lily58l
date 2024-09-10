# Lily58L


# Flashing this keymap
- Install QMK MSYS https://msys.qmk.fm/
- Clone this repo
- Save it to:
    C:\Users\USERNAME\qmk_firmware\keyboards\lily58\keymaps\Lily58l

You can then run the following command to flash the firmware to the left microcontroller:
```bash
qmk flash -kb lily58/rev1 -km lily58l -eCONVERT_TO=helio
```
