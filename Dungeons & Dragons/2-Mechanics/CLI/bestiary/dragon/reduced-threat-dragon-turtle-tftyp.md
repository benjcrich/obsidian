---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/17
- monster/size/gargantuan
- monster/type/dragon
aliases: ["Reduced-Threat Dragon Turtle"]
NoteIcon: monster
BestiaryType: dragon
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 113
---
# [Reduced-Threat Dragon Turtle](2-Mechanics/CLI/bestiary/dragon/reduced-threat-dragon-turtle-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Dragon Turtle (TftYP)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Neutral"
"ac": !!int "20"
"hp": !!int "341"
"hit_dice": "22d20 + 110"
"stats":
- !!int "25"
- !!int "10"
- !!int "20"
- !!int "10"
- !!int "12"
- !!int "12"
"speed": "20 ft., swim 40 ft."
"saves":
  "Dexterity": !!int "6"
  "Wisdom": !!int "7"
  "Constitution": !!int "11"
"damage_resistances": "fire"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Aquan, Draconic"
"cr": "17"
"traits":
- "desc": "The dragon turtle can breathe air and water."
  "name": "Amphibious"
"actions":
- "desc": "The dragon turtle makes three attacks: one with its bite and two with its\
    \ claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +13 to hit, reach 15 ft., one target. Hit: 26\
    \ (3d12 + 7) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +13 to hit, reach 10 ft., one target. Hit: 16\
    \ (2d8 + 7) slashing damage."
  "name": "Claw"
- "desc": "The dragon turtle exhales scalding steam in a 60-foot cone. Each creature\
    \ in that area must make a DC 18 Constitution saving throw, taking 52 (15d6)\
    \ fire damage on a failed save, or half as much damage on a successful one. Being\
    \ underwater doesn't grant resistance against this damage."
  "name": "Steam Breath (Recharge 5-6)"
"source":
- "TftYP"
"image": "/2-Mechanics/CLI/bestiary/dragon/token/reduced-threat-dragon-turtle.png"
```
^statblock

```encounter-table
name: Reduced-Threat Dragon Turtle
creatures:
 - 1: Reduced-Threat Dragon Turtle
```