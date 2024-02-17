---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mot
- monster/cr/1
- monster/size/medium
- monster/type/construct
aliases: ["Bronze Sable"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Mythic Odysseys of Theros p. 210
---
# [Bronze Sable](2-Mechanics/CLI/bestiary/construct/bronze-sable-mot.md)
*Source: Mythic Odysseys of Theros p. 210*  

The first bronze sables were presented to Karametra as a gift by Purphoros to serve primarily as guardians in Karametra's temples. But as others have been created, some have been used as nimble scouts, always on alert for danger.

The first anvilwroughts were created by the god of the forge, Purphoros. He gave the secret of breathing life into these metal creatures to his most devoted followers so they could mimic his works and invent new forms at their own forges.

Some anvilwroughts are vigilant guardians at holy shrines, others serve as familiars and messengers, and a few were created to emulate beauty found among the animals of the mortal world. Each exhibits abilities suited to its role, with some behaving like companionable creatures or stoic guardians.

A few extremely rare and valuable anvilwroughts were crafted by the hand of Purphoros himself. A number of these magnificent creations are now heirlooms of monarchs; others are lost to the sands of time or are guarded by ancient monsters.

```statblock
"name": "Bronze Sable (MOT)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "15"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"stats":
- !!int "13"
- !!int "16"
- !!int "15"
- !!int "3"
- !!int "14"
- !!int "1"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "5"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "understands one language of its creator but can't speak"
"cr": "1"
"traits":
- "desc": "While the sable remains motionless, it is indistinguishable from a normal\
    \ statue."
  "name": "False Appearance"
- "desc": "The sable has advantage on an attack roll against a creature if at least\
    \ one of the sable's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
- "desc": "If the sable surprises a creature and hits it with an attack during the\
    \ first round of combat, the target takes an extra 10 (3d6) damage from the\
    \ attack."
  "name": "Surprise Attack"
"actions":
- "desc": "The sable makes two bite attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage."
  "name": "Bite"
"source":
- "MOT"
"image": "/2-Mechanics/CLI/bestiary/construct/token/bronze-sable.png"
```
^statblock

```encounter-table
name: Bronze Sable
creatures:
 - 1: Bronze Sable
```