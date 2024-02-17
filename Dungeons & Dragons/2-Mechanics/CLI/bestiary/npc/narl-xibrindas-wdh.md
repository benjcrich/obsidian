---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Nar'l Xibrindas"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 211
---
# [Nar'l Xibrindas](2-Mechanics/CLI/bestiary/npc/narl-xibrindas-wdh.md)
*Source: Waterdeep: Dragon Heist p. 211*  

Xanathar's advisor is a nervous and conniving male drow named Nar'l Xibrindas. Nar'l's house was wiped out long ago, but he and his elder brother Soluun survived and joined Bregan D'aerthe. A year ago, Nar'l was given the difficult task of infiltrating the Xanathar Guild and getting as close to the beholder as possible. Not only did he succeed, but in the course of gaining Xanathar's trust, he managed to convince the beholder to eliminate its other advisors. The beholder's paranoia will eventually cause Xanathar to question the drow's loyalty, though, and Nar'l has become increasingly worried about his future. If forced to decide between himself and Bregan D'aerthe, he'll choose the former and betray his drow allies to save his own skin.

Xanathar is aware that something is off with Nar'l, and recently assigned him a grell bodyguard. The grell has instructions to dispose of Nar'l at the first sign of disloyalty.

```statblock
"name": "Nar'l Xibrindas (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "45"
"hit_dice": "10d8"
"stats":
- !!int "9"
- !!int "14"
- !!int "10"
- !!int "17"
- !!int "13"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "4"
  "Stealth": !!int "5"
  "Perception": !!int "4"
  "Arcana": !!int "6"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Elvish, Undercommon"
"cr": "7"
"traits":
- "desc": "Nar'l's spellcasting ability is Charisma (spell save DC 12). It can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\n1/day each:\
    \ [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md) (self only)"
  "name": "innate"
- "desc": "Nar'l is a 10th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 14, +6 to hit with spell attacks). Nar'l has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md), [poison spray](/2-Mechanics/CLI/spells/poison-spray.md),\
    \ [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\n1st level (4 slots):\
    \ [mage armor](/2-Mechanics/CLI/spells/mage-armor.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md), [witch bolt](/2-Mechanics/CLI/spells/witch-bolt.md)\n\
    \n2nd level (3 slots): [alter self](/2-Mechanics/CLI/spells/alter-self.md),\
    \ [misty step](/2-Mechanics/CLI/spells/misty-step.md), [web](/2-Mechanics/CLI/spells/web.md)\n\
    \n3rd level (3 slots): [fly](/2-Mechanics/CLI/spells/fly.md), [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)\n\
    \n4th level (3 slots): [Evard's black tentacles](/2-Mechanics/CLI/spells/evards-black-tentacles.md),\
    \ [greater invisibility](/2-Mechanics/CLI/spells/greater-invisibility.md)\n\n\
    5th level (2 slots): [cloudkill](/2-Mechanics/CLI/spells/cloudkill.md)"
  "name": "spells"
- "desc": "Nar'l has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put Nar'l to sleep."
  "name": "Fey Ancestry"
- "desc": "While in sunlight, Nar'l has disadvantage on attack rolls, as well as on\
    \ Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks that\
    \ rely on sight."
  "name": "Sunlight Sensitivity"
- "desc": "Nar'l carries a vial containing three doses of eyescratch, a contact poison.\
    \ A creature that comes into contact with the poison must succeed on a DC 14 Constitution\
    \ saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 hour and [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded) while\
    \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) in this way. A [lesser\
    \ restoration](/2-Mechanics/CLI/spells/lesser-restoration.md) spell or similar\
    \ magic ends the effect."
  "name": "Special Equipment"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d6\
    \ - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two\
    \ hands, plus 3 (1d6) poison damage."
  "name": "Staff"
- "desc": "Nar'l magically summons a [quasit](/2-Mechanics/CLI/bestiary/fiend/quasit.md),\
    \ or attempts to summon a [shadow demon](/2-Mechanics/CLI/bestiary/fiend/shadow-demon.md)\
    \ with a 50% chance chance of success. The summoned demon appears in an unoccupied\
    \ space within 60 feet of its summoner, acts as an ally of its summoner, and can't\
    \ summon other demons. It remains for 10 minutes, until it or its summoner dies,\
    \ or until its summoner dismisses it as an action."
  "name": "Summon Demon (1/Day)"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/npc/token/narl-xibrindas.png"
```
^statblock

```encounter-table
name: Nar'l Xibrindas
creatures:
 - 1: Nar'l Xibrindas
```