# Creality Ender 3 Pro Wiring

## Current Colour Coding  

|Cable Tie Colours | Function  |
|---------|---------|
|Blue ; Blue     | Extruder Motor        |
|Yellow ; Yellow     | X Motor         |
|Red ; Red     | Y Motor         |
|Green ; Green     | Z Motor         |
|Yellow        | X Stop        |
|Red        | Y Stop        |
|Green        | Z Stop        |
|Yellow ; Black        | Thermistor Bed        |
|Yellow ; Black ; Black        | Thermistor Head        |
|Yellow ; Yellow ; Black        | Fan Permanent        |
|Green ; Red ; Blue        | BLTouch        |

## Wiring to Connectors  

### 4 Pin Connectors  

|Function |Connector Type  |  
|---------|---------|
|X Motor    | 4 Pin GX Connector (1)    |  
|Y Motor    | 4 Pin GX Connector (2)    |
|Z Motor    | 4 Pin GX Connector (3)    |
|E Motor    | 4 Pin GX Connector (4)    |
|Bed , Nozzle Thermistor    | 4 PIN GX Connector (5)    |
|Hotend Heater    | 4 PIN GX Connector (6)    |
|Bed Heater    | 4 PIN GX Connector (7)    |
|Hot End Fan, Part Cooling Fan| 4 Pin GX Connector (8)    |

### 8 Pin Connectors  

|Function |Connector Type  |  
|---------|---------|
|X, Y, Z Stops    | 8 Pin GX Connector (1)    |
|BLtouch    | 8 Pin GX Connector (2)    |

### Internal Connetions

|Function | Connector Type  |  
|---------|---------|
|Mainboard Cooling Fan    |Internal Connection    |
|24 V to Buck Converter    | 12V Output    |
|24 V to Buck Converter    | 5V Output    |
|RPI to SKR E3 Mini V2    | Internal    |
|5V to Relay    | Internal    |

## TO FIX

### 04-May-2021  

~~1. X-Stop Wiring on printer~~  
~~2. X-Motor wiring by board~~

## Motor Board Connections

- X Motor

```bash
|=======================================================|  
|    1              2           3               4       |  
|    |              |           |               |       |  
|    Blue           Red         Green           Black   |
|=======================================================|
                |__|             |__|
```

- Y Motor

```bash
|=======================================================|  
|    1              2           3               4       |  
|    |              |           |               |       |  
|    Blue           Red         Green           Black   |
|=======================================================|
                |__|             |__|
```

- Z Motor

```bash
|=======================================================|  
|    1              2           3               4       |  
|    |              |           |               |       |  
|    Blue           Red         Green           Black   |
|=======================================================|
                |__|             |__|
```

- Extruder Motor

```bash
|=======================================================|  
|    1              2           3               4       |  
|    |              |           |               |       |  
|    Blue           Red         Green           Black   |
|=======================================================|
                |__|             |__|
```
