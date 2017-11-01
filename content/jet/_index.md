---
title: "JeeLabs Embello Toolkit"
weight: 40
---

**JET** is a dataflow framework and server for
multi-node embedded systems
<!--more-->

The JET architecture is in the process of being
redesigned - for a recent (i.e. mid-2017) update about what's going on, see this
[JeeLabs weblog post](http://jeelabs.org/2017/05/revisiting-the-jet-design/).

JET is made from a number of components, as summarised in this diagram:

![](jet-arch.png?width=500px)

Apart from the MQTT _broker_ (which uses the [Mosquitto](https://mosquitto.org)
software), very little of the above has been implemented so far. Most of the
focus is on [Folie](http://folie.jeelabs.org).

The remote "nodes" are based on microcontrollers, see the
[Embello](http://embello.jeelabs.org) project.

## Functional overview

![](jet-conceptual.png?width=500px)

## Development setup

![](jet-setup.png?width=500px)
