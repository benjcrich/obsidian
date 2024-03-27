---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/shapechanger
aliases: ["Zuleika Toranescu"]
NoteIcon: monster
BestiaryType: humanoid (human, shapechanger)
SourceType: Bestiary
BookSource: Curse of Strahd p. 204
---
# [Zuleika Toranescu](2-Mechanics/CLI/bestiary/npc/zuleika-toranescu-cos.md)
*Source: Curse of Strahd p. 204*  

```statblock
"name": "Zuleika Toranescu (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, shapechanger"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"stats":
- !!int "15"
- !!int "13"
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft. (40 ft. in wolf form)"
"skillsaves":
  "Stealth": !!int "3"
  "Perception": !!int "4"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"senses": "passive Perception 14"
"languages": "Common (can't speak in wolf form)"
"cr": "3"
"traits":
- "desc": "Zuleika can use its action to polymorph into a wolf-humanoid hybrid or\
    \ into a wolf, or back into its true form, which is humanoid. Its statistics,\
    \ other than its AC, are the same in each form. Any equipment it is wearing or\
    \ carrying isn't transformed. It reverts to its true form if it dies."
  "name": "Shapechanger"
- "desc": "Zuleika has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or smell."
  "name": "Keen Hearing and Smell"
"actions":
- "desc": "Zuleika makes two attacks: two with its spear (humanoid form) or one with\
    \ its bite and one with its claws (hybrid form)."
  "name": "Multiattack (Humanoid or Hybrid Form Only)"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) piercing damage. If the target is a humanoid, it must succeed on a DC\
    \ 12 Constitution saving throw or be cursed with werewolf lycanthropy."
  "name": "Bite (Wolf or Hybrid Form Only)"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 7 (2d4\
    \ + 2) slashing damage."
  "name": "Claws (Hybrid Form Only)"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one creature. Hit: 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear (Humanoid Form Only)"
"source":
- "CoS"
"image": "/2-Mechanics/CLI/bestiary/npc/token/zuleika-toranescu.png"
```
^statblock

```encounter-table
name: Zuleika Toranescu
creatures:
 - 1: Zuleika Toranescu
```