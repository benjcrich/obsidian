---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/5
- monster/environment/underwater
- monster/size/huge
- monster/type/beast
aliases: ["Giant Shark"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 328, Storm King's Thunder, Tomb of Annihilation, Ghosts of Saltmarsh, Icewind Dale: Rime of the Frostmaiden, Journeys through the Radiant Citadel, Dragonlance: Shadow of the Dragon Queen. Available in the SRD and the Basic Rules.
---
# [Giant Shark](2-Mechanics/CLI/bestiary/beast/giant-shark.md)
*Source: Monster Manual p. 328, Storm King's Thunder, Tomb of Annihilation, Ghosts of Saltmarsh, Icewind Dale: Rime of the Frostmaiden, Journeys through the Radiant Citadel, Dragonlance: Shadow of the Dragon Queen. Available in the SRD and the Basic Rules.*  

A giant shark is 30 feet long and normally found in deep oceans. Utterly fearless, it preys on anything that crosses its path, including whales and ships.

```statblock
"name": "Giant Shark"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "126"
"hit_dice": "11d12 + 55"
"stats":
- !!int "23"
- !!int "11"
- !!int "21"
- !!int "1"
- !!int "10"
- !!int "5"
"speed": "swim 50 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "blindsight 60 ft., passive Perception 13"
"languages": ""
"cr": "5"
"traits":
- "desc": "The shark has advantage on melee attack rolls against any creature that\
    \ doesn't have all its hit points."
  "name": "Blood Frenzy"
- "desc": "The shark can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 22 (3d10\
    \ + 6) piercing damage."
  "name": "Bite"
"source":
- "MM"
- "SKT"
- "ToA"
- "GoS"
- "DIP"
- "SDW"
- "LR"
- "IDRotF"
- "CRCotN"
- "JttRC"
- "DSotDQ"
- "PSX"
"image": "/2-Mechanics/CLI/bestiary/beast/token/giant-shark.png"
```
^statblock

```encounter-table
name: Giant Shark
creatures:
 - 1: Giant Shark
```

## Environment

underwater