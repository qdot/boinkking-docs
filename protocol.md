# Protocol

The BKK protocol consists of either reads from the device (battery
power) or notifications (buttons, accelerometer).

## Buttons

Buttons are relayed as a single byte, via notifications from the ffe1
characteristic. Note that only one button can have its status relayed
at any time, pressing other buttons while a button is pressed may or
may not cause the new value to be transmitted.

- 0x05 - "G" button
- 0x06 - "L" button
- 0x08 - "E" button
- 0x09 - "R" button

## Accelerometer

The accelerometer value is relayed as 15hz updates through the ffa1
characteristic. Update are only sent while the toy is moving. The
accelerometer value seems to consist of 3 bytes, but only reacts to
movement on one axis, a vector going length-wise through the toy.
