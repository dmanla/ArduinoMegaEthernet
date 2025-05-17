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
