[RF6886TR13 - PA - 13” Reel with 2500 pieces](https://www.qorvo.com/products/d/da000557)

System Design
--------------------------------------------------------------------------------------
@433 to 470MHz (Typical 450MHz) 
Max Power -> Max Current requirement (3100mA), Voltage - Vd (4V)
Power dissipation - 5W
Max RF input for 50Ohm Output load - 12dBm

Schematic Design
--------------------------------------------------------------------------------------
Power requirement - 3.6V to 4V Power supply
johanson Hi-Q tight Tolerance check for the same


PCB Design
--------------------------------------------------------------------------------------
The evaluation Board used has been demonstrated with a normalized impedance values
@433MHz -> 1.997 - j 0.941
@450MHz -> 1.866 - j 0.251
Vreg1/2 - 2.7 to 2.8V is enhanced Performance in linear range (Stable ones are required)




Special Capabilities
--------------------------------------------------------------------------------------
Temperature range of Operation - -40Deg to +85Deg

Operational Procedures
--------------------------------------------------------------------------------------
Turn on:
1. Apply VCC
2. Apply VREF1/2
3. Apply drive at RF input
Turn off:
1. Remove drive at RF input
2. Bring down voltage at VREF1/2
3. Bring down VCC
