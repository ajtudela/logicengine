![](https://lh3.googleusercontent.com/-Zi_KUZ6ilPw/VBzyhCag-CI/AAAAAAACT08/8DfxYK9Gips/w600/IMAG0637.jpg)

The plastics for the rear are assembled similarly to the fronts.
Attach the AVR board to the back of the LED board using one 20mm (or 16mm with older kits) and one 45mm screw (use a washer on each screw and an 1/8" spacer between the boards on each screw).
Note: If you have a Rotopod Periscope Lifter in your dome, the AVR board (mounted to the back of the rear LED board) will hinder the wires for the lifter motor. In this case you should NOT mount the AVR board to the back of the LED board; instead mount it remotely and connect it to the rear LED board using a 3-pin cable. 

![](https://lh3.googleusercontent.com/-uUQtMu2U4ic/VBzyhEYaiaI/AAAAAAACT0I/F4ciaoZ5KyU/w300/IMAG0644.jpg)
![](https://lh3.googleusercontent.com/-V8LLzV8NCqk/VBzyhNFPkBI/AAAAAAACT0I/Df_xRqcqhcg/w300/IMAG0642.jpg)
![](https://lh3.googleusercontent.com/-eseKbSaw3PE/VBzyhDLkX6I/AAAAAAACT0I/LqBOZhwGfu0/w300/IMAG0638.jpg)

Sand the 'inner screen', then press-fit the brass inserts into the inner bezel. Place the inner screen (sanded), then the inner bezel (with brass inserts) onto the LED board. Also, put a washer and hex nut on the end of the 20mm screw to hold the inner bezel tight against the rest of the assembly (this isn't shown in these photos). Then add a 40mm screw with washer to the third mounting hole. Place two 1/8" spacers and one 3/4" spacer onto the 40mm and 45mm screws (spacers go on top of the inner bezel)...

![](https://lh3.googleusercontent.com/-zoMFsA8v8MM/VBzyhPfhy_I/AAAAAAACT0I/aN1XJN-Hibs/w300/IMAG0648.jpg)
![](https://lh3.googleusercontent.com/-t9CgmIu3vko/VBzyhBPmUWI/AAAAAAACT0I/OPemfp9GB-Q/w300/IMAG0649.jpg)

Press-fit two brass inserts into the black outer bezel and attach it to the ends of the two long screws...

![](https://lh3.googleusercontent.com/-KXndfl3cUTY/VBzyhAY11-I/AAAAAAACT0I/baDK9rxrTEY/w300/IMAG0647.jpg)
![](https://lh3.googleusercontent.com/-pKv0xzffZ3k/VBzyhEutKeI/AAAAAAACT0I/jok_EwgAWpo/w300/IMAG0650.jpg)

To help prevent the plastics from bowing while assembling the fiber-optics, insert two 35mm screws through the center mounting holes of the outer bezel, and into the brass inserts of the inner bezel. 

![](https://lh3.googleusercontent.com/-qiTl0cXQwpI/VBzyhAZxcjI/AAAAAAACT0I/fISF0kguLtI/w600/IMAG0654.jpg)

The fiber optic cables on the rear should be placed in a specific way to ensure that everyone has their logics mapped identically. To make this simpler I have built in a 'Testpattern Mode' into the code. On the Rear AVR board, remove the S3 jumper (if it exists) and turn the DELAY trimmer completely counter-clockwise. Restart and you should see a color pattern like this for a few minutes (you may need to reset the AVR board occasionally to get back to this pattern during assembly)...

![](https://lh3.googleusercontent.com/-nRwSCPQ3KQ8/VYH0melnmLI/AAAAAAACq-E/M2MitlUiZ5k/s486/rld_pattern.png)

Now, starting from the center and working outwards, fibers should be routed through the outer bezel and into the inner bezel so the color pattern on the outer bezel ends up looking like this...

![](https://lh3.googleusercontent.com/--RNZIMyWVPQ/VYH0mabB80I/AAAAAAACq-E/gMS4fLVSq2I/s489/rld_patternbez.png)

The outer-most fibers shown in blue and pink will be the trickiest to position, so take extra care (and time) with those. Again, a small needle-nose pliers or strong tweezers can come in very useful when positioning the fibers.

<a href="https://rseries-open-control.googlecode.com/svn/trunk/Media/Misc/LEwiki/rld-pattern-numbered.png">
<img src="https://rseries-open-control.googlecode.com/svn/trunk/Media/Misc/LEwiki/RLD-Pattern-Numbered_th.png"/></a>

If after assembly you find that the middle of the RLD is bowed out, don't panic! Loosen the two spacer screws a few turns and the bowing should subside slightly. When mounting the assembly to your logic surrounds the bowing should disappear.