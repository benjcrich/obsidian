---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Enna Galakiir (Levels 5-8)"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 8
---
# [Enna Galakiir (Levels 5-8)](2-Mechanics/CLI/bestiary/npc/enna-galakiir-levels-5-8-kftgv.md)
*Source: Keys from the Golden Vault p. 8*  

```statblock
"name": "Enna Galakiir (Levels 5-8) (KftGV)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "27"
"hit_dice": "6d8"
"stats":
- !!int "10"
- !!int "15"
- !!int "10"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Sleight of Hand": !!int "4"
  "Deception": !!int "5"
  "Stealth": !!int "4"
  "Investigation": !!int "5"
  "Insight": !!int "4"
  "Perception": !!int "6"
  "Persuasion": !!int "5"
"senses": "passive Perception 16"
"languages": "any two languages"
"cr": "1"
"traits":
- "desc": "On each of its turns, Enna Galakiir can use a bonus action to take the\
    \ Dash, Disengage, or Hide action."
  "name": "Cunning Action"
- "desc": "Enna Galakiir deals an extra 7 (2d6) damage when it hits a target with\
    \ a weapon attack and has advantage on the attack roll, or when the target is\
    \ within 5 feet of an ally of Enna Galakiir that isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ and Enna Galakiir doesn't have disadvantage on the attack roll."
  "name": "Sneak Attack (1/Turn)"
"actions":
- "desc": "Enna Galakiir makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage."
  "name": "Hand Crossbow"
"source":
- "KftGV"
"image": "/2-Mechanics/CLI/bestiary/npc/token/enna-galakiir-levels-5-8.png"
```
^statblock

```encounter-table
name: Enna Galakiir (Levels 5-8)
creatures:
 - 1: Enna Galakiir (Levels 5-8)
```