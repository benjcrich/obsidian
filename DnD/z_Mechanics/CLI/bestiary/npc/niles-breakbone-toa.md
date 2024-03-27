---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Niles Breakbone"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 47
---
# [Niles Breakbone](2-Mechanics/CLI/bestiary/npc/niles-breakbone-toa.md)
*Source: Tomb of Annihilation p. 47*  

```statblock
"name": "Niles Breakbone (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Good"
"ac": !!int "15"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "12"
- !!int "11"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Insight": !!int "4"
  "Persuasion": !!int "5"
"senses": "passive Perception 12"
"languages": "any two languages"
"cr": "1/8"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8\
    \ + 1) piercing damage."
  "name": "Rapier"
"reactions":
- "desc": "Niles adds 2 to its AC against one melee attack that would hit it. To do\
    \ so, Niles must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "ToA"
"image": "/2-Mechanics/CLI/bestiary/npc/token/niles-breakbone.png"
```
^statblock

```encounter-table
name: Niles Breakbone
creatures:
 - 1: Niles Breakbone
```