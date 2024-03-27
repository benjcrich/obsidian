---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/16
- monster/size/large
- monster/type/fey
aliases: ["Nintra Siotta"]
NoteIcon: monster
BestiaryType: fey
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 197
---
# [Nintra Siotta](2-Mechanics/CLI/bestiary/npc/nintra-siotta-cm.md)
*Source: Candlekeep Mysteries p. 197*  

Nintra Siotta, a chaotic evil archfey who was exiled from the Gloaming Court by the Queen of Air and Darkness long ago, is known in Faerûn by three titles: Princess of the Shadow Glass, Lady of Dread Omens, and Seeker of the Three Crowns. She appears as a 9-foot-tall humanoid made of smoky gray glass, wrapped in a cloak-like darkness that appears to devour the light.

Nintra's eyes burn with green fire, and she speaks in a high, musical voice. Deception comes naturally to her, but imprisonment in *The Scrivener's Tale*has made her impatient and prone to telepathic outbursts that betray her cruel nature.

```statblock
"name": "Nintra Siotta (CM)"
"size": "Large"
"type": "fey"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"hp": !!int "306"
"hit_dice": "36d10 + 108"
"stats":
- !!int "16"
- !!int "24"
- !!int "16"
- !!int "17"
- !!int "15"
- !!int "24"
"speed": "40 ft., fly 40 ft. (hover)"
"saves":
  "Dexterity": !!int "12"
  "Wisdom": !!int "7"
  "Strength": !!int "8"
"skillsaves":
  "Deception": !!int "12"
  "Insight": !!int "7"
  "Perception": !!int "7"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)"
"senses": "truesight 60 ft., passive Perception 17"
"languages": "Common, Elvish, Sylvan"
"cr": "16"
"traits":
- "desc": "Nintra casts one of the following spells, using Charisma as the spellcasting\
    \ ability (save DC 20) and requiring no material components:\n\n3/day each:\
    \ [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [mirror image](/2-Mechanics/CLI/spells/mirror-image.md)"
  "name": "spells"
- "desc": "If Nintra fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
"actions":
- "desc": "Nintra makes two attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 12 (2d4\
    \ + 7) piercing damage."
  "name": "Claw"
- "desc": "Ranged Spell Attack: +12 to hit, range 120 ft., one target. Hit: 10\
    \ (1d6 + 7) necrotic damage, and if the target is a creature, it must succeed\
    \ on a DC 20 Constitution saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ until the end of its next turn."
  "name": "Shard of Shadow"
- "desc": "Nintra targets a point she can see within 60 feet of her and creates a\
    \ 20-foot-radius sphere of swirling glass shards centered on that point. Each\
    \ creature in the sphere must make a DC 20 Dexterity saving throw, taking 28 (8d6)\
    \ slashing damage on a failed save, or half as much damage on a successful save.\
    \ If Nintra is in the sphere, the shards deal no damage to her."
  "name": "Storm of Shattered Glass (Recharge 6)"
"legendary_actions":
- "desc": "Nintra makes one attack."
  "name": "Attack"
- "desc": "Nintra teleports to an unoccupied space she can see within 30 feet of her."
  "name": "Fey Step"
- "desc": "Provided she is in bright or dim light, Nintra causes her shadow to attack\
    \ a creature within 10 feet of her. Her shadow makes two claw attacks, each attack\
    \ identical to Nintra's claw attack except that it deals psychic damage instead\
    \ of piercing damage."
  "name": "Shadow Strikes (Costs 2 Actions)"
"source":
- "CM"
"image": "/2-Mechanics/CLI/bestiary/npc/token/nintra-siotta.png"
```
^statblock

```encounter-table
name: Nintra Siotta
creatures:
 - 1: Nintra Siotta
```