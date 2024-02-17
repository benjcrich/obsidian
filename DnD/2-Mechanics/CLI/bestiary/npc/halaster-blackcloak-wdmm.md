---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/23
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Halaster Blackcloak"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 310
---
# [Halaster Blackcloak](2-Mechanics/CLI/bestiary/npc/halaster-blackcloak-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 310*  

As the master of Undermountain, Halaster can alter the entire dungeon to some extent. His lair actions and regional effects don't extend beyond Undermountain.

Halaster, the Mad Mage of Undermountain, is the deranged individual behind most of the traps and horrors found in the great dungeon under Waterdeep. Undermountain is his home, an amusement gallery in which others perform to entertain him.

The Mad Mage knows the ever-changing ways of Undermountain as no one else does, for he is the one who controls those changes. He prefers to remain unseen, skulking about invisibly or peering through scrying sensors that resemble wide-open eyes surrounded by sparkling motes of light.

Halaster's abilities far exceed those of most mortal wizards. His expertise with magic gates allows him to travel far and wide to engage in magical research. He spends much of his time creating gates, moving them around, and casting elder runes on them. Halaster's gates connect the different levels of Undermountain, thus enabling him to bring new monsters into the dungeon to replenish those that die or escape. Even as groups of adventurers try to gain decisive control of just a small section of Undermountain's halls, Halaster constantly alters the dungeon's perils to thwart them.

Halaster's true form is that of a tall, gaunt, male human, but he uses magic to take on many other visages and shapes. No matter what form he wears, the Mad Mage giggles and mutters incessantly. Contrary to appearances, however, Halaster is alert and attentive to the activities and preparations of all beings near him. He never willingly enters combat without first casting mage armor and mind blank on himself.

