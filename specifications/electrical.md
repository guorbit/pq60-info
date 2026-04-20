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

<center><b>Figure 4.1</b>: Pin-out for the connector</center>

<table><thead>
  <tr>
    <th colspan="4">Table 4.1: Detailed information on the pins</th>
  </tr></thead>
<tbody>
  <tr style="font-weight: bold;">
    <td>Pin Number</td>
    <td>Name</td>
    <td>Function</td>
    <td>Current, A</td>
  </tr>
  <tr>
    <td>1 + 2</td>
    <td>+3.3_Sw1</td>
    <td>Switch 1 Output</td>
    <td>0.4 (combined)</td>
  </tr>
  <tr>
    <td>3 + 4</td>
    <td>RTN_SW1_3V3</td>
    <td>Switch 1 Return</td>
    <td>0.4 (combined)</td>
  </tr>
  <tr>
    <td>5 + 6</td>
    <td>+3.3_Sw2</td>
    <td>Switch 2 Output</td>
    <td>0.4 (combined)</td>
  </tr>
  <tr>
    <td>7 + 8</td>
    <td>RTN_SW2_3V3</td>
    <td>Switch 2 Return</td>
    <td>0.4 (combined)</td>
  </tr>
  <tr>
    <td>9 + 10</td>
    <td>+3.3_Sw3</td>
    <td>Switch 3 Output</td>
    <td>0.4 (combined)</td>
  </tr>
  <tr>
    <td>11 + 12</td>
    <td>RTN_SW3_3V3</td>
    <td>Switch 3 Return</td>
    <td>0.4 (combined)</td>
  </tr>
  <tr>
    <td>13 + 14</td>
    <td>BatV_Sw1</td>
    <td>BatV Switch 1 Output</td>
    <td>0.4 (combined)</td>
  </tr>
  <tr>
    <td>15 + 16</td>
    <td>RTN_SW1_BatV</td>
    <td>BatV Switch 1 Return</td>
    <td>0.4 (combined)</td>
  </tr>
  <tr>
    <td>17 + 18</td>
    <td>BatV_Sw2</td>
    <td>BatV Switch 2 Output</td>
    <td>0.4 (combined)</td>
  </tr>
  <tr>
    <td>19 + 20</td>
    <td>RTN_SW2_BatV</td>
    <td>BatV Switch 2 Return</td>
    <td>0.4 (combined)</td>
  </tr>
  <tr>
    <td>21 + 22</td>
    <td>BatV_Sw3</td>
    <td>BatV Switch 3 Output</td>
    <td>0.4 (combined)</td>
  </tr>
  <tr>
    <td>23 + 24</td>
    <td>RTN_SW3_BatV</td>
    <td>BatV Switch 3 Return</td>
    <td>0.4 (combined)</td>
  </tr>
  <tr>
    <td>25</td>
    <td>GPIO0</td>
    <td>General I/O</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>26</td>
    <td>GPIO1</td>
    <td>General I/O</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>27</td>
    <td><span style="text-decoration: overline;">RST</span></td>
    <td>Master Reset Line</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>28</td>
    <td>GND</td>
    <td>System Ground</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>29</td>
    <td>SCL</td>
    <td>I²C Clock Line</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>30</td>
    <td>SDA</td>
    <td>I²C Data Line</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>31</td>
    <td>MOSI</td>
    <td>SPI MOSI</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>32</td>
    <td>MISO</td>
    <td>SPI MISO</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>33</td>
    <td>SCK</td>
    <td>SPI Clock</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>34</td>
    <td><span style="text-decoration: overline;">SS</span> / GPIO2</td>
    <td>Slave Select / General I/O</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>35</td>
    <td>GPIO3</td>
    <td>General I/O</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>36</td>
    <td>GPIO4</td>
    <td>General I/O</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>37</td>
    <td>GPIO5</td>
    <td>General I/O</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>38</td>
    <td>GPIO6</td>
    <td>General I/O</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>39</td>
    <td>GPIO7</td>
    <td>General I/O</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>40</td>
    <td>GPIO8</td>
    <td>General I/O</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>41</td>
    <td>GPIO9</td>
    <td>General I/O</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>42</td>
    <td>GPIO10</td>
    <td>General I/O</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>43</td>
    <td>GPIO11</td>
    <td>General I/O</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>44</td>
    <td>GPIO12</td>
    <td>General I/O</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>45 - 48</td>
    <td>RTN_BatV</td>
    <td>Battery Bus Return</td>
    <td>0.8 (combined)</td>
  </tr>
  <tr>
    <td>49 - 52</td>
    <td>BatV bus</td>
    <td>Battery Bus</td>
    <td>0.8 (combined)</td>
  </tr>
  <tr>
    <td>53 - 56</td>
    <td>RTN_3V3</td>
    <td>3V3 Bus Return</td>
    <td>0.8 (combined)</td>
  </tr>
  <tr>
    <td>57 - 60</td>
    <td>3V3 bus</td>
    <td>3V3 Bus</td>
    <td>0.8 (combined)</td>
  </tr>
</tbody></table>

### +3.3V_Sw1-3 / RTN_SW1-3_3V3

These lines are for 3.3V switched power lines. These power lines are designed to be connected to low current systems that are required, or desired, to be switched on and off by the user. It is envisioned that these lines will originate from either a power system or a power distribution board.

### BatV_Sw1-3 / RTN_SW1-3_BatV

These lines are for battery voltage switched power lines. These power lines are designed to be connected to low current systems that are required, or desired, to be switched on and off by the user. It is envisioned that these lines will originate from either a power system or a power distribution board.

### GPIO 0,1,3-12

These lines are provided to the user for general use. Some examples would be: discrete line control, additional communication lines, analogue lines or any other signal relevant to the system under design.

### <span style="text-decoration: overline;">RST</span> / GND

A dedicated line present on every board on the stack, the RST line, with an associated GND signal, can be used as a master reset line for all systems connected to the stack.

### SCL / SDA

An I2C data bus is provided on these lines.

### MOSI, MISO, SCK

These lines provide a SPI bus.

### <span style="text-decoration: overline;">SS</span> / GPIO2

This pin provides either a dedicated SS line for the SPI bus or an additional GPIO line.

### BatV Bus / RTN_BatV

A battery bus and return line. This is to be a protected bus, designed to power systems within the PQ. This line will be provided by a power system or power distribution board.

{: .note }
> This line should not be used as an unprotected battery bus for the main power source of the PQ.

### 3V3 Bus / RTN_3V3

A 3V3 bus and return line. This bus should be a protected bus, designed to power systems within the PQ. This line will be provided by a power system or power distribution board.

## Mounting Holes

The PQ60 standard calls for four mounting holes for each board. Each of these holes should be plated and be connected to *chassis ground* via the mechanical fixings used between each board. This is not ground as described in the Table 4.1 but the chassis ground of the satellite. The user should only connect to the mounting points if there is a requirement for the chassis ground to be used on the board.

The reason for this requirement is to ensure that all boards used in the stack have a common signal through these points. The approach used should protect the user from ground loops and interfacing issues between different boards.
