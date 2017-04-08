# BKK Hardware

BKK currently manufactures two pieces of hardware with bluetooth
capabilities.

## BKK Cup

The BKK Cup is a onahole style stroker/masturbator with an
accelerometer and buttons built in. There is no output or haptic
actuation in the toy, it is only used as a controller for either games
or movies.

## BKK Bracelet

__Note: BKK Bracelet implementation here is speculation taken from ad
copy on the [product website](https://www.bkksextoy.com/product), we
do not actually have a BKK Bracelet on hand at the time of this
writing.__

The BKK Bracelet is most likely the same circuitry as the BKK Cup,
except in "bracelet" form. It probably contains the same accelerometer
and button setup, allowing users to attach it to the onahole of their
choice.

## Chipset

Due to the service IDs and identification of the BKK Cup, it is
assumed that this is
a [TI CC2540 Reference Kit Design](http://www.ti.com/product/cc2540).
In fact, it may
using
[a reference keyfob implementation available on github](http://chipk215.github.io/keyfobsimulation/).
This is apparently a common reference design to
copy,
[as it has also been found in lightbulbs](https://learn.adafruit.com/reverse-engineering-a-bluetooth-low-energy-light-bulb/explore-gatt).
