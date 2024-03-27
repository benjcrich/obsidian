---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/goliath
aliases: ["Aruk Thundercaller Thuunlakalaga"]
NoteIcon: monster
BestiaryType: humanoid (goliath)
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 169
---
# [Aruk Thundercaller Thuunlakalaga](2-Mechanics/CLI/bestiary/npc/aruk-thundercaller-thuunlakalaga-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 169*  

Goliaths inhabit the Spine of the World, where their mettle is tested against orcs, ogres, frost giants, remorhazes, ice trolls, young white dragons, the treacherous mountain terrain, and the cruel indifference of nature.

```statblock
"name": "Aruk Thundercaller Thuunlakalaga (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "goliath"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"stats":
- !!int "18"
- !!int "11"
- !!int "16"
- !!int "10"
- !!int "15"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "6"
  "Perception": !!int "4"
  "Survival": !!int "4"
"damage_resistances": "cold"
"senses": "passive Perception 14"
"languages": "Common, Giant"
"cr": "3"
"traits":
- "desc": "Aruk is acclimated to high altitude, including elevations above 20,000\
    \ feet."
  "name": "Mountain Born"
- "desc": "Aruk counts as one size larger when determining its carrying capacity and\
    \ the weight it can push, drag, or lift."
  "name": "Powerful Build"
"actions":
- "desc": "Aruk makes two attacks with its greataxe or hurls two javelins."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10 (1d12\
    \ + 4) slashing damage."
  "name": "Greataxe"
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 7 (1d6 + 4) piercing damage."
  "name": "Javelin"
"reactions":
- "desc": "When Aruk takes damage, it reduces the damage taken by 9 (1d12 + 3)."
  "name": "Stone's Endurance (Recharges after a Short or Long Rest)"
"source":
- "IDRotF"
"image": "/2-Mechanics/CLI/bestiary/npc/token/aruk-thundercaller-thuunlakalaga.png"
```
^statblock

```encounter-table
name: Aruk Thundercaller Thuunlakalaga
creatures:
 - 1: Aruk Thundercaller Thuunlakalaga
```