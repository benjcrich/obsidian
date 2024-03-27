---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/
- monster/size/medium
- monster/type/humanoid/illuskan-human
aliases: ["Duvessa Shane"]
NoteIcon: monster
BestiaryType: humanoid (Illuskan human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 248
---
# [Duvessa Shane](2-Mechanics/CLI/bestiary/npc/duvessa-shane-skt.md)
*Source: Storm King's Thunder p. 248*  

The daughter of a Waterdhavian trader and a tavern server, Duvessa has her mother's talent for negotiation and her father's charm. As the first woman to serve as Town Speaker of Bryn Shander, and a young one at that, she has much to prove.

Ideal:"The people of Icewind Dale are survivors. They can weather any storm."

Bond:"My mother taught me what it means to be a good leader. I won't disappoint her."

Flaw:"I don't give an inch in any argument or conflict."

```statblock
"name": "Duvessa Shane (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Illuskan human"
"alignment": "Lawful Good"
"ac": !!int "10"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "10"
- !!int "11"
- !!int "10"
- !!int "16"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Insight": !!int "4"
  "Persuasion": !!int "5"
"senses": "passive Perception 12"
"languages": "Common, Dwarvish, Giant, Orc"
"traits":
- "desc": "The daughter of a Waterdhavian trader and a tavern server, Duvessa has\
    \ her mother's talent for negotiation and her father's charm. As the first woman\
    \ to serve as Town Speaker of Bryn Shander, and a young one at that, she has much\
    \ to prove.\n\nIdeal: \"The people of Icewind Dale are survivors. They can weather\
    \ any storm.\"\n\nBond: \"My mother taught me what it means to be a good leader.\
    \ I won't disappoint her.\"\n\nFlaw: \"I don't give an inch in any argument of\
    \ conflict.\""
  "name": "Roleplaying Information"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +2 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 2 (1d4) piercing damage. Duvessa carries only one\
    \ dagger."
  "name": "Dagger"
"reactions":
- "desc": "Duvessa adds 2 to her AC against one melee attack that would hit her. To\
    \ do so, Duvessa must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "SKT"
"image": "/2-Mechanics/CLI/bestiary/npc/token/duvessa-shane.png"
```
^statblock

```encounter-table
name: Duvessa Shane
creatures:
 - 1: Duvessa Shane
```