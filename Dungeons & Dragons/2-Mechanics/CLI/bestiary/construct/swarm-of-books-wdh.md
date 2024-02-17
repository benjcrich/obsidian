---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/1-4
- monster/size/medium
- monster/type/construct
aliases: ["Swarm of Books"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 156
---
# [Swarm of Books](2-Mechanics/CLI/bestiary/construct/swarm-of-books-wdh.md)
*Source: Waterdeep: Dragon Heist p. 156*  

Animated books which form a swarm when disturbed

```statblock
"name": "Swarm of Books (WDH)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d8"
"stats":
- !!int "5"
- !!int "15"
- !!int "10"
- !!int "2"
- !!int "12"
- !!int "4"
"speed": "0 ft., fly 30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [prone](/2-Mechanics/CLI/rules/conditions.md#prone),\
  \ [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained), [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned),\
  \ [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)"
"senses": "blindsight 60 ft., passive Perception 11"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Tiny book. The swarm can't regain\
    \ hit points or gain temporary hit points."
  "name": "Swarm"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 0 ft., one creature in the swarm's\
    \ space. Hit: 5 (2d4) bludgeoning damage, or 2 (1d4) bludgeoning damage\
    \ if the swarm has half of its hit points or fewer."
  "name": "Slam"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/construct/token/swarm-of-books.png"
```
^statblock

```encounter-table
name: Swarm of Books
creatures:
 - 1: Swarm of Books
```