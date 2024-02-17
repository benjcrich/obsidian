---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/3
- monster/size/medium
- monster/type/monstrosity
aliases: ["Reduced-Threat Basilisk"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 113
---
# [Reduced-Threat Basilisk](2-Mechanics/CLI/bestiary/monstrosity/reduced-threat-basilisk-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Basilisk (TftYP)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "16"
- !!int "8"
- !!int "15"
- !!int "2"
- !!int "8"
- !!int "7"
"speed": "20 ft."
"senses": "darkvision 60 ft., passive Perception 9"
"languages": ""
"cr": "3"
"traits":
- "desc": "If a creature starts its turn within 30 feet of the basilisk and the two\
    \ of them can see each other, the basilisk can force the creature to make a DC\
    \ 12 Constitution saving throw if the basilisk isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated).\
    \ On a failed save, the creature magically begins to turn to stone and is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained).\
    \ It must repeat the saving throw at the end of its next turn. On a success, the\
    \ effect ends. On a failure, the creature is [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified)\
    \ until freed by the  [greater restoration](/2-Mechanics/CLI/spells/greater-restoration.md)\
    \ spell or other magic.\n\nA creature that isn't surprised can avert its eyes\
    \ to avoid the saving throw at the start of its turn. If it does so, it can't\
    \ see the basilisk until the start of its next turn, when it can avert its eyes\
    \ again. If it looks at the basilisk in the meantime, it must immediately make\
    \ the save.\n\nIf the basilisk sees its reflection within 30 feet of it in bright\
    \ light, it mistakes itself for a rival and targets itself with its gaze."
  "name": "Petrifying Gaze"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6\
    \ + 3) piercing damage plus 7 (2d6) poison damage."
  "name": "Bite"
"source":
- "TftYP"
"image": "/2-Mechanics/CLI/bestiary/monstrosity/token/reduced-threat-basilisk.png"
```
^statblock

```encounter-table
name: Reduced-Threat Basilisk
creatures:
 - 1: Reduced-Threat Basilisk
```