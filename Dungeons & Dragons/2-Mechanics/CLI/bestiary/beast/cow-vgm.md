---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/vgm
- monster/cr/1-4
- monster/environment/grassland
- monster/size/large
- monster/type/beast
aliases: ["Cow"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Volo's Guide to Monsters p. 207
---
# [Cow](2-Mechanics/CLI/bestiary/beast/cow-vgm.md)
*Source: Volo's Guide to Monsters p. 207*  

There are many kinds of cattle, from common oxen to more unusual, magical variants.

```statblock
"name": "Cow (VGM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "15"
"hit_dice": "2d10 + 4"
"stats":
- !!int "18"
- !!int "10"
- !!int "14"
- !!int "2"
- !!int "10"
- !!int "4"
"speed": "30 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "If the cow moves at least 20 feet straight toward a target and then hits\
    \ it with a gore attack on the same turn, the target takes an extra 7 (2d6)\
    \ piercing damage."
  "name": "Charge"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) piercing damage."
  "name": "Gore"
"source":
- "VGM"
- "DIP"
"image": "/2-Mechanics/CLI/bestiary/beast/token/cow.png"
```
^statblock

```encounter-table
name: Cow
creatures:
 - 1: Cow
```

## Environment

grassland