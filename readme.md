# VC Input Source Protection

Dual transistor based input protection from Eurorack CV to a digital pin on e.g. Arduino.

![PCB](images/pcb-v1.0.png)

## BOM

|ID   |Name        |Designator   |Footprint                       |Quantity|Manufacturer Part|Manufacturer                  |Supplier|Supplier Part  |
|-----|------------|-------------|--------------------------------|--------|-----------------|------------------------------|--------|---------------|
|1    |10k         |R1,R6        |AXIAL-0.3                       |2       |                 |                              |        |               |
|2    |100k        |R2,R3,R4,R5  |AXIAL-0.3                       |4       |                 |                              |        |               |
|3    |1N4001      |D1,D2        |DO-41_BD2.4-L4.7-P8.70-D0.9-RD  |2       |1N4001           |LRC                           |LCSC    |C82804         |
|4    |XH-2A       |P1,P2,P3     |XH-2A                           |3       |XH-2A            |BOOMELE                       |LCSC    |C20079         |
|5    |PN2222A     |Q1,Q2        |TO-92(TO-92-3)-2.54             |2       |PN2222ATA        |ON Semiconductor / Fairchild  |Mouser  |512-PN2222ATA  |
|6    |PJ301M      |U2,U1        |PJ301M                          |2       |PJ301M           |thonk                         |        |PJ301M         |