# Albireo compatible USB ports for the Amstrad CPC

For more information regarding the Albireo, see here: https://www.cpcwiki.eu/index.php/Albireo

> [!IMPORTANT] This PCB here only provides USB ports. not SD-Card or other features. It's probably possible to add a SD card directly to the CH376 IC on the CH376 daughterboard but this is not guaranteed to work. 

<img src="/pictures/albireo-pcb.jpg" width="640"/> 

You can populate one or both USB modules. The left listens to port &FE80/81 the right one to &FE40/41.

If a USB module is not populated you can also leave empty the corresponding 74HCT688 in the same spot. The 74HCT688 on the left is always required. 

## BOM

| Part | Mouser No. (example, not verified yet) | Quantity |
| --- | --- | --- |
| PCB | n/a | x1 |
| 74HCT688 DIP | 595-CD74HCT688E | x2 or x3 |
| CH376s USB module| n/a (buy e.g. on Amazon, AlieExpress or Ebay) | x1 or x2 |
| MX4 connector - angled | e.g. 710-61205021721  | x1 |
| Capacitor 100nF 104 2.5mm | 581-AR155C104K4R | x2 or x3 |
| Capacitor 10uF (or 22uF) - 2.0mm | e.g. 598-106SVF025M  | x1 |

Make sure to get the right USB module. There are at least 2 different variants. Select the one with 6 pins on the side and the correct pinout for the main header:

