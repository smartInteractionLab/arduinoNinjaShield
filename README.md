:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
::                                                           ::
::  Smart Design RF Shield (v0.1 and v0.2)                   ::
::                                                           ::
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::


The actual RF omponents on the shield come from Seeed Studio, 
look for their "433Mhz RF link kit" or "433Mhz RF link kit", 
depending on at which frequency you want to use, at

http://www.seedstudio.com

The shield might be compatible with other similar modules, 
however this has not been tested and should only be done at
your own volition.

You also might want to order stackable headers for the shield
if you're planning on adding another shield, or want to 
connect anything else to the Arduino pins. Such headers can 
be found at most places which deal with Arduino related
hardware, such as Sparkfun, Adafruit.

http://www.sparkfun.com
http://www.adafruit.com

To get the shield to work when it has been populated with the
right components and hooked into the Arduino you need to run 
the RC-Switch library in your Arduino sketch as well. Follow 
the documentation in the library to get your shield running 
in the way you want it to. The library can be found here: 

http://code.google.com/p/rc-switch/

If you do add another shield take into consideration that
digital pins 2 and 7 are used by the RF Shield and thus
cannot be used for other shields. Though, if you only need
TX or RX capability you can free up the according pin. TX 
uses pin 7 and RX uses pin 2.

In case you are planning to use the Arduino as a sensor or 
actuator together with the Ninja Blocks platform there is a 
great tutorial available at http://www.ninjablocks.com called 
"Adding RF 433MHz to your Arduino"

You can read about the process of creating this shield at 

http://www.smartinteractionlab.com

Thank you, and have fun!
