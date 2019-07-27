# eeprom-tachometer

# PDF

https://www.nxp.com/docs/en/data-sheet/PCF8582C_2.pdf


Pin-compatible with other chips including https://www.nxp.com/docs/en/data-sheet/PCF8570.pdf

Linux kernel drivers says that PCF8570 is pin-compatible with Atmel 24c02

https://github.com/torvalds/linux/blob/master/drivers/misc/eeprom/at24.c


# Arduino Library

### I2CScanner

https://github.com/luisllamasbinaburo/Arduino-I2CScanner

Should be 0x50

### External EEPROM library 

https://github.com/PaoloP74/extEEPROM



# Utilities

https://hex-works.com/eng

# Strategy

1. Note tacho reading
2. Take EEPROM dump
3. Advance tacho reading
4. Take EEPROM dump
5. Take diff




