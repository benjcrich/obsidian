---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/20
- monster/size/gargantuan
- monster/type/elemental
aliases: ["Ogrémoch"]
NoteIcon: monster
BestiaryType: elemental
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 216
---
# [Ogrémoch](2-Mechanics/CLI/bestiary/npc/ogremoch-pota.md)
*Source: Princes of the Apocalypse p. 216*  

The Prince of Evil Earth is Ogrémoch (pronounced oh-gray-mock), the Mountain that Walks. His natural form is a shambling, 50-foot-tall colossus of rock, with crystal growths embedded throughout his body. When he bothers to speak, his voice sounds like grinding stones.

Ogrémoch is a miser who regards all the resources and treasures found in the ground as his own. He holds nothing but contempt for mortals (or any other denizens of the Material Plane) and desires nothing more than to crush and subjugate whomever he encounters. What he can't crush, he endures and outlasts.

Ogrémoch especially resents any mortals that dare to remove valuable metal or stone from the earth, and those who shape or build things of stone. He notices each nugget of gold or raw gemstone removed from areas under his influence, seeking to reclaim treasures "stolen" from him-and to punish the thieves. When the Prince of Evil Earth gains access to the Material Plane through an elemental node, he begins to methodically locate and destroy every mine, quarry, town, or fortification in the area. It's not that he needs the wealth, but the principle of the thing-extracting treasure from the earth-is anathema to Ogrémoch.

## Ogrémoch's Lair

Ogrémoch is normally found in the depths of elemental earth, choosing caverns with black crystals and jagged rock spikes to serve as his throne room. He can enter the Material Plane through large and well-established nodes of elemental earth, with a little help from the proper rituals. Within such a node, Ogrémoch wields great power.

```statblock
"name": "Ogrémoch (PotA)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "Neutral Evil"
"ac": !!int "20"
"hp": !!int "526"
"hit_dice": "27d20 + 243"
"stats":
- !!int "26"
- !!int "11"
- !!int "28"
- !!int "11"
- !!int "15"
- !!int "22"
"speed": "50 ft., burrow 50 ft."
"saves":
  "Wisdom": !!int "8"
  "Strength": !!int "14"
  "Constitution": !!int "15"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "blindsight 120 ft., tremorsense 120 ft., passive Perception 12"
"languages": "Common, Terran"
"cr": "20"
"traits":
- "desc": "Ogrémoch's innate spellcasting ability is Charisma (spell save DC 20, +12\
    \ to hit with spell attacks). He can innately cast the following spells, requiring\
    \ no material components:\n\nAt will: [meld into stone](/2-Mechanics/CLI/spells/meld-into-stone.md),\
    \ [move earth](/2-Mechanics/CLI/spells/move-earth.md), [wall of stone](/2-Mechanics/CLI/spells/wall-of-stone.md)"
  "name": "innate"
- "desc": "Ogrémoch's slam attacks are treated as magical and adamantine for the purpose\
    \ of bypassing resistance and immunity to nonmagical attacks."
  "name": "Empowered Attacks"
- "desc": "If Ogrémoch fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Ogrémoch has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Ogrémoch deals double damage to objects and structures with his melee and\
    \ ranged weapon attacks."
  "name": "Siege Monster"
"actions":
- "desc": "Ogrémoch makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 15 ft., one target. Hit: 30\
    \ (4d10 + 8) bludgeoning damage."
  "name": "Slam"
- "desc": "Ranged Weapon Attack: +6 to hit, range 500 ft., one target. Hit: 46\
    \ (7d10 + 8) bludgeoning damage. If the target is a creature, it must succeed\
    \ on a DC 23 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Boulder"
- "desc": "Ogrémoch summons up to three [earth elementals](/2-Mechanics/CLI/bestiary/elemental/earth-elemental.md)\
    \ and loses 30 hit points for each elemental he summons. Summoned elementals have\
    \ maximum hit points, appear within 100 feet of Ogrémoch, and disappear if Ogré\
    moch is reduced to 0 hit points."
  "name": "Summon Elementals (1/Day)"
"legendary_actions":
- "desc": "Ogrémoch's crystalline protrusions flare. Each creature within 30 feet\
    \ of Ogrémoch becomes outlined in orange light, shedding dim light in a 10-foot\
    \ radius. Any attack roll against an affected creature has advantage if the attacker\
    \ can see it, and the affected creature can't benefit from being [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)."
  "name": "Illuminating Crystals"
- "desc": "Ogrémoch stomps the ground, creating an earth tremor that extends in a\
    \ 30-foot radius. Other creatures standing on the ground in that radius must succeed\
    \ on a DC 23 Dexterity saving throw or fall [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Stomp (Costs 2 Actions)"
- "desc": "Ogrémoch's hit points are reduced by 50 as he breaks off a chunk of his\
    \ body and places it on the ground in an unoccupied space within 15 feet of him.\
    \ The chunk of rock instantly transforms into a [gargoyle](/2-Mechanics/CLI/bestiary/elemental/gargoyle.md)\
    \ and acts on the same initiative count as Ogrémoch. Ogrémoch can't use this action\
    \ if he has 50 hit points or fewer. The gargoyle obeys Ogrémoch's commands and\
    \ fights until destroyed."
  "name": "Create Gargoyle (Costs 3 Actions)"
"source":
- "PotA"
"image": "/2-Mechanics/CLI/bestiary/npc/token/ogremoch.png"
```
^statblock

```encounter-table
name: Ogrémoch
creatures:
 - 1: Ogrémoch
```