---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/0
- monster/environment/underwater
- monster/size/tiny
- monster/type/beast
aliases: ["Quipper"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 335, Princes of the Apocalypse, Tomb of Annihilation, Ghosts of Saltmarsh, Mythic Odysseys of Theros, Icewind Dale: Rime of the Frostmaiden. Available in the SRD and the Basic Rules.
---
# [Quipper](2-Mechanics/CLI/bestiary/beast/quipper.md)
*Source: Monster Manual p. 335, Princes of the Apocalypse, Tomb of Annihilation, Ghosts of Saltmarsh, Mythic Odysseys of Theros, Icewind Dale: Rime of the Frostmaiden. Available in the SRD and the Basic Rules.*  

A quipper is a carnivorous fish with sharp teeth.

Quippers can adapt to any aquatic environment, including cold subterranean lakes. They frequently gather in swarms; the statistics for a swarm of quippers appear later in this appendix.

```statblock
"name": "Quipper"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "2"
- !!int "16"
- !!int "9"
- !!int "1"
- !!int "7"
- !!int "2"
"speed": "swim 40 ft."
"senses": "darkvision 60 ft., passive Perception 8"
"languages": ""
"cr": "0"
"traits":
- "desc": "The quipper has advantage on melee attack rolls against any creature that\
    \ doesn't have all its hit points."
  "name": "Blood Frenzy"
- "desc": "The quipper can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 1 piercing\
    \ damage."
  "name": "Bite"
"source":
- "MM"
- "PotA"
- "ToA"
- "GoS"
- "MOT"
- "IDRotF"
- "CRCotN"
- "PSA"
- "ToFW"
"image": "/2-Mechanics/CLI/bestiary/beast/token/quipper.png"
```
^statblock

```encounter-table
name: Quipper
creatures:
 - 1: Quipper
```

## Environment

underwater