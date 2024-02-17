---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/4
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/size/large
- monster/type/fey
aliases: ["Yeth Hound"]
NoteIcon: monster
BestiaryType: fey
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 271, Volo's Guide to Monsters p. 201
---
# [Yeth Hound](2-Mechanics/CLI/bestiary/fey/yeth-hound-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 271, Volo's Guide to Monsters p. 201*  

Granted by mighty Fey to individuals who please them, yeth hounds serve their masters like hunting dogs. They race in pursuit of their prey, running it down until it's too exhausted to fight back. Only the threat of dawn drives the pack back into hiding.

A pack of yeth hounds can be created by powerful Fey such as the Queen of Air and Darkness. Each pack's master can telepathically communicate with their yeth hounds to give the pack commands from afar. If a pack's master is killed, the hounds seek out a new master, typically an evil [vampire](/2-Mechanics/CLI/bestiary/undead/vampire.md), [necromancer](/2-Mechanics/CLI/bestiary/humanoid/necromancer-wizard-mpmm.md), or [hag](/2-Mechanics/CLI/bestiary/fey/green-hag.md).

```statblock
"name": "Yeth Hound (MPMM)"
"size": "Large"
"type": "fey"
"alignment": "Typically  Neutral Evil"
"ac": !!int "14"
"hp": !!int "51"
"hit_dice": "6d10 + 18"
"stats":
- !!int "18"
- !!int "17"
- !!int "16"
- !!int "5"
- !!int "12"
- !!int "7"
"speed": "40 ft., fly 40 ft. (hover)"
"skillsaves":
  "Perception": !!int "5"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks not\
  \ made with silvered weapons"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "understands Common, Elvish and Sylvan but can't speak"
"cr": "4"
"traits":
- "desc": "If the yeth hound starts its turn in sunlight, it is transported to the\
    \ Ethereal Plane. While sunlight shines on the spot from which it vanished, the\
    \ hound must remain in the Deep Ethereal. After sunset, it returns to the Border\
    \ Ethereal at the same spot, whereupon it typically sets out to find its pack\
    \ or its master. The hound is visible on the Material Plane while it is in the\
    \ Border Ethereal, and vice versa, but it can't affect or be affected by anything\
    \ on the other plane. Once it is adjacent to its master or a pack mate that is\
    \ on the Material Plane, a yeth hound in the Border Ethereal can return to the\
    \ Material Plane as an action."
  "name": "Sunlight Banishment"
- "desc": "While the yeth hound is on the same plane of existence as its master, it\
    \ can magically convey what it senses to its master, and the two can communicate\
    \ telepathically with each other."
  "name": "Telepathic Bond"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11 (2d6\
    \ + 4) piercing damage, plus 14 (4d6) psychic damage if the target is [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Bite"
- "desc": "The yeth hound bays magically. Every enemy within 300 feet of the hound\
    \ that can hear it must succeed on a DC 13 Wisdom saving throw or be [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ of the hound until the end of the hound's next turn or until the hound is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated).\
    \ A [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened) target that\
    \ starts its turn within 30 feet of the hound must use all its movement on that\
    \ turn to get as far from the hound as possible, must finish the move before taking\
    \ an action, and must take the most direct route, even if hazards lie that way.\
    \ A target that successfully saves is immune to the baying of all yeth hounds\
    \ for the next 24 hours."
  "name": "Baleful Baying"
"source":
- "MPMM"
- "VGM"
- "BMT"
"image": "/2-Mechanics/CLI/bestiary/fey/token/yeth-hound.png"
```
^statblock

```encounter-table
name: Yeth Hound
creatures:
 - 1: Yeth Hound
```

## Environment

forest, grassland, hill