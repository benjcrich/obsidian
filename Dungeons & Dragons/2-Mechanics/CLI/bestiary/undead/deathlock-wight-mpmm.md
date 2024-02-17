---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/3
- monster/size/medium
- monster/type/undead/warlock
aliases: ["Deathlock Wight"]
NoteIcon: monster
BestiaryType: undead (warlock)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 87, Mordenkainen's Tome of Foes p. 129
---
# [Deathlock Wight](2-Mechanics/CLI/bestiary/undead/deathlock-wight-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 87, Mordenkainen's Tome of Foes p. 129*  

Deprived of much of its magic as a special punishment, a deathlock wight lingers between the warlock it was and the wretched existence of a wight.

## Deathlocks

The forging of a pact between a warlock and a patron is no minor occasion—at least not for the warlock. The consequences of breaking that pact can be dire and, in some cases, lethal. A warlock who fails to live up to a bargain with an evil patron runs the risk of rising from the dead as a deathlock, a foul Undead driven to serve its otherworldly patron.

An powerful necromancer might also discover the wicked methods of creating a deathlock and then subjugate it, acting as the deathlock's patron.

```statblock
"name": "Deathlock Wight (MPMM)"
"size": "Medium"
"type": "undead"
"subtype": "warlock"
"alignment": "Typically  Neutral Evil"
"ac": !!int "12"
"hp": !!int "37"
"hit_dice": "5d8 + 15"
"stats":
- !!int "11"
- !!int "14"
- !!int "16"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
"skillsaves":
  "Perception": !!int "4"
  "Arcana": !!int "3"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "the languages it knew in life"
"cr": "3"
"traits":
- "desc": "The deathlock casts one of the following spells, using Charisma as the\
    \ spellcasting ability (spell save DC 13):\n\nAt will: [detect magic](/2-Mechanics/CLI/spells/detect-magic.md),\
    \ [disguise self](/2-Mechanics/CLI/spells/disguise-self.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)\n\
    \n1/day each: [fear](/2-Mechanics/CLI/spells/fear.md), [hold person](/2-Mechanics/CLI/spells/hold-person.md)"
  "name": "spells"
- "desc": "While in sunlight, the deathlock has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
- "desc": "The deathlock doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The deathlock makes two Life Drain or Grave Bolt attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 6 (1d8\
    \ + 2) necrotic damage. The target must succeed on a DC 13 Constitution saving\
    \ throw, or its hit point maximum is reduced by an amount equal to the damage\
    \ taken. This reduction lasts until the target finishes a long rest. The target\
    \ dies if its hit point maximum is reduced to 0.\n\nA Humanoid slain by this attack\
    \ rises 24 hours later as a [zombie](/2-Mechanics/CLI/bestiary/undead/zombie.md)\
    \ under the deathlock's control, unless the Humanoid is restored to life or its\
    \ body is destroyed. The deathlock can have no more than twelve zombies under\
    \ its control at one time."
  "name": "Life Drain"
- "desc": "Ranged Spell Attack: +5 to hit, range 60 ft., one target. Hit: 12 (2d8\
    \ + 3) necrotic damage."
  "name": "Grave Bolt"
"source":
- "MPMM"
- "MTF"
"image": "/2-Mechanics/CLI/bestiary/undead/token/deathlock-wight.png"
```
^statblock

```encounter-table
name: Deathlock Wight
creatures:
 - 1: Deathlock Wight
```