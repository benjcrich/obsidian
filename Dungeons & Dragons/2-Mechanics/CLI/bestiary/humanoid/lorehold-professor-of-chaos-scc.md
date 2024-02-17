---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/scc
- monster/cr/7
- monster/size/small-or-medium
- monster/type/humanoid/wizard
aliases: ["Lorehold Professor of Chaos"]
NoteIcon: monster
BestiaryType: humanoid (wizard)
SourceType: Bestiary
BookSource: Strixhaven: A Curriculum of Chaos p. 198
---
# [Lorehold Professor of Chaos](2-Mechanics/CLI/bestiary/humanoid/lorehold-professor-of-chaos-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 198*  

Professors of chaos wield magic inspired by the ebb and flow of chance. They study the course history has taken, looking for breaking points in the flow of events, and focus their magic into creating breaks that are to their advantage. Whether those breaks are in a series of events, in obstacles, or in enemies depends on the needs in the moment. They crush enemies' plans under the weight of time and lash out with magical energy that often takes the appearance of books, scrolls, and sheets of parchment.

## Lorehold Scholars

The archaeomancers of Lorehold College draw their magical might from the flow of time and fate and the way those forces shape the course of history. Scholars of this broad mystical study divide between those who see history as an unpredictable jumble of chance and those who believe events form a perfect—and predictable—pattern.

```statblock
"name": "Lorehold Professor of Chaos (SCC)"
"size": "Small or Medium"
"type": "humanoid"
"subtype": "wizard"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "110"
"hit_dice": "17d8 + 34"
"stats":
- !!int "11"
- !!int "14"
- !!int "14"
- !!int "19"
- !!int "15"
- !!int "13"
"speed": "30 ft."
"saves":
  "Charisma": !!int "4"
  "Wisdom": !!int "5"
  "Intelligence": !!int "7"
  "Constitution": !!int "5"
"skillsaves":
  "Perception": !!int "5"
  "History": !!int "7"
  "Arcana": !!int "7"
"senses": "passive Perception 15"
"languages": "Common plus any four languages"
"cr": "7"
"traits":
- "desc": "The professor casts one of the following spells, requiring no material\
    \ components and using Intelligence as the spellcasting ability:\n\nAt will:\
    \ [comprehend languages](/2-Mechanics/CLI/spells/comprehend-languages.md), [dancing\
    \ lights](/2-Mechanics/CLI/spells/dancing-lights.md), [guidance](/2-Mechanics/CLI/spells/guidance.md)\n\
    \n2/day each: [locate object](/2-Mechanics/CLI/spells/locate-object.md), [mage\
    \ armor](/2-Mechanics/CLI/spells/mage-armor.md), [passwall](/2-Mechanics/CLI/spells/passwall.md)"
  "name": "spells"
- "desc": "The professor can cast the [contact other plane](/2-Mechanics/CLI/spells/contact-other-plane.md)\
    \ spell to contact a long-dead spirit, using Intelligence as the spellcasting\
    \ ability."
  "name": "Voice from the Past (1/Day)"
"actions":
- "desc": "The professor makes two Spectral Scroll attacks. It can also use Weight\
    \ of History, if available."
  "name": "Multiattack"
- "desc": "Melee Spell Attack: +7 to hit, reach 30 ft., one target. Hit: 15 (2d10\
    \ + 4) force damage. If the target is a creature, it must succeed on a DC 15\
    \ Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Spectral Scroll"
- "desc": "The professor magically compresses time around up to six creatures of its\
    \ choice that it can see within 30 feet of itself. Each target must succeed on\
    \ a DC 15 Wisdom saving throw or be [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ for 1 minute, but the [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ target's speed is halved instead of being reduced to 0. At the start of each\
    \ of its turns, the [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ target takes 4 (1d8) force damage. A [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ target can repeat the save at the end of each of its turns, ending the effect\
    \ on itself on a success."
  "name": "Weight of History (Recharge 5-6)"
"source":
- "SCC"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/lorehold-professor-of-chaos.png"
```
^statblock

```encounter-table
name: Lorehold Professor of Chaos
creatures:
 - 1: Lorehold Professor of Chaos
```