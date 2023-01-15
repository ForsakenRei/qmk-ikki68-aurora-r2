

# QMK firmware for ikki68 Aurora R2 Snow Bodo Wired PCB

## Use QMK toolbox to flash
`Fn`+`PgUp` to ender bootloader or hold `ESC` when plug the board in.
Remember to clear `EEPROM` before flash.

## Or use QMK CLI to flash
`qmk compile -kb wuque/ikki68_aurora -km shigure -j 32`

`qmk flash -kb wuque/ikki68_aurora -km shigure -j 32`

## Known Issue