# ATS20_atx_ex
Fork of ats20_ats_ex by goshante

Original software ported to platformIO.

Modified line #define BATTERY_VOLTAGE_PIN A2 to #define BATTERY_VOLTAGE_PIN A1
in order to get a battery capicity reading without the suggested hardware modification.

Compiles OK.
Programming into the ATS20+ receiver vie the Arduino USB mini B connector with AVRDude.

WARNING !!!
You MUST use a USB cable with the +5V line removed. It can be done by removing the cable jacket and screening and cutting the RED wire.
Otherwise, you will BURN YOUR AST20+ !
