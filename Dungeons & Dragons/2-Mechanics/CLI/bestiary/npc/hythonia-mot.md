---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mot
- monster/cr/17
- monster/size/large
- monster/type/monstrosity
aliases: ["Hythonia"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Mythic Odysseys of Theros p. 252
---
# [Hythonia](2-Mechanics/CLI/bestiary/npc/hythonia-mot.md)
*Source: Mythic Odysseys of Theros p. 252*  

Theros's reclusive medusas often delight in collecting and expanding their galleries of petrified victims. Unlike other medusas, Hythonia isn't merely a collector; she's an artist.

When Hythonia came to the island of Skathos, the inhabitants worshiped her as an avatar of the god Pharika. The cultists eagerly offered themselves up to the medusa's petrifying gaze in hopes of gaining Pharika's favor. Seeing herself surrounded by willing devotees, Hythonia formulated a cruel plan. After encouraging them to engage in wild rituals, Hythonia began turning her followers to stone, weaving their forms to create a grisly throne made of their petrified bodies.

While the medusa's victims have dwindled, tales of the medusa queen and the divine secrets she hoards have not. Hythonia eagerly trades the mysteries she knows but demands a constant price: a beautiful individual to become part of her throne.

```statblock
"name": "Hythonia (MOT)"
"size": "Large"
"type": "monstrosity"
"alignment": "Lawful Evil"
"ac": !!int "17"
"hp": !!int "199"
"hit_dice": "21d10 + 84"
"stats":
- !!int "21"
- !!int "17"
- !!int "19"
- !!int "14"
- !!int "16"
- !!int "18"
"speed": "40 ft., climb 40 ft., swim 40 ft."
"saves":
  "Charisma": !!int "10"
  "Strength": !!int "11"
  "Constitution": !!int "10"
"skillsaves":
  "Deception": !!int "10"
  "Stealth": !!int "9"
  "Insight": !!int "9"
  "Perception": !!int "9"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 19"
"languages": "Common"
"cr": "17"
"traits":
- "desc": "Hythonia's spellcasting ability is Charisma (spell save DC 18). She can\
    \ innately cast [animate objects](/2-Mechanics/CLI/spells/animate-objects.md)\
    \ once per day requiring no material components.\n\n1/day: [animate objects](/2-Mechanics/CLI/spells/animate-objects.md)"
  "name": "innate"
- "desc": "If Hythonia fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "When a creature that can see Hythonia's eyes starts its turn within 30\
    \ feet of her, Hythonia can force it to make a DC 18 Constitution saving throw\
    \ if she isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ and can see the creature. If the saving throw fails by 5 or more, the creature\
    \ is instantly [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified). Otherwise,\
    \ on a failed save the creature begins to turn to stone and is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained).\
    \ The [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained) creature must\
    \ repeat the saving throw at the end of its next turn, becoming [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified)\
    \ on a failure or ending the effect on a success. The petrification lasts until\
    \ the creature is freed by the [greater restoration](/2-Mechanics/CLI/spells/greater-restoration.md)\
    \ spell or other magic. Unless surprised, a creature can avert its eyes to avoid\
    \ the saving throw at the start of its turn. If the creature does so, it can't\
    \ see Hythonia until the start of its next turn, when it can avert its eyes again.\
    \ If the creature looks at Hythonia in the meantime, it must immediately make\
    \ the save. If Hythonia sees herself reflected on a polished surface within 30\
    \ feet of her and in an area of bright light, she is affected by her own gaze."
  "name": "Petrifying Gaze"
- "desc": "If Hythonia is reduced to 0 hit points, she doesn't die or fall [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious).\
    \ Instead, she sheds her skin, regains 199 hit points, and moves up to her speed\
    \ without provoking opportunity attacks."
  "name": "Shed Skin (Mythic Trait; Recharges after a Short or Long Rest)"
"actions":
- "desc": "Hythonia makes three attacks: one with her claws, one to constrict, and\
    \ one with her snaky hair."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 9 (1d8\
    \ + 5) slashing damage plus 4 (1d8) poison damage."
  "name": "Claws"
- "desc": "Melee Weapon Attack: +11 to hit, reach 15 ft., one Large or smaller creature.\
    \ Hit: 16 (2d10 + 5) bludgeoning damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 19). Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ and takes 15 (3d6 + 5) bludgeoning damage at the start of each of its turns,\
    \ and Hythonia can't constrict another target."
  "name": "Constrict"
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 31\
    \ (4d12 + 5) bludgeoning damage, and Hythonia can pull the target up to 5 feet\
    \ closer to her if it is a Large or smaller creature."
  "name": "Snaky Hair"
"legendary_actions":
- "desc": "Hythonia moves up to her speed without provoking opportunity attacks."
  "name": "Move"
- "desc": "Hythonia makes one attack with her snaky hair."
  "name": "Snaky Hair"
- "desc": "Hythonia causes stone spikes to erupt from the ground in a 30-foot radius\
    \ centered on her. The area becomes difficult terrain until the start of her next\
    \ turn. Any creature, other than Hythonia, takes 9 (2d8) piercing damage for\
    \ every 5 feet it moves on those spikes."
  "name": "Petrified Earth (Costs 2 Actions)"
"source":
- "MOT"
"image": "/2-Mechanics/CLI/bestiary/npc/token/hythonia.png"
```
^statblock

```encounter-table
name: Hythonia
creatures:
 - 1: Hythonia
```