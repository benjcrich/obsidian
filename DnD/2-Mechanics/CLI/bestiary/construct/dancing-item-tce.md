---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tce
- monster/cr/
- monster/size/large
- monster/type/construct
aliases: ["Dancing Item"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Tasha's Cauldron of Everything p. 29
---
# [Dancing Item](2-Mechanics/CLI/bestiary/construct/dancing-item-tce.md)
*Source: Tasha's Cauldron of Everything p. 29*  

```statblock
"name": "Dancing Item (TCE)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "16"
"stats":
- !!int "18"
- !!int "14"
- !!int "16"
- !!int "4"
- !!int "10"
- !!int "6"
"speed": "30 ft., fly 30 ft. (hover)"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages you speak"
"traits":
- "desc": "The item is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "When any creature starts its turn within 10 feet of the item, the item\
    \ can increase or decrease (your choice) the walking speed of that creature by\
    \ 10 feet until the end of the turn, provided the item isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Irrepressible Dance"
"actions":
- "desc": "Melee Weapon Attack: the summoner's spell attack modifier to hit, reach\
    \ 5 ft., one target you can see. Hit: 1d10 + PB force damage."
  "name": "Force-Empowered Slam"
"source":
- "TCE"
"image": "/2-Mechanics/CLI/bestiary/construct/token/dancing-item.png"
```
^statblock

```encounter-table
name: Dancing Item
creatures:
 - 1: Dancing Item
```