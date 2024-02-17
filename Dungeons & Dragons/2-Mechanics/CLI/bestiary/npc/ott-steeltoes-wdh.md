---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Ott Steeltoes"]
NoteIcon: monster
BestiaryType: humanoid (dwarf)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 214
---
# [Ott Steeltoes](2-Mechanics/CLI/bestiary/npc/ott-steeltoes-wdh.md)
*Source: Waterdeep: Dragon Heist p. 214*  

The dwarf Ott Steeltoes has the nerve-wracking task of tending to Xanathar's pet fish, Sylgar. In his spare time, he worships Zuggtmoy, the demon queen of fungi, and cultivates mushrooms, spores, and molds. He wears a leather skullcap stitched with fake beholder eyestalks.

```statblock
"name": "Ott Steeltoes (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "12"
- !!int "10"
- !!int "6"
- !!int "11"
- !!int "10"
"speed": "25 ft."
"skillsaves":
  "Deception": !!int "2"
  "Religion": !!int "0"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Dwarvish"
"cr": "1/8"
"traits":
- "desc": "Ott has advantage on saving throws against poison and resistance to poison\
    \ damage."
  "name": "Dwarven Resilience"
- "desc": "The cultist has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Dark Devotion"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one creature. Hit: 4 (1d6\
    \ + 1) slashing damage."
  "name": "Scimitar"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/npc/token/ott-steeltoes.png"
```
^statblock

```encounter-table
name: Ott Steeltoes
creatures:
 - 1: Ott Steeltoes
```