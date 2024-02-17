---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/3
- monster/size/medium
- monster/type/fey
aliases: ["Nanny Pu'pu"]
NoteIcon: monster
BestiaryType: fey
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 72
---
# [Nanny Pu'pu](2-Mechanics/CLI/bestiary/npc/nanny-pupu-toa.md)
*Source: Tomb of Annihilation p. 72*  

```statblock
"name": "Nanny Pu'pu (ToA)"
"size": "Medium"
"type": "fey"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"stats":
- !!int "18"
- !!int "12"
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "4"
  "Stealth": !!int "3"
  "Perception": !!int "4"
  "Arcana": !!int "3"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Draconic, Sylvan"
"cr": "3"
"traits":
- "desc": "Pu'pu's innate spellcasting ability is Charisma (spell save DC 12). She\
    \ can innately cast the following spells, requiring no material components:\n\n\
    At will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md), [minor\
    \ illusion](/2-Mechanics/CLI/spells/minor-illusion.md), [vicious mockery](/2-Mechanics/CLI/spells/vicious-mockery.md)"
  "name": "innate"
- "desc": "Pu'pu can breathe air and water."
  "name": "Amphibious"
- "desc": "Pu'pu can mimic animal sounds and humanoid voices. A creature that hears\
    \ the sounds can tell they are imitations with a successful DC 14 Wisdom (Insight)\
    \ check."
  "name": "Mimicry"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13 (2d8\
    \ + 4) slashing damage."
  "name": "Claws"
- "desc": "Pu'pu covers herself and anything she is wearing or carrying with a magical\
    \ illusion that makes her look like another creature of her general size and humanoid\
    \ shape. The illusion ends if Pu'pu takes a bonus action to end it or if she dies.\n\
    \nThe changes wrought by this effect fail to hold up to physical inspection. For\
    \ example, Pu'pu could appear to have smooth skin, but someone touching her would\
    \ feel her rough flesh. Otherwise, a creature must take an action to visually\
    \ inspect the illusion and succeed on a DC 20 Intelligence (Investigation) check\
    \ to discern that Pu'pu is disguised."
  "name": "Illusory Appearance"
- "desc": "Pu'pu magically turns [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ until she attacks or casts a spell, or until her [concentration](/2-Mechanics/CLI/rules/conditions.md#concentration)\
    \ ends (as if concentrating on a spell). While [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible),\
    \ she leaves no physical evidence of her passage, so she can be tracked only by\
    \ magic. Any equipment she wears or carries is [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ with her."
  "name": "Invisible Passage"
"source":
- "ToA"
"image": "/2-Mechanics/CLI/bestiary/npc/token/nanny-pupu.png"
```
^statblock

```encounter-table
name: Nanny Pu'pu
creatures:
 - 1: Nanny Pu'pu
```