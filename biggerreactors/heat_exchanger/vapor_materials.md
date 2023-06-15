

**Vapor Materials** are Liquids that can be used in reactors using Coolant ports, mainly in conjunction with Heat exchangers.

*The below information is accurate for Bigger Reactors 0.5.x (1.16) and 0.6.x (1.17-1.19) or earlier versions, the simulation changes in 0.7.x (1.20+)* *

The liquids have five main properties that affect the heat exchange process
 
- **liquid thermal conductivity** , in watts per metre-kelvin "W/mK"*
- **gas thermal conductivity** , in watts per metre-kelvin  "W/mK"*
- **latent heat of vaporization** , in rf/mb  (for the gas??)*
- **boiling point** : The temperature the reactor or heat exchanger needs to be in Kelvin `K` to boil the liquid
- **effect multiplier in a turbine** : Can this Liquid/Gas be used in a Turbine, 0 means it's disabled


## Vapor Liquids
(sorted by Liquid thermal conductivity)

| Liquid Type | ID | Liquid W/mK | Gas Type | ID | Gas W/mK | Latent Heat | Boiling Point K | Turbine Multiplier |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| registry | minecraft:water | 0.6 | tag | forge:steam |0.025 | 4 | 373.15 | 2.5 |
| registry | mekanism:sodium | 1.2 |tag | forge:superheated_sodium | 1.2 | 0.4 | 473.15 | 0 |
| registry | biggerreactors:liquid_obsidian | 1.9 | registry | minecraft:lava | 1.0 | 15 | 1273.15 | 0 |
| registry | allthemodium:molten_allthemodium | 5 | registry | allthemodium:vapor_allthemodium | 5 | 40 | 1773.15 | 0 |
| registry | allthemodium:molten_vibranium | 8 | registry | allthemodium:vapor_vibranium | 8 | 60 | 2523.15 | 0 |   
| registry | allthemodium:molten_unobtainium | 12 | registry |allthemodium:vapor_unobtainium | 12 | 100 | 3523.15 | 0 |  
