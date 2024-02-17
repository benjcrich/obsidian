---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Zhentarim Thug"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Out of the Abyss p. 131
---
# [Zhentarim Thug](2-Mechanics/CLI/bestiary/humanoid/zhentarim-thug-oota.md)
*Source: Out of the Abyss p. 131*  

```statblock
"name": "Zhentarim Thug (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral"
"ac": !!int "11"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"stats":
- !!int "15"
- !!int "11"
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "2"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "1/2"
"traits":
- "desc": "The thug has advantage on an attack roll against a creature if at least\
    \ one of the thug's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "The thug makes two melee attacks"
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage."
  "name": "Mace"
- "desc": "Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. Hit:\
    \ 5 (1d10) piercing damage."
  "name": "Heavy Crossbow"
"source":
- "OotA"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/zhentarim-thug.png"
```
^statblock

```encounter-table
name: Zhentarim Thug
creatures:
 - 1: Zhentarim Thug
```