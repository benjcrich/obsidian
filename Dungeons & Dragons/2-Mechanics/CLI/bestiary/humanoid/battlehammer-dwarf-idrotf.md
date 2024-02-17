---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Battlehammer Dwarf"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 107
---
# [Battlehammer Dwarf](2-Mechanics/CLI/bestiary/humanoid/battlehammer-dwarf-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 107*  

```statblock
"name": "Battlehammer Dwarf (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Good"
"ac": !!int "13"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "11"
- !!int "14"
- !!int "12"
- !!int "11"
- !!int "13"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Nature": !!int "4"
  "Stealth": !!int "6"
  "Perception": !!int "5"
  "Survival": !!int "5"
"senses": "passive Perception 15"
"languages": "any one language (usually Common)"
"cr": "1/2"
"traits":
- "desc": "The dwarf has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or sight."
  "name": "Keen Hearing and Sight"
"actions":
- "desc": "The dwarf makes two melee attacks or two ranged attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +2 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d6 + 0) slashing damage."
  "name": "Handaxe"
- "desc": "Ranged Weapon Attack: +4 to hit, ranged 80/320 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Light Crossbow"
"source":
- "IDRotF"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/battlehammer-dwarf.png"
```
^statblock

```encounter-table
name: Battlehammer Dwarf
creatures:
 - 1: Battlehammer Dwarf
```