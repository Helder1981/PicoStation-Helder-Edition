This is my version of the PicoStation PSX ODE emulator PCB by Paulo who has done some impressive work with this as a cheap DIYish solution to the excellent but a little pricey XStation. Software for this is still very W.I.P but has gotten better recently with better game loading support. The differences between my board and his is that I am providing the files required to get these manufactered by JLCPCB or even PCBWay, they will solder all the parts except the Pico itself which you must provide and solder on.

My board also has a mosfet switch that will stop accepting power from the PSX (when a USB Cable is Plugged into power) and therefore blocking the power being fed back into the PSX possibly damaging it and the LEDs at the top will light up indicating which power source is powering the PicoStation. 

There is a USB-C port facing upwards so it is easy to plug in a cable with the CD lid open to update the Pico, for this port to be functional you need to solder the 2 vias on the left side on the back side of the board otherwise using the MicroUSB port on the Pico can be used for updating it.

The SD card port is the self-ejecting type so simply push it in to insert or remove, no need to pull it out.

Video of this verion of the board being installed (not full install) and being used by ModzVilleUSA
https://www.youtube.com/watch?v=046_GtLkFs8
