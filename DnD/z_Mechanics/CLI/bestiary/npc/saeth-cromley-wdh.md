---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/illuskan-human
aliases: ["Saeth Cromley"]
NoteIcon: monster
BestiaryType: humanoid (Illuskan human)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 216
---
# [Saeth Cromley](2-Mechanics/CLI/bestiary/npc/saeth-cromley-wdh.md)
*Source: Waterdeep: Dragon Heist p. 216*  

Saeth Cromley is a retired sergeant of the City Watch, a likable fellow with a sharp, sarcastic wit. He occasionally comes out of retirement at the request of Barnibus Blastwind, and he assists the mage in investigating unusual crimes in the city. Cromley helps Barnibus relate to the common folk, and he is good at coaxing information out of them. Though Cromley was once a strict proponent of Watch regulations and dress codes, he has grown a bit lax in both matters now that he's officially retired.

```statblock
"name": "Saeth Cromley (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "Illuskan human"
"alignment": "Lawful Good"
"ac": !!int "17"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"stats":
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "4"
  "Athletics": !!int "5"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "3"
"actions":
- "desc": "Saeth makes two longsword attacks. If he has a shortsword drawn, he can\
    \ also make a shortsword attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
  "name": "Longsword"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. Hit:\
    \ 6 (1d10 + 1) piercing damage."
  "name": "Heavy Crossbow"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/npc/token/saeth-cromley.png"
```
^statblock

```encounter-table
name: Saeth Cromley
creatures:
 - 1: Saeth Cromley
```