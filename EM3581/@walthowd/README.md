# zigbee-firmware
## ZigBee Development Firmware

_Note: Generally only 57k6 Baud is supported on EM358x boards - however 115k2 has been used with some success._

## EM3581 - Long Range Versions
__NCP_USW_EM3581-LR_678-57k6__
* NCP - Silabs NCP
* USW - Uart interface, Software Flow Control 
* EM3581 - Long Range EM3581 Dev0680 Based Device PB1=TXD, PB2=RXD
* 678 - EmberZNet Version (EZSP V8!)
* 57k6 - Baud Rate
 
## EM3581 Long Range Versions
__NCP_USW_EM3581-LR_678-115k2__
* NCP - Silabs NCP
* USW - Uart interface, Software Flow Control 
* EM3581 - Long Range EM3581 Dev0680 Based Device PB1=TXD, PB2=RXD
* 678 - EmberZNet Version (EZSP V8!)
* 115k2 - Baud Rate


__Specific Settings for this folder__
* CONFIG_APS_UNICAST_MESSAGE_COUNT:  20 
* CONFIG_MAX_END_DEVICE_CHILDREN:    32
* CONFIG_SOURCE_ROUTE_TABLE_SIZE:    200 
* CONFIG_ROUTE_TABLE_SIZE:           16 
* CONFIG_ADDRESS_TABLE_SIZE:         16 