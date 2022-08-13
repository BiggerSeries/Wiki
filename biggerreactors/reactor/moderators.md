---
title: Reactor Moderators
description: 
published: true
date: 2022-08-13T17:17:51.606Z
tags: 
editor: markdown
dateCreated: 2021-12-05T10:47:17.273Z
---

**Reactor Moderators** (commonly incorrectly referred to as Reactor Coolants) are materials placed inside of a Reactor during construction. When a reactor is in operation, a moderator may change the way the reactor performs depending its properties.

Moderators have four main properties that affect the reactor simulation:

-   **Absorption**: The speed at which radiation is absorbed and converted to case heat.
-   **Efficiency**: How efficiently absorbed radiation is converted into heat.
-   **Moderation**: The effectiveness at which radiation is moderated ("softened").
-   **Conductivity**: How well heat is transferred from the fuel rods to the reactor casing.

In general, higher values are always better (*except* for absorption, which may be better or worse depending on your reactor design). For a more in-depth explanation on how to use the information here, see the [simulation page](https://biggerseries.net/en/biggerreactors/reactor/simulation).

Something to note is that Modpack authors have the ability to add or modify moderators. For an accurate list of supported blocks/fluids, use [Just Enough Items (JEI)](https://www.curseforge.com/minecraft/mc-mods/jei) by checking the uses for the Reactor Terminal (**currently broken on multiplayer**).

## Moderator Properties (0.5.2)

The values listed below are accurate for Bigger Reactors 0.5.2, for Minecraft 1.16.5.  
 

| Type | ID  | Absorption | Efficiency | Moderation | Conductivity |
| --- | --- | --- | --- | --- | --- |
| registry | astralsorcery:liquid\_starlight | 0.85 | 0.8 | 2.0 | 3.0 |
| registry | biggerreactors:ludicrite\_block | 0.6 | 0.87 | 3   | 3   |
| registry | bloodmagic:life\_essence\_block | 0.7 | 0.55 | 1.75 | 2.5 |
| registry | mekanism:ethene | 0.37 | 0.65 | 1.9 | 1.5 |
| registry | mekanism:hydrofluoric\_acid | 0.6 | 0.45 | 1.4 | 2.5 |
| registry | mekanism:hydrogen | 0.2 | 0.3 | 1.2 | 0.1 |
| registry | mekanism:hydrogen\_chloride | 0.31 | 0.65 | 1.7 | 1   |
| registry | mekanism:lithium | 0.7 | 0.6 | 1.04 | 0.7 |
| registry | mekanism:oxygen | 0.01 | 0.35 | 1.04 | 0.1 |
| registry | mekanism:sodium | 0.23 | 0.6 | 1.7 | 1   |
| registry | mekanism:steam | 0.33 | 0.5 | 1.33 | 0.5 |
| registry | mekanismgenerators:deuterium | 0.03 | 0.3 | 1.07 | 0.1 |
| registry | minecraft:air | 0.1 | 0.25 | 1.1 | 0.05 |
| registry | minecraft:cave\_air | 0.1 | 0.25 | 1.1 | 0.05 |
| registry | minecraft:glass | 0.2 | 0.25 | 1.1 | 0.3 |
| registry | minecraft:ice | 0.33 | 0.33 | 1.15 | 0.1 |
| registry | minecraft:snow\_block | 0.15 | 0.33 | 1.05 | 0.05 |
| registry | minecraft:void\_air | 0.1 | 0.25 | 1.1 | 0.05 |
| registry | minecraft:water | 0.33 | 0.5 | 1.33 | 0.1 |
| registry | minecraft:lava | 0.33 | 0.33 | 1.15 | 0.7 |
| tag | forge:storage\_blocks/allthemodium | 0.66 | 0.9 | 3.5 | 3.5 |
| tag | forge:storage\_blocks/aluminum | 0.5 | 0.78 | 1.42 | 0.6 |
| tag | forge:storage\_blocks/bronze | 0.51 | 0.77 | 1.41 | 1   |
| tag | forge:storage\_blocks/copper | 0.5 | 0.75 | 1.4 | 1   |
| tag | forge:storage\_blocks/diamond | 0.55 | 0.85 | 1.5 | 3   |
| tag | forge:storage\_blocks/electrum | 0.53 | 0.82 | 1.47 | 2.2 |
| tag | forge:storage\_blocks/emerald | 0.55 | 0.85 | 1.5 | 2.5 |
| tag | forge:storage\_blocks/enderium | 0.53 | 0.88 | 1.6 | 3   |
| tag | forge:storage\_blocks/gold | 0.52 | 0.8 | 1.45 | 2   |
| tag | forge:storage\_blocks/graphite | 0.1 | 0.5 | 2   | 2   |
| tag | forge:storage\_blocks/invar | 0.5 | 0.79 | 1.43 | 0.6 |
| tag | forge:storage\_blocks/iron | 0.5 | 0.75 | 1.4 | 0.6 |
| tag | forge:storage\_blocks/lead | 0.75 | 0.75 | 1.75 | 1.5 |
| tag | forge:storage\_blocks/lumium | 0.75 | 0.55 | 1.5 | 1.8 |
| tag | forge:storage\_blocks/nickel | 0.5 | 0.82 | 1.46 | 0.6 |
| tag | forge:storage\_blocks/osmium | 0.51 | 0.77 | 1.41 | 1   |
| tag | forge:storage\_blocks/platinum | 0.53 | 0.86 | 1.58 | 2.5 |
| tag | forge:storage\_blocks/signalum | 0.63 | 0.66 | 1.5 | 1.8 |
| tag | forge:storage\_blocks/silver | 0.51 | 0.79 | 1.43 | 1.5 |
| tag | forge:storage\_blocks/steel | 0.5 | 0.78 | 1.42 | 0.6 |
| tag | forge:storage\_blocks/tin | 0.3 | 0.7 | 1.35 | 0.75 |
| tag | forge:storage\_blocks/unobtainium | 0.95 | 0.82 | 2   | 5   |
| tag | forge:storage\_blocks/vibranium | 0.15 | 0.75 | 8   | 4   |
| tag | forge:storage\_blocks/zinc | 0.51 | 0.77 | 1.41 | 1   |
| fluid | biggerreactors:liquid\_obsidian | 0.3 | 0.7 | 1.35 | 0.75 |
| fluid | allthemodium:molten\_allthemodium | 0.66 | 0.9 | 3.5 | 3.5 |
| fluid | allthemodium:molten\_vibranium | 0.15 | 0.75 | 8   | 4   |
| fluid | allthemodium:molten\_unobtainium | 0.95 | 0.82 | 2   | 5   |
| fluid | allthemodium:vapor\_allthemodium | 0.66 | 0.9 | 3.5 | 3.5 |
| fluid | allthemodium:vapor\_vibranium | 0.15 | 0.75 | 8   | 4   |
| fluid | allthemodium:vapor\_unobtainium | 0.95 | 0.82 | 2   | 5   |
| fluidtag | forge:superheated\_sodium | 0.23 | 0.6 | 1.7 | 1   |

## Moderator Properties (0.4.3)

The values listed below are accurate for Bigger Reactors 0.4.3, for Minecraft 1.16.4.  
 

| Type | ID  | Absorption | Efficiency | Moderation | Conductivity |
| --- | --- | --- | --- | --- | --- |
| registry | astralsorcery:liquid\_starlight | 0.85 | 0.8 | 2.0 | 3.0 |
| registry | biggerreactors:ludicrite\_block | 0.6 | 0.87 | 3   | 3   |
| registry | bloodmagic:life\_essence\_block | 0.7 | 0.55 | 1.75 | 2.5 |
| registry | mekanism:ethene | 0.37 | 0.65 | 1.9 | 1.5 |
| registry | mekanism:hydrofluoric\_acid | 0.6 | 0.45 | 1.4 | 2.5 |
| registry | mekanism:hydrogen | 0.2 | 0.3 | 1.2 | 0.1 |
| registry | mekanism:hydrogen\_chloride | 0.31 | 0.65 | 1.7 | 1   |
| registry | mekanism:lithium | 0.7 | 0.6 | 1.04 | 0.7 |
| registry | mekanism:oxygen | 0.01 | 0.35 | 1.04 | 0.1 |
| registry | mekanism:sodium | 0.23 | 0.6 | 1.7 | 1   |
| registry | mekanism:steam | 0.33 | 0.5 | 1.33 | 0.5 |
| registry | mekanismgenerators:deuterium | 0.03 | 0.3 | 1.07 | 0.1 |
| registry | minecraft:air | 0.1 | 0.25 | 1.1 | 0.05 |
| registry | minecraft:cave\_air | 0.1 | 0.25 | 1.1 | 0.05 |
| registry | minecraft:glass | 0.2 | 0.25 | 1.1 | 0.3 |
| registry | minecraft:ice | 0.33 | 0.33 | 1.15 | 0.1 |
| registry | minecraft:snow\_block | 0.15 | 0.33 | 1.05 | 0.05 |
| registry | minecraft:void\_air | 0.1 | 0.25 | 1.1 | 0.05 |
| registry | minecraft:water | 0.33 | 0.5 | 1.33 | 0.1 |
| tag | forge:storage\_blocks/allthemodium | 0.66 | 0.9 | 3.5 | 3.5 |
| tag | forge:storage\_blocks/aluminum | 0.5 | 0.78 | 1.42 | 0.6 |
| tag | forge:storage\_blocks/bronze | 0.51 | 0.77 | 1.41 | 1   |
| tag | forge:storage\_blocks/copper | 0.5 | 0.75 | 1.4 | 1   |
| tag | forge:storage\_blocks/diamond | 0.55 | 0.85 | 1.5 | 3   |
| tag | forge:storage\_blocks/electrum | 0.53 | 0.82 | 1.47 | 2.2 |
| tag | forge:storage\_blocks/emerald | 0.55 | 0.85 | 1.5 | 2.5 |
| tag | forge:storage\_blocks/enderium | 0.53 | 0.88 | 1.6 | 3   |
| tag | forge:storage\_blocks/gold | 0.52 | 0.8 | 1.45 | 2   |
| tag | forge:storage\_blocks/graphite | 0.1 | 0.5 | 2   | 2   |
| tag | forge:storage\_blocks/invar | 0.5 | 0.79 | 1.43 | 0.6 |
| tag | forge:storage\_blocks/iron | 0.5 | 0.75 | 1.4 | 0.6 |
| tag | forge:storage\_blocks/lead | 0.75 | 0.75 | 1.75 | 1.5 |
| tag | forge:storage\_blocks/lumium | 0.75 | 0.55 | 1.5 | 1.8 |
| tag | forge:storage\_blocks/nickel | 0.5 | 0.82 | 1.46 | 0.6 |
| tag | forge:storage\_blocks/osmium | 0.51 | 0.77 | 1.41 | 1   |
| tag | forge:storage\_blocks/platinum | 0.53 | 0.86 | 1.58 | 2.5 |
| tag | forge:storage\_blocks/signalum | 0.63 | 0.66 | 1.5 | 1.8 |
| tag | forge:storage\_blocks/silver | 0.51 | 0.79 | 1.43 | 1.5 |
| tag | forge:storage\_blocks/steel | 0.5 | 0.78 | 1.42 | 0.6 |
| tag | forge:storage\_blocks/tin | 0.3 | 0.7 | 1.35 | 0.75 |
| tag | forge:storage\_blocks/unobtainium | 0.95 | 0.82 | 2   | 5   |
| tag | forge:storage\_blocks/vibranium | 0.15 | 0.75 | 8   | 4   |
| tag | forge:storage\_blocks/zinc | 0.51 | 0.77 | 1.41 | 1   |