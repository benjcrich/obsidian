---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/4
- monster/size/large
- monster/type/monstrosity
aliases: ["Tecuziztecatl"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 245
---
# [Tecuziztecatl](2-Mechanics/CLI/bestiary/npc/tecuziztecatl-tftyp.md)
*Source: Tales from the Yawning Portal p. 245*  

A giant slug named Tecuziztecatl, the Lord of Snails. Tecuziztecatl (TayCOO-zeez-tay-COT-el) is highly intelligent and quite the boaster. In ancient lore it was considered to be related to the moon, a fact of which it is quite proud. During combat the slug will detail, in Olman, what it has in store for the characters and how hopeless their situation is.

```statblock
"name": "Tecuziztecatl (TftYP)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "102"
"hit_dice": "12d10 + 36"
"stats":
- !!int "17"
- !!int "10"
- !!int "16"
- !!int "15"
- !!int "16"
- !!int "13"
"speed": "30 ft., climb 30 ft., swim 30 ft."
"skillsaves":
  "Deception": !!int "3"
  "Stealth": !!int "2"
"damage_resistances": "bludgeoning from nonmagical attacks"
"damage_immunities": "acid"
"senses": "blindsight 30 ft., passive Perception 13"
"languages": "Olman, Primordial"
"cr": "4"
"traits":
- "desc": "Tecuziztecatl can breathe air and water."
  "name": "Amphibious"
- "desc": "Tecuziztecatl sheds dim light within 20 feet of itself."
  "name": "Glowing"
- "desc": "Tecuziztecatl can enter a space large enough for a Medium creature without\
    \ squeezing."
  "name": "Flexible"
- "desc": "Tecuziztecatl can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "Tecuziztecatl makes two pseudopod attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one target. Hit: 12 (2d8\
    \ + 3) bludgeoning damage."
  "name": "Pseudopod"
- "desc": "Tecuziztecatl exhales acid in a 30-foot line that is 5 feet wide. Each\
    \ creature in that line must make a DC 13 Dexterity saving throw, taking 18 (4d8)\
    \ acid damage on a failed save, or half as much damage on a successful one."
  "name": "Spit Acid (Recharge 4-6)"
"source":
- "TftYP"
"image": "/2-Mechanics/CLI/bestiary/npc/token/tecuziztecatl.png"
```
^statblock

```encounter-table
name: Tecuziztecatl
creatures:
 - 1: Tecuziztecatl
```