---
title: Bill of Materials
tags:
- tag1
- tag2
---

## Overview
written context

## Bill of Materials Example (as Table)

*Table ##: An example of one approach to adding your BOM table to this section.*

| **Part Name/Description** | **Qty** | **Unit Cost** | **Total Cost** | **Manufacture** | **Manufacturer #** | **Vendor Link** |**Datasheet Link** | **Schematic Reference Designators** |
|:--------------------|:----|:---------------|:-----|:--------|:-----|:-----|:----|:-----|
8-bit SIPO/SISO Shift Register, SOIC-16 package | 1 | $0.49 | $ 0.49 | NXP | 74HC595D,112 | [DigiKey](https://www.digikey.com/en/products/detail/nexperia-usa-inc/74HC595D-112/763550) | [datasheet link](https://assets.nexperia.com/documents/data-sheet/74HC_HCT595.pdf) | U1 |
0.1 µF Ceramic Capacitor, +/-10%, X7R, 50V, 0805 package |10 | 0.2750 | $2.75 | KEMET | C0805F104K5RACTU | PRLTA 109 |n/a | C2, C4, C6, C7, C8, C9, C10, C11, C12, C16

Note: Setting it up as a table is nice because it is completely viewable without scaling issues. <ins>Downside</ins> is that you have to do the math.

* You could also import your BOM via a screenshot of the spreadsheet created BOM

| Part Name/Description | Unit Quantity | Unit Prototype Cost | Total Prototype Cost | Manufacturer | Manufacturer Part # | Vendor Link | Datasheet Link | Supplier | Schematic Reference Designators |
|------------------------|---------------|---------------------|----------------------|---------------|----------------------|--------------|----------------|-----------|--------------------------------|
| 0.33 µF ±10% 50V Ceramic Capacitor X7R Radial | 3 | $0.30 | $0.90 | TDK Corporation | FG24X7R1H334KNT06 | [DigiKey](https://www.digikey.com/en/products/detail/tdk-corporation/FG24X7R1H334KNT06/5802993) | [Datasheet](https://product.tdk.com/en/system/files/dam/doc/product/capacitor/ceramic/lead-mlcc/catalog/leadmlcc_halogenfree_fg_en.pdf) | DigiKey | C1 |
| 10000 pF ±10% 50V Ceramic Capacitor X7R Radial | 6 | $0.00 | $0.00 | Vishay Beyschlag/Draloric/BC Components | K103K10X7RF5UH5 | [DigiKey](https://www.digikey.com/en/products/detail/vishay-beyschlag-draloric-bc-components/K103K10X7RF5UH5/2356876) | [Datasheet](https://www.vishay.com/docs/45171/kseries.pdf) | PRLTA 109 | C2,C3 |
| Infrared (IR) Emitter 940nm 1.35V 100mA 80mW/sr @ 100mA 20° Radial, 5mm Dia (T 1 3/4) | 3 | $0.49 | $1.47 | Vishay Semiconductor Opto Division | TSAL6100 | [DigiKey](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/TSAL6100/1681338) | [Datasheet](https://www.vishay.com/docs/81009/tsal6100.pdf) | DigiKey | D1 |
| Red TEST LED | 4 | $0.00 | $0.00 | n/a | n/a | n/a | n/a | PRLTA 109 | D4 |
| Fuse 5x20, 500mA | 4 | $0.00 | $0.00 | n/a | n/a | n/a | n/a | PRLTA 109 | F2 |
| DC Barrel Jack connector | 1 | $0.00 | $0.00 | n/a | n/a | n/a | n/a | PRLTA 109 | J1 |
| PCB Terminal Block, Pitch 3.5, S | 14 | $0.25 | $3.46 | Adam Tech | EBBA-02-C-SS-BU | [DigiKey](https://www.digikey.com/en/products/detail/adam-tech/EBBA-02-C-SS-BU/9831915) | [Datasheet](https://app.adam-tech.com/products/download/data_sheet/204164/ebba-xx-c-ss-bu-data-sheet.pdf) | DigiKey | J2-8, Q2 |
| 40 Pin (40 X 1) Header Connector | 2 | $0.00 | $0.00 | Lystaii | B06ZZN8L9S | [Amazon](https://www.amazon.com/Header-Lystaii-Pin-Connector-Electronic/dp/B06ZZN8L9S) | n/a | PRLTA 109 | JP1-7, U3-5 |
| Variable resistor pack | 1 | $0.00 | $0.00 | n/a | n/a | n/a | n/a | PRLTA 109 | R2-13 |
| Potentiometer | 2 | $0.00 | $0.00 | n/a | n/a | n/a | n/a | PRLTA 109 | RV1 |
| Test Switch | 2 | $0.00 | $0.00 | n/a | n/a | n/a | n/a | PRLTA 109 | SW1 |
| IC REG LINEAR 5V 1.5A TO220-3L | 1 | $0.00 | $0.00 | TAEJIN | LM7805T | [DigiKey](https://www.digikey.com/en/products/detail/taejin/LM7805T/22237260) | [Datasheet](https://www.htckorea.co.kr/Datasheet/Voltage%20Regulator/LM78xx.pdf) | PRLTA 109 | U1 |
| PIC18F57Q43 Curiosity Nano | 1 | $0.00 | $0.00 | Microchip | DM164150 | [Microchip](https://www.microchip.com/en-us/development-tool/dm164150) | [Datasheet](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/UserGuides/PIC18F57Q43-Curiosity-Nano-HW-UserGuide-DS40002186B.pdf) | PRLTA 109 | U2 |
| ELEGOO 120pcs Multicolored Dupont Wire 40pin Male to Female, 40pin Male to Male, 40pin Female to Female Breadboard Jumper Ribbon Cables Kit Compatible with Arduino Projects | 1 | $6.98 | $6.98 | ELEGOO | B01EV70C78 | [Amazon](https://www.amazon.com/Elegoo-EL-CP-004-Multicolored-Breadboard-arduino/dp/B01EV70C78) | n/a | Amazon | n/a |
| Standard (General Purpose) Amplifier 4 Circuit Rail-to-Rail 14-PDIP | 4 | $0.59 | $2.36 | Microchip Technology | MCP6004-I/P | [DigiKey](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060?s=N4IgTCBcDaILIGEAKA2ADGgLAWgJIHokQBdAXyA) | [Datasheet](https://ww1.microchip.com/downloads/en/DeviceDoc/MCP6001-1R-1U-2-4-1-MHz-Low-Power-Op-Amp-DS20001733L.pdf) | DigiKey | U6 |
| Red, Green, Blue (RGB) 624nm Red, 525nm Green, 470nm Blue LED Indication - Discrete 2V Red, 3.2V Green, 3.2V Blue Radial | 4 | $1.06 | $4.24 | QT Brightek (QTB) | QBL8RGB60D0-2897 | [DigiKey](https://www.digikey.com/en/products/detail/qt-brightek-qtb/QBL8RGB60D0-2897/10441184) | [Datasheet](https://www.qt-brightek.com/datasheet/QBL8RGB60D0-2897.pdf) | DigiKey | J2,J3 |
| Phototransistors 850nm Top View Radial, 5mm Dia (T 1 3/4) | 4 | $0.95 | $3.80 | Vishay Semiconductor Opto Division | BPW96B | [DigiKey](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/BPW96B/4071185?s=N4IgTCBcDaIEIAUDqBOAbHEBdAvkA) | [Datasheet](https://www.vishay.com/docs/81532/bpw96.pdf) | DigiKey | Q2 |
| 100pcs California JOS 2.54mm Black Jumper Caps Standard Circuit Board Jumper Cap Shunts Short Circuit Connection Pin Blocks | 1 | $4.97 | $4.97 | California JOS | B0BRK36G33 | [Amazon](https://www.amazon.com/California-JOS-Standard-Circuit-Connection/dp/B0BRK36G33) | n/a | Amazon | n/a |
| **TOTAL** |  |  | **$28.18** |  |  |  |  |  |  |


## Bill of Materials Example (as Image)
![](BOM-Screenshot.png){style width: "2000"}
**Figure 2:** Example Bill of Materials as a screenshot.

As you can see, the text can be difficult to read without opening the image.
