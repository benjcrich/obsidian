---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/12
- monster/environment/desert
- monster/environment/forest
- monster/environment/underdark
- monster/size/huge
- monster/type/monstrosity
aliases: ["Yuan-ti Anathema"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 272, Volo's Guide to Monsters p. 202
---
# [Yuan-ti Anathema](2-Mechanics/CLI/bestiary/monstrosity/yuan-ti-anathema-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 272, Volo's Guide to Monsters p. 202*  

As part of their quest for godhood, a yuan-ti abomination might perform a ritual that, if successful, transforms them into an even greater form: a yuan-ti anathema. This ritual demands the sacrifice of hundreds of snakes and requires the abomination to bathe in the blood of their enemies. The transformation is quick but painful.

Anathemas consider themselves demigods on the path to greater divinity. They demand obeisance from weaker creatures and use every resource at their disposal to war against neighbors, seeking the captives, sacrifices, glory, and riches the anathemas believe they need to achieve true divinity.

Anathemas don't age, allowing them to pursue their goals until the end of days. Truly powerful ones might rule multiple yuan-ti cities and bring entire regions under their control.

```statblock
"name": "Yuan-ti Anathema (MPMM)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Typically  Neutral Evil"
"ac": !!int "16"
"hp": !!int "189"
"hit_dice": "18d12 + 72"
"stats":
- !!int "23"
- !!int "13"
- !!int "19"
- !!int "19"
- !!int "17"
- !!int "20"
"speed": "40 ft., climb 40 ft., swim 40 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "11"
"damage_resistances": "acid, fire, lightning"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 30 ft., darkvision 60 ft., passive Perception 21"
"languages": "Abyssal, Common, Draconic"
"cr": "12"
"traits":
- "desc": "The anathema casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 17):\n\nAt will:\
    \ [animal friendship](/2-Mechanics/CLI/spells/animal-friendship.md) (snakes only)\n\
    \n3/day each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [entangle](/2-Mechanics/CLI/spells/entangle.md),\
    \ [fear](/2-Mechanics/CLI/spells/fear.md), [polymorph](/2-Mechanics/CLI/spells/polymorph.md),\
    \ [suggestion](/2-Mechanics/CLI/spells/suggestion.md)"
  "name": "spells"
- "desc": "The anathema has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Any creature of the anathema's choice, other than a snake or a yuan-ti,\
    \ that starts its turn within 30 feet of the anathema must succeed on a DC 17\
    \ Wisdom saving throw or become [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ of snakes and yuan-ti. A [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ target can repeat the saving throw at the end of each of its turns, ending the\
    \ effect on itself on a success. If a target's saving throw is successful or the\
    \ effect ends for it, the target is immune to this anathama's aura for the next\
    \ 24 hours."
  "name": "Ophidiophobia Aura"
- "desc": "The anathema has advantage on saves against being [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
    \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
    \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned),\
    \ or knocked [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)."
  "name": "Six Heads"
"actions":
- "desc": "The anathema makes two Claw attacks and one Flurry of Bites attack."
  "name": "Multiattack (Anathema Form Only)"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 13\
    \ (2d6 + 6) slashing damage."
  "name": "Claw (Anathema Form Only)"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one creature. Hit: 27\
    \ (6d6 + 6) piercing damage plus 14 (4d6) poison damage."
  "name": "Flurry of Bites (Anathema Form Only)"
- "desc": "Melee Weapon Attack: +10 to hit, reach 15 ft., one Large or smaller creature.\
    \ Hit: 16 (3d6 + 6) bludgeoning damage plus 7 (2d6) acid damage, and the\
    \ target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) (escape\
    \ DC 16). Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and it takes 16 (3d6 + 6) bludgeoning damage plus 7 (2d6) acid damage at\
    \ the start of each of its turns. The anathema can constrict only one creature\
    \ at a time."
  "name": "Constrict (Snake Form Only)"
"bonus_actions":
- "desc": "The anathema transforms into a Huge constrictor snake or back into its\
    \ true form. Its statistics are the same in each form. Any equipment it is wearing\
    \ or carrying isn't transformed."
  "name": "Change Shape"
"source":
- "MPMM"
- "VGM"
"image": "/2-Mechanics/CLI/bestiary/monstrosity/token/yuan-ti-anathema.png"
```
^statblock

```encounter-table
name: Yuan-ti Anathema
creatures:
 - 1: Yuan-ti Anathema
```

## Environment

desert, forest, underdark