## Zigbee NCP for the XIAO_MG24

The firmware for the XIAO MG24 "dongle" to be used with Zigbee2MQTT can be found in the [xiao_mg24](https://github.com/grobasoz/xiao_mg24) repository

There are two versions, one for the chip based antenna *(XIAO_MG24_NCP_SW_115k2)* and the other *(XIAO_MG24_NCP_SW_115k2_UFL)* for use with a external UFL antenna.

#### Program the NCP (Network Co Processor)

NB: With only one XIAO MG24 connected via USB C to your (Windows) PC

1. Clone the [xiao_mg24](https://github.com/grobasoz/xiao_mg24) repository
2. Enter the following command line commands
```
cd xiao_mg24
cd OpenOCD
flash_code ..\firmware\ZIGBEE_NCP\XIAO_MG24_BTL_STD_A5.hex 
flash_code ..\firmware\ZIGBEE_NCP\XIAO_MG24_NCP_SW_115k2.hex 
```

#### Notes:

The bootloader GPIO activation is via XIAO MG24 - D10 (PA5)

Pulling low during reset will cause the device to enter the bootloader when the USB is plugged in or the (tiny) reset button pressed 

The following prompt is presented on a Serial Terminal (115k2, N, 8, 1)

```
Gecko Bootloader v3.00.01
1. upload gbl
2. run
3. ebl info
BL > 
```

New firmware (gbl format) can be uploaded using XModem (115k2)
Enter the '1' key and transfer the new firmware via XModem

I use Tera Term for this

There are also [third party applications](https://github.com/Elelabs/elelabs-zigbee-ezsp-utility) available to support flashing new firmware


<hr>

#### With Zigbee2MQTT 

In **configuration.yaml** set the following...
```python
serial:
  port: COMxx
  adapter: ember
  rtscts: false
  baud: 115200
```
