---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Snurrevin"]
NoteIcon: monster
BestiaryType: humanoid (dwarf)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 53
---
# [Snurrevin](2-Mechanics/CLI/bestiary/npc/snurrevin-tftyp.md)
*Source: Tales from the Yawning Portal p. 53*  

The tyrannical duergar, also known as gray dwarves, dwell in fantastic cities deep in the Underdark. Using ancient dwarven knowledge and myriad slaves, they work tirelessly to expand their subterranean kingdoms.

Most duergar (including females) are bald and have ashen gray skin. They wear drab clothing designed to blend in with stone, along with simple jewelry that reflects their severe and utilitarian demeanor.

## Slaves to Slavers

The duergar were once dwarves, before their greed and endless delving beneath the earth brought them into contact with the mind flayers. Held in captivity for generations by the illithids, the dwarves eventually won their independence with the aid of the evil god Laduguer. Slavery had forever changed them, however, darkening their spirits to make the duergar as evil as the tyrants they had escaped. Despite winning their freedom, duergar are dour, pessimistic, untrusting creatures, always toiling and complaining, with no memory of what it means to be happy or proud. Their craftsmanship and accomplishments endure, yet they are bereft of warmth or artistry.

Duergar make war against their dwarven kin and all other subterranean races. They forge alliances when it is convenient, then break those alliances when they have nothing more to gain. They take and hold slaves to toil in the Underdark, regarding them as free labor and crude currency.

## Tough as Stone

Like dwarves, duergar have strong constitutions. Adding to their physical stamina is an incredible mental fortitude resulting from their time as slaves of the illithids. A duergar's mind is a fortress, able to shrug off charms, illusions, and other spells.

## Born of Darkness

The Underdark is saturated with strange magical power, which the duergar absorbed over generations of imprisonment. A duergar can increase its size and strength for a short time, becoming a powerful ogre-sized warrior. If it faces a foe it can't fight, or when spying on creatures approaching its territory, it can just as easily become [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible) to slip away into the darkness. Eons spent in the Underdark also sharpened their [darkvision](/2-Mechanics/CLI/rules/senses.md#darkvision), allowing them to see twice as far as other dwarves. This keen eyesight comes at a cost, however, as a duergar's vision is compromised by sunlight.

## Infernal Master

Asmodeus, Lord of the Nine Hells, has been known to impersonate duergar gods in order to cultivate the evil brimming in the hearts of the gray dwarves. He offers them divine guidance and vengeance against their enemies while urging them on toward greater acts of tyranny, all the while concealing his true identity.

```statblock
"name": "Snurrevin (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Evil"
"ac": !!int "16"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"stats":
- !!int "14"
- !!int "11"
- !!int "14"
- !!int "14"
- !!int "10"
- !!int "9"
"speed": "25 ft."
"damage_resistances": "poison"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "Dwarvish, Undercommon"
"cr": "2"
"traits":
- "desc": "Snurrevin is a 3rd-level spellcaster. His spellcasting ability is Intelligence\
    \ (spell save DC 12, +4 to hit with spell attacks). He has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md),\
    \ [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\n1st level (4\
    \ slots): [color spray](/2-Mechanics/CLI/spells/color-spray.md), [shield](/2-Mechanics/CLI/spells/shield.md),\
    \ [silent image](/2-Mechanics/CLI/spells/silent-image.md)\n\n2nd level (2 slots):\
    \ [hold person](/2-Mechanics/CLI/spells/hold-person.md), [shatter](/2-Mechanics/CLI/spells/shatter.md)"
  "name": "spells"
- "desc": "The duergar has advantage on saving throws against poison, spells, and\
    \ illusions, as well as to resist being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)."
  "name": "Duergar Resilience"
- "desc": "While in sunlight, the duergar has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "For 1 minute, the duergar magically increases in size, along with anything\
    \ it is wearing or carrying. While enlarged, the duergar is Large, doubles its\
    \ damage dice on Strength-based weapon attacks (included in the attacks), and\
    \ makes Strength checks and Strength saving throws with advantage. If the duergar\
    \ lacks the room to become Large, it attains the maximum size possible in the\
    \ space available."
  "name": "Enlarge (Recharges after a Short or Long Rest)"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) piercing damage, or 11 (2d8 + 2) piercing damage while enlarged."
  "name": "War Pick"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage, or 9 (2d6 + 2) piercing\
    \ damage while enlarged."
  "name": "Javelin"
- "desc": "The duergar magically turns [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ until it attacks, casts a spell, or uses its Enlarge, or until its [concentration](/2-Mechanics/CLI/rules/conditions.md#concentration)\
    \ is broken, up to 1 hour (as if concentrating on a spell). Any equipment the\
    \ duergar wears or carries is [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ with it."
  "name": "Invisibility (Recharges after a Short or Long Rest)"
"source":
- "TftYP"
"image": "/2-Mechanics/CLI/bestiary/npc/token/snurrevin.png"
```
^statblock

```encounter-table
name: Snurrevin
creatures:
 - 1: Snurrevin
```