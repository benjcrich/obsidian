---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/1-2
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/size/large
- monster/type/beast
aliases: ["Giant Goat"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 326, Storm King's Thunder, Icewind Dale: Rime of the Frostmaiden, Curse of Strahd, The Wild Beyond the Witchlight. Available in the SRD and the Basic Rules.
---
# [Giant Goat](2-Mechanics/CLI/bestiary/beast/giant-goat.md)
*Source: Monster Manual p. 326, Storm King's Thunder, Icewind Dale: Rime of the Frostmaiden, Curse of Strahd, The Wild Beyond the Witchlight. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Giant Goat"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"stats":
- !!int "17"
- !!int "11"
- !!int "12"
- !!int "3"
- !!int "12"
- !!int "6"
"speed": "40 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "If the goat moves at least 20 feet straight toward a target and then hits\
    \ it with a ram attack on the same turn, the target takes an extra 5 (2d4) bludgeoning\
    \ damage. If the target is a creature, it must succeed on a DC 13 Strength saving\
    \ throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Charge"
- "desc": "The goat has advantage on Strength and Dexterity saving throws made against\
    \ effects that would knock it [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Sure-Footed"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (2d4\
    \ + 3) bludgeoning damage."
  "name": "Ram"
"source":
- "MM"
- "SKT"
- "SLW"
- "IDRotF"
- "CoS"
- "WBtW"
"image": "/2-Mechanics/CLI/bestiary/beast/token/giant-goat.png"
```
^statblock

```encounter-table
name: Giant Goat
creatures:
 - 1: Giant Goat
```

## Environment

mountain, grassland, hill