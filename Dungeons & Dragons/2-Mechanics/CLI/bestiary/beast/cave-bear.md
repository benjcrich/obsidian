---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/2
- monster/environment/forest
- monster/environment/underdark
- monster/size/large
- monster/type/beast
aliases: ["Cave Bear"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 334, Tales from the Yawning Portal, Waterdeep: Dungeon of the Mad Mage
---
# [Cave Bear](2-Mechanics/CLI/bestiary/beast/cave-bear.md)
*Source: Monster Manual p. 334, Tales from the Yawning Portal, Waterdeep: Dungeon of the Mad Mage*  

```statblock
"name": "Cave Bear"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"stats":
- !!int "20"
- !!int "10"
- !!int "16"
- !!int "2"
- !!int "13"
- !!int "7"
"speed": "40 ft., swim 30 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "2"
"traits":
- "desc": "The bear has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
"actions":
- "desc": "The bear makes two attacks: one with its bite and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 9 (1d8\
    \ + 5) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 12 (2d6\
    \ + 5) slashing damage."
  "name": "Claws"
"source":
- "MM"
- "TftYP"
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/beast/token/cave-bear.png"
```
^statblock

```encounter-table
name: Cave Bear
creatures:
 - 1: Cave Bear
```

## Environment

forest, underdark