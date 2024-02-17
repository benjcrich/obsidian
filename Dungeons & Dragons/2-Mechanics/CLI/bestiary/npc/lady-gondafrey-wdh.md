---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/2
- monster/size/medium
- monster/type/elemental
aliases: ["Lady Gondafrey"]
NoteIcon: monster
BestiaryType: elemental
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 152
---
# [Lady Gondafrey](2-Mechanics/CLI/bestiary/npc/lady-gondafrey-wdh.md)
*Source: Waterdeep: Dragon Heist p. 152*  

Lafy Gondafrey is the result of a magical experiment, a gargoyle that has been imbued with the personality of a human knight of Tyr (god of justice). Manshoon is amused by the creature so keeps it alive and locked in a cell.

```statblock
"name": "Lady Gondafrey (WDH)"
"size": "Medium"
"type": "elemental"
"alignment": "Lawful Good"
"ac": !!int "15"
"hp": !!int "52"
"hit_dice": "7d8 + 21"
"stats":
- !!int "15"
- !!int "11"
- !!int "16"
- !!int "10"
- !!int "11"
- !!int "7"
"speed": "30 ft., fly 60 ft."
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't adamantine"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common"
"cr": "2"
"traits":
- "desc": "While the gargoyle remains motionless, it is indistinguishable from an\
    \ inanimate statue."
  "name": "False Appearance"
"actions":
- "desc": "The gargoyle makes two attacks: one with its bite and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage."
  "name": "Claws"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/npc/token/lady-gondafrey.png"
```
^statblock

```encounter-table
name: Lady Gondafrey
creatures:
 - 1: Lady Gondafrey
```