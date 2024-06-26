# HM605 
![AHT20_BMP280 logo](https://github.com/peff74/hanmatek_hm605/blob/main/HM605.jpg)

The HM605 is a very practical and cheap power supply manufactured by etommens and sold through Hanmatek OEM.
It is very easy to use and has a fairly low ripple voltage.
And with a few simple steps, you can make it Modbus enabled.  



## What do to
![AHT20_BMP280 logo](https://github.com/peff74/hanmatek_hm605/blob/main/HM605_case.jpg)
![AHT20_BMP280 logo](https://github.com/peff74/hanmatek_hm605/blob/main/HM605_port.jpg)

- Remove housing
- Remove display board
- solder in a pin header
- Reassemble everything
- Check in Setup (long press on Voltage) that Modbus is active


## How it works

- use a TTL to USB with 3.3V logic level!!!
- only GND (G) TX (T) and RX (R) are sufficient
- TX and RX must be crossed
- use a terminal programme of your choice
- connect with 9600 8 N 2
- send 01 03 00 10 00 01 85 CF as HEX
- now you get the current voltage as a HEX value
- more details in the ModBus-V2.2.pdf file




## Example Output

    XXX
   
