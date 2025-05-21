Adjusting tilt with a full frame sensor can be very demanding. I know that my [[William Optics (Red)Cat 91 WIFD]] is almost tilt-free so the main reason for tilt must be the camera/sensor itself.

# Sources of tilt
There are many possible sources of tilt: focuser, adaptors, OAG, basically everything in the image train. Even optics, filters, reducers or flatteners can add tilt to the system. Before adjusting the tilt in your system you have to find the source of the tilt. In my case most of the time it was the focuser. Focusers are heavily strained by the weight of the camera and other stuff and many of them are too weak. It's easy to find out if the focuser is your source of tile: point your scope to different regions in the sky, make photos and analyse them. I also had bad adapters causing tilt, since then I measure all adaptors with a caliper to be sure. 

# Sensor tilt
This document is only about sensor tilt. I found out that my new camera has some minor sensor tilt. The direction of tilt is always the same, no matter where I point my scope, how I rotate the camera or how I mount the camera. The scope itself is almost tilt free due to the William Optics WIFD focuser.

# Measuring Tilt
I used two ways to measure sensor tilt: [ASTAP](https://www.hnsky.org/astap.htm) and the [Aberration Inspector in N.I.N.A](https://nighttime-imaging.eu/).

This [Touptek IMX455 camera](https://www.teleskop-express.de/de/ts-zubehoer-31/kameras-gekuehlt-16/ts455mp-17896) has three sets of screws for tilt adjustment:
![[IMG_2993.jpg]]
Upper left (UL), upper right (UR), and bottom (B)

I pointed the telescope to the north and ran autofocus after each adjustment setting. For each adjustment I opened all three fastening screws (those in the middle of each set), then adjusted the tilt with the two smaller screws and fastened the fastening screws again. I did that not to bend the plate too much. After that, I made a single 5s exposure, loaded the file into ASTAP, solved it and did Image Analysis/Tilt. Sometimes I had to make a couple of exposures as the ASTAP method is very sensitive to seeing conditions. Every once in a while I ran N.I.N.A. aberration inspector to verify the findings.

# Initial State
![[Screenshot 2025-05-13 190749.png]]

# One
I screwed UL a bit in to move the sensor back on the upper left side. 
![[Screenshot 2025-05-13 190854.png]]
I obviously picked the wrong side, so back to zero.

# Two
I screwed UL back out and UR a bit in.
![[Screenshot 2025-05-13 190923.png]]
Not enough.

# Three
Screwed UR a bit more in.
![[Screenshot 2025-05-13 191029.png]]
Still not enough.

# Four
Screwed UR a bit more in.
![[Screenshot 2025-05-13 191101.png]]
Still not enough.

# Five
Screwed UR a bit more in.
![[Screenshot 2025-05-13 191146.png]]
We are getting there. Now the bottom part is distorted almost equally on both sides. Let's fix that.

# Six
Screwed B in.
![[Screenshot 2025-05-13 191256.png]]
Too much.

# Seven
Screwed B out a bit.
![[Screenshot 2025-05-13 191422.png]]
Ok for now.

# Final test with N.I.N.A aberration inspector

![[Screenshot 2025-05-16 192149.png]]

![[Screenshot 2025-05-16 192157.png]]

# Next Steps
I played around more and more, but it is almost impossible to get a better result using the 3-Point adjustment screws on the camera. To further improve, I would have to add a different way to fine-tune the tilt but for now, I'm OK with it. I'm looking forward to trying this camera with one of my scopes with a sloppy focuser...
In my experience, tilt below 15% is easily fixed in post processing, so no need to get crazy here.