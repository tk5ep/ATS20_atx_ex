# ATS20_atx_ex
Fork of ats20_ats_ex by goshante

Original software ported to platformIO.

Modifications :
1) In order to get a battery capacity reading without the suggested hardware modification.
file defs.h line #define BATTERY_VOLTAGE_PIN A2 to #define BATTERY_VOLTAGE_PIN A1

Compiles OK.
Programming into the ATS20+ receiver via the Arduino USB mini B connector with AVRDude.

WARNING !!!
If you have an older ATS20+ version with 2 USB connectors on the rear.
You MUST use a USB cable with the +5V line removed. It can be done by removing the cable jacket and screening and cutting the RED wire.
Otherwise, you will BURN YOUR AST20+ !
