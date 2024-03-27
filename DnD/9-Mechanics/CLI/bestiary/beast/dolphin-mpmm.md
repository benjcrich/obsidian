---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/1-8
- monster/environment/coastal
- monster/environment/underwater
- monster/size/medium
- monster/type/beast
aliases: ["Dolphin"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 97, Volo's Guide to Monsters p. 208
---
# [Dolphin](2-Mechanics/CLI/bestiary/beast/dolphin-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 97, Volo's Guide to Monsters p. 208*  

Dolphins are symbols of wisdom and playfulness among the sea folk of many worlds. Found in oceans and in the Elemental Plane of Water, dolphins are befriended by druids and rangers, and many tales speak of dolphins that appeared out of nowhere to protect swimmers from sharks and other aquatic predators.

## Dolphins

Dolphins are clever, social marine mammals that feed on small fish and squid. An adult specimen is between 5 and 6 feet long.

```statblock
"name": "Dolphin (MPMM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "14"
- !!int "13"
- !!int "13"
- !!int "6"
- !!int "12"
- !!int "7"
"speed": "0 ft., swim 60 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "blindsight 60 ft., passive Perception 13"
"languages": ""
"cr": "1/8"
"traits":
- "desc": "The dolphin can hold its breath for 20 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage. If the dolphin moved at least 30 feet straight toward\
    \ the target immediately before the hit, the target takes an extra 3 (1d6) bludgeoning\
    \ damage."
  "name": "Slam"
"source":
- "MPMM"
- "VGM"
"image": "/2-Mechanics/CLI/bestiary/beast/token/dolphin.png"
```
^statblock

```encounter-table
name: Dolphin
creatures:
 - 1: Dolphin
```

## Environment

coastal, underwater