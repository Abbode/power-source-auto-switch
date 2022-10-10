# power-source-auto-switch
This module will provide power to your project via main and backup power sources.

You connect the two power sources to the module and it will do the following:

    When your main source is working properly it will provide you circuit power from this source.
    When your main source goes offline it will automatically disconnect the main source and connect to backup source.
    When your main source come back online it will automatically disconnect the backup source and goes back to the main source.

The two source are completely isolated for safety reasons.
The module uses SMD pads, best way to use it is re-flow soldering.
The module supports up to 40V and 4.5A. 
