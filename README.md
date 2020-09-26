# embedded-debug
![CC by SA](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)


This debug board allows two unused traces of a 10pin (1.27mm pitch) connector to be broken out and used for a UART RX & TX line from the target MCU. These UART lines can be used by the Target to send debug print statements through the programming connector, to the USB bridge, and then displayed on a PC terminal. This is useful since board space is no longer needed on the target for any sort of extra headers or test pads for debug data.

This is a revamp of an existing project [ARM-Debug](https://github.com/stephendpmurphy/ARM-Debug) which was originally designed in Eagle CAD, while this project is designed using [KiCAD](https://kicad-pcb.org/)
