---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/4
- monster/environment/arctic
- monster/environment/forest
- monster/environment/mountain
- monster/environment/swamp
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
aliases: ["Warlock of the Archfey"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 255, Volo's Guide to Monsters p. 219
---
# [Warlock of the Archfey](2-Mechanics/CLI/bestiary/humanoid/warlock-of-the-archfey-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 255, Volo's Guide to Monsters p. 219*  

Warlocks of the Archfey gain their powers through magical pacts forged with lords of the Feywild. These warlocks commonly associate with lesser Fey creatures such as [boggles](/2-Mechanics/CLI/bestiary/fey/boggle-mpmm.md), [quicklings](/2-Mechanics/CLI/bestiary/fey/quickling-mpmm.md), and [redcaps](/2-Mechanics/CLI/bestiary/fey/redcap-mpmm.md) (all appear in "this book") or even [satyrs](/2-Mechanics/CLI/bestiary/fey/satyr.md) and [sprites](/2-Mechanics/CLI/bestiary/fey/sprite.md).

## Warlocks

Warlocks gain arcane might through magical pacts with mysterious entities. While some use their abilities to serve the sources of their power, others use them to undermine or even destroy these entities.

```statblock
"name": "Warlock of the Archfey (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "13"
"hp": !!int "67"
"hit_dice": "15d8"
"stats":
- !!int "9"
- !!int "16"
- !!int "11"
- !!int "11"
- !!int "12"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "6"
  "Wisdom": !!int "3"
"skillsaves":
  "Nature": !!int "2"
  "Deception": !!int "6"
  "Arcana": !!int "2"
  "Persuasion": !!int "6"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)"
"senses": "passive Perception 11"
"languages": "any two languages (usually Sylvan)"
"cr": "4"
"traits":
- "desc": "The warlock casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 14): \n\nAt will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md),\
    \ [disguise self](/2-Mechanics/CLI/spells/disguise-self.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)\
    \ (self only), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [speak with\
    \ animals](/2-Mechanics/CLI/spells/speak-with-animals.md)\n\n1/day each: [charm\
    \ person](/2-Mechanics/CLI/spells/charm-person.md), [dimension door](/2-Mechanics/CLI/spells/dimension-door.md),\
    \ [hold monster](/2-Mechanics/CLI/spells/hold-monster.md)"
  "name": "spells"
"actions":
- "desc": "The warlock makes two Rapier attacks, or it uses Bewildering Word twice."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage plus 7 (2d6) piercing damage."
  "name": "Rapier"
- "desc": "The warlock utters a magical bewilderment, targeting one creature it can\
    \ see within 60 feet of it. The target must succeed on a DC 14 Wisdom saving throw\
    \ or take 9 (2d8) psychic damage and have disadvantage on attack rolls until\
    \ the end of the warlock's next turn."
  "name": "Bewildering Word"
"reactions":
- "desc": "In response to taking damage, the warlock turns [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ and teleports, along with any equipment it is wearing or carrying, up to 60\
    \ feet to an unoccupied space it can see. It remains [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ until the start of its next turn or until it attacks, makes a damage roll, or\
    \ casts a spell."
  "name": "Misty Escape (Recharges after a Short or Long Rest)"
"source":
- "MPMM"
- "VGM"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/warlock-of-the-archfey.png"
```
^statblock

```encounter-table
name: Warlock of the Archfey
creatures:
 - 1: Warlock of the Archfey
```

## Environment

arctic, forest, mountain, swamp, urban