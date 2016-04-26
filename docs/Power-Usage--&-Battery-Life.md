The LEDs used in the logics are WS2812B's. These are super-bright RGB LEDs with built-in serial controller chips. Each one consumes quite a bit more power than an average 3mm single color LED. You can test the system using a regular 9V battery, but don't expect it to last much longer than 30 minutes.

A typical 12V SLA battery will run at 13.8V when fully charged. Using a bench top power supply set at 13.8V I tested an RLD board to get an idea of how much current the logics consume. I also tested with a 5V supply to get an idea of what the regulator module needs to output. Note that I don't ever recommend setting LED brightness to over 75%; even 50% is plenty bright. Going over 75% is pretty blinding, washes out colors and eats batteries like crazy. That said, here are my results...

LEDs | Pattern | Bright | Current @ 13.8V | 12V 1Ah Battery  | 12V Note | 5V Note
---- | ------- | ---------- | ------- | ---------------- | ---- | ----
96   | Standard Rear | 100% | 0.42A | 2 hours 22 minutes | Varies from 0.34A to 0.42A | Varies from 0.85 to 0.98A
96   | Standard Rear | 75%  | 0.31A | 3 hours 12 minutes | Varies from 0.25A to 0.31A | Varies from 0.62 to 0.72A
96   | Standard Rear | 50%  | 0.22A | 4 hours 30 minutes | Varies from 0.18A to 0.22A | Varies from 0.44 to 0.49A
80   | Standard Front| 100% | 0.35A | 2 hours 42 minutes | Varies from 0.27A to 0.35A | Varies from 0.55A to 0.85A
80   | Standard Front| 75%  | 0.28A | 3 hours 34 minutes | Varies from 0.21A to 0.28A | Varies from 0.40A to 0.62A
80   | Standard Front| 50%  | 0.21A | 4 hours 45 minutes | Varies from 0.15A to 0.21A | Varies from 0.29 to 0.42A
48   | All White   | 100% | 1.05A | 57 minutes         | Never set a bunch of LEDs to full white like this!
48   | All White    | 75% | 0.78A | 1 hour 17 minutes | If you value your eyesight, don't do this either!
48   | All White    | 50% | 0.52A | 1 hour 55 minutes | Might want to avoid this too!


