---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/1-2
- monster/environment/underwater
- monster/size/medium
- monster/type/beast
aliases: ["Reef Shark"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 336, Tomb of Annihilation, Ghosts of Saltmarsh, Journeys through the Radiant Citadel. Available in the SRD and the Basic Rules.
---
# [Reef Shark](2-Mechanics/CLI/bestiary/beast/reef-shark.md)
*Source: Monster Manual p. 336, Tomb of Annihilation, Ghosts of Saltmarsh, Journeys through the Radiant Citadel. Available in the SRD and the Basic Rules.*  

Smaller than giant sharks and hunter sharks, reef sharks inhabit shallow waters and coral reefs, gathering in small packs to hunt. A full-grown specimen measures 6 to 10 feet long.

```statblock
"name": "Reef Shark"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"stats":
- !!int "14"
- !!int "13"
- !!int "13"
- !!int "1"
- !!int "10"
- !!int "4"
"speed": "swim 40 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "blindsight 30 ft., passive Perception 12"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "The shark has advantage on an attack roll against a creature if at least\
    \ one of the shark's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
- "desc": "The shark can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) piercing damage."
  "name": "Bite"
"source":
- "MM"
- "ToA"
- "GoS"
- "EGW"
- "CRCotN"
- "JttRC"
"image": "/2-Mechanics/CLI/bestiary/beast/token/reef-shark.png"
```
^statblock

```encounter-table
name: Reef Shark
creatures:
 - 1: Reef Shark
```

## Environment

underwater