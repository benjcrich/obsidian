---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/1-4
- monster/size/large
- monster/type/monstrosity
aliases: ["Bone Whelk"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 119
---
# [Bone Whelk](2-Mechanics/CLI/bestiary/monstrosity/bone-whelk-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 119*  

Bone whelks are large mollusks that excrete an adhesive to attach skulls, bones, and other detritus to their bodies for protection.

```statblock
"name": "Bone Whelk (BGDIA)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "27"
"hit_dice": "5d10"
"stats":
- !!int "10"
- !!int "5"
- !!int "11"
- !!int "6"
- !!int "9"
- !!int "3"
"speed": "15 ft., climb 15 ft."
"senses": "darkvision 60 ft., passive Perception 9"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The bone whelk can cause Medium or smaller objects to adhere to it. A Medium\
    \ or smaller creature that touches the bone whelk is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by it (escape DC 10)."
  "name": "Adhesive"
- "desc": "When the bone whelk dies, it emits a blood-curdling shriek than can be\
    \ heard out to a range of 120 feet. This shriek causes nonmagical, organic material\
    \ within 10 feet of the bone whelk to rot. Each creature within 10 feet of the\
    \ bone whelk when it dies takes 9 (2d8) necrotic damage."
  "name": "Death Scream"
- "desc": "The bone whelk can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one creature. Hit: 4 (1d8)\
    \ piercing damage."
  "name": "Bite"
"source":
- "BGDIA"
"image": "/2-Mechanics/CLI/bestiary/monstrosity/token/bone-whelk.png"
```
^statblock

```encounter-table
name: Bone Whelk
creatures:
 - 1: Bone Whelk
```