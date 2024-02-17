---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/tiefling
aliases: ["Tissina Khyret"]
NoteIcon: monster
BestiaryType: humanoid (tiefling)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 116
---
# [Tissina Khyret](2-Mechanics/CLI/bestiary/npc/tissina-khyret-wdh.md)
*Source: Waterdeep: Dragon Heist p. 116*  

Madame Khyret is the personal attendant to Ammalia Cassalanter and is the family's chief housemaid. Madame Khyret dresses in a long black gown and wears a headdress with black tassels. She is an aging tiefling and she spends most of her time in the master sitting room

```statblock
"name": "Tissina Khyret (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "tiefling"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "11"
- !!int "14"
- !!int "12"
- !!int "10"
- !!int "13"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "4"
  "Religion": !!int "2"
  "Persuasion": !!int "4"
"damage_resistances": "fire"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Infernal"
"cr": "2"
"traits":
- "desc": "Tissina's spellcasting ability is Charisma. She can innately cast the following\
    \ spells, requiring no material components:\n\nAt will: [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)"
  "name": "innate"
- "desc": "Tissina is a 4th-level spellcaster. Her spellcasting ability is Wisdom.\
    \ Tissina has the following cleric spells prepared:\n\nCantrips (at will):\
    \ [light](/2-Mechanics/CLI/spells/light.md), [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md),\
    \ [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\n1st level (4 slots):\
    \ [command](/2-Mechanics/CLI/spells/command.md), [inflict wounds](/2-Mechanics/CLI/spells/inflict-wounds.md),\
    \ [shield of faith](/2-Mechanics/CLI/spells/shield-of-faith.md)\n\n2nd level\
    \ (3 slots): [hold person](/2-Mechanics/CLI/spells/hold-person.md), [spiritual\
    \ weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)"
  "name": "spells"
- "desc": "Tissina has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Dark Devotion"
"actions":
- "desc": "Tissina makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 4 (1d4\
    \ + 2) piercing damage. Or Ranged Weapon Attack: +4 to hit, range 20/60 ft.,\
    \ one creature. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/npc/token/tissina-khyret.png"
```
^statblock

```encounter-table
name: Tissina Khyret
creatures:
 - 1: Tissina Khyret
```