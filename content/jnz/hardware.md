---
title: "Hardware"
weight: 1
---

## Pinouts

There are three headers on the JeeNode Zero: a 17-pin main header (left), a
6-pin FTDI header (bottom), and a 5-pin AUX header (bottom right):

![](../jnz-rev4-pinout.png?width=600px)

{{% notice note %}}
The top of the JNZ is the **unpopulated** side. Most components are on the
bottom.
{{% /notice%}}

### Voltage levels

Many - but not all - pins can support a (digital) input voltage level up to
5.5V.  All output voltage levels are between 0V and 3.3V.

Power is normally applied to either of the 5V pins (they are internally tied
together on the PCB). If the supply voltage is between 3.4V and 5.5V, the
JeeNode Zero will run at its nominal 3.3V design level. However, with proper
clock confiuration, a lower voltage can also be applied, since the µC and RF
module can both work down to 1.8V.

If a 3V coin cell is fitted, power _should not_ be applied to any of the supply
pins - one solution is to _always_ remove the coin cell when connecting to FTDI.

## Top and bottom view

The top of the JeeNode Zero is _unpopulated_ by default:

![](../DSC_5703.jpg?width=300px)

The bottom has the wireless radio module, the micrcontroller, and the power
supply regulator:

![](../DSC_5710.jpg?width=300px)

The boards above are shown with the FTDI header mounted in the recommended
"in-line" position, but the header can also be mounted upwards or downwards.
