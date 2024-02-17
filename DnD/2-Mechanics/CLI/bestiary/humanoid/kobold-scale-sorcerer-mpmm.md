---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/1
- monster/environment/forest
- monster/environment/hill
- monster/environment/mountain
- monster/environment/underdark
- monster/environment/urban
- monster/size/small
- monster/type/humanoid
aliases: ["Kobold Scale Sorcerer"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 165, Volo's Guide to Monsters p. 167
---
# [Kobold Scale Sorcerer](2-Mechanics/CLI/bestiary/humanoid/kobold-scale-sorcerer-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 165, Volo's Guide to Monsters p. 167*  

Kobold scale sorcerers have an innate talent for arcane magic, making them highly valuable members of their communities. These sorcerers typically fill the role of advisor, and when threatened, a scale sorcerer lashes out with colorful magic.

A scale sorcerer who resides in or near a dragon's lair may serve as that dragon's diplomat and mouthpiece—anticipating the dragon's needs, issuing commands to others on the dragon's behalf, and reporting information back to the dragon. Such scale sorcerers often wear artificial wings, which are a sign of their draconic office. Scale sorcerers are just as awed by and respectful of dragons as others who venerate these mighty creatures, but they know that duty requires them not to fawn over their master at all times. They also understand that their frequent proximity to their dragon master means they would probably be the first to die if their master became angry or displeased, so they frantically maintain a balance between adoration and terror in their behavior toward their master.

```statblock
"name": "Kobold Scale Sorcerer (MPMM)"
"size": "Small"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "15"
"hp": !!int "27"
"hit_dice": "5d6 + 10"
"stats":
- !!int "7"
- !!int "15"
- !!int "14"
- !!int "10"
- !!int "9"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "1"
  "Arcana": !!int "2"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Draconic"
"cr": "1"
"traits":
- "desc": "The kobold casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 12):\n\nAt will:\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\
    \n2/day each: [charm person](/2-Mechanics/CLI/spells/charm-person.md), [fog\
    \ cloud](/2-Mechanics/CLI/spells/fog-cloud.md), [levitate](/2-Mechanics/CLI/spells/levitate.md)"
  "name": "spells"
- "desc": "The kobold has advantage on an attack roll against a creature if at least\
    \ one of the kobold's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
- "desc": "While in sunlight, the kobold has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "The kobold makes two Dagger or Chromatic Bolt attacks. It can replace one\
    \ attack with a use of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
- "desc": "Ranged Spell Attack: +4 to hit, range 60 feet, one target. Hit: 9 (2d6\
    \ + 2) of a type of the kobold's choice: acid, cold, fire, lightning, poison,\
    \ or thunder."
  "name": "Chromatic Bolt"
"source":
- "MPMM"
- "VGM"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/kobold-scale-sorcerer.png"
```
^statblock

```encounter-table
name: Kobold Scale Sorcerer
creatures:
 - 1: Kobold Scale Sorcerer
```

## Environment

forest, hill, mountain, underdark, urban