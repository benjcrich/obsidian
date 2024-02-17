---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/1-8
- monster/environment/arctic
- monster/environment/coastal
- monster/environment/desert
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/environment/swamp
- monster/environment/underdark
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Tribal Warrior"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Monster Manual p. 350, Princes of the Apocalypse, The Rise of Tiamat, Storm King's Thunder, Tales from the Yawning Portal, Tomb of Annihilation, Ghosts of Saltmarsh, Mythic Odysseys of Theros, Icewind Dale: Rime of the Frostmaiden. Available in the SRD.
---
# [Tribal Warrior](2-Mechanics/CLI/bestiary/humanoid/tribal-warrior.md)
*Source: Monster Manual p. 350, Princes of the Apocalypse, The Rise of Tiamat, Storm King's Thunder, Tales from the Yawning Portal, Tomb of Annihilation, Ghosts of Saltmarsh, Mythic Odysseys of Theros, Icewind Dale: Rime of the Frostmaiden. Available in the SRD.*  

Tribal warriors live beyond civilization, most often subsisting on fishing and hunting. Each tribe acts in accordance with the wishes of its chief, who is the greatest or oldest warrior of the tribe or a tribe member blessed by the gods.

```statblock
"name": "Tribal Warrior"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "13"
- !!int "11"
- !!int "12"
- !!int "8"
- !!int "11"
- !!int "8"
"speed": "30 ft."
"senses": "passive Perception 10"
"languages": "any one language"
"cr": "1/8"
"traits":
- "desc": "The warrior has advantage on an attack roll against a creature if at least\
    \ one of the warrior's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d6 + 1) piercing damage, or 5 (1d8 + 1) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
"source":
- "MM"
- "PotA"
- "RoT"
- "SKT"
- "TftYP"
- "ToA"
- "GoS"
- "EGW"
- "MOT"
- "IDRotF"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/tribal-warrior.png"
```
^statblock

```encounter-table
name: Tribal Warrior
creatures:
 - 1: Tribal Warrior
```

## Environment

coastal, mountain, grassland, hill, arctic, forest, swamp, underdark, desert