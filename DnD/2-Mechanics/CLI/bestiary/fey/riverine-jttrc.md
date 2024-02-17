---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/12
- monster/size/large
- monster/type/fey
aliases: ["Riverine"]
NoteIcon: monster
BestiaryType: fey
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 133
---
# [Riverine](2-Mechanics/CLI/bestiary/fey/riverine-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 133*  

More than mere waterway guardians, riverines are embodiments of particular rivers. These spirits of nature take shape to defend their waters and interact with those who travel along their currents. From the waist up, riverines have skin the color of the waters they protect but are otherwise humanlike in appearance. From the waist down, they can manifest either humanlike legs or churning gouts of water. A riverine's personality reflects the nature of the river it arises from—some are lethargic while others are wild and reckless.

## A Riverine's Lair

Some riverines enjoy reverence akin to worship. Their likenesses are cast as statues and housed in temples, and worshipers act as agents between the river spirits and the people who revere them. These temples often become the home of the riverine itself, serving as its lair, though other nexuses of power along the river's path—such as its source or a significant waterfall—can also be used as lairs by a riverine.

A riverine encountered in its lair has a challenge rating of 13 (10,000 XP).

```statblock
"name": "Riverine (JttRC)"
"size": "Large"
"type": "fey"
"alignment": "Any alignment"
"ac": !!int "14"
"hp": !!int "204"
"hit_dice": "24d10 + 72"
"stats":
- !!int "20"
- !!int "19"
- !!int "17"
- !!int "12"
- !!int "16"
- !!int "21"
"speed": "30 ft., swim 60 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "7"
  "Intelligence": !!int "5"
"skillsaves":
  "Nature": !!int "5"
  "Insight": !!int "7"
  "Perception": !!int "7"
"damage_resistances": "acid, fire"
"senses": "blindsight 60 ft., passive Perception 17"
"languages": "Aquan, Common, Sylvan"
"cr": "12"
"traits":
- "desc": "The riverine casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 17):\n\nAt will:\
    \ [control water](/2-Mechanics/CLI/spells/control-water.md), [fog cloud](/2-Mechanics/CLI/spells/fog-cloud.md)\n\
    \n1/day: [greater restoration](/2-Mechanics/CLI/spells/greater-restoration.md)"
  "name": "spells"
- "desc": "The riverine can breathe air and water."
  "name": "Amphibious"
- "desc": "If the riverine fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
"actions":
- "desc": "The riverine makes two Flood Strike attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 14 (2d8\
    \ + 5) bludgeoning damage plus 10 (3d6) cold damage."
  "name": "Flood Strike"
"bonus_actions":
- "desc": "The riverine magically teleports to an unoccupied space it can see within\
    \ 30 feet of itself. Both the space it leaves and its destination must be in or\
    \ on the surface of water."
  "name": "Whirlpool Step"
"legendary_actions":
- "desc": "The riverine uses its Whirlpool Step. Immediately after it teleports, each\
    \ creature within 5 feet of the riverine's destination space takes 5 (1d10)\
    \ cold damage."
  "name": "Whirlpool Rush"
- "desc": "The riverine unleashes a torrent of river water in a 30-foot line that\
    \ is 5 feet wide. Each creature in that area must make a DC 17 Dexterity saving\
    \ throw. On a failed save, a creature takes 11 (2d10) bludgeoning damage and\
    \ is knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone). On a successful\
    \ save, a creature takes half as much damage and isn't knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Raging Deluge (Costs 2 Actions)"
"source":
- "JttRC"
"image": "/2-Mechanics/CLI/bestiary/fey/token/riverine.png"
```
^statblock

```encounter-table
name: Riverine
creatures:
 - 1: Riverine
```