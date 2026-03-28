---
layout: default
title: Overview
permalink: /spec/overview
nav_order: 1
has_children: true
---

# Standard Overview

The standard provides for a stack of systems to be connected together to form a PQ. Each system is required to fit within the constraints of a typical PQ structure.

The electrical connections between each board are provided via two stack connectors, one on the bottom of the board, the second on the top. Each signal carried by the connector is required to be passed through the board from the bottom connector to the top connector. This scheme means that every signal is present on every board. If the board requires a particular signal, then this signal is to tapped from the connector.

The signals on the connector were selected to provide the basic requirements for any board: power and communications. The standard allows for:

- 2 protected power buses (3.3V and BatteryV) @ 0.8A each (derated)
- 6 switched power lines (3 x 3.3V and 3 x BatteryV) @ 0.4A each (derated)
- 2 dedicated data buses (I2C and SPI)
- 12 GPIO lines
- 1 SS or GPIO line
- Reset Line