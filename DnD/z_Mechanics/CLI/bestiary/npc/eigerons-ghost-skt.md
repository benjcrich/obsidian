---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/4
- monster/size/huge
- monster/type/undead
aliases: ["Eigeron's Ghost"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Storm King's Thunder p. 129
---
# [Eigeron's Ghost](2-Mechanics/CLI/bestiary/npc/eigerons-ghost-skt.md)
*Source: Storm King's Thunder p. 129*  

```statblock
"name": "Eigeron's Ghost (SKT)"
"size": "Huge"
"type": "undead"
"alignment": "Neutral Good"
"ac": !!int "11"
"hp": !!int "65"
"hit_dice": "10d12"
"stats":
- !!int "7"
- !!int "13"
- !!int "10"
- !!int "10"
- !!int "12"
- !!int "17"
"speed": "0 ft., fly 40 ft. (hover)"
"damage_resistances": "acid; fire; lightning; thunder; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone), [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Giant"
"cr": "4"
"traits":
- "desc": "The ghost can see 60 feet into the Ethereal Plane when it is on the Material\
    \ Plane, and vice versa."
  "name": "Ethereal Sight"
- "desc": "The ghost can move through other creatures and objects as if they were\
    \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
    \ an object."
  "name": "Incorporeal Movement"
- "desc": "If it is destroyed, the ghost re-forms after 24 hours. To truly destroy\
    \ the ghost, characters must lay Eigeron's spirit to rest by killing Blagothkus."
  "name": "Rejuvenation"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 17 (4d6\
    \ + 3) necrotic damage."
  "name": "Withering Touch"
- "desc": "The ghost enters the Ethereal Plane from the Material Plane, or vice versa.\
    \ It is visible on the Material Plane while it is in the Border Ethereal, and\
    \ vice versa, yet it can't affect or be affected by anything on the other plane."
  "name": "Etherealness"
- "desc": "One humanoid or giant that the ghost can see within 5 feet of it must succeed\
    \ on a DC 13 Charisma saving throw or be possessed by the ghost; the ghost then\
    \ disappears, and the target is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ and loses control of its body. The ghost now controls the body but doesn't deprive\
    \ the target of awareness. The ghost can't be targeted by any attack, spell, or\
    \ other effect, except ones that turn undead, and it retains its alignment, Intelligence,\
    \ Wisdom, Charisma, and immunity to being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ and [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened). It otherwise\
    \ uses the possessed target's statistics, but doesn't gain access to the target's\
    \ knowledge, class features, or proficiencies.\n\nThe possession lasts until the\
    \ body drops to 0 hit points, the ghost ends it as a bonus action, or the ghost\
    \ is turned or forced out by an effect like the [dispel evil and good](/2-Mechanics/CLI/spells/dispel-evil-and-good.md)\
    \ spell. When the possession ends, the ghost reappears in an unoccupied space\
    \ within 5 feet of the body. The target is immune to this ghost's Possession for\
    \ 24 hours after succeeding on the saving throw or after the possession ends.\
    \ If a creature possessed by the ghost is forcibly removed from the Eye of Annam,\
    \ the ghost is expelled from its host and re-forms in the middle of this room."
  "name": "Possession (Recharge 6)"
"source":
- "SKT"
"image": "/2-Mechanics/CLI/bestiary/npc/token/eigerons-ghost.png"
```
^statblock

```encounter-table
name: Eigeron's Ghost
creatures:
 - 1: Eigeron's Ghost
```