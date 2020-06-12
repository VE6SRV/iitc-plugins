# iitc-plugins
plugins for IITC
DroneRange draws a circle 300 metres in radius around every portal on screen.
The Mark I drone can fly to any portal that can be seen on the scanner from the current drone location.
On my Iphone 11, that equates to approximately 600 metres, although this number seems to vary over time. I have seen portals 540 metres away be out of range, and yet have also completed a drone move of 670 metres.
I have successfully completed a move, only to look back to the portal that I just left, and find that it is out of range.

With all of that in mind, I still wanted to be able to get an idea of where I could possibly travel with the drone.

This plugin will draw a 300 metre radius circle around all portals in view. If the circle drawn touches or overlaps with another portal circle, then a drone move should be possible between these two portals.

Masses of overlapping or touching circles are areas where drone movement should be possible. Gaps between circles show areas where the distance between the two portals is too large for the drone to negotiate. 

Based on my observations, and experience, these circles should be used as an estimate only.

Unknown if different devices with different screen resolution and geometries have different range of movement limits.
