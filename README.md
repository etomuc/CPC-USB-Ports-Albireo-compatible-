# Albireo compatible USB ports for the Amstrad CPC

For more information regarding the Albireo, see here: https://www.cpcwiki.eu/index.php/Albireo

> [!IMPORTANT]
> This is not a full Albireo replacement. The PCB here only provides the option to connect up to two USB CH376s modules as used in many DIY microprocessor projects. No SD-Card or other features are included. Also please don't ask the Albireo developer for any support.
> 
> Regarding SD support: It might be possible to add a SD card slot directly to the CH376 IC on the CH376 daughterboard but this is not guaranteed to work. 

<img src="/pictures/albireo-pcb.jpg" width="640"/> 

You can populate one or both USB modules. The left listens to port &FE80/81 the right one to &FE40/41.

If a USB module is not populated you can also leave empty the corresponding 74HCT688 in the same spot. The 74HCT688 on the left is always required. 

## Building

> [!CAUTION]
>**USE AT YOUR OWN RISK.**
>
>This is a hobby project, I am a hobbyist and no engineer. There is always the risk that the expansion can cause harm to your CPC. 
>Although I have tested the expansion on several CPCs for many hours with many other expansions and lots of software, there is no guarantee that it will properly work under all circumstances, with all expansions or with all revisions of the CPC 6128.
>
> Especially if you are building this for others (commercially or not) make sure to make your own intense tests to guarentee this expansion works as expected before handing over to the recipients.  
>
>**USE AT YOUR OWN RISK.** 

| Part | Mouser No. (example, not verified yet) | Quantity |
| --- | --- | --- |
| PCB | n/a | x1 |
| 74HCT688 DIP | 595-CD74HCT688E | x2 or x3 |
| CH376s USB module| n/a (buy e.g. on Amazon, AliExpress or Ebay) | x1 or x2 |
| MX4 connector - angled | e.g. 710-61205021721  | x1 |
| Capacitor 100nF 104 2.5mm | 581-AR155C104K4R | x2 or x3 |
| Capacitor 10uF (or 22uF) - 2.0mm | e.g. 598-106SVF025M  | x1 |

Make sure to get the right USB module. There are at least 2 different variants. Select the one with 6 pins on the side and the correct pinout for the main header:

<img src="/pictures/albireo-BOM.jpg" width="640"/> 



