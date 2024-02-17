---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/0
- monster/size/tiny
- monster/type/beast
aliases: ["Sylgar"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 220
---
# [Sylgar](2-Mechanics/CLI/bestiary/npc/sylgar-wdh.md)
*Source: Waterdeep: Dragon Heist p. 220*  

Xanathar's pet fish.

```statblock
"name": "Sylgar (WDH)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "2"
- !!int "16"
- !!int "9"
- !!int "1"
- !!int "7"
- !!int "2"
"speed": "0 ft., swim 40 ft."
"senses": "darkvision 60 ft., passive Perception 8"
"languages": ""
"cr": "0"
"traits":
- "desc": "Sylgar can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 1 piercing\
    \ damage."
  "name": "Bite"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/npc/token/sylgar.png"
```
^statblock

```encounter-table
name: Sylgar
creatures:
 - 1: Sylgar
```