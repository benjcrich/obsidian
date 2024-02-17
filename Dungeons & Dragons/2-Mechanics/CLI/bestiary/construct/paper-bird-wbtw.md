---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/0
- monster/size/tiny
- monster/type/construct
aliases: ["Paper Bird"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 166
---
# [Paper Bird](2-Mechanics/CLI/bestiary/construct/paper-bird-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 166*  

Endelyn writes her correspondence on sheets of enchanted parchment, which she then folds into the shape of paper birds that fly to their intended recipients. If a message's recipient is on another plane of existence or is otherwise unreachable, the paper bird bursts into flames on takeoff and is instantly destroyed.

The paper birds are hostile toward all creatures except the hags of the Hourglass Coven.

```statblock
"name": "Paper Bird (WBtW)"
"size": "Tiny"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "5"
- !!int "16"
- !!int "8"
- !!int "2"
- !!int "14"
- !!int "6"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  "Perception": !!int "4"
"damage_vulnerabilities": "fire"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "passive Perception 14"
"languages": ""
"cr": "0"
"traits":
- "desc": "The paper bird has advantage on Wisdom (Perception) checks that rely on\
    \ sight."
  "name": "Keen Sight"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 1 slashing\
    \ damage."
  "name": "Sharp Edges"
"source":
- "WBtW"
"image": "/2-Mechanics/CLI/bestiary/construct/token/paper-bird.png"
```
^statblock

```encounter-table
name: Paper Bird
creatures:
 - 1: Paper Bird
```