---
layout: default
title: PQ60 Compatible
permalink: /spec/compatible
nav_order: 4
parent: Specifications
has_children: false
---

# PQ60 Compatible

Not all satellite missions can be based on the same standard and as designs progress, new ideas emerge. When this occurs, a standard can become a hindrance. To accommodate this, the PQ60 Compatible standard can be used.

The PQ60 Compatible standard is to be used for systems that meet the connector and mounting points constraints, and have compatible pin-outs. The pin-out does not have to match exactly. For example, the connector on the top of the board may match the standard as set down in these pages, but the bottom connector has been altered to allow connection to a dedicated payload or system. A second example would be reallocation of the switched lines. The PQ may not require three 3.3V switches but needs four BatV switches. One of the 3.3V lines could be re-purposed to be a BatV line. This board would no longer follow the standard as set down, but would still be compatible with the standard.

As a baseline, a board would be PQ60 Compatible if:

- the power, communication lines and reset line were still in the same location, but the GPIO lines were re-purposed
- the voltages of the switches are different
- either the bottom or top connector on the board is compatible

It would be the responsibility of the designer of the board to provide the relevant information to the end user.