---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/5
- monster/environment/forest
- monster/environment/grassland
- monster/size/gargantuan
- monster/type/beast/dinosaur
aliases: ["Brontosaurus"]
NoteIcon: monster
BestiaryType: beast (dinosaur)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 95, Volo's Guide to Monsters p. 139
---
# [Brontosaurus](2-Mechanics/CLI/bestiary/beast/brontosaurus-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 95, Volo's Guide to Monsters p. 139*  

This massive four-legged dinosaur is large enough that most predators leave it alone. Its deadly tail can drive away or kill smaller threats.

```statblock
"name": "Brontosaurus (MPMM)"
"size": "Gargantuan"
"type": "beast"
"subtype": "dinosaur"
"alignment": "Unaligned"
"ac": !!int "15"
"hp": !!int "121"
"hit_dice": "9d20 + 27"
"stats":
- !!int "21"
- !!int "9"
- !!int "17"
- !!int "2"
- !!int "10"
- !!int "7"
"speed": "30 ft."
"saves":
  "Constitution": !!int "6"
"senses": "passive Perception 10"
"languages": ""
"cr": "5"
"actions":
- "desc": "Melee Weapon Attack: +8 to hit, reach 20 ft., one target. Hit: 27 (5d8\
    \ + 5) bludgeoning damage, and the target must succeed on a DC 14 Strength saving\
    \ throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Stomp"
- "desc": "Melee Weapon Attack: +8 to hit, reach 20 ft., one target. Hit: 32 (6d8\
    \ + 5) bludgeoning damage"
  "name": "Tail"
"source":
- "MPMM"
- "VGM"
"image": "/2-Mechanics/CLI/bestiary/beast/token/brontosaurus.png"
```
^statblock

```encounter-table
name: Brontosaurus
creatures:
 - 1: Brontosaurus
```

## Environment

forest, grassland