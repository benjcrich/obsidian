---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/1
- monster/environment/forest
- monster/environment/hill
- monster/size/large
- monster/type/beast
aliases: ["Dire Wolf"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 321, Curse of Strahd, Storm King's Thunder, Tales from the Yawning Portal, Ghosts of Saltmarsh, Icewind Dale: Rime of the Frostmaiden, Journeys through the Radiant Citadel. Available in the SRD and the Basic Rules.
---
# [Dire Wolf](2-Mechanics/CLI/bestiary/beast/dire-wolf.md)
*Source: Monster Manual p. 321, Curse of Strahd, Storm King's Thunder, Tales from the Yawning Portal, Ghosts of Saltmarsh, Icewind Dale: Rime of the Frostmaiden, Journeys through the Radiant Citadel. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Dire Wolf"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"hp": !!int "37"
"hit_dice": "5d10 + 10"
"stats":
- !!int "17"
- !!int "15"
- !!int "15"
- !!int "3"
- !!int "12"
- !!int "7"
"speed": "50 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "1"
"traits":
- "desc": "The wolf has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or smell."
  "name": "Keen Hearing and Smell"
- "desc": "The wolf has advantage on an attack roll against a creature if at least\
    \ one of the wolf's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6\
    \ + 3) piercing damage. If the target is a creature, it must succeed on a DC\
    \ 13 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Bite"
"source":
- "MM"
- "CoS"
- "SKT"
- "TftYP"
- "GoS"
- "IDRotF"
- "JttRC"
- "PaBTSO"
- "ToFW"
"image": "/2-Mechanics/CLI/bestiary/beast/token/dire-wolf.png"
```
^statblock

```encounter-table
name: Dire Wolf
creatures:
 - 1: Dire Wolf
```

## Environment

forest, hill