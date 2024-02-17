---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/9
- monster/size/huge
- monster/type/giant
aliases: ["Fire Giant Royal Headsman"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 201
---
# [Fire Giant Royal Headsman](2-Mechanics/CLI/bestiary/giant/fire-giant-royal-headsman-tftyp.md)
*Source: Tales from the Yawning Portal p. 201*  

```statblock
"name": "Fire Giant Royal Headsman (TftYP)"
"size": "Huge"
"type": "giant"
"alignment": "Lawful Evil"
"ac": !!int "18"
"hp": !!int "162"
"hit_dice": "13d12 + 78"
"stats":
- !!int "25"
- !!int "9"
- !!int "23"
- !!int "10"
- !!int "14"
- !!int "13"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Dexterity": !!int "3"
  "Constitution": !!int "10"
"skillsaves":
  "Athletics": !!int "11"
  "Perception": !!int "6"
"damage_immunities": "fire"
"senses": "passive Perception 16"
"languages": "Giant"
"cr": "9"
"actions":
- "desc": "The giant makes two greataxe attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +13 to hit, reach 10 ft., one target. Hit: 28\
    \ (3d12 + 9) slashing damage."
  "name": "Greataxe +2"
- "desc": "Ranged Weapon Attack: +11 to hit, range 60/240 ft., one target. Hit:\
    \ 29 (4d10 + 7) bludgeoning damage."
  "name": "Rock"
"source":
- "TftYP"
"image": "/2-Mechanics/CLI/bestiary/giant/token/fire-giant-royal-headsman.png"
```
^statblock

```encounter-table
name: Fire Giant Royal Headsman
creatures:
 - 1: Fire Giant Royal Headsman
```