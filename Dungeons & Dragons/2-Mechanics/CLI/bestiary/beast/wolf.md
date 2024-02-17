---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/1-4
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/size/medium
- monster/type/beast
aliases: ["Wolf"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 341, Curse of Strahd, Hoard of the Dragon Queen, Lost Mine of Phandelver, Princes of the Apocalypse, The Rise of Tiamat, Storm King's Thunder, Ghosts of Saltmarsh, Icewind Dale: Rime of the Frostmaiden, Tasha's Cauldron of Everything, Candlekeep Mysteries. Available in the SRD and the Basic Rules.
---
# [Wolf](2-Mechanics/CLI/bestiary/beast/wolf.md)
*Source: Monster Manual p. 341, Curse of Strahd, Hoard of the Dragon Queen, Lost Mine of Phandelver, Princes of the Apocalypse, The Rise of Tiamat, Storm King's Thunder, Ghosts of Saltmarsh, Icewind Dale: Rime of the Frostmaiden, Tasha's Cauldron of Everything, Candlekeep Mysteries. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Wolf"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "12"
- !!int "15"
- !!int "12"
- !!int "3"
- !!int "12"
- !!int "6"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The wolf has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or smell."
  "name": "Keen Hearing and Smell"
- "desc": "The wolf has advantage on an attack roll against a creature if at least\
    \ one of the wolf's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) piercing damage. If the target is a creature, it must succeed on a DC\
    \ 11 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Bite"
"source":
- "MM"
- "CoS"
- "HotDQ"
- "LMoP"
- "PotA"
- "RoT"
- "SKT"
- "GoS"
- "EGW"
- "IDRotF"
- "TCE"
- "CM"
- "HftT"
- "PaBTSO"
- "LK"
- "BMT"
- "GHLoE"
"image": "/2-Mechanics/CLI/bestiary/beast/token/wolf.png"
```
^statblock

```encounter-table
name: Wolf
creatures:
 - 1: Wolf
```

## Environment

grassland, forest, hill