---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/0
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Sing-Along"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 148
---
# [Sing-Along](2-Mechanics/CLI/bestiary/npc/sing-along-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 148*  

```statblock
"name": "Sing-Along (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Good"
"ac": !!int "10"
"hp": !!int "4"
"hit_dice": "1d8"
"stats":
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Performance": !!int "4"
"senses": "passive Perception 10"
"languages": "Common, Halfling"
"cr": "0"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ bludgeoning damage."
  "name": "Club"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/npc/token/sing-along.png"
```
^statblock

```encounter-table
name: Sing-Along
creatures:
 - 1: Sing-Along
```