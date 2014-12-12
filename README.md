Controlling RGB LED display with Raspberry Pi GPIO
==================================================

This is mostly experimental code based from (c) Henner Zeller <h.zeller@acm.org> 

Running
-------
The main.cc has some testing demos. You need to run this as root so that the
GPIO pins can be accessed:

     $ make
     $ sudo ./led-matrix <name of ppm> <N number of files>

For this example: sudo ./led-matrix tmp- 18
