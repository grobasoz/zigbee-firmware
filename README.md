# zigbee-firmware
## ZigBee Development Firmware

## Versions
__BTL_STD_S2_768__
* BTL - Bootloader
* STD - Standalone
* S2 - Series 2 (eg EFR32MG2x)
* 768 - 768k Flash
* NB Sonoff Zigbee Bridge Version

__NCP_UHW_GFR8LE_676.gbl__
* NCP - Silabs NCP
* UHW - Uart interface, Hardware Flow Control 
* GFR8LE - ZigBee Module
* 676 - EmberZNet Version

__NCP_USW_115k2_S2_F768_676.gbl__
* NCP - Silabs NCP
* USW - Uart interface, Software Flow Control 
* 115k2 - Baud Rate
* S2 - Series 2 (ie EFR32MG21A020).
* F768 - Flash size
* 676 - EmberZNet Version

__BTL_STD_S1_256-COM_PB14-PB15-PA0.s37__
* BTL - Bootloader
* STD - Standalone
* S1 - Series 1 (eg EFR32MG1x)
* 256 - 256k Flash
* COM - Combined (necessary for Series 1)
* PB14-PB15 - TXD and RXD Port
* PA0 - Bootloader GPIO Activation

__NCP_USW_115K2_S1_F256_676_PB14-PB15.s37__
* NCP - Silabs NCP
* USW - Uart interface, Software Flow Control 
* 115k2 - Baud Rate
* S1 - Series 1 (ie EFR32MG1x)
* F256 - Flash size = 256k
* 676 - EmberZNet Version (EZSP V8!)
* PB14-PB15 - TX, RX
* NB Address Table Size = 8

__NCP_USW_115K2_S1_F256_664_PB14-PB15.s37__
* NCP - Silabs NCP
* USW - Uart interface, Software Flow Control 
* 115k2 - Baud Rate
* S1 - Series 1 (ie EFR32MG1x).
* F256 - Flash size = 256k
* 664 - EmberZNet Version (EZSP V7!)
* PB14-PB15 - TX, RX
* NB Address Table Size = 8

__NCP_USW_115K2_S1_F256_678_PB14-PB15-PA0.xxx__
* NCP - Silabs NCP
* USW - Uart interface, Software Flow Control 
* 115k2 - Baud Rate
* S1 - Series 1 (ie EFR32MG1x).
* F256 - Flash size = 256k
* 678 - EmberZNet Version (EZSP V8!)
* PB14-PB15-PA0 - TX=PB14, RX=PB15, Bootload = PA0
* NB Route Table Size = 32, Address Table Size = 100

__NCP_USW_115K2_S1_F256_690_PB14-PB15-PA0.xxx__
* NCP - Silabs NCP
* USW - Uart interface, Software Flow Control 
* 115k2 - Baud Rate
* S1 - Series 1 (ie EFR32MG1x).
* F256 - Flash size = 256k
* 690 - EmberZNet Version (EZSP V9!)
* PB14-PB15-PA0 - TX=PB14, RX=PB15, Bootload = PA0
* NB Route Table Size = 32, Address Table Size = 100

__NCP_USW_115k2_ZBBridge_678.gbl__
* NCP - Silabs NCP
* USW - Uart interface, Software Flow Control 
* 115k2 - Baud Rate
* ZBBridge - Sonoff ZBBridge
* 678 - EmberZNet Version

__NCP_USW_115k2_ZBBridge_690.gbl__
* NCP - Silabs NCP
* USW - Uart interface, Software Flow Control 
* 115k2 - Baud Rate
* ZBBridge - Sonoff ZBBridge
* 690 - EmberZNet Version
