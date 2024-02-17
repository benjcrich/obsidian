---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/5
- monster/size/large
- monster/type/aberration
aliases: ["Reduced-Threat Otyugh"]
NoteIcon: monster
BestiaryType: aberration
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 113
---
# [Reduced-Threat Otyugh](2-Mechanics/CLI/bestiary/aberration/reduced-threat-otyugh-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Otyugh (TftYP)"
"size": "Large"
"type": "aberration"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "114"
"hit_dice": "12d10 + 48"
"stats":
- !!int "16"
- !!int "11"
- !!int "19"
- !!int "6"
- !!int "13"
- !!int "6"
"speed": "30 ft."
"saves":
  "Constitution": !!int "7"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Otyugh"
"cr": "5"
"traits":
- "desc": "The otyugh can magically transmit simple messages and images to any creature\
    \ within 120 feet of it that can understand a language. This form of telepathy\
    \ doesn't allow the receiving creature to telepathically respond."
  "name": "Limited Telepathy"
"actions":
- "desc": "The otyugh makes three attacks: one with its bite and two with its tentacles."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 12 (2d8\
    \ + 3) piercing damage. If the target is a creature, it must succeed on a DC\
    \ 15 Constitution saving throw against disease or become [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ until the disease is cured. Every 24 hours that elapse, the target must repeat\
    \ the saving throw, reducing its hit point maximum by 5 (1d10) on a failure.\
    \ The disease is cured on a success. The target dies if the disease reduces its\
    \ hit point maximum to 0. This reduction to the target's hit point maximum lasts\
    \ until the disease is cured."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 7 (1d8\
    \ + 3) bludgeoning damage plus 4 (1d8) piercing damage."
  "name": "Tentacle"
"source":
- "TftYP"
"image": "/2-Mechanics/CLI/bestiary/aberration/token/reduced-threat-otyugh.png"
```
^statblock

```encounter-table
name: Reduced-Threat Otyugh
creatures:
 - 1: Reduced-Threat Otyugh
```