---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/0
- monster/size/small
- monster/type/plant
aliases: ["Stool"]
NoteIcon: monster
BestiaryType: plant
SourceType: Bestiary
BookSource: Out of the Abyss p. 7
---
# [Stool](2-Mechanics/CLI/bestiary/npc/stool-oota.md)
*Source: Out of the Abyss p. 7*  

```statblock
"name": "Stool (OotA)"
"size": "Small"
"type": "plant"
"alignment": "Lawful Neutral"
"ac": !!int "10"
"hp": !!int "7"
"hit_dice": "2d6"
"stats":
- !!int "8"
- !!int "10"
- !!int "10"
- !!int "8"
- !!int "11"
- !!int "5"
"speed": "10 ft."
"senses": "darkvision 120 ft., passive Perception 10"
"languages": ""
"cr": "0"
"traits":
- "desc": "When Stool takes damage, all other myconids within 240 feet of it can sense\
    \ its pain."
  "name": "Distress Spores"
- "desc": "While in sunlight, Stool has disadvantage on ability checks, attack rolls,\
    \ and saving throws. Stool dies if it spends more than 1 hour in direct sunlight."
  "name": "Sun Sickness"
"actions":
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one target. Hit: 1 (1d4\
    \ - 1) bludgeoning damage plus 2 (1d4) poison damage."
  "name": "Fist"
- "desc": "A 10-foot radius of spores extends from Stool. These spores can go around\
    \ corners and affect only creatures with an Intelligence of 2 or higher that aren't\
    \ undead, constructs, or elementals. Affected creatures can communicate telepathically\
    \ with one another while they are within 30 feet of each other. The effect lasts\
    \ for 1 hour."
  "name": "Rapport Spores (3/Day)"
"source":
- "OotA"
"image": "/2-Mechanics/CLI/bestiary/npc/token/stool.png"
```
^statblock

```encounter-table
name: Stool
creatures:
 - 1: Stool
```