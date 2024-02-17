---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Viln Tirin"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Out of the Abyss p. 202
---
# [Viln Tirin](2-Mechanics/CLI/bestiary/npc/viln-tirin-oota.md)
*Source: Out of the Abyss p. 202*  

```statblock
"name": "Viln Tirin (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "15"
- !!int "16"
- !!int "14"
- !!int "14"
- !!int "11"
- !!int "14"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "2"
  "Strength": !!int "4"
"skillsaves":
  "Athletics": !!int "4"
  "Deception": !!int "4"
"senses": "passive Perception 10"
"languages": "any two languages"
"cr": "5"
"traits":
- "desc": "Viln carries a [scimitar of speed](/2-Mechanics/CLI/items/scimitar-of-speed.md)\
    \ and can make one attack with it as a bonus action on her turn. Viln also carries\
    \ four daggers coated with [purple worm poison](/2-Mechanics/CLI/items/purple-worm-poison.md).\
    \ The poison on a dagger's blade is good for one hit only, whether the poison\
    \ takes effect or not."
  "name": "Special Equipment"
"actions":
- "desc": "Viln makes three melee attacks: two with its scimitar and one with its\
    \ dagger. Or Viln makes two ranged attacks with its daggers."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d6\
    \ + 5) slashing damage."
  "name": "Scimitar"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
  "name": "Dagger"
"reactions":
- "desc": "Viln adds 2 to its AC against one melee attack that would hit it. To do\
    \ so, Viln must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "OotA"
"image": "/2-Mechanics/CLI/bestiary/npc/token/viln-tirin.png"
```
^statblock

```encounter-table
name: Viln Tirin
creatures:
 - 1: Viln Tirin
```