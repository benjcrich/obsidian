---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/1-2
- monster/size/medium
- monster/type/construct
aliases: ["Swarm of Mechanical Spiders"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 143
---
# [Swarm of Mechanical Spiders](2-Mechanics/CLI/bestiary/construct/swarm-of-mechanical-spiders-wdh.md)
*Source: Waterdeep: Dragon Heist p. 143*  

A swarm of tiny constructed spiders which attack anyone messing with Jarlaxle's chest aboard the Scarlet Marpenoth

```statblock
"name": "Swarm of Mechanical Spiders (WDH)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d8"
"stats":
- !!int "3"
- !!int "13"
- !!int "10"
- !!int "1"
- !!int "7"
- !!int "1"
"speed": "20 ft., climb 20 ft."
"damage_vulnerabilities": "lightning"
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [prone](/2-Mechanics/CLI/rules/conditions.md#prone),\
  \ [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained), [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 10 ft., passive Perception 8"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "The swarm doesn't require air, food, drink, or sleep."
  "name": "Constructed Nature"
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Tiny insect. The swarm can't\
    \ regain hit points or gain temporary hit points."
  "name": "Swarm"
- "desc": "The swarm can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "While in contact with a web, the swarm knows the exact location of any\
    \ other creature in contact with the same web."
  "name": "Web Sense"
- "desc": "The swarm ignores movement restrictions caused by webbing."
  "name": "Web Walker"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 0 ft., one target in the swarm's\
    \ space. Hit: 10 (4d4) piercing damage, or 5 (2d4) piercing damage if the\
    \ swarm has half of its hit points or fewer."
  "name": "Bites"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/construct/token/swarm-of-mechanical-spiders.png"
```
^statblock

```encounter-table
name: Swarm of Mechanical Spiders
creatures:
 - 1: Swarm of Mechanical Spiders
```