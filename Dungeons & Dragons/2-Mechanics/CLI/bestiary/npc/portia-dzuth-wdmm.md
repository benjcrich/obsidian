---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Portia Dzuth"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 239
---
# [Portia Dzuth](2-Mechanics/CLI/bestiary/npc/portia-dzuth-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 239*  

```statblock
"name": "Portia Dzuth (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"hp": !!int "143"
"hit_dice": "22d8 + 44"
"stats":
- !!int "20"
- !!int "15"
- !!int "14"
- !!int "10"
- !!int "14"
- !!int "12"
"speed": "30 ft."
"saves":
  "Strength": !!int "9"
  "Constitution": !!int "6"
"skillsaves":
  "Intimidation": !!int "5"
  "Athletics": !!int "9"
  "Perception": !!int "6"
"senses": "passive Perception 16"
"languages": "Common"
"cr": "9"
"traits":
- "desc": "Portia rerolls a failed saving throw."
  "name": "Indomitable (2/Day)"
- "desc": "As a bonus action, Portia can regain 20 hit points."
  "name": "Second Wind (Recharges after a Short or Long Rest)"
- "desc": "Portia suffers from Shadowfell despair manifesting as unshakable dread.\
    \ Until the despair ends, she has disadvantage on all saving throws and gains\
    \ the following flaw: \"I'm convinced that I'm going to die in Vanrakdoom.\" Portia\
    \ can attempt to end her despair each time she finishes a long rest, doing so\
    \ with a successful DC 15 Wisdom saving throw. A [calm emotions](/2-Mechanics/CLI/spells/calm-emotions.md)\
    \ spell also ends her despair, as does any spell or other magical effect that\
    \ removes a curse."
  "name": "Shadowfell Despair"
"actions":
- "desc": "Portia makes three attacks with its greatsword or its shortbow."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12 (2d6\
    \ + 5) slashing damage, plus 7 (2d6) slashing damage if Portia has more than\
    \ half of its total hit points remaining."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +6 to hit, range 80/320 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage, plus 7 (2d6) piercing damage if Portia has\
    \ more than half of its total hit points remaining."
  "name": "Shortbow"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/npc/token/portia-dzuth.png"
```
^statblock

```encounter-table
name: Portia Dzuth
creatures:
 - 1: Portia Dzuth
```