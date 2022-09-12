# CM4108256 - CM4 module with 256GB eMMC

## Project description

The aim of the project was to modify the eMMC memory (by soldering) from the default 32GB to 256GB, ie to create a unique, custom CM4108256 ("Little Big Monster") configuration, which is not available on the market.
For this purpose, a brand new Raspberry Pi CM4 module was used in the maximum configuration: 8GB RAM + 32GB eMMC + WiFi (CM4108032).

## EMMC memory
The following model (v5.1 standard) was used as eMMC memory: SanDisk iNAND7350, part number SDINBDD4-256G, in the BGA153 housing.
https://www.sandisk.com/content/dam/sandisk-main/en_us/assets/resources/data-sheets/iNAND-7350-Prod-Brief.pdf
The memory was bought on the Aliexpress portal for about $ 90.

## Execution
1. First, the eMMC memory chip was desoldered.
2. There is a place on the CM4 module for soldering a new memory (cleaning of soldering pads).
2. Then the first attempt was made to solder the eMMC 256GB chip. Unfortunately, the chip was soldered inaccurately and crookedly, so it was necessary to clean the pads and re-solder the memory chip.
3. Before re-soldering, it was necessary to perform BGA reballing of the eMMC system with steel stencil.
4. The second attempt to solder the memory chip was successful and the eMMC memory was detected after starting the CM4 module.

