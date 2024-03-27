---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/8
- monster/environment/coastal
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/size/large
- monster/type/fiend/demon
aliases: ["Shoosuva"]
NoteIcon: monster
BestiaryType: fiend (demon)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 216, Volo's Guide to Monsters p. 137
---
# [Shoosuva](2-Mechanics/CLI/bestiary/fiend/shoosuva-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 216, Volo's Guide to Monsters p. 137*  

> [!quote]- A quote from Mordenkainen  
> 
> What? Are you expecting me to comment on these creatures? Fine, how's this: a loyal pet deserves a loyal pet.

> [!quote]- A quote from Tasha  
> 
> Trust Mordenkainen to look down on any sort of companionship—even the slavering, venomous, demonic puppy kind.

A shoosuva is a hyena-demon gifted by [Yeenoghu](/2-Mechanics/CLI/bestiary/npc/yeenoghu-mpmm.md) to an especially powerful worshiper (typically a [fang of Yeenoghu](/2-Mechanics/CLI/bestiary/fiend/gnoll-fang-of-yeenoghu.md)). A shoosuva manifests shortly after a Yeenoghu-worshiping war band achieves a great victory, emerging from a billowing, fetid cloud of smoke as it arrives from the Abyss. In battle, the demon wraps its slavering jaws around one victim while lashing out with the poisonous stinger on its tail to bring down another. A creature immobilized by the poison becomes easy pickings for any nearby members of the war band.

Each shoosuva is bonded to a particular worshiper of Yeenoghu and fights alongside its master. A gnoll that has been gifted with a shoosuva is second only to a flind in status within a war band dedicated to Yeenoghu.

```statblock
"name": "Shoosuva (MPMM)"
"size": "Large"
"type": "fiend"
"subtype": "demon"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "14"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"stats":
- !!int "18"
- !!int "13"
- !!int "17"
- !!int "7"
- !!int "14"
- !!int "9"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "4"
  "Wisdom": !!int "5"
  "Constitution": !!int "6"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Abyssal, Gnoll, telepathy 120 ft."
"cr": "8"
"actions":
- "desc": "The shoosuva makes one Bite attack and one Tail Stinger attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 26 (4d10\
    \ + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 15 ft., one creature. Hit: 13\
    \ (2d8 + 4) piercing damage, and the target must succeed on a DC 14 Constitution\
    \ saving throw or become [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned).\
    \ While [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) in this way,\
    \ the target is also [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed).\
    \ The target can repeat the saving throw at the end of each of its turns, ending\
    \ the effect on itself on a success."
  "name": "Tail Stinger"
"bonus_actions":
- "desc": "When it reduces a creature to 0 hit points with a melee attack on its turn,\
    \ the shoosuva can move up to half its speed and make one Bite attack."
  "name": "Rampage"
"source":
- "MPMM"
- "VGM"
- "BMT"
"image": "/2-Mechanics/CLI/bestiary/fiend/token/shoosuva.png"
```
^statblock

```encounter-table
name: Shoosuva
creatures:
 - 1: Shoosuva
```

## Environment

coastal, forest, grassland, hill