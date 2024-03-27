---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/6
- monster/size/large
- monster/type/dragon
aliases: ["Reduced-Threat Wyvern"]
NoteIcon: monster
BestiaryType: dragon
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 113
---
# [Reduced-Threat Wyvern](2-Mechanics/CLI/bestiary/dragon/reduced-threat-wyvern-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Wyvern (TftYP)"
"size": "Large"
"type": "dragon"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "110"
"hit_dice": "13d10 + 39"
"stats":
- !!int "19"
- !!int "10"
- !!int "16"
- !!int "5"
- !!int "12"
- !!int "6"
"speed": "20 ft., fly 80 ft."
"skillsaves":
  "Perception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": ""
"cr": "6"
"actions":
- "desc": "The wyvern makes two attacks: one with its bite and one with its stinger.\
    \ While flying, it can use its claws in place of one other attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one creature. Hit: 11\
    \ (2d6 + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13 (2d8\
    \ + 4) slashing damage."
  "name": "Claws"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one creature. Hit: 11\
    \ (2d6 + 4) piercing damage. The target must make a DC 15 Constitution saving\
    \ throw, taking 24 (7d6) poison damage on a failed save, or half as much damage\
    \ on a successful one."
  "name": "Stinger"
"source":
- "TftYP"
"image": "/2-Mechanics/CLI/bestiary/dragon/token/reduced-threat-wyvern.png"
```
^statblock

```encounter-table
name: Reduced-Threat Wyvern
creatures:
 - 1: Reduced-Threat Wyvern
```