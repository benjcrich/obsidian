---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/wood-elf
aliases: ["Fala Lefaliir"]
NoteIcon: monster
BestiaryType: humanoid (Wood elf)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 32
---
# [Fala Lefaliir](2-Mechanics/CLI/bestiary/npc/fala-lefaliir-wdh.md)
*Source: Waterdeep: Dragon Heist p. 32*  

Fala Lefaliir is an outgoing wood elf with long, braided hair. Like the elven god Corellon Larethian, Fala is neither male nor female. If referred to as "he" or "she," Fala gently requests to be addressed by name or as "they." Fala is friends with a member of the Zhentarim named Ziraj, who saved Fala's life. He visits Fala from time to time, and Fala has set aside a room for him on the second floor. Fala runs Correllon's Crown, a herbalist shop in Trollskull Alley

```statblock
"name": "Fala Lefaliir (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "Wood elf"
"alignment": "Chaotic Good"
"ac": !!int "11"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "10"
- !!int "12"
- !!int "13"
- !!int "12"
- !!int "15"
- !!int "11"
"speed": "35 ft."
"skillsaves":
  "Medicine": !!int "4"
  "Nature": !!int "3"
  "Perception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Druidic, Common, Elvish"
"cr": "2"
"traits":
- "desc": "Fala is a 4th-level spellcaster. Their spellcasting ability is Wisdom.\
    \ They have the following druid spells prepared:\n\nCantrips (at will): [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md),\
    \ [produce flame](/2-Mechanics/CLI/spells/produce-flame.md), [shillelagh](/2-Mechanics/CLI/spells/shillelagh.md)\n\
    \n1st level (4 slots): [entangle](/2-Mechanics/CLI/spells/entangle.md), [longstrider](/2-Mechanics/CLI/spells/longstrider.md),\
    \ [speak with animals](/2-Mechanics/CLI/spells/speak-with-animals.md), [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\n\
    \n2nd level (3 slots): [animal messenger](/2-Mechanics/CLI/spells/animal-messenger.md),\
    \ [barkskin](/2-Mechanics/CLI/spells/barkskin.md)"
  "name": "spells"
- "desc": "Fala has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put them to sleep."
  "name": "Fey Ancestry"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit or Melee Weapon Attack +4 to hit with\
    \ shillelagh, reach 5 ft., one target. Hit: 3 (1d6) bludgeoning damage, or\
    \ 6 (1d8 + 2) bludgeoning damage with shillelagh or if wielded with two hands."
  "name": "Quarterstaff"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/npc/token/fala-lefaliir.png"
```
^statblock

```encounter-table
name: Fala Lefaliir
creatures:
 - 1: Fala Lefaliir
```