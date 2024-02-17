---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Drow Cultist"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Out of the Abyss p. 196
---
# [Drow Cultist](2-Mechanics/CLI/bestiary/humanoid/drow-cultist-oota.md)
*Source: Out of the Abyss p. 196*  

```statblock
"name": "Drow Cultist (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Good alignment"
"ac": !!int "12"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "12"
- !!int "10"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "2"
  "Religion": !!int "2"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "1/8"
"traits":
- "desc": "The cultist has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Dark Devotion"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one creature. Hit: 4 (1d6\
    \ + 1) slashing damage."
  "name": "Scimitar"
"source":
- "OotA"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/drow-cultist.png"
```
^statblock

```encounter-table
name: Drow Cultist
creatures:
 - 1: Drow Cultist
```