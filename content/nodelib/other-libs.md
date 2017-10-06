---
title: "Other libraries"
weight: 4
---

{{% notice info %}}
The code below is not JeeNode-specific, it can also be used with other
Arduino'ish boards.
{{% /notice %}}

## EtherCard

The [EtherCard library](https://github.com/jcw/ethercard) on GitHub can be used
to send and receive Ethernet packets via an [Ether
Card](https://jeelabs.net/projects/hardware/wiki/Ether_Card) board, or any other
expansion board with an ENC28J60 chip. It's based on an initial implementation
by Guido Socher and Pascal Stang, but has since evolved considerably.

## RTClib

The [RTC library](https://github.com/jcw/rtclib) on GitHub can be used to
connect to a variety of I2C-based Real Time Clock chips. It includes to ability
to set the RTC from the last-compiled date, which makes it easy to get the clock
running at the (aproximately) correct time.

## GLCDlib

The [GLCD library](https://github.com/jcw/glcdlib) on GitHub contains a driver
for ST7656-based Graphics LCD screens, such as the [Graphics
Board](https://jeelabs.net/projects/hardware/wiki/Graphics_Board) for JeeNodes.
This code was derived from the [ST7565](https://github.com/adafruit/ST7565-LCD)
library by AdaFruit.

GLCDlib includes a large set of monospaced and proportional fonts, as well as
some optimisations to improve refresh rates when only parts of the display
change.

## IDE-hardware

The [IDE-hardware](https://github.com/jcw/ide-hardware) repository on GitHub is
not so much a library, but an add-on for version 1.5 of the Arduino IDE to
support the ATtiny84 found on the [JeeNode
Micro](/nodelib/hardware/#jeenode-micro).

This code was adapted from the
[arduino-tiny](https://code.google.com/archive/p/arduino-tiny/) project, but has
not kept up with changes in the way the Arduino IDE now handles hardware
platform differences.
