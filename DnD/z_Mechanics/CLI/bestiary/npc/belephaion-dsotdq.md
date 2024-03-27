---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/9
- monster/size/large
- monster/type/dragon
aliases: ["Belephaion"]
NoteIcon: monster
BestiaryType: dragon
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 157
---
# [Belephaion](2-Mechanics/CLI/bestiary/npc/belephaion-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 157*  

```statblock
"name": "Belephaion (DSotDQ)"
"size": "Large"
"type": "dragon"
"alignment": "Lawful Evil"
"ac": !!int "18"
"hp": !!int "152"
"hit_dice": "16d10 + 64"
"stats":
- !!int "21"
- !!int "10"
- !!int "19"
- !!int "14"
- !!int "13"
- !!int "17"
"speed": "40 ft., burrow 20 ft., fly 80 ft."
"saves":
  "Charisma": !!int "7"
  "Dexterity": !!int "4"
  "Wisdom": !!int "5"
  "Constitution": !!int "8"
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "9"
"damage_immunities": "lightning"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 19"
"languages": "Common, Draconic"
"cr": "9"
"actions":
- "desc": "Belephaion makes three attacks: one with its bite and two with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 16 (2d10\
    \ + 5) piercing damage plus 5 (1d10) lightning damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12 (2d6\
    \ + 5) slashing damage."
  "name": "Claw"
- "desc": "Belephaion exhales lightning in a 60-foot line that is 5 feet wide. Each\
    \ creature in that line must make a DC 16 Dexterity saving throw, taking 55 (10d10)\
    \ lightning damage on a failed save, or half as much damage on a successful one."
  "name": "Lightning Breath (Recharge 5-6)"
- "desc": "Belephaion magically transforms into an [eagle](/2-Mechanics/CLI/bestiary/beast/eagle.md)\
    \ or a [priest](/2-Mechanics/CLI/bestiary/humanoid/priest.md), while retaining\
    \ his alignment, damage immunities, hit points, Hit Dice, and Intelligence, Wisdom,\
    \ and Charisma scores. This transformation ends if he is reduced to 0 hit points\
    \ or uses a bonus action to end it."
  "name": "Alter Shape"
"source":
- "DSotDQ"
"image": "/2-Mechanics/CLI/bestiary/npc/token/belephaion.png"
```
^statblock

```encounter-table
name: Belephaion
creatures:
 - 1: Belephaion
```