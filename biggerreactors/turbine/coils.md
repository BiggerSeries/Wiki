---
title: Turbine Coils
published: true
editor: markdown
---

**Turbine Coils** are materials placed around a turbine shaft at one end of the turbine during construction.

*The below information is accurate for Bigger Reactors 0.5.x (1.16) and 0.6.x (1.17-1.19) or earlier versions, the simulation changes in 0.7.x (1.20+)*

The Coils have three main properties that affect turbine simulation. 

- **Extraction Rate**: Affects the RF extracted per tick per RPM.
- **Efficiency**: Affects how much of the extracted RF is then turned into Output RF.
- **Bonus**: Applies a final exponential RF bonus onto the outputted RF value .

In general, higher values are better.

Modpack authors can also add more coil materials via [Datapacks](https://biggerseries.net/biggerreactors/datapacks)

## Turbine Coil Materials

The values listed below are accurate for Bigger Reactors 0.5.x (1.16) and 0.6.x (1.17-1.19).
Sorted "Worst" to "Best".


| Type | ID | Efficiency | Extraction Rate | Bonus |
| --- | --- | --- | --- | --- |
| tag | forge:storage_blocks/iron | 0.33 | 0.1 | 1 |
| tag | forge:storage_blocks/copper | 0.396 | 0.12 | 1 |
| tag | forge:storage_blocks/osmium | 0.462 | 0.12 | 1 |
| tag | forge:storage_blocks/steel | 0.495 | 0.13 | 1 |
| tag | forge:storage_blocks/invar | 0.495 | 0.14 | 1 |
| tag | forge:storage_blocks/silver | 0.561 | 0.15 | 1 |
| tag | forge:storage_blocks/gold | 0.66 | 0.175 | 1 |
| tag | forge:storage_blocks/electrum | 0.825 | 0.2 | 1 |
| tag | forge:storage_blocks/enderium | 0.99 | 0.3 | 1.02 |
| tag | forge:storage_blocks/platinum | 0.99 | 0.25 | 1 |
| registry | biggerreactors:ludicrite_block | 1.15 | 0.35 | 1.02 |
| tag | forge:storage_blocks/allthemodium | 1.2 | 0.4 | 1.02 |
| tag | forge:storage_blocks/vibranium | 1.35 | 0.5 | 1.04 |
| tag | forge:storage_blocks/unobtainium | 1.5 | 0.7 | 1.06 |
