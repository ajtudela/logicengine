For basic functionality, the AVR board should never need to be reprogrammed. If, however, a future update should be released or you just like to play with the code, the AVR board can be reprogrammed using the Arduino IDE and an FTDI adapter. In the Arduino IDE software you should select 'Arduino UNO' from the Tools->Board menu.

[https://rseries-open-control.googlecode.com/svn/trunk/Media/Misc/LEwiki/avr_ftdi.png]

The basic Arduino sketches are available on the repository [https://code.google.com/p/rseries-open-control/source/browse/trunk#trunk%2FSoftware%2FLogicEngine here].

#Development Notes
This system is basically an Arduino running a bunch of WS2812B LEDs. WS2812B's require only one data wire from a microcontroller to run dozens (maybe hundreds) of the RGB LEDs. We use functions from the [https://code.google.com/p/fastspi FastSPI_LED2 Library] to control all the LEDs, assigning them HSV (Hue Saturation Value) color values and address each LED in the order it is wired.

In order to pack all the LEDs to closely on the PCBs, they have been wired in a serpentine configuration. Each LED board has 48 LEDs. For the Front Logic two boards are connected via a 3-pin jumper cable and the top row of LEDs is unused on each logic. For the Rear Logic two boards are soldered together side-by-side and all 96 LEDs are used. These odd configurations are simplified in the software by mapping the physical LED numbers to typical matrix numbering.

<a href="https://rseries-open-control.googlecode.com/svn/trunk/Media/Misc/Logic-Engine-LED-board-front.png">
<img src="https://rseries-open-control.googlecode.com/svn/trunk/Media/Misc/Logic-Engine-LED-board-front.png" width="210">
<a href="https://rseries-open-control.googlecode.com/svn/trunk/Media/Misc/Logic-Engine-LED-board-rear.png">
<img src="https://rseries-open-control.googlecode.com/svn/trunk/Media/Misc/Logic-Engine-LED-board-rear.png" width="400">
