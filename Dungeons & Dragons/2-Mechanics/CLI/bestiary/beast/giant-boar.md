---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/2
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/size/large
- monster/type/beast
aliases: ["Giant Boar"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 323, Storm King's Thunder, Tomb of Annihilation, Ghosts of Saltmarsh, Mythic Odysseys of Theros. Available in the SRD and the Basic Rules.
---
# [Giant Boar](2-Mechanics/CLI/bestiary/beast/giant-boar.md)
*Source: Monster Manual p. 323, Storm King's Thunder, Tomb of Annihilation, Ghosts of Saltmarsh, Mythic Odysseys of Theros. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Giant Boar"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"stats":
- !!int "17"
- !!int "10"
- !!int "16"
- !!int "2"
- !!int "7"
- !!int "5"
"speed": "40 ft."
"senses": "passive Perception 8"
"languages": ""
"cr": "2"
"traits":
- "desc": "If the boar moves at least 20 feet straight toward a target and then hits\
    \ it with a tusk attack on the same turn, the target takes an extra 7 (2d6)\
    \ slashing damage. If the target is a creature, it must succeed on a DC 13 Strength\
    \ saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Charge"
- "desc": "If the boar takes 10 damage or less that would reduce it to 0 hit points,\
    \ it is reduced to 1 hit point instead."
  "name": "Relentless (Recharges after a Short or Long Rest)"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6\
    \ + 3) slashing damage."
  "name": "Tusk"
"source":
- "MM"
- "SKT"
- "ToA"
- "GoS"
- "MOT"
- "PSI"
- "BMT"
"image": "/2-Mechanics/CLI/bestiary/beast/token/giant-boar.png"
```
^statblock

```encounter-table
name: Giant Boar
creatures:
 - 1: Giant Boar
```

## Environment

grassland, forest, hill