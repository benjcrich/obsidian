---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/2
- monster/size/small
- monster/type/humanoid/halfling
- monster/type/humanoid/shapechanger
aliases: ["Shard Shunner"]
NoteIcon: monster
BestiaryType: humanoid (halfling, shapechanger)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 42
---
# [Shard Shunner](2-Mechanics/CLI/bestiary/humanoid/shard-shunner-wdh.md)
*Source: Waterdeep: Dragon Heist p. 42*  

 Member of the Shard Shunner gang hired by Emmek Frewn to disrupt the characters' running of the Trollskull Manor

```statblock
"name": "Shard Shunner (WDH)"
"size": "Small"
"type": "humanoid"
"subtype": "halfling, shapechanger"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "27"
"hit_dice": "6d6 + 6"
"stats":
- !!int "10"
- !!int "15"
- !!int "12"
- !!int "11"
- !!int "10"
- !!int "8"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "2"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"senses": "darkvision 60 ft. (rat form only), passive Perception 12"
"languages": "Common, Halfling, Thieves' cant"
"cr": "2"
"traits":
- "desc": "The Shard Shunner can use their action to polymorph into a rat-humanoid\
    \ hybrid or into a giant rat, or back into their true form, which is humanoid.\
    \ Their statistics, other than their size, are the same in each form. Any equipment\
    \ they are wearing or carrying isn't transformed. They revert to their true form\
    \ if they die."
  "name": "Shapechanger"
- "desc": "The Shard Shunner has advantage on Wisdom (Perception) checks that rely\
    \ on smell."
  "name": "Keen Smell"
- "desc": "The Shard Shunner can move through the space of creatures that is of a\
    \ size larger than them."
  "name": "Halfling Nimbleness"
- "desc": "The Shard Shunner has advantage on saving throws against being [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Brave"
"actions":
- "desc": "The Shard Shunner makes two attacks, only one of which can be a bite."
  "name": "Multiattack (Humanoid or Hybrid Form Only)"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage. If the target is a humanoid, it must succeed on a DC\
    \ 11 Constitution saving throw or be cursed with wererat lycanthropy."
  "name": "Bite (Rat or Hybrid Form Only)"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword (Humanoid or Hybrid Form Only)"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage."
  "name": "Hand Crossbow (Humanoid or Hybrid Form Only)"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/shard-shunner.png"
```
^statblock

```encounter-table
name: Shard Shunner
creatures:
 - 1: Shard Shunner
```