# zigbee-firmware

## Zigbee Development Firmware

### Usage

* Make sure device drivers for your adapter's USB-to-UART bridge/converter is already installed if required.
  * VCP (Virtual COM port) driver for your operating system like those from [Silicon Labs](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers), [FTDI Chip](https://ftdichip.com/drivers/vcp-drivers/), or [WCH (CH34x/CH91xx)](http://www.wch-ic.com/downloads/category/30.html).
* Stop (and disable) any application/service/integration that is connected (or will try connect) to the serial port used by the adapter.
* Backup NVRAM with [bellows CLI tools](https://github.com/zigpy/bellows) (multi platform Python based command line tool).
* Download and install [Python](https://www.python.org/downloads/) (latest version for [Linux](https://www.python.org/downloads/source/), [macOS](https://www.python.org/downloads/macos/), or [Windows](https://www.python.org/downloads/windows/) depending on operating system).
* Install [Elelabs Firmware Update Utility](https://github.com/Elelabs/elelabs-zigbee-ezsp-utility) (multi platform Python based command line tool).
* Use command `python Elelabs_EzspFwUtility.py flash -p /dev/select/correct/tty-device -f 'path/to/firmware.gbl'`
* Optionally use alternative use other flashing tools and methods for flashing firmware Silicon Labs EFR32 based adapters:
    * [Elelabs Firmware Update Utility](https://github.com/Elelabs/elelabs-zigbee-ezsp-utility/) .
    * [puddly Universal Silicon Labs Flasher](https://github.com/puddly/universal-silabs-flasher) (multi platform Python based command line tool).
    * [agners silabs-flasher - Silicon Labs Firmware flashing utility](https://github.com/agners/silabs-flasher) (multi platform Python based command line tool).
    * [walthowd husbzb-firmware script](https://github.com/walthowd/husbzb-firmware) (community maintained multi platform bash script).
    * [Manual Xmodem sending commands over a terminal console](https://sonoff.tech/wp-content/uploads/2022/08/SONOFF-Zigbee-3.0-USB-dongle-plus-firmware-flashing-.pdf) (any terminal application with "Xmodem(N)" send can be used).
    * Silicon Labs [Simplicity Studio](https://www.silabs.com/developers/simplicity-studio) included "Flash Programmer" ([instructions](https://docs.silabs.com/simplicity-studio-5-users-guide/latest/ss-5-users-guide-building-and-flashing/flashing#flash-programmer)).
    * Silabs also list a few additional programming options and methods for Silicon Labs MCU based devices (see [here](https://www.silabs.com/developers/mcu-programming-options)).
* If needed restore NVRAM from the backup file you created with [bellows CLI tools](https://github.com/zigpy/bellows).

### Versions

__Folders containing different versions of bootloader and NCP firmware.__

* EFR32 Series 1
* EFR32 Series 2
  * EFR32MG21A020F1024 <sup>C
* EFR32MG2x-768k <sup>B  
* EFR32MG22 <sup>B
* EM357     <sup>A
* EM3581    <sup>A
* EM3585    <sup>A
* EM3587    <sup>A
* EM3588    <sup>A
* GFR8LE
* MG1B232
* Sonoff-ZBBridge <sup>B
* XIAO-MG24 <sup>D

__Notes__
+ A -> Updated to EmberZNet 6.7.10
+ B -> Updated to EmberZNet 6.10.3
+ C -> Added EmberZNet 7.0.1
+ D -> Added SDK 2024.12.1

__Folders containing legacy firmware for older Ember/Silabs chips.__
* EM250
  
