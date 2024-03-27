---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/0
- monster/size/medium
- monster/type/humanoid/half-elf
aliases: ["Magister Umbero Zastro"]
NoteIcon: monster
BestiaryType: humanoid (half-elf)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 82
---
# [Magister Umbero Zastro](2-Mechanics/CLI/bestiary/npc/magister-umbero-zastro-wdh.md)
*Source: Waterdeep: Dragon Heist p. 82*  

A handsome, eloquent, and fair-minded half-elf in his thirties. He's known for his finely honed sense of poetic justice and for meting out unconventional punishments.

```statblock
"name": "Magister Umbero Zastro (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf"
"alignment": "Lawful Neutral"
"ac": !!int "11"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "12"
- !!int "11"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Insight": !!int "4"
  "Persuasion": !!int "5"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Elvish"
"cr": "0"
"traits":
- "desc": "Umbero has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ and magic can't put him to sleep."
  "name": "Fey Ancestry"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8\
    \ + 1) piercing damage."
  "name": "Rapier"
"reactions":
- "desc": "The noble adds 2 to its AC against one melee attack that would hit it.\
    \ To do so, the noble must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/npc/token/magister-umbero-zastro.png"
```
^statblock

```encounter-table
name: Magister Umbero Zastro
creatures:
 - 1: Magister Umbero Zastro
```