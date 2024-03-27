---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/2
- monster/size/large
- monster/type/giant
aliases: ["Carrion Ogre"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 189
---
# [Carrion Ogre](2-Mechanics/CLI/bestiary/giant/carrion-ogre-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 189*  

A creature that has the body of an ogre and the head of a carrion crawler.

```statblock
"name": "Carrion Ogre (WDMM)"
"size": "Large"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"hp": !!int "59"
"hit_dice": "7d10 + 21"
"stats":
- !!int "19"
- !!int "8"
- !!int "16"
- !!int "1"
- !!int "7"
- !!int "7"
"speed": "40 ft."
"senses": "darkvision 60 ft., passive Perception 8"
"languages": ""
"cr": "2"
"traits":
- "desc": "While lashed to the floor, the creature is [prone](/2-Mechanics/CLI/rules/conditions.md#prone)\
    \ and [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained). It also suffers\
    \ from two levels of [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion)."
  "name": "Tied Down"
"actions":
- "desc": "The creature makes two attacks: one with its tentacles and one with its\
    \ bite."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one creature. Hit: 4\
    \ (1d4 + 2) poison damage, and the target must succeed on a DC 13 Constitution\
    \ saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 minute. Until this poison ends, the target is [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed).\
    \ The target can repeat the saving throw at the end of each of its turns, ending\
    \ the poison on itself on a success."
  "name": "Tentacles"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) piercing damage."
  "name": "Bite"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/giant/token/carrion-ogre.png"
```
^statblock

```encounter-table
name: Carrion Ogre
creatures:
 - 1: Carrion Ogre
```