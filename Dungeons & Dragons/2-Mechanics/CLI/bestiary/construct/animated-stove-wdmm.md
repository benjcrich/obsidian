---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/3
- monster/size/large
- monster/type/construct
aliases: ["Animated Stove"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 186
---
# [Animated Stove](2-Mechanics/CLI/bestiary/construct/animated-stove-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 186*  

The stove was given a semblance of life through an [animate objects](/2-Mechanics/CLI/spells/animate-objects.md) spell made permanent by a [wish](/2-Mechanics/CLI/spells/wish.md) spell.

```statblock
"name": "Animated Stove (WDMM)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"hp": !!int "50"
"hit_dice": "50d1"
"stats":
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "3"
- !!int "3"
- !!int "1"
"speed": "30 ft."
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 6"
"languages": ""
"cr": "3"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11 (2d8\
    \ + 2) bludgeoning damage."
  "name": "Slam"
- "desc": "The stove belches fire in a 15-foot cone. Each creature in the area must\
    \ make a DC 10 Dexterity saving throw, taking 22 (4d10) fire damage on a failed\
    \ save, or half as much damage on a successful one."
  "name": "Belch Fire (Recharge 4-6)"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/construct/token/animated-stove.png"
```
^statblock

```encounter-table
name: Animated Stove
creatures:
 - 1: Animated Stove
```