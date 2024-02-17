---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/sahuagin
aliases: ["Sahuagin Champion"]
NoteIcon: monster
BestiaryType: humanoid (sahuagin)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 249
---
# [Sahuagin Champion](2-Mechanics/CLI/bestiary/humanoid/sahuagin-champion-gos.md)
*Source: Ghosts of Saltmarsh p. 249*  

Those sahuagin warriors who prove themselves through heroic acts are given both title and status. Sahuagin champions often serve as lieutenants in the sahuagin army, as they do in The Final Enemy.

```statblock
"name": "Sahuagin Champion (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "sahuagin"
"alignment": "Lawful Evil"
"ac": !!int "16"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"stats":
- !!int "16"
- !!int "14"
- !!int "12"
- !!int "12"
- !!int "13"
- !!int "9"
"speed": "30 ft., swim 40 ft."
"skillsaves":
  "Perception": !!int "5"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Sahuagin"
"cr": "3"
"traits":
- "desc": "The champion has advantage on melee attack rolls against any creature that\
    \ doesn't have all its hit points."
  "name": "Blood Frenzy"
- "desc": "The champion can breathe air and water, but it needs to be submerged at\
    \ least once every 4 hours to avoid suffocating."
  "name": "Limited Amphibiousness"
- "desc": "The champion can magically command any shark within 120 feet of it, using\
    \ a limited telepathy."
  "name": "Shark Telepathy"
"actions":
- "desc": "The champion makes three attacks with its spear, or one attack with its\
    \ bite and two with its claws."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 6 (1d6 + 3) piercing damage, or 7 (1d8 + 3) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Claws"
"source":
- "GoS"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/sahuagin-champion.png"
```
^statblock

```encounter-table
name: Sahuagin Champion
creatures:
 - 1: Sahuagin Champion
```