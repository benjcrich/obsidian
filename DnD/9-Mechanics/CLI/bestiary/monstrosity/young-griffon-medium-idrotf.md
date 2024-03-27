---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/1
- monster/size/medium
- monster/type/monstrosity
aliases: ["Young Griffon (Medium)"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 163
---
# [Young Griffon (Medium)](2-Mechanics/CLI/bestiary/monstrosity/young-griffon-medium-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 163*  

A griffon is a ferocious avian carnivore with the muscular body of a lion and the head, forelegs, and wings of an eagle.

```statblock
"name": "Young Griffon (Medium) (IDRotF)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "32"
"hit_dice": "5d6 + 15"
"stats":
- !!int "12"
- !!int "15"
- !!int "16"
- !!int "2"
- !!int "13"
- !!int "8"
"speed": "30 ft., fly 80 ft."
"skillsaves":
  "Perception": !!int "5"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": ""
"cr": "1"
"traits":
- "desc": "The griffon has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on sight."
  "name": "Keen Sight"
"actions":
- "desc": "The griffon makes two attacks: one with its beak and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) piercing damage."
  "name": "Beak"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 6 (2d4\
    \ + 1) slashing damage."
  "name": "Claws"
"source":
- "IDRotF"
"image": "/2-Mechanics/CLI/bestiary/monstrosity/token/young-griffon-medium.png"
```
^statblock

```encounter-table
name: Young Griffon (Medium)
creatures:
 - 1: Young Griffon (Medium)
```