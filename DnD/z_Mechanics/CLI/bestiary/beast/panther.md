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
aliases: ["Panther"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 333, Tales from the Yawning Portal, Tomb of Annihilation, Waterdeep: Dragon Heist. Available in the SRD and the Basic Rules.
---
# [Panther](2-Mechanics/CLI/bestiary/beast/panther.md)
*Source: Monster Manual p. 333, Tales from the Yawning Portal, Tomb of Annihilation, Waterdeep: Dragon Heist. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Panther"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "13"
"hit_dice": "3d8"
"stats":
- !!int "14"
- !!int "15"
- !!int "10"
- !!int "3"
- !!int "14"
- !!int "7"
"speed": "50 ft., climb 40 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The panther has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "If the panther moves at least 20 feet straight toward a creature and then\
    \ hits it with a claw attack on the same turn, that target must succeed on a DC\
    \ 12 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone).\
    \ If the target is [prone](/2-Mechanics/CLI/rules/conditions.md#prone), the panther\
    \ can make one bite attack against it as a bonus action."
  "name": "Pounce"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) slashing damage."
  "name": "Claw"
"source":
- "MM"
- "TftYP"
- "ToA"
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/beast/token/panther.png"
```
^statblock

```encounter-table
name: Panther
creatures:
 - 1: Panther
```

## Environment

grassland, forest, hill