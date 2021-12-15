# SHARPIW0

![Sharpiwo](https://github.com/ccadic/SHARPIW0/blob/main/20211214_233359.jpg)

The SHARPIW0 carrier board has been designed to hold both a Raspberry(R) PI ZERO 2W or W + 2.7"  (400x240) Sharp Memory Display. 
This display is capable of a fast refresh which allows the use of linux shells or display game images. 

The board also has 4 independently controlable LEDs you can switch on/off with classic GPIO commands (C++ or Python) 

The board also has 5 buttons you may also control via GPIO voltage detection (UP/Down voltage detection).  You can use this board for gaming.

You can get a fully made board here: https://www.tindie.com/products/electronictrik/sharpiw0-a-rpi-zero-27-sharp-memory-display/ 
It is also a good way to support opensource devices creators


**Extra GPIO available**
 
We added several extra GPIO, should you want to add an external UART extra board or a I2C board.  For the maker, we also added access to the display pins with the right bottom line of 2.54 mm header pinout (SCK to GND). If you want, you can drive the LCD without the Raspberry PI ZERO , and replace it with a classic microcontroller. In the same idea, you have B1 to B5 buttons signals available on pins.

**Installation**
If the board and display come separate, please connect the display's ribbon to the white connector, ribbon contacts facing the board surface. 
Plug the Raspberry PI ZERO like show on the diagram below.
 

**Software setup**
The Buttons and LEDs are controleable using classic python scripts. 
For the display, you have to install 2 libraries/code and compile them

1° ONE BITE DISPLAY LIB:  https://github.com/bitbank2/OneBitDisplay
Install with git clone https://github.com/bitbank2/OneBitDisplay
Go to /linux/Sharp_LCD directory and type make. 

2° ARMBIANIO LIB: https://github.com/bitbank2/ArmbianIO
Install the lib with git clone https://github.com/bitbank2/ArmbianIO
and make

Go back to Go to /linux/Sharp_LCD directory and  run the compiled executable ./sharp_lcd

Have fun !
Dr CADIC Philippe




Special credits to : Larry Bank for hi precious help and support in this project. 
@fast_code_r_us



Link to new LCD if an accident occurs
Link to SHARP Display: https://fr.aliexpress.com/item/4000674316500.html 

