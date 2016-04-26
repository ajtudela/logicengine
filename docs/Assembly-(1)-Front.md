#Front Master
This is the upper front logic and connects directly to the AVR Board. The LED board has two sets of 3 pins; one set labeled *IN* and another labeled *OUT*. We piggyback the AVR Board directly to the back of the LED board using those IN pins.

*Parts & Hardware Required:*
 * (1) AVR board (the one without the yellow jumper)
 * (1) Front LED board (the one with side "OUT" pins)
 * (1) Front Inner Screen (to be lightly sanded)
 * (1) Front Inner Bezel
 * (1) Front Outer Bezel
 * (2) 40mm M3 screws
 * (2) 3/4" spacers
 * (2) 1/8" spacers
 * (2) washers
 * (2) M3 threaded brass inserts

To help diffuse the LED colors, lightly sand both sides of the inner-screen (the thin piece without fiber-optic holes) before assembly. 300-500 grit sandpaper should do the trick. Wipe all dust away afterwards. DO NOT SAND THE OUTER SCREENS!!

Line up all the plastic parts with the LED PCB (the one with two sets of pins) to ensure they're all the correct way up.

![oo](https://rseries-open-control.googlecode.com/svn/trunk/Media/Misc/LEwiki/front_bez_orientation1.jpg) ![oo](https://rseries-open-control.googlecode.com/svn/trunk/Media/Misc/LEwiki/front_bez_orientation2.jpg)

Determine which side of the outer bezel will face out; we'll call this the front surface. Remove any paper liner from the front surface (handy tip- if teeny pieces of paper remain between the holes you can use some masking tape to pull it up). Press the two brass inserts into their holes with some light force - a pliers may be used to squeeze them into place.<br>

![Original Kits!](https://lh3.googleusercontent.com/-lSwxLmfYTJs/Ust0pwu70ZI/AAAAAAABxVE/lgt9h2CPcmM/w302/IMAG1748.jpg)![September 2014 Kits and newer](https://lh3.googleusercontent.com/--HJlvy55QUg/VBzyhGfwT-I/AAAAAAACT0I/MSSNXBRk3E4/s400/IMAG0616.jpg)<br/>Note that threaded inserts from the first run (left photo) did not have a flange. Kits from Sept 2014 on use threaded inserts with a flange (right photo) to prevent the insert from slipping.

Put plastic washers on both 40mm screws and position the screws through the AVR PCB, inner screen and inner bezel.
Place a 1/8" spacer on each screw, then attach the LED board so that the three IN pins insert into the back of the AVR board.
![](https://lh3.googleusercontent.com/-YeUYPoIqqSQ/VBzyhFLwQjI/AAAAAAACT0I/-TznAty9GHY/s360/IMAG0617.jpg) ![](https://lh3.googleusercontent.com/-A2eTCDpj0eU/VBzyhJOAyXI/AAAAAAACT0I/R7_Rm207hXM/s360/IMAG0620.jpg)

Then stack one 1/8" spacer and one 3/4" spacer onto each screw. Ensuring that you have the outer bezel positioned the correct way out, drive the two screws into the bezels brass inserts.<br>Note: Optionally, to keep the assembly as compact as possible you can use only the 3/4" spacer between the bezels (no 1/8" spacers) and 35mm screws. This makes positioning fibers a little trickier.

![](https://lh3.googleusercontent.com/-G6kwAwLe9eY/VBzyhCr2-MI/AAAAAAACT0Q/IyC44d7opmY/s360/IMAG0626.jpg) ![oo](https://lh4.googleusercontent.com/-Z_ehUj8IfkQ/Us6R84SdHJI/AAAAAAABxeY/7La_YN8uUYc/w274/IMAG1799.jpg)

#Fiber-Optic Placement

Take the bundle of fiber-optic cable and cut a tiny amount from the end to create a nice flat end with all fibers visible. A razor blade or sharp wire cutter can be used for this.

![oo](https://lh4.googleusercontent.com/-RDuUFvauTmg/Ust0p-yiRvI/AAAAAAABxV8/TRxXGX0yKFI/w240/IMAG1773.jpg)

Starting from the middle row, thread the end of the fiber-optic cable through a hole in the front surface of the outer bezel. A small needle-nose pliers or strong tweezers can be used to pull the cable through inside and position it into the corresponding hole of the inner bezel. Ensure that the cable is seated fully into the inner bezel.

![oo](https://lh5.googleusercontent.com/-0gcoMXwQhKA/Ust0p_rlzRI/AAAAAAABxVE/3qp-HiTYi78/w240/IMAG1775.jpg)
![oo](https://lh4.googleusercontent.com/-w62-2OKtRu8/Ust0p46Y0SI/AAAAAAABxVE/MKU5CbP7U-Y/w240/IMAG1776.jpg)
![oo](https://lh6.googleusercontent.com/-wY8NQ3916oM/Ust0p7WAuGI/AAAAAAABxVE/wv7yBIuIXVg/w240/IMAG1777.jpg)

Use a sharp flush-cutter to trim the fiber-optic cable bundle as close to the outer bezel as possible. After trimming the end of the remaining cable may appear "pinched" from the cutter so it may be necessary to trim a tiny portion of cable again (using a razor or sharp wire cutter).

Continue this procedure until fiber-optic cable has been placed in all holes of the bezel.

#Front Slave
This is the lower front logic display. Assembly procedure is very similar to the upper front logic. The main difference is that the slave does not have the AVR board piggybacked.

*Parts & Hardware Required:*
 * (1) Front LED board (the one without side pins)
 * (1) Front Inner Screen (to be lightly sanded)
 * (1) Front Inner Bezel
 * (1) Front Outer Bezel
 * (2) 35mm M3 screws
 * (2) 3/4" spacers 
 * (2) 1/8" spacers
 * (2) washers
 * (2) M3 threaded brass inserts
 * For Sept 2014 Kits (black/yellow C3PO on back) : (4) extra washers

Assemble following the same procedure as the Front Master.
When it comes to placing the spacers on the 35mm screws, you may want to add two washers to each screw so each screw gets a 3/4" spacer, 1/8" spacer and two washers. This will help when the time comes to mount everything in your dome - the differing spacer length prevents the two LED boards from pushing into each other. This is particularly helpful with the Sept 2014 kits, where the LED boards were a hair bigger than they should have been (my bad!).

Once assembled, the Front Slave is connected to the Front Master using the short 3-wire jumper cable as shown here...

![](https://lh3.googleusercontent.com/-DepatTZq6xY/VYH0mQOy4dI/AAAAAAACq-E/Wjid-pgK3xY/w600/fld-connections.png)