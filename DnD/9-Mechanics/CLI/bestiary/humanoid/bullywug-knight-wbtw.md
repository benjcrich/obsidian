---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/3
- monster/size/medium
- monster/type/humanoid
aliases: ["Bullywug Knight"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 231
---
# [Bullywug Knight](2-Mechanics/CLI/bestiary/humanoid/bullywug-knight-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 231*  

Bullywug knights adhere to a code of chivalry. Their sense of honor compels these noble bullywugs to fight fairly and to insist that others do so as well.

```statblock
"name": "Bullywug Knight (WBtW)"
"size": "Medium"
"type": "humanoid"
"alignment": "typically  Lawful Good"
"ac": !!int "18"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"stats":
- !!int "16"
- !!int "12"
- !!int "13"
- !!int "9"
- !!int "11"
- !!int "14"
"speed": "30 ft., swim 30 ft."
"saves":
  "Wisdom": !!int "2"
  "Constitution": !!int "3"
"senses": "passive Perception 10"
"languages": "Bullywug, Common"
"cr": "3"
"traits":
- "desc": "The knight can breathe air and water."
  "name": "Amphibious"
- "desc": "The knight can communicate simple concepts to frogs and toads when it speaks\
    \ in Bullywug."
  "name": "Speak with Frogs and Toads"
- "desc": "The knight's long jump is up to 20 feet and its high jump is up to 10 feet,\
    \ with or without a running start."
  "name": "Standing Leap"
"actions":
- "desc": "The knight makes two Glaive attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one target. Hit: 8 (1d10\
    \ + 3) slashing damage."
  "name": "Glaive"
"bonus_actions":
- "desc": "The knight makes a loud croak while targeting one creature it can see within\
    \ 30 feet of it. The target must succeed on a DC 12 Wisdom saving throw or be\
    \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed) until the end of its\
    \ next turn."
  "name": "Croak of Charming (Recharges after a Short or Long Rest)"
"source":
- "WBtW"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/bullywug-knight.png"
```
^statblock

```encounter-table
name: Bullywug Knight
creatures:
 - 1: Bullywug Knight
```