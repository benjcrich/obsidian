---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/10
- monster/size/huge
- monster/type/construct
aliases: ["Huge Stone Golem"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Storm King's Thunder p. 153
---
# [Huge Stone Golem](2-Mechanics/CLI/bestiary/construct/huge-stone-golem-skt.md)
*Source: Storm King's Thunder p. 153*  

```statblock
"name": "Huge Stone Golem (SKT)"
"size": "Huge"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"hp": !!int "195"
"hit_dice": "17d12 + 85"
"stats":
- !!int "22"
- !!int "9"
- !!int "20"
- !!int "3"
- !!int "11"
- !!int "1"
"speed": "30 ft."
"damage_immunities": "poison; psychic; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't adamantine"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "10"
"traits":
- "desc": "The golem is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "The golem has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The golem's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "The golem makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 19 (3d8\
    \ + 6) bludgeoning damage."
  "name": "Slam"
- "desc": "The golem targets one or more creatures it can see within 10 feet of it.\
    \ Each target must make a DC 17 Wisdom saving throw against this magic. On a failed\
    \ save, a target can't use reactions, its speed is halved, and it can't make more\
    \ than one attack on its turn. In addition, the target can take either an action\
    \ or a bonus action on its turn, not both. These effects last for 1 minute. A\
    \ target can repeat the saving throw at the end of each of its turns, ending the\
    \ effect on itself on a success."
  "name": "Slow (Recharge 5-6)"
"source":
- "SKT"
"image": "/2-Mechanics/CLI/bestiary/construct/token/huge-stone-golem.png"
```
^statblock

```encounter-table
name: Huge Stone Golem
creatures:
 - 1: Huge Stone Golem
```