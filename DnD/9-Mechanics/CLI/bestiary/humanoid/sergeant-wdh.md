---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Sergeant"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 197
---
# [Sergeant](2-Mechanics/CLI/bestiary/humanoid/sergeant-wdh.md)
*Source: Waterdeep: Dragon Heist p. 197*  

```statblock
"name": "Sergeant (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "16"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "13"
- !!int "12"
- !!int "12"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "1/8"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d6 + 1) piercing damage, or 5 (1d8 + 1) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/sergeant.png"
```
^statblock

```encounter-table
name: Sergeant
creatures:
 - 1: Sergeant
```