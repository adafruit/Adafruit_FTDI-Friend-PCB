# FTDI Friend

<a href="http://www.adafruit.com/products/284"><img src="assets/board.jpg?raw=true" width="500px"></a>

Note: These use genuine FTDI chips, either we purchase them or they are manufactured to our specifications with the requirement of genuine FTDI chips 10/22/14 - [read more](https://blog.adafruit.com/2014/10/22/ftdi-drivers-brick-counterfeit-chips-with-latest-windows-update/).

Long gone are the days of parallel ports and serial ports. Now the USB port reigns supreme! But USB is hard, and you just want to transfer your every-day serial data from a microcontroller to computer. What now? Enter the FTDI Friend!

The FTDI Friend is a tweaked out FTDI FT232RL chip adapter. Sure, like the well-known FTDI cable, it can provide power to your project and there are 4 signal lines for sending data back and forth. But the Friend can do much more! For example, you can change the signal and power lines to be either 3.3V or 5V. Arduino-derivatives and XBees use the RTS line for programming but what if you need that DTR line? It's there for you.
By default, we've set it up so that it matches our FTDI cables. The 6th pin is RTS (as of Arduino IDE v18 this will work perfectly for uploading to 'inos), the power wire is +5V and the signal levels are 3.3V (they are 5V compliant, and should work in the vast majority of 3.3V and 5V signal systems).


And of course, we include __a little extra__ - in this case its the extra-long headers that you can use to plug it into a breadboard. There are also blinkies, 2 red & green LEDs __already on the board__ that pulse when serial is sent or received.

You can also purchase a [a 6-pin extension cable](https://www.adafruit.com/product/206) from us, which will let you rearrange the wire order.

In a pinch, [you can even use it to program AVRs](https://learn.adafruit.com/ftdi-friend) (its a bit slow but works!)

[We have a full tutorial page about the FTDI friend](https://learn.adafruit.com/ftdi-friend) and you can peruse the [FTDI cable datasheet](https://cdn-shop.adafruit.com/datasheets/DS_TTL-232R_CABLES_V201.pdf), [FTDI FT232RL chip datasheet](https://cdn-shop.adafruit.com/datasheets/DS_FT232R.pdf) or the schematic/layout files at GitHub.

