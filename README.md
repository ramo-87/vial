# Chocofi split keyboard firmware
Based off the Corne keyboard and using the same keymap albeit with some tweaks.
## Changes:
- Removed the extra columns, making vial show 3x5 properly.
- Increased the layout count to 15

## Notes
- Clone both qmk and vial_qmk repos.
- point qmk to use vial instead of the default environment.
- clone this repo inside `vial-qmk/keyboards/crkbd/keymaps`
- compile with `qmk compile -kb ckrbd/rev1 -km vial -e CONVERT_TO=rp2040_ce`
- paste the uf2 file to the rp2040 bootloader.
