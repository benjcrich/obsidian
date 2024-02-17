---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/2
- monster/size/large
- monster/type/giant
aliases: ["Fewmaster Gholcag"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 74
---
# [Fewmaster Gholcag](2-Mechanics/CLI/bestiary/npc/fewmaster-gholcag-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 74*  

Fewmaster Gholcag is a low-ranking commander in the Red Dragon Army and the leader of the raid on Vogler.

Ogres are hulking giants notorious for their quick tempers. When its rage is incited, an ogre lashes out in a frustrated tantrum until it runs out of objects or creatures to smash.

```statblock
"name": "Fewmaster Gholcag (DSotDQ)"
"size": "Large"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "59"
"hit_dice": "7d10 + 21"
"stats":
- !!int "19"
- !!int "8"
- !!int "16"
- !!int "5"
- !!int "7"
- !!int "7"
"speed": "40 ft."
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "Common, Giant"
"cr": "2"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13 (2d8\
    \ + 4) bludgeoning damage."
  "name": "Greatclub"
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 11 (2d6 + 4) piercing damage."
  "name": "Javelin"
"source":
- "DSotDQ"
"image": "/2-Mechanics/CLI/bestiary/npc/token/fewmaster-gholcag.png"
```
^statblock

```encounter-table
name: Fewmaster Gholcag
creatures:
 - 1: Fewmaster Gholcag
```