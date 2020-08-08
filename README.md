---
title: Arena PCB
parent: Hardware
grand_parent: Generation 4
---

# Arena PCB 

An arena consists of a *Bottom PCB*, a *Top PCB*, and an *Interconnect PCB*.

The *Bottom PCB* is the basis on which the panels are mounted and where the power and input signal are connected. The *Top PCB* terminates the signal lines for each of the panel columns. The *Interconnect PCB* is an adapter from the NI connector to a ribbon connector required on the *Bottom PCB*. An arena can support up to 12 columns with up to 4 panels in each column. There are different forms of the panel, a full cylinder and a 12-18 cylinder.

## Arena 12-18

The Arena 12-18 allows to build panels around the fly in a 2/3 cylinder with a diameter of 250mm. The name originates from a the full cylinder virtually consisting of 18 columns of which 12 are actually part of the PCB. The current design interation developed in 2019 uses 7 layers.

## Interconnect PCB

The interconnect is a 2 layer PCB.

```
├── Production              - Gerber and drill files
│   ├── Arena_12-18         - Arena board (2019)
│   └── Interconnect        - Interconnect board 
├── Schematic
│   └── Arena_bottom.pdf    - generated 2017-06-09
└── README.md
```
