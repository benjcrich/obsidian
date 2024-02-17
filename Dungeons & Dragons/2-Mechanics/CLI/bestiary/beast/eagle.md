---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/0
- monster/environment/coastal
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/size/small
- monster/type/beast
aliases: ["Eagle"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 322, Candlekeep Mysteries. Available in the SRD and the Basic Rules.
---
# [Eagle](2-Mechanics/CLI/bestiary/beast/eagle.md)
*Source: Monster Manual p. 322, Candlekeep Mysteries. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Eagle"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "3"
"hit_dice": "1d6"
"stats":
- !!int "6"
- !!int "15"
- !!int "10"
- !!int "2"
- !!int "14"
- !!int "7"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": ""
"cr": "0"
"traits":
- "desc": "The eagle has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on sight."
  "name": "Keen Sight"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) slashing damage."
  "name": "Talons"
"source":
- "MM"
- "CM"
- "ToFW"
"image": "/2-Mechanics/CLI/bestiary/beast/token/eagle.png"
```
^statblock

```encounter-table
name: Eagle
creatures:
 - 1: Eagle
```

## Environment

mountain, grassland, hill, coastal