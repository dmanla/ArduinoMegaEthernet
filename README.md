# ArduinoMegaEthernet

This is an open hardware platform designed to be compatible with Arduino Mega hardware. This platform includes Ethernet, an IoT Coprocessor, SD Card, and an IMU.

This project was inspired by (but not a copy of) the Freetronics EtherMega: https://github.com/freetronics/EtherMega
This project was created as an alternative to the platform offered by Freetronics.

Features:
- CH340 USB->Serial Converter (Functionally similar to FT232, Driver should be installed automatically) 
- 5V 2A USB-C Input
- MicroSD Card Slot
- 10/100 Ethernet provided over SPI using the W5500
- SE050 EdgeLock Plug and Trust Secure Element to provide security features for connected applications, accessible using I2C
- ISM330DHCX Inertial Measurement Unit accessible using I2C

**WARNING**: This project is under development and has not yet been validated.


## Top Render
![Render of Top of PCB](https://github.com/dmanla/ArduinoMegaEthernet/blob/main/3D_Render_TOP.JPG)

## Bottom Render
![Render of Bottom of PCB](https://github.com/dmanla/ArduinoMegaEthernet/blob/main/3D_Render_BOTTOM.JPG)

## Side Render
![Render of Side of PCB](https://github.com/dmanla/ArduinoMegaEthernet/blob/main/3D_Render_ANGLED.JPG)

## Relevant Datasheets

- [CH340N](https://datasheet.lcsc.com/szlcsc/Jiangsu-Qin-Heng-CH340C_C84681.pdf): USB->Serial Bridge
- [AP22805AW5](https://www.diodes.com/assets/Datasheets/AP22804_14.pdf): USB Protection
- [W5500](http://wizwiki.net/wiki/lib/exe/fetch.php/products:w5500:w5500_ds_v109e.pdf): SPI->Ethernet Bridge
- [ISM330DHCX](https://www.st.com/resource/en/datasheet/ism330dhcx.pdf): "AI Enabled" Inertial Measurement Unit
- [SE050C2HQ1](https://www.nxp.com/docs/en/data-sheet/SE050-DATASHEET.pdf): Security Coprocessor
- [Atmega2560](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-2549-8-bit-AVR-Microcontroller-ATmega640-1280-1281-2560-2561_datasheet.pdf): Main Microcontroller
