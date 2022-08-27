---
title: turbine
description: 
published: true
date: 2022-08-27T03:10:49.341Z
tags: 
editor: markdown
dateCreated: 2022-08-27T03:10:46.422Z
---

**Turbines** are multi-block power generators that run on steam. The steam can be sourced from an active [reactor](/biggerreactors/reactor.html) that boils water, or from a [heat exchanger](/biggerreactors/heat_exchanger.md). During operation, the steam is condensed into water which can be fed back into the source or it can be voided.

The smallest possible turbine size is 5 × 4 × 5, assuming a vertical shaft. With the default config, turbines may be built as large as 32 × 192 × 32.

## Required Components

![Turbine Casing](/biggerreactors/turbine/turbine_casing.png)
**Turbine Casings** make up the frame and walls of the turbine.

![Turbine Fluid Port](/biggerreactors/turbine/turbine_fluid_port.png)
**Turbine Fluid Ports** are used to insert steam and extract water. They provide a UI to set input or output status.

![Turbine Power Tap](/biggerreactors/turbine/turbine_power_tap.png)
**Power Taps** are used to extract power.

![Turbine Rotor Bearing](/biggerreactors/turbine/turbine_rotor_bearing.png)
**Rotor Bearings** are located at each end of the shaft of the turbine. Exactly 2 are required.

![Turbine Rotor Shaft](/biggerreactors/turbine/turbine_rotor_shaft.png)
**Rotor Shafts** form the shaft of your turbine that spans end to end and connects to the rotor bearings.

![Turbine Rotor Blade](/biggerreactors/turbine/turbine_rotor_blade.png)
**Rotor Blades** make the rotor spin by converting the thermal energy of the steam into rotational kinetic energy of the shaft. They are placed onto shaft components and can be multiple blocks in length. They can also be placed asymmetrically.

## Optional Components

![Turbine Terminal](/biggerreactors/turbine/turbine_terminal.png)
**Turbine Terminals** are the control panels of the turbine. A turbine multi-block will form without a terminal, but you can't do much without it.

![Turbine Glass](/biggerreactors/turbine/turbine_glass.png)
**Turbine Glass** functions identically to casings, but may only be used on walls. It allows you to see inside of the turbine.

![Turbine Computer Port](/biggerreactors/turbine/turbine_computer_port.png)
**Computer Ports** allow for control of various turbine functions via Lua scripting. This requires a computers mod such as [CC: Tweaked](https://www.curseforge.com/minecraft/mc-mods/cc-tweaked) to be installed.