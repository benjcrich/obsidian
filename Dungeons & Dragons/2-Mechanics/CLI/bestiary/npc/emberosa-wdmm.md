---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/9
- monster/size/huge
- monster/type/giant
aliases: ["Emberosa"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 185
---
# [Emberosa](2-Mechanics/CLI/bestiary/npc/emberosa-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 185*  

With dark skin and flaming red hair, fire giants have a fearsome reputation as soldiers and conquerors. They dwell among volcanoes, lava flows, and rocky mountains, and are known for their ability to burn, plunder, and destroy.

```statblock
"name": "Emberosa (WDMM)"
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
- "desc": "Emberosa makes two greatsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 28\
    \ (6d6 + 7) slashing damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +11 to hit, range 60/240 ft., one target. Hit:\
    \ 29 (4d10 + 7) fire damage."
  "name": "Hurl Fire"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/npc/token/emberosa.png"
```
^statblock

```encounter-table
name: Emberosa
creatures:
 - 1: Emberosa
```