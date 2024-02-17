---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/0
- monster/size/tiny
- monster/type/beast
aliases: ["Crow"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 302
---
# [Crow](2-Mechanics/CLI/bestiary/beast/crow-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 302*  

```statblock
"name": "Crow (WDMM)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "2"
- !!int "14"
- !!int "8"
- !!int "2"
- !!int "12"
- !!int "6"
"speed": "10 ft., fly 50 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "0"
"traits":
- "desc": "The crow can mimic simple sounds it has heard, such as a person whispering,\
    \ a baby crying, or an animal chittering. A creature that hears the sounds can\
    \ tell they are imitations with a successful DC 10 Wisdom (Insight) check."
  "name": "Mimicry"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 1 piercing\
    \ damage."
  "name": "Beak"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/beast/token/crow.png"
```
^statblock

```encounter-table
name: Crow
creatures:
 - 1: Crow
```