---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Sir Braford"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 243
---
# [Sir Braford](2-Mechanics/CLI/bestiary/npc/sir-braford-tftyp.md)
*Source: Tales from the Yawning Portal p. 243*  

While traveling in the vicinity of the Sunless Citadel, Sir Braford and his companions were captured by goblins. The young paladin of Pelor has been corrupted by the sinister Gulthias Tree and now swings his magic sword, [Shatterspike](/2-Mechanics/CLI/items/shatterspike-tftyp.md), on behalf of a different sort of "deity."

```statblock
"name": "Sir Braford (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "18"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"stats":
- !!int "16"
- !!int "9"
- !!int "14"
- !!int "10"
- !!int "13"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "5"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": "Common"
"cr": "1/2"
"traits":
- "desc": "Sir Braford's AC can't be lower than 16."
  "name": "Barkskin"
- "desc": "Sir Braford wields [Shatterspike](/2-Mechanics/CLI/items/shatterspike-tftyp.md),\
    \ a magic longsword that grants a +1 bonus to attack and damage rolls made with\
    \ it (included in his attack). See the Shatterspike handout for the item's other\
    \ properties."
  "name": "Special Equipment"
- "desc": "If the Gulthias Tree dies, Sir Braford dies 24 hours later."
  "name": "Tree Thrall"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands."
  "name": "Longsword"
"reactions":
- "desc": "When a creature Sir Braford can see attacks a target other than him that\
    \ is within 5 feet of him, he can use a reaction to use his shield to impose disadvantage\
    \ on the attack roll."
  "name": "Protection"
"source":
- "TftYP"
"image": "/2-Mechanics/CLI/bestiary/npc/token/sir-braford.png"
```
^statblock

```encounter-table
name: Sir Braford
creatures:
 - 1: Sir Braford
```