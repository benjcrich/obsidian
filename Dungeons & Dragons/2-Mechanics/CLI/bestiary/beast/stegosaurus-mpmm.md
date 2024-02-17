---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/4
- monster/environment/forest
- monster/environment/grassland
- monster/size/huge
- monster/type/beast/dinosaur
aliases: ["Stegosaurus"]
NoteIcon: monster
BestiaryType: beast (dinosaur)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 96, Volo's Guide to Monsters p. 140
---
# [Stegosaurus](2-Mechanics/CLI/bestiary/beast/stegosaurus-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 96, Volo's Guide to Monsters p. 140*  

This heavily built dinosaur has rows of plates on its back and a flexible, spiked tail held high to strike predators. It tends to travel in herds of mixed ages.

```statblock
"name": "Stegosaurus (MPMM)"
"size": "Huge"
"type": "beast"
"subtype": "dinosaur"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "76"
"hit_dice": "8d12 + 24"
"stats":
- !!int "20"
- !!int "9"
- !!int "17"
- !!int "2"
- !!int "11"
- !!int "5"
"speed": "40 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "4"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 26 (6d6\
    \ + 5) piercing damage."
  "name": "Tail"
"source":
- "MPMM"
- "VGM"
- "BMT"
"image": "/2-Mechanics/CLI/bestiary/beast/token/stegosaurus.png"
```
^statblock

```encounter-table
name: Stegosaurus
creatures:
 - 1: Stegosaurus
```

## Environment

forest, grassland