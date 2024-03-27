---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/2
- monster/size/large
- monster/type/giant
aliases: ["Ogre Goblin Hucker"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Storm King's Thunder p. 50
---
# [Ogre Goblin Hucker](2-Mechanics/CLI/bestiary/giant/ogre-goblin-hucker-skt.md)
*Source: Storm King's Thunder p. 50*  

```statblock
"name": "Ogre Goblin Hucker (SKT)"
"size": "Large"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "11"
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
- "desc": "Ranged Weapon Attack: +3 to hit, range 150/600 ft. (can't hit targets\
    \ within 30 feet of the hucker), one target. Hit: 5 (2d4) bludgeoning damage,\
    \ or 10 (4d4) piercing damage if the projectile is wearing a spiked helmet.\
    \ Hit or Miss: The goblin projectile takes 1d6 bludgeoning damage per 10 feet\
    \ it travels through the air (maximum 20d6)."
  "name": "Goblin Projectile"
"source":
- "SKT"
"image": "/2-Mechanics/CLI/bestiary/giant/token/ogre-goblin-hucker.png"
```
^statblock

```encounter-table
name: Ogre Goblin Hucker
creatures:
 - 1: Ogre Goblin Hucker
```