# PCB

Board size: 30.0x20.0 mm (1.18x0.79 inches)

- This is the size of the rectangle that contains the board
- Thickness: 1.6 mm (63 mils)
- Material: FR4
- Finish: None
- Layers: 2
- Copper thickness: 35 µm

Solder mask: TOP / BOTTOM

- Color: Green

Silk screen: TOP / BOTTOM

- Color: White


Stackup:

| Name                 | Type                 | Color            | Thickness [µm]| Material        | Er        | Loss tan     |
|----------------------|----------------------|------------------|---------------|-----------------|-----------|--------------|
| F.SilkS              | Top Silk Screen      |                  |               |                 |           |              |
| F.Paste              | Top Solder Paste     |                  |               |                 |           |              |
| F.Mask               | Top Solder Mask      | Green            |            10 |                 |           |              |
| F.Cu                 | copper               |                  |            35 |                 |           |              |
| dielectric 1         | core                 |                  |          1510 | FR4             |       4.5 |        0.020 |
| B.Cu                 | copper               |                  |            35 |                 |           |              |
| B.Mask               | Bottom Solder Mask   | Green            |            10 |                 |           |              |
| B.Paste              | Bottom Solder Paste  |                  |               |                 |           |              |
| B.SilkS              | Bottom Silk Screen   |                  |               |                 |           |              |

# Important sizes

Clearance: 0.2 mm (8 mils)

Track width: 0.2 mm (8 mils)

- By design rules: 0.2 mm (8 mils)

Drill: 0.5 mm (20 mils)

- Vias: 0.5 mm (20 mils) [Design: 0.4 mm (16 mils)]
- Pads: N/A mm (N/A mils)
- The above values are real drill sizes, they add 0.1 mm (4 mils) to plated holes (PTH)

Via: 0.8/0.4 mm (31/16 mils)

- By design rules: 0.4/0.3 mm (16/12 mils)
- Micro via: yes [0.2/0.1 mm (8/4 mils)]
- Buried/blind via: yes
- Total: 49 (thru: 49 buried/blind: 0 micro: 0)

Outer Annular Ring: 0.15 mm (6 mils)

- By design rules: N/A mm (N/A mils)

Eurocircuits class: 4B
- Using min drill 0.5 mm for an OAR of 0.15 mm


# General stats

Components count: (SMD/THT)

- Top: 2/0 (SMD)
- Bottom: 27/0 (SMD)

Defined tracks:

- 0.2 mm (8 mils)
- 0.3 mm (12 mils)
- 0.4 mm (16 mils)
- 0.5 mm (20 mils)
- 0.6 mm (24 mils)

Used tracks:

- 0.2 mm (8 mils) (155) defined: yes
- 0.25 mm (10 mils) (20) defined: no
- 0.5 mm (20 mils) (73) defined: yes

Defined vias:


Used vias:

- 0.8/0.4 mm (31/16 mils) (Count: 49, Aspect: 2.0 A) defined: no

Holes (excluding vias):


Oval holes:


Drill tools (including vias and computing adjusts and rounding):

- 0.5 mm (20 mils) (49)

Solder paste stats:

Using a paste with 87.75 % alloy, that has an specific gravity for the alloy of 7.4 g/cm³
and 1.0 g/cm³ for the flux. This paste has an specific gravity of  4.15 g/cm³.

The stencil thickness is  0.12 mm.

| Side   | Pads with paste | Area [mm²] | Paste [g] |
|--------|-----------------|------------|-----------|
| Top    |              12 |      18.56 |      0.09 |
| Bottom |              97 |      80.05 |      0.40 |
| Total  |             109 |      98.61 |      0.49 |

Note: this is just an approximation to the theoretical value. Margins of the solder mask and waste aren't computed.



