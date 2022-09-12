# CM4108256 - CM4 module with 256GB eMMC

![Screenshot](photos/03.png)

## Project description

The aim of the project was to modify the eMMC memory (by soldering) from the default 32GB (SAMSUNG KLMBG2JETD-B041) to 256GB (SanDisk SDINBDD4-256G), ie to create a unique, custom CM4108256 ("Little Big Monster") configuration, which is not available on the market.
For this purpose, a brand new Raspberry Pi CM4 module was used in the maximum configuration: 8GB RAM + 32GB eMMC + WiFi (CM4108032).

## EMMC memory
The following model (v5.1 standard) was used as eMMC memory: SanDisk iNAND7350, part number SDINBDD4-256G, in the BGA153 package.
https://www.sandisk.com/content/dam/sandisk-main/en_us/assets/resources/data-sheets/iNAND-7350-Prod-Brief.pdf

The memory was bought on the Aliexpress portal for about $90.

## Execution
1. First, the eMMC memory chip was desoldered.
2. Next, by cleaning of the soldering pads, place for soldering a new memory has been prepared.
2. Then the first attempt was made to solder the eMMC 256GB chip. Unfortunately, the chip was soldered inaccurately and crookedly, so it was necessary to clean the pads and re-solder the memory chip.
3. Before re-soldering, it was necessary to perform BGA reballing of the eMMC system with steel stencil.
4. The second attempt to solder the memory chip was successful and the eMMC memory was detected after starting the CM4 module.

## Photos

CM4108256 module (with soldered 256GB eMMC chip):
![Screenshot](photos/01.png)

CM4108256 module (with soldered 256GB eMMC chip):
![Screenshot](photos/02.png)

CM4108256 module (with soldered 256GB eMMC chip):
![Screenshot](photos/03.png)

CM4108256 module (with soldered 256GB eMMC chip):
![Screenshot](photos/04.png)

Original CM4108032 module:
![Screenshot](photos/05.png)

Both eMMC chips:
![Screenshot](photos/06.png)

Both eMMC chips:
![Screenshot](photos/07.png)

After desoldered original BGA eMMC chip:
![Screenshot](photos/08.png)

Cleaned up BGA pads:
![Screenshot](photos/09.png)

CM4 module ready for soldering new eMMC chip:
![Screenshot](photos/10.png)

SanDisk 256GB eMMC chip ready to solder:
![Screenshot](photos/11.png)

First attempt failed, eMMC chip require BGA reballing:
![Screenshot](photos/12.png)

Cleaned up again BGA footprint:
![Screenshot](photos/13.png)

BGA reballing by using steel stencil:
![Screenshot](photos/14.png)

CM4 module during flashing new 256GB eMMC chip:
![Screenshot](photos/15.png)

SMT steel stencil:
![Screenshot](photos/16.png)

CM4108256 during testing:
![Screenshot](photos/17.png)

BGA balls (Sn63Pb37, 0.3mm size) for reballing:
![Screenshot](photos/18.png)

BGA balls:
![Screenshot](photos/19.png)

During tests:
![Screenshot](photos/20.png)

Desoldered eMMC chip (SAMSUNG 32GB KLMBG2JETD-B041):
![Screenshot](photos/21.png)

Samsung eMMC chip after cleaning:
![Screenshot](photos/22.png)

CM4108256 module:
![Screenshot](photos/23.png)

SanDisk SDINBDD4-256G chip:
![Screenshot](photos/24.png)

Raspberry Pi Imager during flashing eMMC chip:
![Screenshot](photos/25.png)

GParted tool: properties of 256GB eMMC memory: 
![Screenshot](photos/26.png)

Benchmark of 256GB chip:
![Screenshot](photos/27.png)

Benchmark of original eMMC chip (SAMSUNG):
![Screenshot](photos/28.png)
