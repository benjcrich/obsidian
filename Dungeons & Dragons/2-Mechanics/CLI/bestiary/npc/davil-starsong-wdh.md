---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Davil Starsong"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 199
---
# [Davil Starsong](2-Mechanics/CLI/bestiary/npc/davil-starsong-wdh.md)
*Source: Waterdeep: Dragon Heist p. 199*  

Within the Waterdeep division of the Black Network, Davil is accorded the title of Master of Opportunities and Negotiations because he's good at sniffing out lucrative business deals, and he makes friends easily.

Like many sun elves, Davil has an affinity for magic and is gifted with the kind of patience that comes with a long life span. Unlike most, he's not the least bit pretentious or aloof. He keeps a room at the Yawning Portal and does all his business in the establishment's taproom. He negotiates deals with grace and aplomb, even while drunk, and uses an elven lute as a spellcasting focus.

Davil can put the characters in contact with other leaders of the Black Network's Waterdeep division, namely Istrid Horn (if they need a loan), Skeemo Weirdbottle (if they need magic), Tashlyn Yafeera (if they need weapons or mercenaries), and Ziraj the Hunter (if they need a highly skilled assassin).

## The Doom Raiders

The Doom Raiders were five unscrupulous adventurers who liked to plunder lich lairs (called "dooms" by some). They gave up adventuring to join the Black Network and came to Waterdeep three years ago with plans to establish a Zhentarim foothold in the city. In that time, they have forged alliances with various nobles and guilds and run afoul of others, all the while fending off Harper spies.

```statblock
"name": "Davil Starsong (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral"
"ac": !!int "15"
"hp": !!int "82"
"hit_dice": "15d8 + 15"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "16"
- !!int "12"
- !!int "17"
"speed": "30 ft."
"saves":
  "Charisma": !!int "6"
  "Dexterity": !!int "5"
"skillsaves":
  "Insight": !!int "4"
  "Perception": !!int "4"
  "History": !!int "6"
  "Performance": !!int "6"
  "Arcana": !!int "6"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Draconic, Dwarvish, Elvish"
"cr": "6"
"traits":
- "desc": "Davil is a 12th-level spellcaster. His spellcasting ability is Charisma\
    \ (spell save DC 14, +6 to hit with spell attacks) He has the following bard spells\
    \ prepared:\n\nCantrips (at will): [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [mending](/2-Mechanics/CLI/spells/mending.md), [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md),\
    \ [vicious mockery](/2-Mechanics/CLI/spells/vicious-mockery.md)\n\n1st level\
    \ (4 slots): [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md), [disguise\
    \ self](/2-Mechanics/CLI/spells/disguise-self.md), [sleep](/2-Mechanics/CLI/spells/sleep.md)\n\
    \n2nd level (3 slots): [crown of madness](/2-Mechanics/CLI/spells/crown-of-madness.md),\
    \ [invisibility](/2-Mechanics/CLI/spells/invisibility.md), [suggestion](/2-Mechanics/CLI/spells/suggestion.md)\n\
    \n3rd level (3 slots): [nondetection](/2-Mechanics/CLI/spells/nondetection.md),\
    \ [sending](/2-Mechanics/CLI/spells/sending.md), [tongues](/2-Mechanics/CLI/spells/tongues.md)\n\
    \n4th level (3 slots): [compulsion](/2-Mechanics/CLI/spells/compulsion.md),\
    \ [freedom of movement](/2-Mechanics/CLI/spells/freedom-of-movement.md), [polymorph](/2-Mechanics/CLI/spells/polymorph.md)\n\
    \n5th level (2 slots): [dominate person](/2-Mechanics/CLI/spells/dominate-person.md),\
    \ [greater restoration](/2-Mechanics/CLI/spells/greater-restoration.md)\n\n6th\
    \ level (1 slots): [Otto's irresistible dance](/2-Mechanics/CLI/spells/ottos-irresistible-dance.md)"
  "name": "spells"
- "desc": "Davil has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put him to sleep."
  "name": "Fey Ancestry"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage. Or Ranged Weapon Attack: +5 to hit, range 20/60 ft.,\
    \ one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "WDH"
"image": "/2-Mechanics/CLI/bestiary/npc/token/davil-starsong.png"
```
^statblock

```encounter-table
name: Davil Starsong
creatures:
 - 1: Davil Starsong
```