---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid
aliases: ["Harengon Brigand"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 235
---
# [Harengon Brigand](2-Mechanics/CLI/bestiary/humanoid/harengon-brigand-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 235*  

Harengons are rabbit-folk native to the Feywild, through they often migrate to the Material Plane. They love to travel on foot and rarely stay in one place for long.

Not all harengons are mean-spirited bullies like the ones presented here. Every harengon follows their own path through life, their disposition shaped in part by the company they keep. One harengon might travel to far lands, make friends along the way, delight in freedom and the open trail, and find inner peace. Another might become an adventurer with a strong heart and fervent dreams. For more information on harengons as player characters, see the introduction of this adventure.

```statblock
"name": "Harengon Brigand (WBtW)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "14"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "14"
- !!int "17"
- !!int "11"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
"skillsaves":
  "Perception": !!int "4"
  "Acrobatics": !!int "5"
"senses": "passive Perception 14"
"languages": "Common, Sylvan"
"cr": "1/8"
"traits":
- "desc": "The harengon has advantage on an attack roll against a creature if at least\
    \ one of the harengon's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
- "desc": "The harengon's long jump is up to 20 feet and its high jump is up to 10\
    \ feet, with or without a running start."
  "name": "Standing Leap"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) bludgeoning damage."
  "name": "Club"
- "desc": "Ranged Weapon Attack: +5 to hit, range 30/120 ft., one target. Hit:\
    \ 5 (1d4 + 3) bludgeoning damage."
  "name": "Sling"
"source":
- "WBtW"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/harengon-brigand.png"
```
^statblock

```encounter-table
name: Harengon Brigand
creatures:
 - 1: Harengon Brigand
```