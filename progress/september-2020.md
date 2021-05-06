# September 2020 Progress

## 18-September-2020

1. Printed a Electronics Box for my hardware - [U1JO - Control Box v2](https://www.thingiverse.com/thing:4194627)
1. Schematics
   1. Relay
   1. Buck Converters
   1. RPI
   1. SKR E3 Mini V2
   1. Meanwell PSU

BLTouch Measurements  
Left = -42 (-)
Forward = -7 (-)

```bash
 *     +-- BACK ---+
 *     |    [+]    |
 *   L |        1  | R <-- Example "1" (right+,  back+)
 *   E |  2        | I <-- Example "2" ( left-,  back+)
 *   F |[-]  N  [+]| G <-- Nozzle
 *   T |       3   | H <-- Example "3" (right+, front-)
 *     | 4         | T <-- Example "4" ( left-, front-)
 *     |    [-]    |
 *     O-- FRONT --+
 *
 ```

Z-Probe offset = -1.2
M211 S0 to enable negative offset  
M211 S1 to disable negative offset
