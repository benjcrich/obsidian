---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/1-4
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
aliases: ["Apprentice Wizard"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 259, Volo's Guide to Monsters p. 209
---
# [Apprentice Wizard](2-Mechanics/CLI/bestiary/humanoid/apprentice-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 259, Volo's Guide to Monsters p. 209*  

Apprentices are novice arcane spellcasters who serve more experienced wizards or attend school. They perform menial work like cooking or cleaning in exchange for education in the ways of magic.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Apprentice Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "10"
"hp": !!int "13"
"hit_dice": "3d8"
"stats":
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "14"
- !!int "10"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "History": !!int "4"
  "Arcana": !!int "4"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "1/4"
"traits":
- "desc": "The apprentice casts one of the following spells, using Intelligence as\
    \ the spellcasting ability (spell save DC 12)\n\nAt will: [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\n1/day each:\
    \ [burning hands](/2-Mechanics/CLI/spells/burning-hands.md), [disguise self](/2-Mechanics/CLI/spells/disguise-self.md),\
    \ [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
  "name": "spells"
"actions":
- "desc": "Melee or Ranged Spell Attack: +4 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 7 (1d10 + 2) force damage."
  "name": "Arcane Burst"
"source":
- "MPMM"
- "VGM"
- "SjA"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/apprentice-wizard.png"
```
^statblock

```encounter-table
name: Apprentice Wizard
creatures:
 - 1: Apprentice Wizard
```

## Environment

urban