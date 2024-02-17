---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/1
- monster/environment/arctic
- monster/environment/forest
- monster/environment/hill
- monster/size/large
- monster/type/beast
aliases: ["Brown Bear"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 319, Princes of the Apocalypse, Storm King's Thunder, Tales from the Yawning Portal, Ghosts of Saltmarsh, Mythic Odysseys of Theros, Icewind Dale: Rime of the Frostmaiden, The Wild Beyond the Witchlight. Available in the SRD and the Basic Rules.
---
# [Brown Bear](2-Mechanics/CLI/bestiary/beast/brown-bear.md)
*Source: Monster Manual p. 319, Princes of the Apocalypse, Storm King's Thunder, Tales from the Yawning Portal, Ghosts of Saltmarsh, Mythic Odysseys of Theros, Icewind Dale: Rime of the Frostmaiden, The Wild Beyond the Witchlight. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Brown Bear"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "34"
"hit_dice": "4d10 + 12"
"stats":
- !!int "19"
- !!int "10"
- !!int "16"
- !!int "2"
- !!int "13"
- !!int "7"
"speed": "40 ft., climb 30 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "1"
"traits":
- "desc": "The bear has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
"actions":
- "desc": "The bear makes two attacks: one with its bite and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11 (2d6\
    \ + 4) slashing damage."
  "name": "Claws"
"source":
- "MM"
- "PotA"
- "SKT"
- "TftYP"
- "GoS"
- "IMR"
- "MOT"
- "IDRotF"
- "WBtW"
- "BMT"
"image": "/2-Mechanics/CLI/bestiary/beast/token/brown-bear.png"
```
^statblock

```encounter-table
name: Brown Bear
creatures:
 - 1: Brown Bear
```

## Environment

forest, hill, arctic