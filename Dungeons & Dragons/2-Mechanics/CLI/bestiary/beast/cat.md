---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/0
- monster/environment/desert
- monster/environment/forest
- monster/environment/grassland
- monster/environment/urban
- monster/size/tiny
- monster/type/beast
aliases: ["Cat"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 320, Curse of Strahd, Hoard of the Dragon Queen, Storm King's Thunder, Tomb of Annihilation, Waterdeep: Dragon Heist, Icewind Dale: Rime of the Frostmaiden, Tasha's Cauldron of Everything, Candlekeep Mysteries, The Wild Beyond the Witchlight, Journeys through the Radiant Citadel. Available in the SRD and the Basic Rules.
---
# [Cat](2-Mechanics/CLI/bestiary/beast/cat.md)
*Source: Monster Manual p. 320, Curse of Strahd, Hoard of the Dragon Queen, Storm King's Thunder, Tomb of Annihilation, Waterdeep: Dragon Heist, Icewind Dale: Rime of the Frostmaiden, Tasha's Cauldron of Everything, Candlekeep Mysteries, The Wild Beyond the Witchlight, Journeys through the Radiant Citadel. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Cat"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "2"
"hit_dice": "1d4"
"stats":
- !!int "3"
- !!int "15"
- !!int "10"
- !!int "3"
- !!int "12"
- !!int "7"
"speed": "40 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "0"
"traits":
- "desc": "The cat has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
"actions":
- "desc": "Melee Weapon Attack: +0 to hit, reach 5 ft., one target. Hit: 1 slashing\
    \ damage."
  "name": "Claws"
"source":
- "MM"
- "CoS"
- "HotDQ"
- "SKT"
- "ToA"
- "WDH"
- "IMR"
- "IDRotF"
- "TCE"
- "CM"
- "WBtW"
- "JttRC"
- "DoDk"
"image": "/2-Mechanics/CLI/bestiary/beast/token/cat.png"
```
^statblock

```encounter-table
name: Cat
creatures:
 - 1: Cat
```

## Environment

grassland, forest, urban, desert