Controlling RGB LED display with Raspberry Pi GPIO
==================================================

This is mostly experimental code based from (c) Henner Zeller <h.zeller@acm.org> 

This version works with a [16 x 32 LED matrix](http://www.adafruit.com/products/420) and displays an image sequence animation. Convert any .gif file to .ppm, then save in source directory to run. I used (Gifmaker)[http://gifmaker.me/exploder/] to split the files in a .gif as separate images, then used (Gimp)[http://www.gimp.org/downloads/] to convert each gif slice into a ppm. Make sure to rename each file consistently for the program to iterate through the images, for example "imagename-1.ppm"..."imagename-N.ppm", and so forth. I named mine "tmp-" with 18 images in the sequence.

Running
-------

     $ make
     $ sudo ./led-matrix <name of ppm> <N number of files>

For this example: sudo ./led-matrix tmp- 18
