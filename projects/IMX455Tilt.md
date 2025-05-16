Adjusting tilt with a full frame sensor can be very demanding. I know that my [William Optics Cat 91](../gear/Cat91) is almost tilt-free so the main reason for tilt must be the camera/sensor itself.

# Measuring Tilt
I used two ways to measure sensor tilt: [ASTAP](https://www.hnsky.org/astap.htm) and the [Aberration Inspector in N.I.N.A](https://nighttime-imaging.eu/).

This [Touptek IMX455 camera](https://www.teleskop-express.de/de/ts-zubehoer-31/kameras-gekuehlt-16/ts455mp-17896) has three sets of screws for tilt adjustment:
![](../IMG_2993.jpg)
Upper left (UL), upper right (UR), and bottom (B)

I pointed the telescope to the north and ran autofocus after each adjustment setting. For each adjustment I opened all three fastening screws (those in the middle of each set), then adjusted the tilt with the two smaller screws and fastened the fastening screws again. I did that not to bend the plate too much. After that, I made a single 5s exposure, loaded the file into ASTAP, solved it and did Image Analysis/Tilt. Sometimes I had to make a couple of exposures as the ASTAP method is very sensitive to seeing conditions. Every once in a while I ran N.I.N.A. aberration inspector to verify the findings.

# Initial State
![](../Screenshot%202025-05-13%20190749.png)

# One
I screwed UL a bit in to move the sensor back on the upper left side. 
![](../Screenshot%202025-05-13%20190854.png)
I obviously picked the wrong side, so back to zero.

# Two
I screwed UL back out and UR a bit in.
![](../Screenshot%202025-05-13%20190923.png)
Not enough.

# Three
Screwed UR a bit more in.
![](../Screenshot%202025-05-13%20191029.png)
Still not enough.

# Four
Screwed UR a bit more in.
![](../Screenshot%202025-05-13%20191101.png)
Still not enough.

# Five
Screwed UR a bit more in.
![](../Screenshot%202025-05-13%20191146.png)
We are getting there. Now the bottom part is distorted almost equally on both sides. Let's fix that.

# Six
Screwed B in.
![](../Screenshot%202025-05-13%20191256.png)
Too much.

# Seven
Screwed B out a bit.
![](../Screenshot%202025-05-13%20191422.png)
Ok for now.

# Final test with N.I.N.A aberration inspector
![](../Screenshot%202025-05-16%20192149)
![](../Screenshot%202025-05-16%20192157)


# Next Steps
I played around more and more, but it is almost impossible to get a better result using the 3-Point adjustment screws on the camera. To further improve, I would have to add a different way to fine-tune the tilt but for now, I'm OK with it. I could also confirm that the tilt is caused by the camera by rotating the imaging train. I'm looking forward to trying this camera with one of my scopes with a sloppy focuser...
In my experience, tilt below 15% is easily fixed in post processing, so no need to get crazy here.
