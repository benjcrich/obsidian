---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/gith
aliases: ["Al'chaia"]
NoteIcon: monster
BestiaryType: humanoid (gith)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 218
---
# [Al'chaia](2-Mechanics/CLI/bestiary/npc/alchaia-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 218*  

```statblock
"name": "Al'chaia (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "gith"
"alignment": "Lawful Evil"
"ac": !!int "18"
"hp": !!int "91"
"hit_dice": "14d8 + 28"
"stats":
- !!int "16"
- !!int "14"
- !!int "15"
- !!int "14"
- !!int "14"
- !!int "15"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "5"
  "Constitution": !!int "5"
"senses": "passive Perception 12"
"languages": "Gith"
"cr": "8"
"traits":
- "desc": "Al'chaia's innate spellcasting ability is Intelligence (spell save DC 13,\
    \ +5 to hit with spell attacks). It can innately cast the following spells, requiring\
    \ no components:\n\nAt will: [mage hand](/2-Mechanics/CLI/spells/mage-hand.md)\
    \ (the hand is invisible)\n\n1/day each: [plane shift](/2-Mechanics/CLI/spells/plane-shift.md),\
    \ [telekinesis](/2-Mechanics/CLI/spells/telekinesis.md)\n\n3/day each: [jump](/2-Mechanics/CLI/spells/jump.md),\
    \ [misty step](/2-Mechanics/CLI/spells/misty-step.md), [nondetection](/2-Mechanics/CLI/spells/nondetection.md)\
    \ (self only), [tongues](/2-Mechanics/CLI/spells/tongues.md)"
  "name": "innate"
"actions":
- "desc": "Al'chaia makes two silver greatsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 13 (2d6\
    \ + 6) slashing damage plus 10 (3d6) psychic damage. This is a magic weapon\
    \ attack. On a critical hit against a target in an astral body (as with the [astral\
    \ projection](/2-Mechanics/CLI/spells/astral-projection.md) spell), Al'chaia can\
    \ cut the silvery cord that tethers the target to its material body, instead of\
    \ dealing damage."
  "name": "Silver Greatsword"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/npc/token/alchaia.png"
```
^statblock

```encounter-table
name: Al'chaia
creatures:
 - 1: Al'chaia
```