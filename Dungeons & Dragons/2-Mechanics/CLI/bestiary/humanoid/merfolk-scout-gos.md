---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/merfolk
aliases: ["Merfolk Scout"]
NoteIcon: monster
BestiaryType: humanoid (merfolk)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 216
---
# [Merfolk Scout](2-Mechanics/CLI/bestiary/humanoid/merfolk-scout-gos.md)
*Source: Ghosts of Saltmarsh p. 216*  

```statblock
"name": "Merfolk Scout (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "merfolk"
"alignment": "Chaotic Evil"
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
- "desc": "The scout has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or sight."
  "name": "Keen Hearing and Sight"
"actions":
- "desc": "The scout makes two melee attacks or two ranged attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
"source":
- "GoS"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/merfolk-scout.png"
```
^statblock

```encounter-table
name: Merfolk Scout
creatures:
 - 1: Merfolk Scout
```