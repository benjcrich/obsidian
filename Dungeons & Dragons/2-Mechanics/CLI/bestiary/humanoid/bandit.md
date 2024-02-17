---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/1-8
- monster/environment/arctic
- monster/environment/coastal
- monster/environment/desert
- monster/environment/forest
- monster/environment/hill
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Bandit"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Monster Manual p. 343, Hoard of the Dragon Queen, Princes of the Apocalypse, Storm King's Thunder, Tomb of Annihilation, Waterdeep: Dragon Heist, Waterdeep: Dungeon of the Mad Mage, Ghosts of Saltmarsh, Baldur's Gate: Descent Into Avernus, Icewind Dale: Rime of the Frostmaiden, Candlekeep Mysteries, Curse of Strahd, Journeys through the Radiant Citadel, Dragonlance: Shadow of the Dragon Queen, Keys from the Golden Vault. Available in the SRD and the Basic Rules.
---
# [Bandit](2-Mechanics/CLI/bestiary/humanoid/bandit.md)
*Source: Monster Manual p. 343, Hoard of the Dragon Queen, Princes of the Apocalypse, Storm King's Thunder, Tomb of Annihilation, Waterdeep: Dragon Heist, Waterdeep: Dungeon of the Mad Mage, Ghosts of Saltmarsh, Baldur's Gate: Descent Into Avernus, Icewind Dale: Rime of the Frostmaiden, Candlekeep Mysteries, Curse of Strahd, Journeys through the Radiant Citadel, Dragonlance: Shadow of the Dragon Queen, Keys from the Golden Vault. Available in the SRD and the Basic Rules.*  

Bandits rove in gangs and are sometimes led by thugs, veterans, or spellcasters. Not all bandits are evil. Oppression, drought, disease, or famine can often drive otherwise honest folk to a life of banditry.

Pirates are bandits of the high seas. They might be freebooters interested only in treasure and murder, or they might be privateers sanctioned by the crown to attack and plunder an enemy nation's vessels.

```statblock
"name": "Bandit"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Lawful alignment"
"ac": !!int "12"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "11"
- !!int "12"
- !!int "12"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "30 ft."
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "1/8"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) slashing damage."
  "name": "Scimitar"
- "desc": "Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. Hit:\
    \ 5 (1d8 + 1) piercing damage."
  "name": "Light Crossbow"
"source":
- "MM"
- "HotDQ"
- "PotA"
- "SKT"
- "ToA"
- "WDH"
- "WDMM"
- "GoS"
- "DC"
- "DIP"
- "SLW"
- "BGDIA"
- "ERLW"
- "EGW"
- "IDRotF"
- "CM"
- "CoS"
- "CRCotN"
- "JttRC"
- "SjA"
- "LoX"
- "DSotDQ"
- "KftGV"
- "PaBTSO"
- "SatO"
- "BMT"
- "DoDk"
"image": "/2-Mechanics/CLI/bestiary/humanoid/token/bandit.png"
```
^statblock

```encounter-table
name: Bandit
creatures:
 - 1: Bandit
```

## Environment

coastal, hill, arctic, urban, forest, desert