---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/8
- monster/environment/urban
- monster/size/medium
- monster/type/undead/warlock
aliases: ["Deathlock Mastermind"]
NoteIcon: monster
BestiaryType: undead (warlock)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 87, Mordenkainen's Tome of Foes p. 129
---
# [Deathlock Mastermind](2-Mechanics/CLI/bestiary/undead/deathlock-mastermind-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 87, Mordenkainen's Tome of Foes p. 129*  

Though deathlocks exist to serve their patrons, they retain some freedom when it comes to devising tactics and carrying out plans. Powerful deathlocks recruit lesser creatures to help them carry out their missions, becoming the masterminds behind vast conspiracies and intrigues that culminate in the accomplishment of great acts of evil.

## Deathlocks

The forging of a pact between a warlock and a patron is no minor occasion—at least not for the warlock. The consequences of breaking that pact can be dire and, in some cases, lethal. A warlock who fails to live up to a bargain with an evil patron runs the risk of rising from the dead as a deathlock, a foul Undead driven to serve its otherworldly patron.

An powerful necromancer might also discover the wicked methods of creating a deathlock and then subjugate it, acting as the deathlock's patron.

```statblock
"name": "Deathlock Mastermind (MPMM)"
"size": "Medium"
"type": "undead"
"subtype": "warlock"
"alignment": "Typically  Neutral Evil"
"ac": !!int "13"
"hp": !!int "110"
"hit_dice": "20d8 + 20"
"stats":
- !!int "11"
- !!int "16"
- !!int "12"
- !!int "15"
- !!int "12"
- !!int "17"
"speed": "30 ft."
"saves":
  "Charisma": !!int "6"
  "Intelligence": !!int "5"
"skillsaves":
  "Perception": !!int "4"
  "History": !!int "5"
  "Arcana": !!int "5"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "the languages it knew in life"
"cr": "8"
"traits":
- "desc": "The deathlock casts one of the following spells, using Charisma as the\
    \ spellcasting ability (spell save DC 14):\n\nAt will: [detect magic](/2-Mechanics/CLI/spells/detect-magic.md),\
    \ [disguise self](/2-Mechanics/CLI/spells/disguise-self.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md)\n\n1/day each:\
    \ [darkness](/2-Mechanics/CLI/spells/darkness.md), [dimension door](/2-Mechanics/CLI/spells/dimension-door.md),\
    \ [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), [fly](/2-Mechanics/CLI/spells/fly.md),\
    \ [invisibility](/2-Mechanics/CLI/spells/invisibility.md)"
  "name": "spells"
- "desc": "Magical darkness doesn't impede the deathlock's [darkvision](/2-Mechanics/CLI/rules/senses.md#darkvision)."
  "name": "Devil's Sight"
- "desc": "The deathlock has advantage on saving throws against any effect that turns\
    \ Undead."
  "name": "Turn Resistance"
- "desc": "The deathlock doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The deathlock makes two Deathly Claw or Grave Bolt attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13 (3d6\
    \ + 3 necrotic damage)."
  "name": "Deathly Claw"
- "desc": "Ranged Spell Attack: +6 to hit, range 120 ft., one target. Hit: 13\
    \ (3d8) necrotic damage. If the target is Large or smaller, it must succeed\
    \ on a DC 16 Strength saving throw or become [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ as shadowy tendrils wrap around it for 1 minute. A [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ target can use its action to repeat the saving throw, ending the effect on itself\
    \ on a success."
  "name": "Grave Bolt"
"source":
- "MPMM"
- "MTF"
- "AATM"
"image": "/2-Mechanics/CLI/bestiary/undead/token/deathlock-mastermind.png"
```
^statblock

```encounter-table
name: Deathlock Mastermind
creatures:
 - 1: Deathlock Mastermind
```

## Environment

urban