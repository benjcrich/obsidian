---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/0
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Walking Corpse"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Curse of Strahd p. 165
---
# [Walking Corpse](2-Mechanics/CLI/bestiary/humanoid/walking-corpse-cos.md)
*Source: Curse of Strahd p. 165*  

```statblock
"name": "Walking Corpse (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "10"
"hp": !!int "4"
"hit_dice": "1d8"
"stats":
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "20 ft."
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "0"
"traits":
- "desc": "When a corpse is reduced to 0 hit points, it splits open, disgorging a\
    \ [swarm of poisonous snakes](/2-Mechanics/CLI/bestiary/beast/swarm-of-poisonous-snakes.md).\
    \ The snakes are hungry and fight until slain."
  "name": "Violent Death"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ bludgeoning damage."
  "name": "Club"
"source":
- "CoS"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/walking-corpse.png"
```
^statblock

```encounter-table
name: Walking Corpse
creatures:
 - 1: Walking Corpse
```