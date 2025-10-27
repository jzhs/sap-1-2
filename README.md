# sap-1-2
Malvino SAP-1 with microprogrammed control. 


Functionally same as previous SAP-1-1 project. However I changed the
control unit to microprogramming in line with Malvino-Brown section
10-8.

Also cleaned up a number of warnings: There are no more infered
latches. The 1kHz clock has been replaced with a clock enable
signal. Everyone uses the 100MHz system clock.

