---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/4
- monster/size/large
- monster/type/ooze
aliases: ["Intelligent Black Pudding"]
NoteIcon: monster
BestiaryType: ooze
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 244
---
# [Intelligent Black Pudding](2-Mechanics/CLI/bestiary/ooze/intelligent-black-pudding-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 244*  

```statblock
"name": "Intelligent Black Pudding (WDMM)"
"size": "Large"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "7"
"hp": !!int "85"
"hit_dice": "10d10 + 30"
"stats":
- !!int "16"
- !!int "5"
- !!int "16"
- !!int "14"
- !!int "6"
- !!int "1"
"speed": "20 ft., climb 20 ft."
"damage_immunities": "acid, cold, lightning, slashing"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 8"
"languages": "Elvish and Undercommon but can't speak"
"cr": "4"
"traits":
- "desc": "The pudding's spellcasting ability is Intelligence (spell save DC 12, +4\
    \ to hit with spell attacks). It can cast the following spells, requiring no components:\n\
    \nAt will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md), [mage\
    \ hand](/2-Mechanics/CLI/spells/mage-hand.md)\n\n1/day: [Melf's acid arrow](/2-Mechanics/CLI/spells/melfs-acid-arrow.md)\n\
    \n3/day each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md)"
  "name": "innate"
- "desc": "The pudding can move through a space as narrow as 1 inch wide without squeezing."
  "name": "Amorphous"
- "desc": "A creature that touches the pudding or hits it with a melee attack while\
    \ within 5 feet of it takes 4 (1d8) acid damage. Any nonmagical weapon made\
    \ of metal or wood that hits the pudding corrodes. After dealing damage, the weapon\
    \ takes a permanent and cumulative −1 penalty to damage rolls. If its penalty\
    \ drops to −5, the weapon is destroyed. Nonmagical ammunition made of metal or\
    \ wood that hits the pudding is destroyed after dealing damage. The pudding can\
    \ eat through 2-inch-thick, nonmagical wood or metal in 1 round."
  "name": "Corrosive Form"
- "desc": "The pudding can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) bludgeoning damage plus 18 (4d8) acid damage. In addition, nonmagical\
    \ armor worn by the target is partly dissolved and takes a permanent and cumulative\
    \ −1 penalty to the AC it offers. The armor is destroyed if the penalty reduces\
    \ its AC to 10."
  "name": "Pseudopod"
"reactions":
- "desc": "When a pudding that is Medium or larger is subjected to lightning or slashing\
    \ damage, it splits into two new puddings if it has at least 10 hit points. Each\
    \ new pudding has hit points equal to half the original pudding's, rounded down.\
    \ New puddings are one size smaller than the original pudding."
  "name": "Split"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/ooze/token/intelligent-black-pudding.png"
```
^statblock

```encounter-table
name: Intelligent Black Pudding
creatures:
 - 1: Intelligent Black Pudding
```