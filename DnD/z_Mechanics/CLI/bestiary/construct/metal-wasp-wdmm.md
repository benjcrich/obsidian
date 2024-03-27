---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/1-2
- monster/size/medium
- monster/type/construct
aliases: ["Metal Wasp"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 174
---
# [Metal Wasp](2-Mechanics/CLI/bestiary/construct/metal-wasp-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 174*  

```statblock
"name": "Metal Wasp (WDMM)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "16"
"hp": !!int "13"
"hit_dice": "3d8"
"stats":
- !!int "10"
- !!int "14"
- !!int "10"
- !!int "1"
- !!int "10"
- !!int "3"
"speed": "10 ft., fly 50 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "1/2"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 5 (1d6\
    \ + 2) piercing damage, and the target must make a DC 11 Constitution saving\
    \ throw, taking 10 (3d6) poison damage on a failed save, or half as much damage\
    \ on a successful one. If the poison damage reduces the target to 0 hit points,\
    \ the target is stable but [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 hour, even after regaining hit points, and is [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)\
    \ while [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) in this way."
  "name": "Sting"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/construct/token/metal-wasp.png"
```
^statblock

```encounter-table
name: Metal Wasp
creatures:
 - 1: Metal Wasp
```