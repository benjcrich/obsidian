---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/3
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/size/large
- monster/type/giant
aliases: ["Ogre Chain Brute"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 201, Mordenkainen's Tome of Foes p. 221
---
# [Ogre Chain Brute](2-Mechanics/CLI/bestiary/giant/ogre-chain-brute-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 201, Mordenkainen's Tome of Foes p. 221*  

An ogre chain brute wields a great spiked chain, swinging it with both hands in a wide circle to knock foes off their feet. Alternatively, the ogre can swing the chain in a crushing overhead smash.

## Ogres of War

Ogres love to rush headlong into battle, but with enough time and patience, some of them learn to carry out specialized missions. The names they are given—the battering ram, the bolt launcher, the chain brute, and the howdah—reflect their particular functions. These jobs are tailored to take advantage of an ogre's strengths.

```statblock
"name": "Ogre Chain Brute (MPMM)"
"size": "Large"
"type": "giant"
"alignment": "Typically  Chaotic Evil"
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
"cr": "3"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (2d4\
    \ + 4) bludgeoning damage."
  "name": "Fist"
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 13 (2d8\
    \ + 4) bludgeoning damage, and the target must make a DC 14 Constitution saving\
    \ throw or be [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned) for 1 minute.\
    \ The target repeats the saving throw if it takes damage and at the end of each\
    \ of its turns, ending the effect on itself on a success."
  "name": "Chain Smash (Recharge 6)"
- "desc": "The ogre swings its chain, and every creature within 10 feet of it must\
    \ make a DC 14 Dexterity saving throw. On a failed saving throw, a creature takes\
    \ 8 (1d8 + 4) bludgeoning damage and is knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone).\
    \ On a successful save, the creature takes half as much damage and isn't knocked\
    \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Chain Sweep"
"source":
- "MPMM"
- "MTF"
"image": "/2-Mechanics/CLI/bestiary/giant/token/ogre-chain-brute.png"
```
^statblock

```encounter-table
name: Ogre Chain Brute
creatures:
 - 1: Ogre Chain Brute
```

## Environment

grassland, hill, mountain