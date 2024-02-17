---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Soluun Xibrindas"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 202
---
# [Soluun Xibrindas](2-Mechanics/CLI/bestiary/npc/soluun-xibrindas-wdh.md)
*Source: Waterdeep: Dragon Heist p. 202*  

Soluun is a sadistic, fanatical bully who is fiercely loyal to Bregan D'aerthe, and to Jarlaxle in particular. His younger brother, Nar'l, has infiltrated the Xanathar Guild. Soluun considers Nar'l a weakling who turned to arcane magic by way of compensation, and he has never had much faith in his brother or his abilities.

Soluun has a burning hatred of surface elves and halfelves, having been taught from a young age to kill them as opportunity permits. When not engaged in a Bregan D'aerthe operation, Soluun spends his nights haunting the darkened streets and alleys of Waterdeep, looking for solitary elves or half-elves to pick off. He conceals his nighttime escapades as well as he can, but Jarlaxle, Fel'rekt, and Krebbyg know what he's up to.

```statblock
"name": "Soluun Xibrindas (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Lawful Evil"
"ac": !!int "18"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"stats":
- !!int "13"
- !!int "18"
- !!int "14"
- !!int "11"
- !!int "13"
- !!int "14"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "6"
  "Wisdom": !!int "3"
  "Constitution": !!int "4"
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "3"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Elvish, Undercommon"
"cr": "4"
"traits":
- "desc": "Soluun's spellcasting ability is Charisma. It can innately cast the following\
    \ spells, requiring no material components:\n\nAt will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\
    \n1/day each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md) (self only)"
  "name": "innate"
- "desc": "Soluun has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put Soluun to sleep."
  "name": "Fey Ancestry"
- "desc": "Being within 5 feet of a hostile creature or attacking at long range doesn't\
    \ impose disadvantage on Soluun's ranged attack rolls with a pistol. In addition,\
    \ Soluun ignores half cover and three-quarters cover when making ranged attacks\
    \ with a pistol."
  "name": "Gunslinger"
- "desc": "While in sunlight, Soluun has disadvantage on attack rolls, as well as\
    \ on Wisdom (Perception) checks that rely on sight."
  "name": "Sunlight Sensitivity"
- "desc": "Four packets of smokepowder and a pouch containing 20 pistol bullets"
  "name": "Equipment"
- "desc": "Whilst wearing these boots Soluun's steps make no sound and he has advantage\
    \ on any Dexterity (Stealth) checks that rely on moving silently."
  "name": "Boots of Elvenkind"
"actions":
- "desc": "Soluun makes two scimitar attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) slashing damage."
  "name": "Scimitar"
- "desc": "Ranged Weapon Attack: +6 to hit, range 30/90 ft., one target. Hit:\
    \ 9 (1d10 + 4) piercing damage plus 11 (2d10) poison damage."
  "name": "Poisonous Pistol"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/npc/token/soluun-xibrindas.png"
```
^statblock

```encounter-table
name: Soluun Xibrindas
creatures:
 - 1: Soluun Xibrindas
```