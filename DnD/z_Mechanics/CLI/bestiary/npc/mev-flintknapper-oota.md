---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Mev Flintknapper"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Out of the Abyss p. 103
---
# [Mev Flintknapper](2-Mechanics/CLI/bestiary/npc/mev-flintknapper-oota.md)
*Source: Out of the Abyss p. 103*  

```statblock
"name": "Mev Flintknapper (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "17"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"stats":
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "5"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "3"
"actions":
- "desc": "Mev makes two longsword attacks. If it has a shortsword drawn, it can also\
    \ make a shortsword attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
  "name": "Longsword"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. Hit:\
    \ 6 (1d10 + 1) piercing damage."
  "name": "Heavy Crossbow"
"source":
- "OotA"
"image": "/2-Mechanics/CLI/bestiary/npc/token/mev-flintknapper.png"
```
^statblock

```encounter-table
name: Mev Flintknapper
creatures:
 - 1: Mev Flintknapper
```