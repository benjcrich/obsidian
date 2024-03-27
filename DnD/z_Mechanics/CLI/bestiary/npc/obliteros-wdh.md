---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/5
- monster/size/huge
- monster/type/beast
aliases: ["Obliteros"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 66
---
# [Obliteros](2-Mechanics/CLI/bestiary/npc/obliteros-wdh.md)
*Source: Waterdeep: Dragon Heist p. 66*  

An awakened Giant Shark who inhabits the harbor around Mistshore.

```statblock
"name": "Obliteros (WDH)"
"size": "Huge"
"type": "beast"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "126"
"hit_dice": "11d12 + 55"
"stats":
- !!int "23"
- !!int "11"
- !!int "21"
- !!int "10"
- !!int "10"
- !!int "5"
"speed": "0 ft., swim 50 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "blindsight 60 ft., passive Perception 13"
"languages": "Aquan"
"cr": "5"
"traits":
- "desc": "Obliteros has advantage on melee attack rolls against any creature that\
    \ doesn't have all its hit points."
  "name": "Blood Frenzy"
- "desc": "Obliteros can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 22 (3d10\
    \ + 6) piercing damage."
  "name": "Bite"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/npc/token/obliteros.png"
```
^statblock

```encounter-table
name: Obliteros
creatures:
 - 1: Obliteros
```