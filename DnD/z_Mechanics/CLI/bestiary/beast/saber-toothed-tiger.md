---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/2
- monster/environment/arctic
- monster/environment/mountain
- monster/size/large
- monster/type/beast
aliases: ["Saber-Toothed Tiger"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 336, Mythic Odysseys of Theros, Icewind Dale: Rime of the Frostmaiden, Curse of Strahd, Journeys through the Radiant Citadel. Available in the SRD and the Basic Rules.
---
# [Saber-Toothed Tiger](2-Mechanics/CLI/bestiary/beast/saber-toothed-tiger.md)
*Source: Monster Manual p. 336, Mythic Odysseys of Theros, Icewind Dale: Rime of the Frostmaiden, Curse of Strahd, Journeys through the Radiant Citadel. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Saber-Toothed Tiger"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "52"
"hit_dice": "7d10 + 14"
"stats":
- !!int "18"
- !!int "14"
- !!int "15"
- !!int "3"
- !!int "12"
- !!int "8"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "2"
"traits":
- "desc": "The tiger has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "If the tiger moves at least 20 feet straight toward a creature and then\
    \ hits it with a claw attack on the same turn, that target must succeed on a DC\
    \ 14 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone).\
    \ If the target is [prone](/2-Mechanics/CLI/rules/conditions.md#prone), the tiger\
    \ can make one bite attack against it as a bonus action."
  "name": "Pounce"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10 (1d10\
    \ + 5) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 12 (2d6\
    \ + 5) slashing damage."
  "name": "Claw"
"source":
- "MM"
- "EGW"
- "MOT"
- "IDRotF"
- "CoS"
- "JttRC"
- "SatO"
- "ToFW"
"image": "/2-Mechanics/CLI/bestiary/beast/token/saber-toothed-tiger.png"
```
^statblock

```encounter-table
name: Saber-Toothed Tiger
creatures:
 - 1: Saber-Toothed Tiger
```

## Environment

mountain, arctic