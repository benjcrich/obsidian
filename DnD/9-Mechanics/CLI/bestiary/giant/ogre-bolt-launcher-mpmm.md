---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/2
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/size/large
- monster/type/giant
aliases: ["Ogre Bolt Launcher"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 200, Mordenkainen's Tome of Foes p. 220
---
# [Ogre Bolt Launcher](2-Mechanics/CLI/bestiary/giant/ogre-bolt-launcher-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 200, Mordenkainen's Tome of Foes p. 220*  

A bolt launcher carries a gigantic crossbow—a weapon so large it's essentially an ogre-held ballista. An ogre bolt launcher can load this immense weapon and loose its deadly missile as quickly as a dwarf handles a crossbow. The bolts are so large that few ogres can carry more than a half dozen at a time, but bolt launchers have been known to uproot small trees or tear beams out of buildings and launch those when their ammunition runs low.

## Ogres of War

Ogres love to rush headlong into battle, but with enough time and patience, some of them learn to carry out specialized missions. The names they are given—the battering ram, the bolt launcher, the chain brute, and the howdah—reflect their particular functions. These jobs are tailored to take advantage of an ogre's strengths.

```statblock
"name": "Ogre Bolt Launcher (MPMM)"
"size": "Large"
"type": "giant"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "13"
"hp": !!int "59"
"hit_dice": "7d10 + 21"
"stats":
- !!int "19"
- !!int "12"
- !!int "16"
- !!int "5"
- !!int "7"
- !!int "7"
"speed": "40 ft."
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "Common, Giant"
"cr": "2"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (2d4\
    \ + 4) bludgeoning damage."
  "name": "Fist"
- "desc": "Ranged Weapon Attack: +3 to hit, range 120/480 ft., one target. Hit:\
    \ 17 (3d10 + 1) piercing damage."
  "name": "Bolt Launcher"
"source":
- "MPMM"
- "MTF"
"image": "/2-Mechanics/CLI/bestiary/giant/token/ogre-bolt-launcher.png"
```
^statblock

```encounter-table
name: Ogre Bolt Launcher
creatures:
 - 1: Ogre Bolt Launcher
```

## Environment

grassland, hill, mountain