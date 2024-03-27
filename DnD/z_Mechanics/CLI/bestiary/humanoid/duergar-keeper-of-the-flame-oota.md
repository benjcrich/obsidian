---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Duergar Keeper of the Flame"]
NoteIcon: monster
BestiaryType: humanoid (dwarf)
SourceType: Bestiary
BookSource: Out of the Abyss p. 226
---
# [Duergar Keeper of the Flame](2-Mechanics/CLI/bestiary/humanoid/duergar-keeper-of-the-flame-oota.md)
*Source: Out of the Abyss p. 226*  

The tyrannical duergar, also known as gray dwarves, dwell in fantastic cities deep in the Underdark. Using ancient dwarven knowledge and myriad slaves, they work tirelessly to expand their subterranean kingdoms.

Most duergar (including females) are bald and have ashen gray skin. They wear drab clothing designed to blend in with stone, along with simple jewelry that reflects their severe and utilitarian demeanor.

## Slaves to Slavers

The duergar were once dwarves, before their greed and endless delving beneath the earth brought them into contact with the mind flayers. Held in captivity for generations by the illithids, the dwarves eventually won their independence with the aid of the evil god Laduguer. Slavery had forever changed them, however, darkening their spirits to make the duergar as evil as the tyrants they had escaped. Despite winning their freedom, duergar are dour, pessimistic, untrusting creatures, always toiling and complaining, with no memory of what it means to be happy or proud. Their craftsmanship and accomplishments endure, yet they are bereft of warmth or artistry.Duergar make war against their dwarven kin and all other subterranean races. They forge alliances when it is convenient, then break those alliances when they have nothing more to gain. They take and hold slaves to toil in the Underdark, regarding them as free labor and crude currency.

## Tough as Stone

Like dwarves, duergar have strong constitutions. Adding to their physical stamina is an incredible mental fortitude resulting from their time as slaves of the illithids. A duergar's mind is a fortress, able to shrug off charms, illusions, and other spells.Born of Darkness. The Underdark is saturated with strange magical power, which the duergar absorbed over generations of imprisonment. A duergar can increase its size and strength for a short time, becoming a powerful ogre-sized warrior. If it faces a foe it can't fight, or when spying on creatures approaching its territory, it can just as easily become [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible) to slip away into the darkness. Eons spent in the Underdark also sharpened their [darkvision](/2-Mechanics/CLI/rules/senses.md#darkvision), allowing them to see twice as far as other dwarves. This keen eyesight comes at a cost, however, as a duergar's vision is compromised by sunlight.

## Infernal Master

Asmodeus, Lord of the Nine Hells, has been known to impersonate duergar gods in order to cultivate the evil brimming in the hearts of the gray dwarves. He offers them divine guidance and vengeance against their enemies while urging them on toward greater acts of tyranny, all the while concealing his true identity.

## Duergar Keeper of the Flame

The Keepers of the Flame is a well-respected order of psionic clerics that serves the red dragon Themberchaud in Gracklstugh, and whose members are advisors to the Deepking.

The duergar Keeper of the Flame uses the same statistics as the duergar in the Monster Manual, except that its challenge rating is 2 (450 XP) and it has the following additional features.

### Innate Spellcasting (Psionics)

The Keeper of the Flame's innate spellcasting ability is Wisdom (spell save DC 12). It can innately cast the following spells, requiring no components:

At will: friends, message

3/day: command

### Spellcasting

The Keeper of the Flame is a 3rd-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 12, +4 to hit with spell attacks). The Keeper of the Flame has the following cleric spells prepared:

Cantrips (at will): guidance, mending, sacred flame

1st level (4 slots): bane, inflict wounds, shield of faith

2nd level (2 slots): enhance ability, spiritual weapon

```statblock
"name": "Duergar Keeper of the Flame (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Evil"
"ac": !!int "16"
"hp": !!int "26"
"hit_dice": "4d8 + 4"
"stats":
- !!int "14"
- !!int "11"
- !!int "14"
- !!int "11"
- !!int "10"
- !!int "9"
"speed": "25 ft."
"damage_resistances": "poison"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "Dwarvish, Undercommon"
"cr": "2"
"traits":
- "desc": "The Keeper of the Flame's innate spellcasting ability is Wisdom (spell\
    \ save DC 12.) It can innately cast the following spells, requiring no components:\n\
    \nAt will: [friends](/2-Mechanics/CLI/spells/friends.md), [message](/2-Mechanics/CLI/spells/message.md)\n\
    \n1/day each: [command](/2-Mechanics/CLI/spells/command.md)"
  "name": "innate"
- "desc": "The Keeper of the Flame is a 3rd-level spellcaster. Its spellcasting ability\
    \ is Wisdom (spell save DC 12, +4 to hit with spell attacks). The Keeper of the\
    \ Flame has the following cleric spells prepared:\n\nCantrips (at will): [guidance](/2-Mechanics/CLI/spells/guidance.md),\
    \ [mending](/2-Mechanics/CLI/spells/mending.md), [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md)\n\
    \n1st level (4 slots): [bane](/2-Mechanics/CLI/spells/bane.md), [inflict wounds](/2-Mechanics/CLI/spells/inflict-wounds.md),\
    \ [shield of faith](/2-Mechanics/CLI/spells/shield-of-faith.md)\n\n2nd level\
    \ (2 slots): [enhance ability](/2-Mechanics/CLI/spells/enhance-ability.md),\
    \ [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)"
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
- "OotA"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/duergar-keeper-of-the-flame.png"
```
^statblock

```encounter-table
name: Duergar Keeper of the Flame
creatures:
 - 1: Duergar Keeper of the Flame
```