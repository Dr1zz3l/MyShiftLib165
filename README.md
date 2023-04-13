# MyShiftLib165
Slight edit of ShiftLib165 by superadm1n. Passing a pin for clock_enable is now optional. With informative examples. I highly reccomend checking out the original ShiftLib165 by superadm1n [here](https://github.com/superadm1n/ShiftLib165).

I haven't changed much. But since I just grounded the clock_enabl pins on the 74HC165, I don't need to specify a GPIO for it. With "my" version, this pin is optional. And I log the bit changes with the logging module, which is shown in the examples at the end.
