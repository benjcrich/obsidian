---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/ftd
- monster/cr/2
- monster/size/medium
- monster/type/monstrosity
aliases: ["Swarm of Hoard Scarabs"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Fizban's Treasury of Dragons p. 205
---
# [Swarm of Hoard Scarabs](2-Mechanics/CLI/bestiary/monstrosity/swarm-of-hoard-scarabs-ftd.md)
*Source: Fizban's Treasury of Dragons p. 205*  

Hoard scarabs are beetle-like creatures that, through some feat of natural adaptation or alchemical ingenuity, blend in perfectly among piles of gold coins. They feed on tiny mites that infest a dragon's scales and lair, and their painful bite can be a strong deterrent to would-be treasure thieves.

Hoard scarabs also produce a glittering metallic dust from their wings that coats intruders who get too close to them. The magic of this dust allows the lair's draconic owner to sense intruders' location as they move about the lair.

```statblock
"name": "Swarm of Hoard Scarabs (FTD)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "14"
"hp": !!int "31"
"hit_dice": "7d8"
"stats":
- !!int "6"
- !!int "16"
- !!int "11"
- !!int "3"
- !!int "8"
- !!int "6"
"speed": "20 ft., burrow 20 ft., fly 20 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone), [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
  \ [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)"
"senses": "darkvision 60 ft., tremorsense 60 ft., passive Perception 9"
"languages": ""
"cr": "2"
"traits":
- "desc": "If the swarm is motionless at the start of combat, it has advantage on\
    \ its initiative roll. Moreover, if a creature hasn't observed the swarm move\
    \ or act, that creature must succeed on a DC 18 Intelligence (Investigation) check\
    \ to discern that the swarm is animate."
  "name": "False Appearance"
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Tiny scarab. The swarm can't\
    \ regain hit points or gain temporary hit points."
  "name": "Swarm"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 0 ft., one creature in the swarm's\
    \ space. Hit: 13 (3d6 + 3) piercing damage, or 6 (1d6 + 3) piercing damage\
    \ if the swarm is at half of its hit points or fewer, and the target has disadvantage\
    \ on attack rolls until the start of its next turn."
  "name": "Swarm of Bites"
"bonus_actions":
- "desc": "The swarm releases magical glittering dust from its wings. Each creature\
    \ within 10 feet of the swarm must succeed on a DC 13 Dexterity saving throw or\
    \ be outlined in blue light for 10 minutes. While outlined in this way, a creature\
    \ sheds dim light in a 10-foot radius and can't benefit from being [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible).\
    \ In addition, every Dragon within 1 mile of the creature becomes aware of it\
    \ and can unerringly track the creature. Casting [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md)\
    \ on the creature ends the effect on it."
  "name": "Scale Dust (1/Day)"
"source":
- "FTD"
"image": "/2-Mechanics/CLI/bestiary/monstrosity/token/swarm-of-hoard-scarabs.png"
```
^statblock

```encounter-table
name: Swarm of Hoard Scarabs
creatures:
 - 1: Swarm of Hoard Scarabs
```