---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/5
- monster/size/large
- monster/type/monstrosity
aliases: ["Molten Magma Roper"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 143
---
# [Molten Magma Roper](2-Mechanics/CLI/bestiary/monstrosity/molten-magma-roper-pota.md)
*Source: Princes of the Apocalypse p. 143*  

```statblock
"name": "Molten Magma Roper (PotA)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "20"
"hp": !!int "93"
"hit_dice": "11d10 + 33"
"stats":
- !!int "18"
- !!int "8"
- !!int "17"
- !!int "7"
- !!int "16"
- !!int "6"
"speed": "10 ft., climb 10 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "6"
"damage_vulnerabilities": "cold"
"damage_immunities": "fire"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": ""
"cr": "5"
"traits":
- "desc": "While the roper remains motionless, it is indistinguishable from a normal\
    \ cave formation, such as a stalagmite."
  "name": "False Appearance"
- "desc": "The roper can have up to six tendrils at a time. Each tendril can be attacked\
    \ (AC 20; 10 hit points; immunity to poison and psychic damage). Destroying a\
    \ tendril deals no damage to the roper, which can extrude a replacement tendril\
    \ on its next turn. A tendril can also be broken if a creature takes an action\
    \ and succeeds on a DC 15 Strength check against it."
  "name": "Grasping Tendrils"
- "desc": "The roper can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "The roper makes four attacks with its tendrils, uses Reel, and makes one\
    \ attack with its bite."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 22 (4d8\
    \ + 4) fire damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 50 ft., one creature. Hit: 4\
    \ (1d8) fire damage and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 15). Until the grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ and has disadvantage on Strength checks and Strength saving throws, and the\
    \ roper can't use the same tendril on another target. A creature takes 4 (1d8)\
    \ fire damage each time it ends its turn grappled by the roper."
  "name": "Tendril"
- "desc": "The roper pulls each creature [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by it up to 25 feet straight toward it."
  "name": "Reel"
"source":
- "PotA"
"image": "/2-Mechanics/CLI/bestiary/monstrosity/token/molten-magma-roper.png"
```
^statblock

```encounter-table
name: Molten Magma Roper
creatures:
 - 1: Molten Magma Roper
```