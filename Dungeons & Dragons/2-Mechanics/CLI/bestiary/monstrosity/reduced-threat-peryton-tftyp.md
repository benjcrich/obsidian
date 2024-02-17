---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/medium
- monster/type/monstrosity
aliases: ["Reduced-Threat Peryton"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 113
---
# [Reduced-Threat Peryton](2-Mechanics/CLI/bestiary/monstrosity/reduced-threat-peryton-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Peryton (TftYP)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "16"
- !!int "12"
- !!int "13"
- !!int "9"
- !!int "12"
- !!int "10"
"speed": "20 ft., fly 60 ft."
"skillsaves":
  "Perception": !!int "5"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "passive Perception 15"
"languages": "understands Common and Elvish but can't speak"
"cr": "2"
"traits":
- "desc": "If the peryton is flying and dives at least 30 feet straight toward a target\
    \ and then hits it with a melee weapon attack, the attack deals an extra 9 (2d8)\
    \ damage to the target."
  "name": "Dive Attack"
- "desc": "The peryton doesn't provoke an opportunity attack when it flies out of\
    \ an enemy's reach."
  "name": "Flyby"
- "desc": "The peryton has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on sight or smell."
  "name": "Keen Sight and Smell"
"actions":
- "desc": "The peryton makes one gore attack and one talon attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage."
  "name": "Gore"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (2d4\
    \ + 3) piercing damage."
  "name": "Talons"
"source":
- "TftYP"
"image": "/2-Mechanics/CLI/bestiary/monstrosity/token/reduced-threat-peryton.png"
```
^statblock

```encounter-table
name: Reduced-Threat Peryton
creatures:
 - 1: Reduced-Threat Peryton
```