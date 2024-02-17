---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/1
- monster/size/large
- monster/type/beast
aliases: ["Awakened Brown Bear"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 72
---
# [Awakened Brown Bear](2-Mechanics/CLI/bestiary/beast/awakened-brown-bear-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 72*  

```statblock
"name": "Awakened Brown Bear (WDMM)"
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
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/beast/token/awakened-brown-bear.png"
```
^statblock

```encounter-table
name: Awakened Brown Bear
creatures:
 - 1: Awakened Brown Bear
```