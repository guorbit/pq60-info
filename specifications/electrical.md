---
layout: default
title: Pin-out and Electrical Details
permalink: /spec/electrical
nav_order: 3
parent: Specifications
has_children: false
---

# Pin-out and Electrical Details

The following section describes the pin-out, pin descriptions and electrical details related to the PQ60 standard.

## Pin-out with Pin Descriptions

This section provides the pin-out and electrical details of the connector used. Each signal on the connector is discussed. The relevant information can be found in Figure 4.1 and Table 4.1.

|              |     |     |           |
|-------------:|-----|-----|:----------|
| +3.3_Sw1     | P1  | P60 | 3V3 bus   |
| +3.3_Sw1     | P2  | P59 | 3V3 bus   |
| RTN_SW1_3V3  | P3  | P58 | 3V3 bus   |
| RTN_SW1_3V3  | P4  | P57 | 3V3 bus   |
| +3.3_Sw2     | P5  | P56 | RTN_3V3   |
| +3.3_Sw2     | P6  | P55 | RTN_3V3   |
| RTN_SW2_3V3  | P7  | P54 | RTN_3V3   |
| RTN_SW2_3V3  | P8  | P53 | RTN_3V3   |
| +3.3_Sw3     | P9  | P52 | BatV bus  |
| +3.3_Sw3     | P10 | P51 | BatV bus  |
| RTN_SW3_3V3  | P11 | P50 | BatV bus  |
| RTN_SW3_3V3  | P12 | P49 | BatV bus  |
| BatV_SW1     | P13 | P48 | RTN_BatV  |
| BatV_SW1     | P14 | P47 | RTN_BatV  |
| RTN_SW1_BatV | P15 | P46 | RTN_BatV  |
| RTN_SW1_BatV | P16 | P45 | RTN_BatV  |
| BatV_SW2     | P17 | P44 | GPIO12    |
| BatV_SW2     | P18 | P43 | GPIO11    |
| RTN_SW2_BatV | P19 | P42 | GPIO10    |
| RTN_SW2_BatV | P20 | P41 | GPIO9     |
| BatV_SW3     | P21 | P40 | GPIO8     |
| BatV_SW3     | P22 | P39 | GPIO7     |
| RTN_SW3_BatV | P23 | P38 | GPIO6     |
| RTN_SW3_BatV | P24 | P37 | GPIO5     |
| GPIO0        | P25 | P36 | GPIO4     |
| GPIO1        | P26 | P35 | GPIO3     |
| <span style="text-decoration: overline;">RST</span>        | P27 | P34 | <span style="text-decoration: overline;">SS</span>/GPIO2 |
| GND          | P28 | P33 | SCK       |
| SCL          | P29 | P32 | MISO      |
| SDA          | P30 | P31 | MOSI      |
|==============|=====|=====|===========|
| **Figure 4.1**: Pin-out for the connector|
