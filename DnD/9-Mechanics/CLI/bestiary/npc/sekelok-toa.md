---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Sekelok"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 120
---
# [Sekelok](2-Mechanics/CLI/bestiary/npc/sekelok-toa.md)
*Source: Tomb of Annihilation p. 120*  

```statblock
"name": "Sekelok (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "18"
"hp": !!int "143"
"hit_dice": "22d8 + 44"
"stats":
- !!int "20"
- !!int "15"
- !!int "14"
- !!int "10"
- !!int "14"
- !!int "12"
"speed": "30 ft."
"saves":
  "Strength": !!int "9"
  "Constitution": !!int "6"
"skillsaves":
  "Intimidation": !!int "5"
  "Athletics": !!int "9"
  "Perception": !!int "6"
"senses": "passive Perception 16"
"languages": "any one language (usually Common)"
"cr": "9"
"traits":
- "desc": "Sekelok rerolls a failed saving throw."
  "name": "Indomitable (2/Day)"
- "desc": "As a bonus action, Sekelok can regain 20 hit points."
  "name": "Second Wind (Recharges after a Short or Long Rest)"
"actions":
- "desc": "Sekelok makes three attacks with its greatsword or its shortbow."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12 (2d6\
    \ + 5) slashing damage, plus 7 (2d6) slashing damage if Sekelok has more than\
    \ half of its total hit points remaining."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +6 to hit, range 80/320 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage, plus 7 (2d6) piercing damage if Sekelok has\
    \ more than half of its total hit points remaining."
  "name": "Shortbow"
"source":
- "ToA"
"image": "/2-Mechanics/CLI/bestiary/npc/token/sekelok.png"
```
^statblock

```encounter-table
name: Sekelok
creatures:
 - 1: Sekelok
```