---
title: Arena PCB
parent: Hardware
grand_parent: Generation 4
---

# Arena PCB 

An arena consists of a *Bottom PCB*, a *Top PCB*, and an *Interconnect PCB*.

The *Bottom PCB* is the basis on which the panels are mounted and where the power and input signal are connected. The *Top PCB* terminates the signal lines for each of the panel columns. The *Interconnect PCB* is an adapter from the NI connector to a ribbon connector required on the *Bottom PCB*. An arena can support up to 12 columns with up to 4 panels in each column.

## Arena 12-18

The Arena 12-18 allows to build panels around the fly in a 2/3 cylinder with a diameter of 250mm. The name originates from a the full cylinder virtually consisting of 18 columns of which 12 are actually part of the PCB. Version 1 and 2 are based on the same schematic, differences are in routing. Also, v2.0 uses hidden vias, is more difficult and expensive to manufacture, and has not been used as often as v1 boards. We recommend using v1.1 at the moment.

## Interconnect PCB

Recent tests have shown, that these ribbon cables introduce noise and should be kept as short as possible.


# Files

```
├── arena_12-18             - 12-18 Arena
│   ├── production_v1p1     - production files v1.1 (current)
│   ├── production_v2p0     - production files v2.0 (not yet ready)
│   ├── Arena_bottom.pdf    - schematic
│   └── Arena_bottom_V1.brd - OrCAD EDA PCB design
├── interconnect            - interconnect board VHDI → ribbon cable
│   ├── production_v1p0     - gerber, drill v1.0 (2 layer, no power connector)
│   ├── production_v2p0     - gerber, drill v2.0 (4 layer, power connector)
│   ├── Interconnect_V1.pdf - schematic (no power, no extra panel header)
│   ├── Interconnect_V2.brd - OrCAD EDA PCB design (4 layer, power connector)
│   └── Interconnect_v2.pdf - schematic (power connector)
├── index.md                - documentation for https://reiserlab.github.io/Modular-LED-Display/
└── README.mdown            - project readme for https://github.com/floesche/Arena-G4-Hardware
```

Files were collected from several email conversations. These exact files have not been used in production, yet.

# Changelog

- 2020-08-20: Add V1 schematic
- 2020-08-19: added OrCAD design files
- 2020-08-17: reorder files
