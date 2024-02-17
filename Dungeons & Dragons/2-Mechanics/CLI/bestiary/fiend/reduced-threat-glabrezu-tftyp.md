---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/9
- monster/size/large
- monster/type/fiend/demon
aliases: ["Reduced-Threat Glabrezu"]
NoteIcon: monster
BestiaryType: fiend (demon)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 113
---
# [Reduced-Threat Glabrezu](2-Mechanics/CLI/bestiary/fiend/reduced-threat-glabrezu-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Glabrezu (TftYP)"
"size": "Large"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"hp": !!int "157"
"hit_dice": "15d10 + 75"
"stats":
- !!int "20"
- !!int "15"
- !!int "21"
- !!int "19"
- !!int "17"
- !!int "16"
"speed": "40 ft."
"saves":
  "Charisma": !!int "7"
  "Wisdom": !!int "7"
  "Strength": !!int "9"
  "Constitution": !!int "9"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "truesight 120 ft., passive Perception 13"
"languages": "Abyssal, telepathy 120 ft."
"cr": "9"
"traits":
- "desc": "The glabrezu's spellcasting ability is Intelligence (spell save DC 16).\
    \ The glabrezu can innately cast the following spells, requiring no material components:\n\
    \nAt will: [darkness](/2-Mechanics/CLI/spells/darkness.md), [detect magic](/2-Mechanics/CLI/spells/detect-magic.md),\
    \ [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md)\n\n1/day each: [confusion](/2-Mechanics/CLI/spells/confusion.md),\
    \ [fly](/2-Mechanics/CLI/spells/fly.md), [power word stun](/2-Mechanics/CLI/spells/power-word-stun.md)"
  "name": "innate"
- "desc": "The glabrezu has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The glabrezu makes four attacks: two with its pincers and two with its\
    \ fists. Alternatively, it makes two attacks with its pincers and casts one spell."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 16 (2d10\
    \ + 5) bludgeoning damage. If the target is a Medium or smaller creature, it\
    \ is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) (escape DC 15).\
    \ The glabrezu has two pincers, each of which can grapple only one target."
  "name": "Pincer"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) bludgeoning damage."
  "name": "Fist"
"source":
- "TftYP"
"image": "/2-Mechanics/CLI/bestiary/fiend/token/reduced-threat-glabrezu.png"
```
^statblock

```encounter-table
name: Reduced-Threat Glabrezu
creatures:
 - 1: Reduced-Threat Glabrezu
```