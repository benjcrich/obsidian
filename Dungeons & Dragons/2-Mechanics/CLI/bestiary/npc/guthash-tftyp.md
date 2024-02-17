---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/1-4
- monster/size/medium
- monster/type/beast
aliases: ["Guthash"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 21
---
# [Guthash](2-Mechanics/CLI/bestiary/npc/guthash-tftyp.md)
*Source: Tales from the Yawning Portal p. 21*  

Some giant rats carry vile diseases that they spread with their bites.

```statblock
"name": "Guthash (TftYP)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "16"
"hit_dice": "2d6"
"stats":
- !!int "7"
- !!int "15"
- !!int "11"
- !!int "2"
- !!int "10"
- !!int "4"
"speed": "30 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "1/4"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage. If the target is a creature, it must succeed on a DC\
    \ 10 Constitution saving throw or contract a disease. Until the disease is cured,\
    \ the target can't regain hit points except by magical means, and the target's\
    \ hit point maximum decreases by 3 (1d6) every 24 hours. If the target's hit\
    \ point maximum drops to 0 as a result of this disease, the target dies."
  "name": "Bite"
"source":
- "TftYP"
"image": "/2-Mechanics/CLI/bestiary/npc/token/guthash.png"
```
^statblock

```encounter-table
name: Guthash
creatures:
 - 1: Guthash
```