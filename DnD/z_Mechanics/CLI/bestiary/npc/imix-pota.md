---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/19
- monster/size/huge
- monster/type/elemental
aliases: ["Imix"]
NoteIcon: monster
BestiaryType: elemental
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 214
---
# [Imix](2-Mechanics/CLI/bestiary/npc/imix-pota.md)
*Source: Princes of the Apocalypse p. 214*  

Imix, the Eternal Flame and the All-Consuming Fire, is the Prince of Evil Fire. His natural form resembles a 30-foot-tall, 10-foot-wide pillar of fire with smoldering black pits for eyes. Imix rarely speaks, but he crackles and roars with terrible laughter as anything combustible within his grasp bursts into flame and feeds his hate. Mortal beings are mere objects of contempt to Imix, and he burns alive any he can catch for nothing more than the wicked glee of watching them writhe and die in his flames.

Like his native element, Imix is fickle, temperamental, and highly destructive. Anything combustible stokes his hunger, but he takes special delight in feeding on the handiwork and possessions of intelligent beings, such as crops, buildings, or goods. Imix doesn't even spare his own followers or those who placate him with gifts and sacrifices-he is capricious and unpredictable, and often turns on those who think they have earned his favor.

## Imix's Lair

Imix's home is a fiery inverted pyramid within a volcano on the Elemental Plane of Fire. This fortress-palace is known as the Temple of Ultimate Consumption. Imix is quick to answer calls from the Material Plane, since he hungers eternally for new forests, plains, and kingdoms to burn.

```statblock
"name": "Imix (PotA)"
"size": "Huge"
"type": "elemental"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "325"
"hit_dice": "26d12 + 156"
"stats":
- !!int "19"
- !!int "24"
- !!int "22"
- !!int "15"
- !!int "16"
- !!int "23"
"speed": "50 ft., fly 50 ft."
"saves":
  "Charisma": !!int "12"
  "Dexterity": !!int "13"
  "Constitution": !!int "12"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone), [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)"
"senses": "blindsight 120 ft., passive Perception 13"
"languages": "Common, Ignan"
"cr": "19"
"traits":
- "desc": "Imix's innate spellcasting ability is Charisma (spell save DC 20, +12 to\
    \ hit with spell attacks). He can innately cast the following spells, requiring\
    \ no material components:\n\nAt will: [fireball](/2-Mechanics/CLI/spells/fireball.md),\
    \ [wall of fire](/2-Mechanics/CLI/spells/wall-of-fire.md)\n\n3/day each: [fire\
    \ storm](/2-Mechanics/CLI/spells/fire-storm.md), [haste](/2-Mechanics/CLI/spells/haste.md),\
    \ [teleport](/2-Mechanics/CLI/spells/teleport.md)"
  "name": "innate"
- "desc": "Imix's slam attacks are treated as magical for the purpose of bypassing\
    \ resistance and immunity to nonmagical attacks."
  "name": "Empowered Attacks"
- "desc": "At the start of each of Imix's turns, each creature within 10 feet of him\
    \ takes 17 (5d6) fire damage, and flammable objects in the aura that aren't\
    \ being worn or carried ignite. A creature also takes 17 (5d6) fire damage if\
    \ it touches Imix or hits him with a melee attack while within 10 feet of him,\
    \ and a creature takes that damage the first time on a turn that Imix moves into\
    \ its space. Nonmagical weapons that hit Imix are destroyed by fire immediately\
    \ after dealing damage to him"
  "name": "Fire Aura"
- "desc": "Imix can enter a hostile creature's space and stop there. He can move through\
    \ a space as narrow as 1 inch without squeezing if fire could pass through that\
    \ space."
  "name": "Fire Form"
- "desc": "Imix sheds bright light in a 60-foot radius and dim light for an additional\
    \ 60 feet."
  "name": "Illumination"
- "desc": "If Imix fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Imix has advantage on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Imix makes two slam attacks or two flame blast attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 18\
    \ (2d10 + 7) bludgeoning damage plus 18 (5d6) fire damage."
  "name": "Slam"
- "desc": "Ranged Spell Attack: +12 to hit, range 250 ft., one target. Hit: 35\
    \ (10d6) fire damage."
  "name": "Flame Blast"
- "desc": "Imix summons up to three [fire elementals](/2-Mechanics/CLI/bestiary/elemental/fire-elemental.md)\
    \ and loses 30 hit points for each elemental he summons. Summoned elementals have\
    \ maximum hit points, appear within 100 feet of Imix, and disappear if Imix is\
    \ reduced to 0 hit points."
  "name": "Summon Elementals (1/Day)"
"legendary_actions":
- "desc": "Imix creates a blast of heat within 300 feet of himself. Each creature\
    \ in the area in physical contact with metal objects (for example, carrying metal\
    \ weapons or wearing metal armor) takes 9 (2d8) fire damage. Each creature in\
    \ the area that isn't resistant or immune to fire damage must make a DC 21 Constitution\
    \ saving throw or gain one level of [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion)."
  "name": "Heat Wave"
- "desc": "Imix magically teleports up to 120 feet to an unoccupied space he can see.\
    \ Anything Imix is wearing or carrying isn't teleported with him."
  "name": "Teleport (Costs 2 Actions)"
- "desc": "Imix causes one creature he can see within 30 feet of him to burst into\
    \ flames. The target must make a DC 21 Constitution saving throw. On a failed\
    \ save, the target takes 70 (20d6) fire damage and catches fire. A target on\
    \ fire takes 10 (3d6) fire damage when it starts its turn, and remains on fire\
    \ until it or another creature takes an action to douse the flames. On a successful\
    \ save, the target takes half as much damage and doesn't catch fire."
  "name": "Combustion (Costs 3 Actions)"
"source":
- "PotA"
"image": "/2-Mechanics/CLI/bestiary/npc/token/imix.png"
```
^statblock

```encounter-table
name: Imix
creatures:
 - 1: Imix
```