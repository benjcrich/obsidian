---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/1-4
- monster/environment/grassland
- monster/environment/swamp
- monster/size/large
- monster/type/beast/dinosaur
aliases: ["Hadrosaurus"]
NoteIcon: monster
BestiaryType: beast (dinosaur)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 96, Volo's Guide to Monsters p. 140
---
# [Hadrosaurus](2-Mechanics/CLI/bestiary/beast/hadrosaurus-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 96, Volo's Guide to Monsters p. 140*  

A hadrosaurus is a semi-quadrupedal herbivore with bony head crests. If raised from a hatchling, it can be trained to carry a rider.

```statblock
"name": "Hadrosaurus (MPMM)"
"size": "Large"
"type": "beast"
"subtype": "dinosaur"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"stats":
- !!int "15"
- !!int "10"
- !!int "13"
- !!int "2"
- !!int "10"
- !!int "5"
"speed": "40 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": ""
"cr": "1/4"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (1d10\
    \ + 2) bludgeoning damage."
  "name": "Tail"
"source":
- "MPMM"
- "VGM"
"image": "/2-Mechanics/CLI/bestiary/beast/token/hadrosaurus.png"
```
^statblock

```encounter-table
name: Hadrosaurus
creatures:
 - 1: Hadrosaurus
```

## Environment

grassland, swamp