---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/5
- monster/size/large
- monster/type/undead
aliases: ["Skeletal Juggernaut"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 253
---
# [Skeletal Juggernaut](2-Mechanics/CLI/bestiary/undead/skeletal-juggernaut-gos.md)
*Source: Ghosts of Saltmarsh p. 253*  

As seen lumbering across the beaches in Isle of the Abbey, a skeletal juggernaut is an oversized, bipedal assembly of bones that loses a portion of its mass with each step. These skeletal guardians hold together for only a short time before disassembling into a gang of individual undead.

```statblock
"name": "Skeletal Juggernaut (GoS)"
"size": "Large"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "142"
"hit_dice": "19d10 + 38"
"stats":
- !!int "16"
- !!int "14"
- !!int "15"
- !!int "6"
- !!int "8"
- !!int "5"
"speed": "30 ft."
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": ""
"cr": "5"
"traits":
- "desc": "If the juggernaut is reduced to 0 hit points, twelve skeletons rise from\
    \ its remains."
  "name": "Disassemble"
- "desc": "If the juggernaut does not have all of its hit points at the start of its\
    \ turn, it loses 10 hit points."
  "name": "Falling Apart"
"actions":
- "desc": "The juggernaut makes two claws attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 12 (2d8\
    \ + 3) slashing damage."
  "name": "Claws"
- "desc": "The juggernaut collapses into a large heap before quickly reforming. Each\
    \ creature within 10 feet of the juggernaut must make a DC 14 Dexterity saving\
    \ throw, taking 18 (4d8) bludgeoning damage on a failed save, or half as much\
    \ damage on a successful one. A creature that fails this saving throw is also\
    \ knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Avalanche of Bones (Recharge 5-6)"
"source":
- "GoS"
- "IMR"
"image": "/2-Mechanics/CLI/bestiary/undead/token/skeletal-juggernaut.png"
```
^statblock

```encounter-table
name: Skeletal Juggernaut
creatures:
 - 1: Skeletal Juggernaut
```