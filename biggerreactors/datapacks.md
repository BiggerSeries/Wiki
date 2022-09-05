---
title: Datapacks
published: true
editor: markdown
---

Bigger Reactors can be customised either by the configs or via the datapacks, primarily by modpack authors. Below are some examples of both Moderators and Coils and a simple "how to" for adding moderators and coils via Datapacks.
For more information on how the material stats affect the simulations, refer to the [Moderators](https://biggerseries.net/biggerreactors/reactor/moderators) and [Coils](https://biggerseries.net/biggerreactors/turbine/coils) pages

In my Examples i've used [KubeJS](https://www.curseforge.com/minecraft/mc-mods/kubejs) and put the files in the directory `kubejs\data\biggerreactors\`.
The file extensions can be either `.json` or `.json5`


## Reactor Moderators

Example file, in this case `lapis_block.json5`, this one needs to be placed into the folder `\ebcr\moderators\`
You can use any of the following types `registry, tag, fluid, fluidtag` to ID the materials to be used as moderators 

```
{
    type: "tag",
    location: "forge:storage_blocks/lapis",
    absorption: 0.35,
    efficiency: 0.45,
    moderation: 1.1,
    conductivity: 1.2,
}
```


## Turbines

Example file, in this case `lapis.json5`, this one needs to be placed into the folder `\ebest\coils\`
You can use any of the following types `registry, tag` to ID the materials to be used as coils, no fluids

```
{
    type: "tag",
    location: "forge:storage_blocks/lapis",
    efficiency: 0.20,
    extractionRate: 0.1,
    bonus: 1,
}
```
