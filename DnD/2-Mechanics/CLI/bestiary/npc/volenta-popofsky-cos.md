---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/5
- monster/size/medium
- monster/type/undead
aliases: ["Volenta Popofsky"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Curse of Strahd p. 93
---
# [Volenta Popofsky](2-Mechanics/CLI/bestiary/npc/volenta-popofsky-cos.md)
*Source: Curse of Strahd p. 93*  

```statblock
"name": "Volenta Popofsky (CoS)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"stats":
- !!int "16"
- !!int "16"
- !!int "16"
- !!int "11"
- !!int "10"
- !!int "12"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "6"
  "Wisdom": !!int "3"
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "3"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "the languages it knew in life"
"cr": "5"
"traits":
- "desc": "Volenta regains 10 hit points at the start of its turn if it has at least\
    \ 1 hit point and isn't in sunlight or running water. If Volenta takes radiant\
    \ damage or damage from holy water, this trait doesn't function at the start of\
    \ Volenta's next turn."
  "name": "Regeneration"
- "desc": "Volenta can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "Volenta has the following flaws:\n\nForbiddance. Volenta can't enter\
    \ a residence without an invitation from one of the occupants.\n\nHarmed by Running\
    \ Water. Volenta takes 20 acid damage when it ends its turn in running water.\n\
    \nStake to the Heart. Volenta is destroyed if a piercing weapon made of wood\
    \ is driven into its heart while it is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ in its resting place.\n\nSunlight Hypersensitivity. Volenta takes 20 radiant\
    \ damage when it starts its turn in sunlight. While in sunlight, it has disadvantage\
    \ on attack rolls and ability checks."
  "name": "Vampire Weaknesses"
"actions":
- "desc": "Volenta makes two attacks, only one of which can be a bite attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one willing creature, or\
    \ a creature that is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by Volenta, [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated),\
    \ or [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained). Hit: 6 (1d6\
    \ + 3) piercing damage plus 7 (2d6) necrotic damage. The target's hit point\
    \ maximum is reduced by an amount equal to the necrotic damage taken, and Volenta\
    \ regains hit points equal to that amount. The reduction lasts until the target\
    \ finishes a long rest. The target dies if this effect reduces its hit point maximum\
    \ to 0."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 8 (2d4\
    \ + 3) slashing damage. Instead of dealing damage, Volenta can grapple the target\
    \ (escape DC 13)."
  "name": "Claws"
"source":
- "CoS"
"image": "/2-Mechanics/CLI/bestiary/npc/token/volenta-popofsky.png"
```
^statblock

```encounter-table
name: Volenta Popofsky
creatures:
 - 1: Volenta Popofsky
```