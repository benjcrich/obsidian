---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/2
- monster/environment/desert
- monster/environment/forest
- monster/environment/underdark
- monster/size/medium
- monster/type/monstrosity
aliases: ["Yuan-ti Broodguard"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 273, Volo's Guide to Monsters p. 203
---
# [Yuan-ti Broodguard](2-Mechanics/CLI/bestiary/monstrosity/yuan-ti-broodguard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 273, Volo's Guide to Monsters p. 203*  

> [!quote]- A quote from Mordekainen  
> 
> Tasha once likened histachii to the bees that tend to larvae in beehives. It is a fanciful view of a horrific process.

Broodguards were once Humanoids, but they have been transformed by yuan-ti into simpleminded, scaly Monstrosities that do their serpentine masters' bidding. The transformation process warps not only a subject's body but also their mind, making them instinctively obey any yuan-ti and filling them with a seething rage at the sight of non-reptilian creatures.

Although broodguards can no longer think as clearly as before their transformation, they are able to perform simple yet important tasks in the community, such as guarding eggs or patrolling for intruders. Yuan-ti refer to broodguards as "histachii," which means "egg-watchers."

Most broodguards are made from human captives forced to consume a magical brew that renders them helpless and unable to fight off the inevitable transformation. A human transformed into a broodguard loses all semblance of who they once were. A broodguard is hairless and emaciated, with scaly skin. They have a forked tongue, and they smell faintly of rotting meat. Broodguards can speak but rarely do so, preferring to communicate via snakelike hisses and guttural noises.

```statblock
"name": "Yuan-ti Broodguard (MPMM)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Typically  Neutral Evil"
"ac": !!int "14"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"stats":
- !!int "15"
- !!int "14"
- !!int "14"
- !!int "6"
- !!int "11"
- !!int "4"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "4"
  "Wisdom": !!int "2"
  "Strength": !!int "4"
"skillsaves":
  "Perception": !!int "2"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Abyssal, Common, Draconic"
"cr": "2"
"traits":
- "desc": "At the start of its turn, the broodguard can gain advantage on all melee\
    \ weapon attack rolls it makes during that turn, but attack rolls against it have\
    \ advantage until the start of its next turn."
  "name": "Reckless"
"actions":
- "desc": "The broodguard makes one Bite attack and two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage."
  "name": "Claw"
"source":
- "MPMM"
- "VGM"
"image": "/2-Mechanics/CLI/bestiary/monstrosity/token/yuan-ti-broodguard.png"
```
^statblock

```encounter-table
name: Yuan-ti Broodguard
creatures:
 - 1: Yuan-ti Broodguard
```

## Environment

desert, forest, underdark