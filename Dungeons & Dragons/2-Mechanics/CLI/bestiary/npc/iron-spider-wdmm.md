---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/
- monster/size/medium
- monster/type/construct
aliases: ["Iron Spider"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 165
---
# [Iron Spider](2-Mechanics/CLI/bestiary/npc/iron-spider-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 165*  

```statblock
"name": "Iron Spider (WDMM)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "19"
"hp": !!int "80"
"stats":
- !!int "18"
- !!int "10"
- !!int "10"
- !!int "3"
- !!int "3"
- !!int "1"
"speed": "30 ft., climb 30 ft."
"damage_immunities": "poison, psychic"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 6"
"languages": ""
"actions":
- "desc": "The iron spider shoots out a 6-inch-thick web cable up to 50 feet long,\
    \ attaching the far end of the cable to a solid surface up to 50 feet away from\
    \ it. As a bonus action, it can detach the other end of the cable from itself\
    \ and attach it to a solid surface within 10 feet of it. Once it creates 200 feet\
    \ of web cable, the spider can't produce any more cable until the next dawn."
  "name": "Web Cable"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/npc/token/iron-spider.png"
```
^statblock

```encounter-table
name: Iron Spider
creatures:
 - 1: Iron Spider
```