# Programmer for EPROM 27 series (16-512) based on Arduino

Compatible Chips List (not all chips are tested):

 * 27C16 (connects from 3 to 26 leg DIP28 socket)
 * 27C32 (connects from 3 to 26 leg DIP28 socket)
 * 27C64
 * 27C128
 * 27C256
 * 27C512

Before write, check programming voltage in datasheet! 

# Schematic

Based on the project: https://github.com/bouletmarc/BMBurner

![Schematic](https://github.com/walhi/arduino_eprom27_programmer/blob/master/imgs/sch.png)

PCB divorced using autotracer. Not yet tested, but the prototype is working properly.

# Software

Software for PC written by Qt5.

Functions:

 * Read chip
 * Write chip
 * Verify and check for write (no bits to be set to 1)
 * Programming voltage control (for AVR in TQFP case)

![GUI on Windows 10](https://github.com/walhi/arduino_eprom27_programmer/blob/master/imgs/win.png)

Requared Windows 7 or later.

![GUI on Ubuntu Mate](https://github.com/walhi/arduino_eprom27_programmer/blob/master/imgs/ubuntu_mate.png)
