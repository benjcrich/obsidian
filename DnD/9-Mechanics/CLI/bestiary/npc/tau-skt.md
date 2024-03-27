---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/shou-human
aliases: ["Tau"]
NoteIcon: monster
BestiaryType: humanoid (Shou human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 103
---
# [Tau](2-Mechanics/CLI/bestiary/npc/tau-skt.md)
*Source: Storm King's Thunder p. 103*  

```statblock
"name": "Tau (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Shou human"
"alignment": "Neutral Evil"
"ac": !!int "16"
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
"senses": "passive Perception 11"
"languages": "Common, Terran"
"cr": "2"
"traits":
- "desc": "Tau is a 4th-level spellcaster. Its spellcasting ability is Wisdom (spell\
    \ save DC 11, +3 to hit with spell attacks). Tau has the following cleric spells\
    \ prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [command](/2-Mechanics/CLI/spells/command.md), [inflict\
    \ wounds](/2-Mechanics/CLI/spells/inflict-wounds.md), [shield of faith](/2-Mechanics/CLI/spells/shield-of-faith.md)\n\
    \n2nd level (3 slots): [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)"
  "name": "spells"
- "desc": "Tau has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Dark Devotion"
"actions":
- "desc": "Tau makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 4 (1d4\
    \ + 2) bludgeoning damage."
  "name": "Club"
"source":
- "SKT"
"image": "/2-Mechanics/CLI/bestiary/npc/token/tau.png"
```
^statblock

```encounter-table
name: Tau
creatures:
 - 1: Tau
```