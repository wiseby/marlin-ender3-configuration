# My Creality Ender3 Marlin Configurations

## How to flash

- Install bootloader to the printer if it's missing
- Install additional boards from URL: https://raw.githubusercontent.com/Lauszus/Sanguino/master/package_lauszus_sanguino_index.json (Dont forget to restart the IDE before searching for the Sanguino board in BoardsManager)
- Install additional libraries U8glib and U8glib-HAL
- Select Sanguino board from the Tools => Board menu
- Select the correct processor type (mine was the Atmega1284P 16Mhz)
- Verify the sketch
- Upload to Printer

I had to tweak Extruder Steps/mm to 96.5. easily configured on the printer and stored to EEPROM.
