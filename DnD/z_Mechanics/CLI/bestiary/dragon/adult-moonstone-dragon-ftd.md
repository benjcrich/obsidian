---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/ftd
- monster/cr/15
- monster/size/huge
- monster/type/dragon
aliases: ["Adult Moonstone Dragon"]
NoteIcon: monster
BestiaryType: dragon
SourceType: Bestiary
BookSource: Fizban's Treasury of Dragons p. 212
---
# [Adult Moonstone Dragon](2-Mechanics/CLI/bestiary/dragon/adult-moonstone-dragon-ftd.md)
*Source: Fizban's Treasury of Dragons p. 212*  

Ancient legends suggest that when the gods came to the First World and tried to populate it with their Humanoid followers, a clever dragon fled to the Feywild to hide a clutch of eggs. The magic of that faerie realm suffused the eggs, which hatched into the first moonstone dragons. Their descendants are now found throughout the Feywild.

Moonstone dragons are graceful and elegant creatures with opalescent scales and ruffs of emerald-green fur running down their chins, chests, backs, and tails. One horn arcs from the back of a moonstone dragon's skull and another at the tip of the nose; the two horns together form a shape that's reminiscent of a slender crescent moon. Moonstone dragons are playful and impetuous forces of mischief in their early years, but the best of them mature into wise teachers and storytellers who anchor Feywild communities. The worst of them are pompous and ill behaved, but even those remain gentle by nature and curious about all things—especially travelers from faraway places.

Moonstone dragons can project themselves into the realm of dreams to communicate with the creatures that sleep near their lairs. In this way, they inspire artists and poets, encourage great thinkers, and spur adventurers to heroic deeds. They sometimes give guidance to those in need or request help from adventurers to encourage them to greatness.

As a rule, moonstone dragons are not particularly interested in gold or copper, but they love silver, platinum, and mithral. They also cherish treasures whose value can't be easily quantified—a song sung from the heart, a lock of a loved one's hair, or a painting of a favorite place. A story of happy times fondly remembered is more precious to a moonstone dragon than a sack of gold.

## A Moonstone Dragon's Lair

For their lairs, moonstone dragons look for places kissed by the moon; lonely peaks, forest clearings, and placid lakes are among their favorite sites. Their whimsical nature makes them more likely than other dragons to establish multiple lairs even at a young age. They link their scattered sites with magic portals, often splitting their time between the Feywild, the Material Plane, and the Ethereal Plane.

The challenge rating of a legendary moonstone dragon increases by 1 when it's encountered in its lair.

```statblock
"name": "Adult Moonstone Dragon (FTD)"
"size": "Huge"
"type": "dragon"
"alignment": "typically  Neutral"
"ac": !!int "19"
"hp": !!int "195"
"hit_dice": "17d12 + 85"
"stats":
- !!int "20"
- !!int "18"
- !!int "20"
- !!int "22"
- !!int "20"
- !!int "23"
"speed": "40 ft., fly 80 ft."
"saves":
  "Charisma": !!int "11"
  "Wisdom": !!int "10"
  "Intelligence": !!int "11"
"skillsaves":
  "Stealth": !!int "9"
  "Perception": !!int "10"
  "Persuasion": !!int "11"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 20"
"languages": "Common, Draconic, Elvish, Gnomish, Sylvan"
"cr": "15"
"traits":
- "desc": "The dragon casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 19):\n\nAt will:\
    \ [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md)\n\n1/day each: [calm\
    \ emotions](/2-Mechanics/CLI/spells/calm-emotions.md), [invisibility](/2-Mechanics/CLI/spells/invisibility.md),\
    \ [revivify](/2-Mechanics/CLI/spells/revivify.md)"
  "name": "spells"
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
"actions":
- "desc": "The dragon makes one Bite attack and two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 16\
    \ (2d10 + 5) piercing damage plus 7 (2d6) radiant damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 12 (2d6\
    \ + 5) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +10 to hit, reach 15 ft., one target. Hit: 9 (1d8\
    \ + 5) bludgeoning damage. If the target is a creature, it must succeed on a\
    \ DC 18 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Tail"
- "desc": "The dragon uses one of the following breath weapons:\n\n- Dream Breath.\
    \ The dragon exhales mist in a 90-foot cone. Each creature in that area must succeed\
    \ on a DC 18 Constitution saving throw or fall [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)\
    \ for 10 minutes. This effect ends for a creature if the creature takes damage\
    \ or someone uses an action to wake it.  \n- Moonlight Breath. The dragon\
    \ exhales a beam of moonlight in a 90-foot line that is 10 feet wide. Each creature\
    \ in that area must make a DC 18 Dexterity saving throw, taking 49 (9d10) radiant\
    \ damage on a failed save, or half as much damage on a successful one.  "
  "name": "Breath Weapon (Recharge 5-6)"
"legendary_actions":
- "desc": "The dragon makes one Tail attack."
  "name": "Tail"
- "desc": "The dragon uses Spellcasting."
  "name": "Cast a Spell (Costs 2 Actions)"
"source":
- "FTD"
"image": "/2-Mechanics/CLI/bestiary/dragon/token/adult-moonstone-dragon.png"
```
^statblock

```encounter-table
name: Adult Moonstone Dragon
creatures:
 - 1: Adult Moonstone Dragon
```