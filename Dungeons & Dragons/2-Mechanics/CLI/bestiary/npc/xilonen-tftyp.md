---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/5
- monster/size/large
- monster/type/monstrosity
aliases: ["Xilonen"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 83
---
# [Xilonen](2-Mechanics/CLI/bestiary/npc/xilonen-tftyp.md)
*Source: Tales from the Yawning Portal p. 83*  

```statblock
"name": "Xilonen (TftYP)"
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
- !!int "2"
- !!int "16"
- !!int "6"
"speed": "10 ft., climb 10 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "6"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": ""
"cr": "5"
"traits":
- "desc": "While Xilonen remains motionless, it is indistinguishable from a normal\
    \ cave formation, such as a stalagmite."
  "name": "False Appearance"
- "desc": "Xilonen can have up to six tendrils at a time. Each tendril can be attacked\
    \ (AC 20; 10 hit points; immunity to poison and psychic damage). Destroying a\
    \ tendril deals no damage to Xilonen, which can extrude a replacement tendril\
    \ on its next turn. A tendril can also be broken if a creature takes an action\
    \ and succeeds on a DC 15 Strength check against it."
  "name": "Grasping Tendrils"
- "desc": "Xilonen can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "Xilonen makes four attacks with its tendrils, uses Reel, and makes one\
    \ attack with its bite."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 22 (4d8\
    \ + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 50 ft., one creature. Hit: The\
    \ target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) (escape\
    \ DC 15). Until the grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ and has disadvantage on Strength checks and Strength saving throws, and Xilonen\
    \ can't use the same tendril on another target."
  "name": "Tendril"
- "desc": "Xilonen pulls each creature [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by it up to 25 feet straight toward it."
  "name": "Reel"
"source":
- "TftYP"
"image": "/2-Mechanics/CLI/bestiary/npc/token/xilonen.png"
```
^statblock

```encounter-table
name: Xilonen
creatures:
 - 1: Xilonen
```