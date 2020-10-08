# CrealityEnder3Pro

## Progress

### 07-October-2020  
Filament Runout Sensor (Microswicth version) is now and running and working, agin, more JST XH crimps.

### 06-October-2020  
BLTouch is finally wired in and working, lots of JST XH crimps alter, but worth the effort, printing really nicely now. 

### 04-October-2020
Some rewiring is needed, my first attempt did not work out so well. Happily the Ender 3 is [open-sourced](https://github.com/Creality3DPrinting/Ender-3) so i can find the required wiring and try again.  

**Personal Rant :** Really wish that everyone used the same connectors. Silly Ender 3 uses JST PH on the motor connections and JST XH everywhere else. I only bought replacement JST XH. Thank goodness I own a soldering iron. :)

### 18-September-2020
1. Printed a Electronics Box for my hardware - [U1JO - Control Box v2](https://www.thingiverse.com/thing:4194627)
2. Schematics
   1. Relay
   2. Buck Converters
   3. RPI
   4. SKR E3 Mini V2
   5. Meanwell PSU

BLTouch Measurements  
Left = -42 (-)
Forward = -7 (-)

```
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

Z-Probe offset = -1.4  
M211 S0 to enable negative offset  
M211 S1 to disable negative offset