```statblock
"name": "Halaster Blackcloak (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "246"
"hit_dice": "29d8 + 116"
"stats":
- !!int "10"
- !!int "18"
- !!int "18"
- !!int "24"
- !!int "18"
- !!int "18"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "11"
  "Intelligence": !!int "14"
"skillsaves":
  "Perception": !!int "11"
  "History": !!int "21"
  "Arcana": !!int "21"
"damage_resistances": "fire; lightning (granted by the blast scepter, see \"Special\
  \ Equipment\" below)"
"senses": "darkvision 120 ft., passive Perception 21"
"languages": "Abyssal, Celestial, Common, Draconic, Dwarvish, Elvish, Infernal, Undercommon"
"cr": "23"
"traits":
- "desc": "Halaster is a 20th-level spellcaster. His spellcasting ability is Intelligence\
    \ (spell save DC 22, +14 to hit with spell attacks). He can cast [disguise self](/2-Mechanics/CLI/spells/disguise-self.md)\
    \ and [invisibility](/2-Mechanics/CLI/spells/invisibility.md) at will. He can\
    \ cast [fly](/2-Mechanics/CLI/spells/fly.md) and [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)\
    \ once each without expending a spell slot, but can't do so again until he finishes\
    \ a short or long rest. Halaster has the following wizard spells prepared:\n\n\
    At will: [disguise self](/2-Mechanics/CLI/spells/disguise-self.md), [invisibility](/2-Mechanics/CLI/spells/invisibility.md)\n\
    \n1/day: [fly](/2-Mechanics/CLI/spells/fly.md), [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)\n\
    \nCantrips (at will): [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md),\
    \ [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md), [light](/2-Mechanics/CLI/spells/light.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\
    \n1st level (4 slots): [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md), [shield](/2-Mechanics/CLI/spells/shield.md),\
    \ [silent image](/2-Mechanics/CLI/spells/silent-image.md)\n\n2nd level (3 slots):\
    \ [arcane lock](/2-Mechanics/CLI/spells/arcane-lock.md), [cloud of daggers](/2-Mechanics/CLI/spells/cloud-of-daggers.md),\
    \ [darkvision](/2-Mechanics/CLI/spells/darkvision.md), [knock](/2-Mechanics/CLI/spells/knock.md)\n\
    \n3rd level (3 slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md),\
    \ [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), [fireball](/2-Mechanics/CLI/spells/fireball.md)\n\
    \n4th level (3 slots): [confusion](/2-Mechanics/CLI/spells/confusion.md),\
    \ [hallucinatory terrain](/2-Mechanics/CLI/spells/hallucinatory-terrain.md), [polymorph](/2-Mechanics/CLI/spells/polymorph.md)\n\
    \n5th level (3 slots): [Bigby's hand](/2-Mechanics/CLI/spells/bigbys-hand.md),\
    \ [geas](/2-Mechanics/CLI/spells/geas.md), [wall of force](/2-Mechanics/CLI/spells/wall-of-force.md)\n\
    \n6th level (2 slots): [chain lightning](/2-Mechanics/CLI/spells/chain-lightning.md),\
    \ [globe of invulnerability](/2-Mechanics/CLI/spells/globe-of-invulnerability.md),\
    \ [programmed illusion](/2-Mechanics/CLI/spells/programmed-illusion.md)\n\n7th\
    \ level (2 slots): [finger of death](/2-Mechanics/CLI/spells/finger-of-death.md),\
    \ [symbol](/2-Mechanics/CLI/spells/symbol.md), [teleport](/2-Mechanics/CLI/spells/teleport.md)\n\
    \n8th level (1 slots): [maze](/2-Mechanics/CLI/spells/maze.md), [mind blank](/2-Mechanics/CLI/spells/mind-blank.md)\n\
    \n9th level (1 slots): [meteor swarm](/2-Mechanics/CLI/spells/meteor-swarm.md),\
    \ [wish](/2-Mechanics/CLI/spells/wish.md)"
  "name": "spells"
- "desc": "Halaster wears a robe of eyes that lets him see in all directions, gives\
    \ him darkvision out to a range of 120 feet, grants advantage on Wisdom (Perception)\
    \ checks that rely on sight, and allows him to see [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ creatures and objects, as well as into the Ethereal Plane, out to a range of\
    \ 120 feet.\n\nHalaster wields a blast scepter (a very rare magic item that requires\
    \ attunement). It can be used as an arcane focus. Whoever is attuned to the blast\
    \ scepter gains resistance to fire and lightning damage and can, as an action,\
    \ use it to cast [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md) as a 4th-level\
    \ spell (save DC 16) without expending a spell slot.\n\nHalaster also wears a\
    \ horned ring (a very rare magic item that requires attunement), which allows\
    \ an attuned wearer to ignore Undermountain's magical restrictions (see \"Alterations\
    \ to Magic\")."
  "name": "Special Equipment"
- "desc": "When he finishes a short rest, Halaster recovers all his spell slots of\
    \ 5th level and lower."
  "name": "Arcane Recovery (1/Day)"
- "desc": "If Halaster fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "If Halaster dies in Undermountain, he revives after 1d10 days, with all\
    \ his hit points and any missing body parts restored. His new body appears in\
    \ a random safe location in Undermountain."
  "name": "Rejuvenation"
"actions":
- "desc": "Halaster uses his blast scepter to cast [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\
    \ as a 4th-level spell. Each creature in a 15-foot cube originating from him must\
    \ make a DC 16 Constitution saving throw. On a failed save, a creature takes 5d8\
    \ thunder damage and is pushed 10 feet away. On a successful save, the creature\
    \ takes half as much damage and isn't pushed"
  "name": "Blast Scepter"
"legendary_actions":
- "desc": "Halaster casts a spell of 3rd level or lower."
  "name": "Cast Spell"
- "desc": "Halaster expends a spell slot of 4th level or lower and gains 5 temporary\
    \ hit points per level of the slot."
  "name": "Spell Ward (Costs 2 Actions)"
"source":
- "WDMM"
"image": "/2-Mechanics/CLI/bestiary/npc/token/halaster-blackcloak.png"
```
^statblock

```encounter-table
name: Halaster Blackcloak
creatures:
 - 1: Halaster Blackcloak
```