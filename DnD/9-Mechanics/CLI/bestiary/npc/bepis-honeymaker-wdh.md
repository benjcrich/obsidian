---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/0
- monster/size/small
- monster/type/humanoid/strongheart-halfling
aliases: ["Bepis Honeymaker"]
NoteIcon: monster
BestiaryType: humanoid (Strongheart halfling)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 112
---
# [Bepis Honeymaker](2-Mechanics/CLI/bestiary/npc/bepis-honeymaker-wdh.md)
*Source: Waterdeep: Dragon Heist p. 112*  

Bepis Honeymaker is a honey merchant who was kidnapped from his Trades Ward home a month ago. The Xanathar Guild tried to ransom him back, but seemingly his relatives either couldn't pay or decided not to. (In truth, his rotten in-laws destroyed the ransom notes and told Bepis's wife and children that he ran away with another family.) Ahmaergo has put him to work as a cook but threatens to give him over to the mind flayer Nihiloor every so often.

```statblock
"name": "Bepis Honeymaker (WDH)"
"size": "Small"
"type": "humanoid"
"subtype": "Strongheart halfling"
"alignment": "Lawful Good"
"ac": !!int "10"
"hp": !!int "4"
"hit_dice": "1d8"
"stats":
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "25 ft."
"senses": "passive Perception 10"
"languages": "Common, Halfling"
"cr": "0"
"traits":
- "desc": "Bepis can move through a space occupied by a creature of a size larger\
    \ than him"
  "name": "Halfling Nimbleness"
- "desc": "Bepis has advantage on saving throws against being [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Brave"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/npc/token/bepis-honeymaker.png"
```
^statblock

```encounter-table
name: Bepis Honeymaker
creatures:
 - 1: Bepis Honeymaker
```