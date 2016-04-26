#Powering
The AVR board features an efficient regulator module that is capable of supplying plenty of current (up to 2.25A) to the AVR and LED boards. It can take an input voltage between +6V and +17V, so you can safely connect power from a 12V battery.

[[https://raw.githubusercontent.com/joymonkey/logicengine/master/docs/img/avr_powering.png|alt="Powering AVR"]]

#Standard Settings

The AVR board can be set to produce standard R2-D2 logic colors and speeds for both the Front (FLD) and Rear (RLD) Logic Displays.

[[https://raw.githubusercontent.com/joymonkey/logicengine/master/docs/img/avr_mode.png]]

By default the AVR board will output FLD colors (black, blues, whites) & speeds. Placing a jumper/shunt on the *S4* pin switches it to RLD mode (slower black, greens, yellows, reds).

#Custom Settings
The *BRIGHT* and *COLOR* trimpots on the AVR board are used to adjust global brightness and hue values of all LEDs.

Using a small screwdriver to turn the *BRIGHT* trimpot completely counter-clockwise sets the LEDs to their darkest levels (ie black). Turning the *BRIGHT* trimpot slowly clockwise will increase brightness until the maximum brightness is achieved. This maximum brightness value is set to 50% of the LED's possible brightness. This limit is in place to keep current consumption and heat generation down, and also to prevent anyone from being blinded (they're insanely bright at 100%!!). A custom settings file on the microSD card can be used to bypass this safety feature and get 100% brightness - this not recommended for long periods of time so do so at your own risk.

Similarly turning the *COLOR* trimpot completely counter-clockwise sets the color palette to their default hues (FLD will be black/blue/white, RLD will be black/green/yellow/red). Slowly turning the *COLOR* trimpot clockwise will shift the hues of all colors through the full color spectrum, finally arriving at the same default hues again when turned completely clockwise. 

[[https://raw.githubusercontent.com/joymonkey/logicengine/master/docs/img/avr_speed.png]]

Additionally, if different speeds are desired a jumper can be placed on the *S3* pin to enable the *DELAY* and *FADE* trimpots. Delay controls how long each key color is paused for. Fade controls how long each "tween" color is paused for - this adjusts how long each key color takes to cross-fade into the next color. When turned completely counter-clockwise the LEDs will behave fastest, turning clockwise slows the LEDs.

Additional custom settings (such as specific color palettes) may be set by editing the settings.txt file on the microSD card. The microSD card is optional and not needed for basic functionality.

[[https://raw.githubusercontent.com/joymonkey/logicengine/master/docs/img/avr_microsd.png]]

#Connecting a Teeces PSI
The AVR board is also programmed to run a Teeces v3.2 PSI if you have one. To get your PSI running, just connect it using a 5-pin jumper cable like this...

[[https://raw.githubusercontent.com/joymonkey/logicengine/master/docs/img/avr_to_teeces_psi.png]]