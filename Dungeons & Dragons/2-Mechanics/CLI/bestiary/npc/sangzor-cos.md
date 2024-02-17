---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/1
- monster/size/large
- monster/type/beast
aliases: ["Sangzor"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Curse of Strahd p. 160
---
# [Sangzor](2-Mechanics/CLI/bestiary/npc/sangzor-cos.md)
*Source: Curse of Strahd p. 160*  

```statblock
"name": "Sangzor (CoS)"
"size": "Large"
"type": "beast"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"hp": !!int "33"
"hit_dice": "3d10 + 3"
"stats":
- !!int "17"
- !!int "11"
- !!int "12"
- !!int "6"
- !!int "12"
- !!int "6"
"speed": "40 ft."
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "passive Perception 11"
"languages": ""
"cr": "1"
"traits":
- "desc": "If Sangzor moves at least 20 feet straight toward a target and then hits\
    \ it with a ram attack on the same turn, the target takes an extra 5 (2d4) bludgeoning\
    \ damage. If the target is a creature, it must succeed on a DC 13 Strength saving\
    \ throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Charge"
- "desc": "Sangzor has advantage on Strength and Dexterity saving throws made against\
    \ effects that would knock it [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Sure-Footed"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (2d4\
    \ + 3) bludgeoning damage."
  "name": "Ram"
"source":
- "CoS"
"image": "/2-Mechanics/CLI/bestiary/npc/token/sangzor.png"
```
^statblock

```encounter-table
name: Sangzor
creatures:
 - 1: Sangzor
```