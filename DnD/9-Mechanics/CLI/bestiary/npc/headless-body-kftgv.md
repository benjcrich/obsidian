---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Headless Body"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 51
---
# [Headless Body](2-Mechanics/CLI/bestiary/npc/headless-body-kftgv.md)
*Source: Keys from the Golden Vault p. 51*  

```statblock
"name": "Headless Body (KftGV)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "18"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "16"
- !!int "11"
- !!int "14"
- !!int "11"
- !!int "11"
- !!int "15"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "2"
  "Constitution": !!int "4"
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "3"
"traits":
- "desc": "The headless body has advantage on saving throws against being [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Brave"
"actions":
- "desc": "The headless body makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6\
    \ + 3) slashing damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. Hit:\
    \ 5 (1d10) piercing damage."
  "name": "Heavy Crossbow"
- "desc": "For 1 minute, the headless body can utter a special command or warning\
    \ whenever a nonhostile creature that it can see within 30 feet of it makes an\
    \ attack roll or a saving throw. The creature can add a d4 to its roll provided\
    \ it can hear and understand the headless body. A creature can benefit from only\
    \ one Leadership die at a time. This effect ends if the headless body is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Leadership (Recharges after a Short or Long Rest)"
"reactions":
- "desc": "The headless body adds 2 to its AC against one melee attack that would\
    \ hit it. To do so, the headless body must see the attacker and be wielding a\
    \ melee weapon."
  "name": "Parry"
"source":
- "KftGV"
"image": "/2-Mechanics/CLI/bestiary/npc/token/headless-body.png"
```
^statblock

```encounter-table
name: Headless Body
creatures:
 - 1: Headless Body
```