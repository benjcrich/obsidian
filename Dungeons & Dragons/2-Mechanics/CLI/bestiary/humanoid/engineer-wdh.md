---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/1-4
- monster/size/small
- monster/type/humanoid/rock-gnome
aliases: ["Engineer"]
NoteIcon: monster
BestiaryType: humanoid (Rock gnome)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 141
---
# [Engineer](2-Mechanics/CLI/bestiary/humanoid/engineer-wdh.md)
*Source: Waterdeep: Dragon Heist p. 141*  

An engineer who maintains and operates the Scarlet Marpenoth, a submarine, currently attached below Jarlaxle's flagship the Eyecatcher

```statblock
"name": "Engineer (WDH)"
"size": "Small"
"type": "humanoid"
"subtype": "Rock gnome"
"alignment": "Neutral Good"
"ac": !!int "10"
"hp": !!int "7"
"hit_dice": "2d6"
"stats":
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "14"
- !!int "10"
- !!int "11"
"speed": "25 ft."
"skillsaves":
  "History": !!int "4"
  "Arcana": !!int "4"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Gnomish"
"cr": "1/4"
"traits":
- "desc": "The gnome is a 1st-level spellcaster. Its spellcasting ability is Intelligence.\
    \ It has the following wizard spells prepared:\n\nCantrips (at will): [fire\
    \ bolt](/2-Mechanics/CLI/spells/fire-bolt.md), [mending](/2-Mechanics/CLI/spells/mending.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\n1st level\
    \ (2 slots): [burning hands](/2-Mechanics/CLI/spells/burning-hands.md), [disguise\
    \ self](/2-Mechanics/CLI/spells/disguise-self.md), [shield](/2-Mechanics/CLI/spells/shield.md)"
  "name": "spells"
- "desc": "The gnome has advantage on all Intelligence, Wisdom and Charisma saving\
    \ throws against magic."
  "name": "Gnome Cunning"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ piercing damage. Or Ranged Weapon Attack: +2 to hit, range 20/60 ft., one target.\
    \ Hit: 2 (1d4) piercing damage."
  "name": "Dagger"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/engineer.png"
```
^statblock

```encounter-table
name: Engineer
creatures:
 - 1: Engineer
```