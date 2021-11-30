# zigbee-firmware
## ZigBee Development Firmware

_Note: Generally only 57k6 Baud is supported on EM358x boards - however 115k2 has been used with some success._

## EM3585 - Long Range Versions
__NCP_USW_EM3585-LR_678-57k6__
* NCP - Silabs NCP
* USW - Uart interface, Software Flow Control 
* EM3585 - Long Range EM3585 Dev0680 Based Device PB1=TXD, PB2=RXD
* 678 - EmberZNet Version (EZSP V8!)
* 57k6 - Baud Rate
 
## EM3585 Long Range Versions
__NCP_USW_EM3585-LR_678-115k2__
* NCP - Silabs NCP
* USW - Uart interface, Software Flow Control 
* EM3585 - Long Range EM3585 Dev0680 Based Device PB1=TXD, PB2=RXD
* 678 - EmberZNet Version (EZSP V8!)
* 115k2 - Baud Rate

## EM3585 Long Range Versions - EmberZNet 6.7.10 - 115K2 Baud
__NCP_USW_EM3585_6710_PCx__
* NCP - Silabs NCP
* USW - Uart interface, Software Flow Control 
* EM3585 - Long Range EM3585 Dev0680 Based Device PB1=TXD, PB2=RXD
* 6710 - EmberZNet Version (EZSP V8!)
* PCx - PC5 or PC6 for TX Active Enable

## BOOTLOADER ##
__BTL_STD_EM3585.s37__
* Standalone uart xmodem bootloader for EM3585
