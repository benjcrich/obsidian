---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/16
- monster/size/large
- monster/type/celestial
aliases: ["Fazrian"]
NoteIcon: monster
BestiaryType: celestial
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 275
---
# [Fazrian](2-Mechanics/CLI/bestiary/npc/fazrian-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 275*  

Once an exemplar of courage and good judgment, Fazrian now seeks to destroy any creature it believes is undeserving of continued existence. Fazrian's views are a mockery of what they once were. Every creature is guilty of "deformity" in the planetar's eyes. Unless someone can swiftly prove their innocence, Fazrian sentences that individual to an immediate death.

```statblock
"name": "Fazrian (WDMM)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Evil"
"ac": !!int "19"
"hp": !!int "200"
"hit_dice": "16d10 + 112"
"stats":
- !!int "24"
- !!int "20"
- !!int "24"
- !!int "19"
- !!int "22"
- !!int "25"
"speed": "40 ft., fly 120 ft."
"saves":
  "Charisma": !!int "12"
  "Wisdom": !!int "11"
  "Constitution": !!int "12"
"skillsaves":
  "Perception": !!int "11"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "truesight 120 ft., passive Perception 21"
"languages": "all, telepathy 120 ft."
"cr": "16"
"traits":
- "desc": "Fazrian's spellcasting ability is Charisma (spell save DC 20). Fazrian\
    \ can innately cast the following spells, requiring no material components:\n\n\
    At will: [detect evil and good](/2-Mechanics/CLI/spells/detect-evil-and-good.md),\
    \ [invisibility](/2-Mechanics/CLI/spells/invisibility.md) (self only)\n\n1/day\
    \ each: [commune](/2-Mechanics/CLI/spells/commune.md), [control weather](/2-Mechanics/CLI/spells/control-weather.md),\
    \ [insect plague](/2-Mechanics/CLI/spells/insect-plague.md)\n\n3/day each:\
    \ [blade barrier](/2-Mechanics/CLI/spells/blade-barrier.md), [dispel evil and\
    \ good](/2-Mechanics/CLI/spells/dispel-evil-and-good.md), [flame strike](/2-Mechanics/CLI/spells/flame-strike.md),\
    \ [raise dead](/2-Mechanics/CLI/spells/raise-dead.md)"
  "name": "innate"
- "desc": "Fazrian's weapon attacks are magical. When Fazrian hits with any weapon,\
    \ the weapon deals an extra 5d8 radiant damage (included in the attack)."
  "name": "Angelic Weapons"
- "desc": "Fazrian knows if it hears a lie."
  "name": "Divine Awareness"
- "desc": "Fazrian has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Fazrian makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 21 (4d6\
    \ + 7) slashing damage plus 22 (5d8) radiant damage."
  "name": "Greatsword"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/npc/token/fazrian.png"
```
^statblock

```encounter-table
name: Fazrian
creatures:
 - 1: Fazrian
```