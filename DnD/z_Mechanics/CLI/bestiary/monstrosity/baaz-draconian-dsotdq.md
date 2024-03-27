---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/1-2
- monster/size/medium
- monster/type/monstrosity
aliases: ["Baaz Draconian"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 197
---
# [Baaz Draconian](2-Mechanics/CLI/bestiary/monstrosity/baaz-draconian-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 197*  

Baaz draconians are fanatical foot soldiers that emerge from the eggs of brass dragons. They are the smallest of the draconians, and their slight wings are incapable of flight, though they do afford the draconians some control when falling. These wings are small enough to be hidden beneath a cloak or robe, and baaz draconians disguise themselves to spy for the Dragon Armies. The sight of dragons drives baaz draconians into a deadly furor. When baaz draconians die, their bodies turn to stone and unleash clouds of petrifying gas that turn their corpses and any nearby creatures into stone.

## Draconians

Draconians are bipedal monsters born from metallic dragon eggs that have been corrupted by a combination of warped alchemy and the Dragon Queen's foul magic. The Dragon Armies closely guard the secret of the draconians' creation, allowing Krynn's metallic dragons to continue to think their eggs are being held hostage so they don't oppose the Dragon Queen's conquests.

```statblock
"name": "Baaz Draconian (DSotDQ)"
"size": "Medium"
"type": "monstrosity"
"alignment": "typically  Lawful Evil"
"ac": !!int "14"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"stats":
- !!int "13"
- !!int "11"
- !!int "13"
- !!int "8"
- !!int "8"
- !!int "10"
"speed": "30 ft."
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Draconic"
"cr": "1/2"
"traits":
- "desc": "When the draconian falls and isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated),\
    \ it subtracts up to 100 feet from the fall when calculating the fall's damage."
  "name": "Controlled Fall"
- "desc": "When the draconian is reduced to 0 hit points, its body turns to stone\
    \ and releases a petrifying gas. Each creature within 5 feet of the draconian\
    \ must succeed on a DC 11 Constitution saving throw or be [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ as it begins to turn to stone. The [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ creature must repeat the saving throw at the end of its next turn. On a success,\
    \ the effect ends; otherwise the creature is [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified)\
    \ for 1 minute. After 1 minute, the body of the draconian crumbles to dust."
  "name": "Death Throes"
- "desc": "While the draconian can see a Dragon that isn't hostile to it, the draconian\
    \ has advantage on attack rolls."
  "name": "Draconic Devotion"
"actions":
- "desc": "The draconian makes two Shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) piercing damage."
  "name": "Shortsword"
"source":
- "DSotDQ"
"image": "/2-Mechanics/CLI/bestiary/monstrosity/token/baaz-draconian.png"
```
^statblock

```encounter-table
name: Baaz Draconian
creatures:
 - 1: Baaz Draconian
```