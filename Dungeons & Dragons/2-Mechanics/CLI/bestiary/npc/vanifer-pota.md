---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/tiefling
aliases: ["Vanifer"]
NoteIcon: monster
BestiaryType: humanoid (tiefling)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 203
---
# [Vanifer](2-Mechanics/CLI/bestiary/npc/vanifer-pota.md)
*Source: Princes of the Apocalypse p. 203*  

Vanifer's rough childhood has hardened her heart against others. The world is a corrupt, painful place, she thinks, and deserving of a fiery end. For years, she was a dancer and concubine in a pasha's court in Calimshan. Later, she took up the mantle of prophet when she found Tinderstrike, and the same ruthless ambition and practiced manipulation that enabled her to escape a life of servitude serves her well as the head of a growing cult.

For Vanifer, battle is best observed at a distance. She prefers to hurl destructive magic from afar. Those who challenge Vanifer in melee learn a painful lesson, as she and Tinderstrike make a formidable pair.

In the Fire Node

When enemies threaten the Temple of Eternal Flame, Vanifer withdraws to the Weeping Colossus, the fire node. Within this node, Vanifer gains one additional use of her Legendary Resistance trait.

```statblock
"name": "Vanifer (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "tiefling"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"stats":
- !!int "11"
- !!int "16"
- !!int "17"
- !!int "12"
- !!int "13"
- !!int "19"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "8"
  "Performance": !!int "8"
  "Arcana": !!int "5"
"damage_immunities": "fire"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Ignan, Infernal"
"cr": "9"
"traits":
- "desc": "Vanifer is a 10th-level spellcaster. Her spellcasting ability is Charisma\
    \ (spell save DC 16, +8 to hit with spell attacks). Vanifer knows the following\
    \ sorcerer spells:\n\nCantrips (at will): [chill touch](/2-Mechanics/CLI/spells/chill-touch.md),\
    \ [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md), [friends](/2-Mechanics/CLI/spells/friends.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [message](/2-Mechanics/CLI/spells/message.md),\
    \ [produce flame](/2-Mechanics/CLI/spells/produce-flame.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [burning hands](/2-Mechanics/CLI/spells/burning-hands.md),\
    \ [chromatic orb](/2-Mechanics/CLI/spells/chromatic-orb.md), [hellish rebuke](/2-Mechanics/CLI/spells/hellish-rebuke.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md)\n\n2nd level (3 slots): [darkness](/2-Mechanics/CLI/spells/darkness.md),\
    \ [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md), [misty step](/2-Mechanics/CLI/spells/misty-step.md),\
    \ [scorching ray](/2-Mechanics/CLI/spells/scorching-ray.md)\n\n3rd level (3\
    \ slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md), [fireball](/2-Mechanics/CLI/spells/fireball.md),\
    \ [hypnotic pattern](/2-Mechanics/CLI/spells/hypnotic-pattern.md)\n\n4th level\
    \ (3 slots): [wall of fire](/2-Mechanics/CLI/spells/wall-of-fire.md)\n\n5th\
    \ level (2 slots): [dominate person](/2-Mechanics/CLI/spells/dominate-person.md)"
  "name": "spells"
- "desc": "When Vanifer drops to 0 hit points, her body is consumed in a flash of\
    \ fire and smoke. Anything she was wearing or carrying is left behind among ashes."
  "name": "Funeral Pyre"
- "desc": "If Vanifer fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (2/Day)"
"actions":
- "desc": "Vanifer makes two attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +9 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 7 (1d4 + 5) piercing damage plus 7 (2d6) fire damage."
  "name": "Tinderstrike"
"source":
- "PotA"
"image": "/2-Mechanics/CLI/bestiary/npc/token/vanifer.png"
```
^statblock

```encounter-table
name: Vanifer
creatures:
 - 1: Vanifer
```