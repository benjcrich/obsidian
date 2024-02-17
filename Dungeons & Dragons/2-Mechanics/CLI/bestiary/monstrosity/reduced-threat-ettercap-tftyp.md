---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/medium
- monster/type/monstrosity
aliases: ["Reduced-Threat Ettercap"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 113
---
# [Reduced-Threat Ettercap](2-Mechanics/CLI/bestiary/monstrosity/reduced-threat-ettercap-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Ettercap (TftYP)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"stats":
- !!int "14"
- !!int "15"
- !!int "13"
- !!int "7"
- !!int "12"
- !!int "8"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
  "Survival": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "2"
"traits":
- "desc": "The ettercap can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "While in contact with a web, the ettercap knows the exact location of any\
    \ other creature in contact with the same web."
  "name": "Web Sense"
- "desc": "The ettercap ignores movement restrictions caused by webbing."
  "name": "Web Walker"
"actions":
- "desc": "The ettercap makes two attacks: one with its bite and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 6 (1d8\
    \ + 2) piercing damage plus 4 (1d8) poison damage. The target must succeed\
    \ on a DC 11 Constitution saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 minute. The creature can repeat the saving throw at the end of each of\
    \ its turns, ending the effect on itself on a success."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) slashing damage."
  "name": "Claws"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/60 ft., one Large or smaller\
    \ creature. Hit: The creature is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ by webbing. As an action, the [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ creature can make a DC 11 Strength check, escaping from the webbing on a success.\
    \ The effect ends if the webbing is destroyed. The webbing has AC 10, 5 hit points,\
    \ is vulnerable to fire damage and immune to bludgeoning, poison and psychic damage."
  "name": "Web (Recharge 5-6)"
"source":
- "TftYP"
"image": "/2-Mechanics/CLI/bestiary/monstrosity/token/reduced-threat-ettercap.png"
```
^statblock

```encounter-table
name: Reduced-Threat Ettercap
creatures:
 - 1: Reduced-Threat Ettercap
```