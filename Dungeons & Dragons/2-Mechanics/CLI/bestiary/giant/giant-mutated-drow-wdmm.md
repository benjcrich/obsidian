---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/9
- monster/size/huge
- monster/type/giant
aliases: ["Giant Mutated Drow"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 143
---
# [Giant Mutated Drow](2-Mechanics/CLI/bestiary/giant/giant-mutated-drow-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 143*  

```statblock
"name": "Giant Mutated Drow (WDMM)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral Evil"
"ac": !!int "14"
"hp": !!int "200"
"hit_dice": "16d12 + 96"
"stats":
- !!int "27"
- !!int "10"
- !!int "22"
- !!int "12"
- !!int "16"
- !!int "16"
"speed": "40 ft."
"saves":
  "Charisma": !!int "7"
  "Wisdom": !!int "7"
  "Constitution": !!int "10"
"skillsaves":
  "Insight": !!int "7"
  "Perception": !!int "7"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "Elvish, Undercommon"
"cr": "9"
"traits":
- "desc": "The drow's innate spellcasting ability is Charisma (spell save DC 15).\
    \ The drow can innately cast the following spells, requiring no material components:\n\
    \nAt will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\n\
    1/day each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md)"
  "name": "innate"
- "desc": "The drow has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "The drow has advantage on saving throws against being charmed, and magic\
    \ can't put the drow to sleep."
  "name": "Fey Ancestry"
- "desc": "While in sunlight, the drow has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "The drow makes two morningstar attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 21\
    \ (3d8 + 8) piercing damage."
  "name": "Morningstar"
- "desc": "Ranged Weapon Attack: +12 to hit, range 60/240 ft., one target. Hit:\
    \ 30 (4d10 + 8) bludgeoning damage."
  "name": "Rock"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/giant/token/giant-mutated-drow.png"
```
^statblock

```encounter-table
name: Giant Mutated Drow
creatures:
 - 1: Giant Mutated Drow
```