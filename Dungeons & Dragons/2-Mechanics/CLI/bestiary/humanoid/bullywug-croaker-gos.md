---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/bullywug
aliases: ["Bullywug Croaker"]
NoteIcon: monster
BestiaryType: humanoid (bullywug)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 232
---
# [Bullywug Croaker](2-Mechanics/CLI/bestiary/humanoid/bullywug-croaker-gos.md)
*Source: Ghosts of Saltmarsh p. 232*  

Some bullywugs are born with the ability to weave magic into their songs. These rare specimens are raised in protected enclaves where they are taught to use their magic to both heal and harm. As demonstrated in Danger at Dunwater, they are among the most pompous of bullywugs.

```statblock
"name": "Bullywug Croaker (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "bullywug"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "14"
- !!int "12"
- !!int "12"
- !!int "7"
- !!int "15"
- !!int "10"
"speed": "20 ft., swim 40 ft."
"saves":
  "Constitution": !!int "3"
"skillsaves":
  "Stealth": !!int "3"
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": "Bullywug"
"cr": "2"
"traits":
- "desc": "The croaker can breathe air and water."
  "name": "Amphibious"
- "desc": "The croaker can communicate simple concepts to frogs and toads when it\
    \ speaks in Bullywug."
  "name": "Speak with Frogs and Toads"
- "desc": "The croaker's long jump is up to 20 feet and its high jump is up to 10\
    \ feet, with or without a running start."
  "name": "Standing Leap"
- "desc": "The croaker has advantage on Dexterity (Stealth) checks made to hide in\
    \ swampy terrain."
  "name": "Swamp Camouflage"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "The croaker sings a song of marshy doom. Each chosen creature within 30\
    \ feet of the croaker that can hear the song must make a DC 12 Wisdom saving throw,\
    \ taking 9 (2d8) psychic damage on a failed save, or half as much damage on\
    \ a successful one. A creature that fails this saving throw also has disadvantage\
    \ on Constitution saving throws until the end of its next turn."
  "name": "Glaaar-pat (3/Day)"
- "desc": "The croaker sings an ode to an elder froghemoth. Each bullywug within 30\
    \ feet of the croaker that can hear the song gains 10 temporary hit points."
  "name": "Rooooo-glog (1/Day)"
"source":
- "GoS"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/bullywug-croaker.png"
```
^statblock

```encounter-table
name: Bullywug Croaker
creatures:
 - 1: Bullywug Croaker
```