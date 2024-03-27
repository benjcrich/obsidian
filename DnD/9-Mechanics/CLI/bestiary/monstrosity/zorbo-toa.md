---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/1-2
- monster/size/small
- monster/type/monstrosity
aliases: ["Zorbo"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 241
---
# [Zorbo](2-Mechanics/CLI/bestiary/monstrosity/zorbo-toa.md)
*Source: Tomb of Annihilation p. 241*  

A zorbo (pronounced ZOR-boh) is a ferocious omnivore similar in size and appearance to a koala. Living in trees and caves, it has long claws, a dour disposition, and a fondness for humanoid flesh. A zorbo alters its natural armor to match its surroundings, and it can weaken and destroy armor, shields, and protective magic items with its sharp claws.

```statblock
"name": "Zorbo (ToA)"
"size": "Small"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "27"
"hit_dice": "6d6 + 6"
"stats":
- !!int "13"
- !!int "11"
- !!int "13"
- !!int "3"
- !!int "12"
- !!int "7"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Athletics": !!int "3"
"senses": "passive Perception 11"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "The zorbo has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The zorbo magically absorbs the natural strength of its surroundings, adjusting\
    \ its Armor Class based on the material it is standing or climbing on: AC 15 for\
    \ wood or bone, AC 17 for earth or stone, or AC 19 for metal. If the zorbo isn't\
    \ in contact with any of these substances, its AC is 10."
  "name": "Natural Armor"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 8 (2d6\
    \ + 1) slashing damage, and if the target is a creature wearing armor, carrying\
    \ a shield, or in possession of a magic item that improves its AC, it must make\
    \ a DC 11 Dexterity saving throw. On a failed save, one such item worn or carried\
    \ by the creature (the target's choice) magically deteriorates, taking a permanent\
    \ and cumulative −1 penalty to the AC it offers, and the zorbo gains a +1 bonus\
    \ to AC until the start of its next turn. Armor reduced to an AC of 10 or a shield\
    \ or magic item that drops to a 0 AC increase is destroyed."
  "name": "Destructive Claws"
"source":
- "ToA"
"image": "/2-Mechanics/CLI/bestiary/monstrosity/token/zorbo.png"
```
^statblock

```encounter-table
name: Zorbo
creatures:
 - 1: Zorbo
```