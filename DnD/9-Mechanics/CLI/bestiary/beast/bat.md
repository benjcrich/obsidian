---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/0
- monster/size/tiny
- monster/type/beast
aliases: ["Bat"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 318, Curse of Strahd, Tomb of Annihilation, Waterdeep: Dungeon of the Mad Mage, Icewind Dale: Rime of the Frostmaiden, The Wild Beyond the Witchlight. Available in the SRD and the Basic Rules.
---
# [Bat](2-Mechanics/CLI/bestiary/beast/bat.md)
*Source: Monster Manual p. 318, Curse of Strahd, Tomb of Annihilation, Waterdeep: Dungeon of the Mad Mage, Icewind Dale: Rime of the Frostmaiden, The Wild Beyond the Witchlight. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Bat"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "2"
- !!int "15"
- !!int "8"
- !!int "2"
- !!int "12"
- !!int "4"
"speed": "5 ft., fly 30 ft."
"senses": "blindsight 60 ft., passive Perception 11"
"languages": ""
"cr": "0"
"traits":
- "desc": "The bat can't use its blindsight while [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened)."
  "name": "Echolocation"
- "desc": "The bat has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing."
  "name": "Keen Hearing"
"actions":
- "desc": "Melee Weapon Attack: +0 to hit, reach 5 ft., one creature. Hit: 1 piercing\
    \ damage."
  "name": "Bite"
"source":
- "MM"
- "CoS"
- "ToA"
- "WDMM"
- "IDRotF"
- "WBtW"
- "PSX"
- "DoDk"
"image": "/2-Mechanics/CLI/bestiary/beast/token/bat.png"
```
^statblock

```encounter-table
name: Bat
creatures:
 - 1: Bat
```