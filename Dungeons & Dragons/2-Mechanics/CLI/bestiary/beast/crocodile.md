---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/1-2
- monster/environment/swamp
- monster/environment/urban
- monster/size/large
- monster/type/beast
aliases: ["Crocodile"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 320, Hoard of the Dragon Queen, Princes of the Apocalypse, Tomb of Annihilation, Ghosts of Saltmarsh, The Wild Beyond the Witchlight. Available in the SRD and the Basic Rules.
---
# [Crocodile](2-Mechanics/CLI/bestiary/beast/crocodile.md)
*Source: Monster Manual p. 320, Hoard of the Dragon Queen, Princes of the Apocalypse, Tomb of Annihilation, Ghosts of Saltmarsh, The Wild Beyond the Witchlight. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Crocodile"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"stats":
- !!int "15"
- !!int "10"
- !!int "13"
- !!int "2"
- !!int "10"
- !!int "5"
"speed": "20 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "2"
"senses": "passive Perception 10"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "The crocodile can hold its breath for 15 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 7 (1d10\
    \ + 2) piercing damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 12). Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and the crocodile can't bite another target"
  "name": "Bite"
"source":
- "MM"
- "HotDQ"
- "PotA"
- "ToA"
- "GoS"
- "DIP"
- "SLW"
- "IMR"
- "EGW"
- "WBtW"
- "PSX"
- "PSA"
"image": "/2-Mechanics/CLI/bestiary/beast/token/crocodile.png"
```
^statblock

```encounter-table
name: Crocodile
creatures:
 - 1: Crocodile
```

## Environment

swamp, urban