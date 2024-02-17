---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/26
- monster/size/large
- monster/type/fiend/devil
aliases: ["Zariel"]
NoteIcon: monster
BestiaryType: fiend (devil)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 280, Mordenkainen's Tome of Foes p. 180
---
# [Zariel](2-Mechanics/CLI/bestiary/npc/zariel-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 280, Mordenkainen's Tome of Foes p. 180*  

> [!quote]- A quote from Mordenkainen  
> 
> That which falls from grace may yet rise to regain it. If Zariel were to return to her celestial self, how glorious would be the tales!

Once a mighty angel charged with watching the tides of the Blood War, Zariel succumbed to the corrupting influence of the Nine Hells and fell from grace. Asmodeus admired Zariel's passion for war and offered her rulership of Avernus. She accepted his offer, and he transformed her into an archdevil.

Zariel's rise in status came at the expense of Bel, her pit fiend predecessor. Zariel and Bel hate each other. To keep Bel busy and out of her sight, Zariel tasks him with forging weapons, armor, and grue some demon-slaying machines.

To replenish her legions, Zariel needs the souls of mortals to create lemures, which she can then promote to higher forms of devils. She is keenly interested in collecting souls from the greatest warriors on the Material Plane. She bargains hard, and there is little hope of wriggling out of a pact. However, she expects the best from her servants, so she allows her mortal followers to live out their lives provided they continue to hone their talents to increase their value. As a result, Zariel's servants are universally effective, disciplined, and dangerous.

## Cultists of Zariel

> [!note]
> See the Cult of Zariel entry.

## Zariel's Lair

Zariel makes her lair in a basalt citadel that rises up in Avernus. From nearly a mile away, one can hear the screams and moans coming from the burned victims chained to the stronghold's wall, the dying remains of those who failed to impress the archdevil. The stronghold, covering five square miles, is surrounded by walls reinforced with high turrets. Devils of all kinds crawl over the structure, ensuring that no intruders breach their defenses.

```statblock
"name": "Zariel (MPMM)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "21"
"hp": !!int "420"
"hit_dice": "29d10 + 261"
"stats":
- !!int "27"
- !!int "24"
- !!int "28"
- !!int "26"
- !!int "27"
- !!int "30"
"speed": "50 ft., fly 150 ft."
"saves":
  "Charisma": !!int "18"
  "Wisdom": !!int "16"
  "Intelligence": !!int "16"
"skillsaves":
  "Intimidation": !!int "18"
  "Perception": !!int "16"
"damage_resistances": "cold; fire; radiant; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 26"
"languages": "all, telepathy 120 ft."
"cr": "26"
"traits":
- "desc": "Zariel casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 26):\n\nAt will:\
    \ [alter self](/2-Mechanics/CLI/spells/alter-self.md) (can become Medium when\
    \ changing her appearance), [detect evil and good](/2-Mechanics/CLI/spells/detect-evil-and-good.md),\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md), [invisibility](/2-Mechanics/CLI/spells/invisibility.md)\
    \ (self only), [major image](/2-Mechanics/CLI/spells/major-image.md), [wall of\
    \ fire](/2-Mechanics/CLI/spells/wall-of-fire.md)\n\n3/day each: [blade barrier](/2-Mechanics/CLI/spells/blade-barrier.md),\
    \ [dispel evil and good](/2-Mechanics/CLI/spells/dispel-evil-and-good.md), [finger\
    \ of death](/2-Mechanics/CLI/spells/finger-of-death.md)"
  "name": "spells"
- "desc": "Magical darkness doesn't impede Zariel's [darkvision](/2-Mechanics/CLI/rules/senses.md#darkvision)."
  "name": "Devil's Sight"
- "desc": "If Zariel fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Zariel has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Zariel regains 20 hit points at the start of her turn. If she takes radiant\
    \ damage, this trait doesn't function at the start of her next turn. Zariel dies\
    \ only if she starts her turn with 0 hit points and doesn't regenerate."
  "name": "Regeneration"
"actions":
- "desc": "Zariel makes three Flail or Longsword attacks. She can replace one attack\
    \ with a use of Horrid Touch, if available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +16 to hit, reach 10 ft., one target. Hit: 17\
    \ (2d8 + 8) force damage plus 36 (8d8) fire damage."
  "name": "Flail"
- "desc": "Melee Weapon Attack: +16 to hit, reach 10 ft., one target. Hit: 17\
    \ (2d8 + 8) radiant damage, or 19 (2d10 + 8) radiant damage when used with\
    \ two hands, plus 36 (8d8) fire damage."
  "name": "Longsword"
- "desc": "Zariel touches one creature within 10 feet of her. The target must succeed\
    \ on a DC 26 Constitution saving throw or take 44 (8d10) necrotic damage and\
    \ be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) for 1 minute. While\
    \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) in this way, the target\
    \ is [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded) and [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened).\
    \ The target can repeat the saving throw at the end of each of its turns, ending\
    \ the effect on itself on a success."
  "name": "Horrid Touch (Recharge 5-6)"
- "desc": "Zariel teleports, along with any equipment she is wearing or carrying,\
    \ up to 120 feet to an unoccupied space she can see."
  "name": "Teleport"
"legendary_actions":
- "desc": "Zariel uses Teleport."
  "name": "Teleport"
- "desc": "Zariel turns her magical gaze toward one creature she can see within 120\
    \ feet of her and commands it to burn. The target must succeed on a DC 26 Wisdom\
    \ saving throw or take 22 (4d10) fire damage."
  "name": "Immolating Gaze (Costs 2 Actions)"
"source":
- "MPMM"
- "MTF"
"image": "/2-Mechanics/CLI/bestiary/npc/token/zariel.png"
```
^statblock

```encounter-table
name: Zariel
creatures:
 - 1: Zariel
```