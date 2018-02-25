16 Tiny Pixels!

![16 Tiny Pixels 3D View](https://raw.githubusercontent.com/SynchronisticSavage/16-Tiny-PIxels/master/16-Tiny-Pixels.png)
(Cause sometimes you just need a little ring of programable leds...)

A Simple little board combining an AT-Tiny, 16 WS2812 LEDS, Micro-USB Connector, 2x3 Pin Header, and a handful of capacitors, resistors, and Diodes. All Packed into a nice circular little package.

Relativly large smd components, and hand solder pads have been used to make this board simple to solder.

MicroNuculus can be programmed to the Attiny-85 prior to soldering or via the pin header, allowing subsequent programming to be done over the USB.

Code for this and controlling the ws2812 LEDs can be found somewhere out there on the interwebs(Multiple Sources), you know how to find it ;)

To keep this board as simple as possible there is no power protection cicuitry provided...this may change in later versions, but i like the simpisity for now.

As of the Time of This Writing this board has not been tested, this is the first board this being has designed

One thing i am not certain about is the capacitor placment and connection, i think it should work as it is, but maybe i am wrong?

Also not sure if it is a good idea to fill the top layer with gnd and bottom with vcc, mostly just wanted to try the filled zone feature...seems good...pretty sure it is good...let me know if i am wrong... :)

Note: this board was created using the WifI Pixels kicad files as a template, a cool Open Source Board using the esp8266 created by ProtoNeer.
Check it out here:
https://github.com/Protoneer/WifiPixels
and here:
https://wiki.protoneer.co.nz/WifiPixels

this board is also based on the Digispark Schematics Found Here:
http://www.instructables.com/id/Digispark-DIY-The-smallest-USB-Arduino/

Big Ups to the Open Source Community!
TO-DO!
Organize and rename stuff
make sure it is portable and opens fine on other systems 
make bettery PCB-Art
Add IR Sensor possibly another attiny to fully support IR (More Testing Required~!)
Add WS2812 LEDs to the 3D Viewer View :P


