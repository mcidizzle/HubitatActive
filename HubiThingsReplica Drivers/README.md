# HubiThings Replica Drivers MAY REQUIRE MOD TO APP

This series of drivers is for HubiThings Replica.  It requires a HubiThings Replica version greater than 1.2.09.

For version 1.0.9, the following needs to be applied to the HubiThings Replica app:

Line 1253, change "arguments = map" to "arguments = [ map ]

Without this, the Color Bulb Driver will not be able to setColor, hue, or saturation!

Dave