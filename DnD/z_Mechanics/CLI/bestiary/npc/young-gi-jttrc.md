---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Young-Gi"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 85
---
# [Young-Gi](2-Mechanics/CLI/bestiary/npc/young-gi-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 85*  

```statblock
"name": "Young-Gi (JttRC)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral"
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
- "desc": "Young-Gi adds 2 to its AC against one melee attack that would hit it. To\
    \ do so, Young-Gi must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "JttRC"
"image": "/2-Mechanics/CLI/bestiary/npc/token/young-gi.png"
```
^statblock

```encounter-table
name: Young-Gi
creatures:
 - 1: Young-Gi
```