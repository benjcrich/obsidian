---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/1-4
- monster/size/large
- monster/type/beast
aliases: ["Awakened Elk"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 72
---
# [Awakened Elk](2-Mechanics/CLI/bestiary/beast/awakened-elk-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 72*  

```statblock
"name": "Awakened Elk (WDMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "13"
"hit_dice": "2d10 + 2"
"stats":
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "2"
- !!int "10"
- !!int "6"
"speed": "50 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "If the elk moves at least 20 feet straight toward a target and then hits\
    \ it with a ram attack on the same turn, the target takes an extra 7 (2d6) damage.\
    \ If the target is a creature, it must succeed on a DC 13 Strength saving throw\
    \ or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Charge"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) bludgeoning damage."
  "name": "Ram"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one [prone](/2-Mechanics/CLI/rules/conditions.md#prone)\
    \ creature. Hit: 8 (2d4 + 3) bludgeoning damage."
  "name": "Hooves"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/beast/token/awakened-elk.png"
```
^statblock

```encounter-table
name: Awakened Elk
creatures:
 - 1: Awakened Elk
```