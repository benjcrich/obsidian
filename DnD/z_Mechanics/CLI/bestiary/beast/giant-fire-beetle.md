---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/0
- monster/environment/underdark
- monster/size/small
- monster/type/beast
aliases: ["Giant Fire Beetle"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 325, Tales from the Yawning Portal, Waterdeep: Dragon Heist, Waterdeep: Dungeon of the Mad Mage. Available in the SRD and the Basic Rules.
---
# [Giant Fire Beetle](2-Mechanics/CLI/bestiary/beast/giant-fire-beetle.md)
*Source: Monster Manual p. 325, Tales from the Yawning Portal, Waterdeep: Dragon Heist, Waterdeep: Dungeon of the Mad Mage. Available in the SRD and the Basic Rules.*  

A giant fire beetle is a nocturnal creature that takes its name from a pair of glowing glands that give off light. Miners and adventurers prize these creatures, for a giant fire beetle's glands continue to shed light for `1d6` days after the beetle dies. Giant fire beetles are most commonly found underground and in dark forests.

```statblock
"name": "Giant Fire Beetle"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "4"
"hit_dice": "1d6 + 1"
"stats":
- !!int "8"
- !!int "10"
- !!int "12"
- !!int "1"
- !!int "7"
- !!int "3"
"speed": "30 ft."
"senses": "blindsight 30 ft., passive Perception 8"
"languages": ""
"cr": "0"
"traits":
- "desc": "The beetle sheds bright light in a 10-foot radius and dim light for an\
    \ additional 10 ft.."
  "name": "Illumination"
"actions":
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one target. Hit: 2 (1d6\
    \ - 1) slashing damage."
  "name": "Bite"
"source":
- "MM"
- "TftYP"
- "WDH"
- "WDMM"
- "PSX"
"image": "/2-Mechanics/CLI/bestiary/beast/token/giant-fire-beetle.png"
```
^statblock

```encounter-table
name: Giant Fire Beetle
creatures:
 - 1: Giant Fire Beetle
```

## Environment

underdark