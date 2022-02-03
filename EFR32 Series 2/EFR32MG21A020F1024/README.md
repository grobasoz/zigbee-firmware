# zigbee-firmware
## ZigBee Development Firmware

## Versions - EFR32 Series 2 - EFR32MG21A020F1024

__MP_NCP_UHW_S21_701.xxx__
* MP - Multi-Pan (PAN 1 Secure, PAN 2 - No Security)
* NCP - Silabs NCP
* UHW - Uart interface, Hardware Flow Control 
* S21 - Series 21
* 701 - EmberZNet Version (EZSP V9!)
* NB 
  * Route Table Size = 128, Address Table Size = 100
  * TXD PA5, RXD PA6, CTS = PA0, RTS = PA4

<br>
<br>

## Gateway Test Host for Silabs EZSP NCP
__MpZ3TcCustomTcHost.exe__
* Mp - Multi Pan
* Z3 - Zigbee 3
* Tc - Network 1 - Trust Center (Security)
* CustomTc - Network 2 (No Security)
* Host - Host for NCP
* NB
  * Cygwin 64
  * Windows 10 with included files 