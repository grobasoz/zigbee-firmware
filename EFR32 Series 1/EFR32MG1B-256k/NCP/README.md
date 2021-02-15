# zigbee-firmware
## ZigBee Development Firmware

## Versions - EFR32 Series 1 B (256k Flash)

__NCP_USW_EFR32MG1B-256_678_PA0-PA1-PB11.ebl__
* NCP - Silabs NCP
* USW - Uart interface, Software Flow Control 
* S1 - Series 1 (ie EFR32MG1x)
* F256 - Flash size = 256k
* 678 - EmberZNet Version (EZSP V8!)
* PA0-PA1 - TX, RX
* PB11 = Bootloader Entry GPIO

__Specific Settings for this folder__
* CONFIG_APS_UNICAST_MESSAGE_COUNT:  20 
* CONFIG_MAX_END_DEVICE_CHILDREN:    32
* CONFIG_SOURCE_ROUTE_TABLE_SIZE:    200 
* CONFIG_ROUTE_TABLE_SIZE:           16 
* CONFIG_ADDRESS_TABLE_SIZE:         16 

__NB__
* 115k2 - Baud Rate