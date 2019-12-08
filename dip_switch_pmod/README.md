# 8P DIP Switch PMOD

This is a 8-position DIP swith PMOD.  The 9-pin SIP module is for an optional
pull-down resistor array.  It is not strictly necessary as the pins on the
FPGA should have weak pull-downs that can be enabled.

This board expects that there are inline current limiting resistors on the
PMOD signal lines to avoid exceeding the current rating of both the switch
and the FPGA should the FPGA pins be accidentally configured for output
rather than input.

This repo contains KiCAD files and Gerbers for those wanting to make their
own boards.  The board was auto-routed using FreeRouting.

This project is OSHW (Open Source Hardware), released under the GPLv3 license.

![dip_switch_pmod.png](dip_switch_pmod.png)

If you are interested in purchasing kits or complete modules, please contant
me at rob@mobilinkd.com.

