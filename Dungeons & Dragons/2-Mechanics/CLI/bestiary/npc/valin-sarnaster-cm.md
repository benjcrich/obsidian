---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/16
- monster/size/medium
- monster/type/undead
aliases: ["Valin Sarnaster"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 182
---
# [Valin Sarnaster](2-Mechanics/CLI/bestiary/npc/valin-sarnaster-cm.md)
*Source: Candlekeep Mysteries p. 182*  

Valin Sarnaster has been thoroughly corrupted by visions of a future in which she sees herself as the immortal heir of Savras's realm.*The Canopic Being*came into her possession years ago, and an obsession with the dark rituals therein set the oracle on her present course.

Valin has become a powerful undead as the first step on her path to godhood, and is now a mummy lord.

Valin can use her lair actions in any area of the tomb.

## Valin Sarnaster's Lair

Valin can use her lair actions in any area of the tomb.

```statblock
"name": "Valin Sarnaster (CM)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "17"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"stats":
- !!int "18"
- !!int "10"
- !!int "17"
- !!int "11"
- !!int "18"
- !!int "16"
"speed": "20 ft."
"saves":
  "Charisma": !!int "8"
  "Wisdom": !!int "9"
  "Intelligence": !!int "5"
  "Constitution": !!int "8"
"skillsaves":
  "Religion": !!int "5"
  "History": !!int "5"
"damage_vulnerabilities": "fire"
"damage_immunities": "necrotic; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "The languages it knew in life"
"cr": "16"
"traits":
- "desc": "Valin Sarnaster is a 10th-level spellcaster. Her spellcasting ability is\
    \ Wisdom (spell save DC 17, +9 to hit with spell attacks). Valin has the following\
    \ cleric spells prepared:\n\nCantrips (at will): [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md),\
    \ [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\n1st level (4 slots):\
    \ [command](/2-Mechanics/CLI/spells/command.md), [guiding bolt](/2-Mechanics/CLI/spells/guiding-bolt.md),\
    \ [shield of faith](/2-Mechanics/CLI/spells/shield-of-faith.md)\n\n2nd level\
    \ (3 slots): [hold person](/2-Mechanics/CLI/spells/hold-person.md), [silence](/2-Mechanics/CLI/spells/silence.md),\
    \ [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)\n\n3rd level\
    \ (3 slots): [clairvoyance](/2-Mechanics/CLI/spells/clairvoyance.md), [dispel\
    \ magic](/2-Mechanics/CLI/spells/dispel-magic.md)\n\n4th level (3 slots):\
    \ [divination](/2-Mechanics/CLI/spells/divination.md), [dimension door](/2-Mechanics/CLI/spells/dimension-door.md)\n\
    \n5th level (2 slots): [contagion](/2-Mechanics/CLI/spells/contagion.md),\
    \ [scrying](/2-Mechanics/CLI/spells/scrying.md)\n\n6th level (1 slots): [harm](/2-Mechanics/CLI/spells/harm.md)"
  "name": "spells"
- "desc": "Valin has advantage on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
- "desc": "While her heart remains in Alessia's body, Valin re-forms inside her sarcophagus,\
    \ regaining all her hit points and becoming active again."
  "name": "Rejuvenation"
"actions":
- "desc": "Valin can use her Dreadful Glare and makes one attack with her rotting\
    \ fist."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 14 (3d6\
    \ + 4) bludgeoning damage plus 21 (6d6) necrotic damage. If the target is a\
    \ creature, it must succeed on a DC 16 Constitution saving throw or be cursed\
    \ with mummy rot. The cursed target can't regain hit points, and its hit point\
    \ maximum decreases by 10 (3d6) for every 24 hours that elapse. If the curse\
    \ reduces the target's hit point maximum to 0, the target dies, and its body turns\
    \ to dust. The curse lasts until removed by the [remove curse](/2-Mechanics/CLI/spells/remove-curse.md)\
    \ spell or other magic."
  "name": "Rotting Fist"
- "desc": "Valin targets one creature she can see within 60 feet of her. If the target\
    \ can see Valin, it must succeed on a DC 16 Wisdom saving throw against this magic\
    \ or become [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened) until\
    \ the end of Valin's next turn. If the target fails the saving throw by 5 or more,\
    \ it is also [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed) for the\
    \ same duration. A target that succeeds on the saving throw is immune to the Dreadful\
    \ Glare of all mummies and mummy lords for the next 24 hours."
  "name": "Dreadful Glare"
"legendary_actions":
- "desc": "Valin makes one attack with her rotting fist or uses her Dreadful Glare."
  "name": "Attack"
- "desc": "Blinding dust and sand swirls magically around Valin. Each creature within\
    \ 5 feet of Valin must succeed on a DC 16 Constitution saving throw or be [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded)\
    \ until the end of her next turn."
  "name": "Blinding Dust"
- "desc": "Valin utters a blasphemous word. Each non-undead creature within 10 feet\
    \ of Valin that can hear the magical utterance must succeed on a DC 16 Constitution\
    \ saving throw or be [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned) until\
    \ the end of Valin's next turn."
  "name": "Blasphemous Word (Costs 2 Actions)"
- "desc": "Valin magically unleashes negative energy. Creatures within 60 feet of\
    \ Valin, including ones behind barriers and around corners, can't regain hit points\
    \ until the end of Valin's next turn."
  "name": "Channel Negative Energy (Costs 2 Actions)"
- "desc": "Valin magically transforms into a whirlwind of sand, moves up to 60 feet,\
    \ and reverts to her normal form. While in whirlwind form, Valin is immune to\
    \ all damage, and it can't be [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled),\
    \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone),\
    \ [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained), or [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned).\
    \ Equipment worn or carried by Valin remain in her possession."
  "name": "Whirlwind of Sand (Costs 2 Actions)"
"source":
- "CM"
"image": "/2-Mechanics/CLI/bestiary/npc/token/valin-sarnaster.png"
```
^statblock

```encounter-table
name: Valin Sarnaster
creatures:
 - 1: Valin Sarnaster
```