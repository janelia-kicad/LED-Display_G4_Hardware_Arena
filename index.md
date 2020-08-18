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
├── arena_12-18             - 12-18 Arena (schematic)
│   ├── production_v1p1     - production files v1.1 (current)
│   ├── production_v2p0     - production files v2.0 (not yet ready)
│   └── Arena_bottom.pdf
├── interconnect            - interconnect board VHDI → ribbon cable
│   └── production_v1p0     - gerber, drill
└── README.mdown            - this file
```

Files were collected from several email conversations. These exact files have not been used in production, yet.