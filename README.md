# Bitpixel CoinOPS Next 2 Support

3/8/2021

Just received my atgames bitpixel and it did not work with Next 2. Added support in retrofe for support for bitPixel.
First test release for bitPixel support for Next 2 and later iterations.

This also assumes you have already installed the pixelcade listener at https://pixelcade.org/download-pc/

Backup the following files:
\Next2\settings.conf
\Next2\core

Extract to root folder of Coinops Next 2 overwriting the files.

Run bitpixel_lf.exe once. (Only need to run this whenever you add new artwork this)
Ex: 
bitpixel_lf localhost
or
bitpixel_lf 192.168.1.11


Open settings.conf
Look for #BitPixel Integration
set 
enableBitPixel = true

and set
bitPixelIP = localhost or whatever IP address your bitPixel is assigned to.

Now just run CoinOPS Next 2 like normal.

*Note: You will only have to run the bitpixel_lf if you add new artwork for the bitpixel

