---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/0
- monster/environment/hill
- monster/environment/swamp
- monster/environment/urban
- monster/size/tiny
- monster/type/beast
aliases: ["Raven"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 335, Curse of Strahd, Icewind Dale: Rime of the Frostmaiden, Candlekeep Mysteries, The Wild Beyond the Witchlight, Keys from the Golden Vault. Available in the SRD and the Basic Rules.
---
# [Raven](2-Mechanics/CLI/bestiary/beast/raven.md)
*Source: Monster Manual p. 335, Curse of Strahd, Icewind Dale: Rime of the Frostmaiden, Candlekeep Mysteries, The Wild Beyond the Witchlight, Keys from the Golden Vault. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Raven"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "2"
- !!int "14"
- !!int "8"
- !!int "2"
- !!int "12"
- !!int "6"
"speed": "10 ft., fly 50 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "0"
"traits":
- "desc": "The raven can mimic simple sounds it has heard, such as a person whispering,\
    \ a baby crying, or an animal chittering. A creature that hears the sounds can\
    \ tell they are imitations with a successful DC 10 Wisdom (Insight) check."
  "name": "Mimicry"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 1 piercing\
    \ damage."
  "name": "Beak"
"source":
- "MM"
- "CoS"
- "IDRotF"
- "CM"
- "WBtW"
- "KftGV"
"image": "/2-Mechanics/CLI/bestiary/beast/token/raven.png"
```
^statblock

```encounter-table
name: Raven
creatures:
 - 1: Raven
```

## Environment

swamp, hill, urban