---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Copper Stormforge"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 30
---
# [Copper Stormforge](2-Mechanics/CLI/bestiary/npc/copper-stormforge-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 30*  

Scouts are skilled hunters and trackers who offer their services for a fee. Most hunt wild game, but a few work as bounty hunters, serve as guides, or provide military reconnaissance.

```statblock
"name": "Copper Stormforge (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "11"
- !!int "14"
- !!int "12"
- !!int "11"
- !!int "13"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Nature": !!int "4"
  "Stealth": !!int "6"
  "Perception": !!int "5"
  "Survival": !!int "5"
"senses": "passive Perception 15"
"languages": "any one language (usually Common)"
"cr": "1/2"
"traits":
- "desc": "Copper has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or sight."
  "name": "Keen Hearing and Sight"
"actions":
- "desc": "Copper makes two melee attacks or two ranged attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +4 to hit, ranged 150/600 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Longbow"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/npc/token/copper-stormforge.png"
```
^statblock

```encounter-table
name: Copper Stormforge
creatures:
 - 1: Copper Stormforge
```