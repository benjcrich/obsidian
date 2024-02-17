---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/6
- monster/size/large
- monster/type/undead
aliases: ["Centaur Mummy"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 231
---
# [Centaur Mummy](2-Mechanics/CLI/bestiary/undead/centaur-mummy-tftyp.md)
*Source: Tales from the Yawning Portal p. 231*  

In The Hidden Shrine of Tamoachan, characters must contend with a mummified centaur that wants to prevent them from moving any farther into the dungeon. Combining the most lethal features of two creature types, the centaur mummy can attack nearby targets with its melee weapons while trying to use its Dreadful Glare against enemies that hold back.

```statblock
"name": "Centaur Mummy (TftYP)"
"size": "Large"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "85"
"hit_dice": "10d10 + 30"
"stats":
- !!int "20"
- !!int "12"
- !!int "16"
- !!int "5"
- !!int "14"
- !!int "12"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Sylvan"
"cr": "6"
"traits":
- "desc": "If the centaur mummy moves at least 20 feet straight toward a target and\
    \ then hits it with a pike attack on the same turn, the target takes an extra\
    \ 10 (3d6) piercing damage."
  "name": "Charge"
"actions":
- "desc": "The centaur mummy makes two melee attacks, one with its pike and one with\
    \ its hooves, or it attacks with its pike and uses Dreadful Glare."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 10 (1d10\
    \ + 5) piercing damage."
  "name": "Pike"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 12 (2d6\
    \ + 5) piercing damage plus 10 (3d6) necrotic damage. If the target is a creature,\
    \ it must succeed on a DC 14 Constitution saving throw or be cursed with mummy\
    \ rot. The cursed target can't regain hit points, and its hit point maximum decreases\
    \ by 10 (3d6) for every 24 hours that elapse. If the curse reduces the target's\
    \ hit point maximum to 0, the target dies, and its body turns to dust. The curse\
    \ lasts until removed by the [remove curse](/2-Mechanics/CLI/spells/remove-curse.md)\
    \ spell or similar magic."
  "name": "Hooves"
- "desc": "The centaur mummy targets one creature it can see within 60 feet of it.\
    \ If the target can see the mummy, the target must succeed on a DC 12 Wisdom saving\
    \ throw against this magic or become [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ until the end of the mummy's next turn. If the target fails the saving throw\
    \ by 5 or more, it is also [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)\
    \ for the same duration. A target that succeeds on the saving throw is immune\
    \ to the Dreadful Glare of all mummies (but not mummy lords) for the next 24 hours."
  "name": "Dreadful Glare"
"source":
- "TftYP"
"image": "/2-Mechanics/CLI/bestiary/undead/token/centaur-mummy.png"
```
^statblock

```encounter-table
name: Centaur Mummy
creatures:
 - 1: Centaur Mummy
```