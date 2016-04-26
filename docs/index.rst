RSeries Lights Module
========================

Logic Displays are the blinky lights in the rectangular openings of R2-D2's dome (2 front, 1 rear) that separate dead droids from the living.

The RSeries Logic Engine combines Arduino, RGB LEDs and fiber-optics to accurately emulate the color-wheel logic display patterns seen in the original Star Wars trilogy. This is arguably the most screen-accurate logic display system since Return of The Jedi.

At it's heart is an AVR Board (with Arduino Uno bootloader) which runs a series of WS2812B LEDs. These RGB LEDs cross-fade between set colors. For example the Front logic LEDs fade from black to blue to white and back again. As it arrives at each "key" color, that LED is paused for a random length of time - this creates constantly evolving color patterns that appear almost random at first glance.

Fiber-optic cable is used to route the light from each LED to specific 'pixels' on the logic bezel, which is what is finally seen on your droid. 

Where To Buy?
---------------
The Logic Engine is supplied in DIY kits that are prepared exclusively for members of the R2 Builders Club. Look in [the 'Other Parts' forum on Astromech.net](http://astromech.net/forums/forumdisplay.php?63) to check current availability.

.. toctree::
   :maxdepth: 2
   :caption: Versions
   
   versions
   