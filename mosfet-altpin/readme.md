**BTT SKR Mini E3 V2**

[Wiring Guide](mosfet-altpin\BTT_SKR_Mini_E3_V2_pin.png)  

## Pin Changes  
### File(s)  
[Common Pins](
mosfet-altpin\mosfetFirmware\Marlin-2.0.x\Marlin\src\pins\stm32f1\pins_BTT_SKR_MINI_E3_common.h)  
[BTT SKR Mini E3 V2 Pins](mosfet-altpin\mosfetFirmware\Marlin-2.0.x\Marlin\src\pins\stm32f1\pins_BTT_SKR_MINI_E3_V2_0.h)


### Change(s)
PS-ON -> External MOSFET  
pins.h: PC13 -> Replaces PC9
|Original  |New  |
|---------|---------|
|BED |External MOSFET |
|PC9 |PC13 |
