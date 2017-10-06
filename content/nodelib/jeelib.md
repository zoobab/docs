---
title: "JeeLib"
weight: 3
---

[JeeLib](https://github.com/jcw/jeelib) is an open source library on GitHub with
a range of functions and examples. It has evolved alongside the different
[JeeNodes](../hardware) over the years. JeeLib is an add-on library for the
Arduino IDE.

The main components of JeeLib are:

* a **Ports** class, for easy access to the ports on a JeeNode
* a **PortsI2C** class for bit-banged I2C bus support on arbitrary I/O pins
* an **RF12** driver (in various configurations) for the wireless RFM12B modules
* an **RF69** driver (in various configurations) for the wireless RFM69CW
  modules
* a **Sleepy** class for ultra low-power sleeping of ATmega and ATtiny µC's
* custom drivers for a variety of add-on
  [JeePlugs](https://jeelabs.net/projects/hardware/wiki)

The examples in JeeLib are split into a number of areas:

* [DIJN](https://github.com/jcw/jeelib/tree/master/examples/DIJN) - the [Dive
  into JeeNodes](https://jeelabs.net/projects/cafe/wiki/Dive_Into_JeeNodes)
  tutorial series
* [Ports](https://github.com/jcw/jeelib/tree/master/examples/Ports) - some 65
  examples using the Ports functionality
* [RF12](https://github.com/jcw/jeelib/tree/master/examples/RF12) - some 40
  examples using the RF12 radio driver
* [RTOS](https://github.com/jcw/jeelib/tree/master/examples/RTOS) - demo code
  using the [ChibiOS-AVR](https://github.com/matteoserva/ChibiOS-AVR/)
  multi-tasking library

There is an elaborate (but somewhat ageing) [documentation
area](https://jeelabs.org/pub/docs/jeelib/files.html) for most of the code in
JeeLib, including most of the example code.
