---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Elister"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 154
---
# [Elister](2-Mechanics/CLI/bestiary/npc/elister-skt.md)
*Source: Storm King's Thunder p. 154*  

```statblock
"name": "Elister (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "10"
- !!int "10"
- !!int "12"
- !!int "13"
- !!int "16"
- !!int "13"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "7"
  "Religion": !!int "5"
  "Persuasion": !!int "3"
"senses": "passive Perception 13"
"languages": "any two languages"
"cr": "2"
"traits":
- "desc": "Elister is a 5th-level spellcaster. His spellcasting ability is Wisdom\
    \ (spell save DC 13, +5 to hit with spell attacks). Elister has the following\
    \ cleric spells prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md),\
    \ [guiding bolt](/2-Mechanics/CLI/spells/guiding-bolt.md), [sanctuary](/2-Mechanics/CLI/spells/sanctuary.md)\n\
    \n2nd level (3 slots): [lesser restoration](/2-Mechanics/CLI/spells/lesser-restoration.md),\
    \ [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)\n\n3rd level\
    \ (2 slots): [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), [create\
    \ food and water](/2-Mechanics/CLI/spells/create-food-and-water.md)"
  "name": "spells"
- "desc": "As a bonus action, the priest can expend a spell slot to cause its melee\
    \ weapon attacks to magically deal an extra 10 (3d6) radiant damage to a target\
    \ on a hit. This benefit lasts until the end of the turn. If the priest expends\
    \ a spell slot of 2nd level or higher, the extra damage increases by 1d6 for\
    \ each level above 1st."
  "name": "Divine Eminence"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 3 (1d6)\
    \ bludgeoning damage."
  "name": "Mace"
"source":
- "SKT"
"image": "/2-Mechanics/CLI/bestiary/npc/token/elister.png"
```
^statblock

```encounter-table
name: Elister
creatures:
 - 1: Elister
```