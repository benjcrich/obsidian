---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/13
- monster/size/medium
- monster/type/fiend
aliases: ["Vincent Trench"]
NoteIcon: monster
BestiaryType: fiend
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 32
---
# [Vincent Trench](2-Mechanics/CLI/bestiary/npc/vincent-trench-wdh.md)
*Source: Waterdeep: Dragon Heist p. 32*  

```statblock
"name": "Vincent Trench (WDH)"
"size": "Medium"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "16"
"hp": !!int "110"
"hit_dice": "13d8 + 52"
"stats":
- !!int "14"
- !!int "17"
- !!int "18"
- !!int "13"
- !!int "16"
- !!int "20"
"speed": "40 ft."
"skillsaves":
  "Deception": !!int "10"
  "Insight": !!int "8"
"damage_vulnerabilities": "piercing from magic weapons wielded by good creatures"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Infernal"
"cr": "13"
"traits":
- "desc": "Vincent's innate spellcasting ability is Charisma (spell save DC 18, +10\
    \ to hit with spell attacks). Vincent can innately cast the following spells,\
    \ requiring no material components:\n\nAt will: [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md),\
    \ [disguise self](/2-Mechanics/CLI/spells/disguise-self.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md)\n\n1/day each:\
    \ [dominate person](/2-Mechanics/CLI/spells/dominate-person.md), [fly](/2-Mechanics/CLI/spells/fly.md),\
    \ [plane shift](/2-Mechanics/CLI/spells/plane-shift.md), [true seeing](/2-Mechanics/CLI/spells/true-seeing.md)\n\
    \n3/day each: [charm person](/2-Mechanics/CLI/spells/charm-person.md), [detect\
    \ magic](/2-Mechanics/CLI/spells/detect-magic.md), [invisibility](/2-Mechanics/CLI/spells/invisibility.md),\
    \ [major image](/2-Mechanics/CLI/spells/major-image.md), [suggestion](/2-Mechanics/CLI/spells/suggestion.md)"
  "name": "innate"
- "desc": "Vincent can't be affected or detected by spells of 6th level or lower unless\
    \ it wishes to be. It has advantage on saving throws against all other spells\
    \ and magical effects."
  "name": "Limited Magic Immunity"
"actions":
- "desc": "Vincent makes two claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 9 (2d6\
    \ + 2) slashing damage, and the target is cursed if it is a creature. The magical\
    \ curse takes effect whenever the target takes a short or long rest, filling the\
    \ target's thoughts with horrible images and dreams. The cursed target gains no\
    \ benefit from finishing a short or long rest. The curse lasts until it is lifted\
    \ by a [remove curse](/2-Mechanics/CLI/spells/remove-curse.md) spell or similar\
    \ magic."
  "name": "Claw"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/npc/token/vincent-trench.png"
```
^statblock

```encounter-table
name: Vincent Trench
creatures:
 - 1: Vincent Trench
```