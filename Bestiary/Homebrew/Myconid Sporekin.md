---
cssclasses:
  - creature-note
noteType: creature
tags:
  - creature/type/fey
  - creature/type/humanoid
  - creature/type/plant
  - creature/role/encounter/soldier
  - creature/role/minion
  - creature/size/medium
  - creature/rank/iron
  - creature/level/4
statblock: inline
name: Myconid Sporekin
level: 4
---

> [!creature-description] Description
> Myconid Sporekin are the ordinary members of myconid communities, tending fungal beds, gathering resources, and protecting their colonies from danger. Though less formidable than their larger kin, they defend one another instinctively, releasing clouds of numbing spores when threatened.

> [!creature-lore] Myconid Lore
> A character knows the following information with a successful Arcana check.
> - **DC 12** Myconids are plant creatures touched by the madness of the fomorians. Although not necessarily evil, myconids strive to expand their territory and numbers, which pits them against other creatures competing for the same resources. Myconids like dark places and often prefer the Underdark and the Shadowdark to their home plane. Because of the inherent resilience of a colony of myconids, other races cultivate them for cheap labor or enslave them. Drow, fomorians, and shadar-kai command myconids in great numbers.
> - **DC 17** Vast mushroom forests sprawl over tracts of the Feywild and areas of the Underdark and the Shadowdark, providing myconids with ideal conditions under which to thrive and to multiply. Other fungal creatures represent a full range of predators of and prey for myconids.
> - **DC 19** Myconids communicate with each other by releasing spores. These spores convey raw emotions such as fear, satisfaction, and desire. A colony’s sovereign is the only myconid that can communicate with other types of creatures, which it does by using its telepathy.

```statblock
layout: Basic Dungeon Layout
image: myconid-sporekin.png
name: Myconid Sporekin
size: Medium
rank: Iron
level: 4
encounter_role: Minion
type: Plant
subtype: Natural
prim_essence: Fungus
sec_essence: Growth, Plant
assoc_essence: Gathering, Life
ac: 18
hp: 1
speed: 5
modifier: 3
stats: [12, 10, 16, 15, 10, 13]
fage_stats: 
saves:
  - Fortitude: 16
  - Reflex: 14
  - Will: 16
skillsaves:
  - Nature: 9
  - turtle: 
damage_vulnerabilities: 
damage_resistances: 
damage_immunities: 
condition_immunities: 
senses: Perception +4; low-light vision
languages: Common
spells:
  - 
  - 
  -  
traits:
  - name: Fungal Communion
    desc: A myconid sporekin gains a +2 bonus to saving throws while adjacent to another myconid.
  - name: 
    desc: 
actions:
  - name: Fungal Slam (single; at-will)
    desc: "`dice: 1d20+7|form` +7 vs. AC; 4 damage."
  - name: Numbing Spores (single; encounter) ✦ Poison
    desc: "Close blast 2; creatures in blast; `dice: 1d20+5|form` +5 vs. Fortitude; Hit: The target is [[Conditions#Slowed|Slowed 1]] until the end of the myconid sporekin's next turn."
legendary_actions:
  - name: 
    desc: 
  - name: 
    desc: 
bonus_actions:
  - name: 
    desc: 
  - name: 
    desc: 
reactions:
  - name: 
    desc: 
  - name: 
    desc: 
```

> [!creature-tactics] Tactics  
> Myconid Sporekin avoid combat unless their community or fungal beds are threatened. When fighting alongside other myconids, they remain close to their kin and use Numbing Spores to slow approaching enemies. They attack primarily to protect more important members of the colony and do not pursue enemies who withdraw.