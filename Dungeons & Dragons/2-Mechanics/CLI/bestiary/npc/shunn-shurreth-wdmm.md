---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Shunn Shurreth"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 33
---
# [Shunn Shurreth](2-Mechanics/CLI/bestiary/npc/shunn-shurreth-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 33*  

A drow priestess of Lolth placed a curse on Shunn and forced him into exile after he displeased her. The curse partially transformed him into a spider, giving him eight red arachnid eyes, a mouth full of fangs, and black bristles sprouting from his slender limbs. A remove curse or [greater restoration](/2-Mechanics/CLI/spells/greater-restoration.md) spell restores Shunn's natural form, but Shunn doesn't want the curse lifted. His horrific appearance strikes fear into the hearts of his comrades-in-arms and has earned him favor with Xanathar. Shunn believes that returning to his normal form might weaken his influence over his gang and diminish his status in the Xanathar Guild.

```statblock
"name": "Shunn Shurreth (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Lawful Evil"
"ac": !!int "18"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"stats":
- !!int "13"
- !!int "18"
- !!int "14"
- !!int "11"
- !!int "13"
- !!int "12"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "7"
  "Wisdom": !!int "4"
  "Constitution": !!int "5"
"skillsaves":
  "Stealth": !!int "10"
  "Perception": !!int "4"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Elvish, Undercommon"
"cr": "5"
"traits":
- "desc": "Shunn's spellcasting ability is Charisma (spell save DC 12). It can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\n1/day each:\
    \ [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md) (self only)"
  "name": "innate"
- "desc": "While cursed with spider features, Shunn can climb difficult surfaces,\
    \ even across ceilings, without needing to make an ability check."
  "name": "Spider Features"
- "desc": "Shunn has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put Shunn to sleep."
  "name": "Fey Ancestry"
- "desc": "While in sunlight, Shunn has disadvantage on attack rolls, as well as on\
    \ Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks that\
    \ rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Shunn makes two shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) piercing damage plus 10 (3d6) poison damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +7 to hit, range 30/120 ft., one target. Hit:\
    \ 7 (1d6 + 4) piercing damage, and the target must succeed on a DC 13 Constitution\
    \ saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 hour. If the saving throw fails by 5 or more, the target is also [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)\
    \ while [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) in this way.\
    \ The target wakes up if it takes damage or if another creature takes an action\
    \ to shake it awake."
  "name": "Hand Crossbow"
"reactions":
- "desc": "Shunn adds 3 to its AC against one melee attack that would hit it. To do\
    \ so, Shunn must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/npc/token/shunn-shurreth.png"
```
^statblock

```encounter-table
name: Shunn Shurreth
creatures:
 - 1: Shunn Shurreth
```