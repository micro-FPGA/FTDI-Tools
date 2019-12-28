

========= ======================================
VID/PID   
========= ======================================
0000/0000v 
0000/0000 
========= ======================================

List of known products using User EEPROM

* all Digilent JTAG adapters

List of JTAG software that can be used with empty EEPROM

* Lattice Diamond Programmer
* Gowin Programmer
* ToolZ
* OpenOCD

Lattice Programmer
==================
Lattice has made a smart decision and allows the use of FT chips with blank EEPROM, JTAG is supported on any channel, not limited to channel A. Supported modes are JTAG, I2C and SPI. If duplicating the schematic look at Lattice evaluation boards for detailed info.


Arrow USB Programmer
====================
This is a special DLL that makes the FT2232 chip to work with Intel FPGA's. Available both for Windows and Linux hosts. Only JTAG mode supported on fixed channel A. Default VID/PID are used, programmer is detected by the Product string, user EEPROM is not used.
