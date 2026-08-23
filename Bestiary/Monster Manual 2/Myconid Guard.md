---
cssclasses:
  - creature-note
noteType: creature
tags:
  - creature/type/fey
  - creature/type/humanoid
  - creature/type/plant
  - creature/role/encounter/soldier
  - creature/role/standard
  - creature/size/medium
  - creature/rank/iron
  - creature/level/4
statblock: inline
name: Myconid Guard
level: 4
---

> [!creature-description] Description
> Myconid guards are a colony's protectors and shock troops.

> [!creature-lore] Myconid Lore
> A character knows the following information with a successful Arcana check.
> - **DC 12** Myconids are plant creatures touched by the madness of the fomorians. Although not necessarily evil, myconids strive to expand their territory and numbers, which pits them against other creatures competing for the same resources. Myconids like dark places and often prefer the Underdark and the Shadowdark to their home plane. Because of the inherent resilience of a colony of myconids, other races cultivate them for cheap labor or enslave them. Drow, fomorians, and shadar-kai command myconids in great numbers.
> - **DC 17** Vast mushroom forests sprawl over tracts of the Feywild and areas of the Underdark and the Shadowdark, providing myconids with ideal conditions under which to thrive and to multiply. Other fungal creatures represent a full range of predators of and prey for myconids.
> - **DC 19** Myconids communicate with each other by releasing spores. These spores convey raw emotions such as fear, satisfaction, and desire. A colony’s sovereign is the only myconid that can communicate with other types of creatures, which it does by using its telepathy.

```statblock
layout: Basic Dungeon Layout
image: myconid-guard.png
name: Myconid Guard
size: Medium
rank: Iron
level: 4
encounter_role: Standard
type: Humanoid (plant)
subtype: Fey
prim_essence: Fungus
sec_essence: Growth, Plant
assoc_essence: Gathering, Life
ac: 18
hp: 56
speed: 6
modifier: 3
stats: [18, 16, 16, 8, 12, 10]
fage_stats: 
saves:
  - Fortitude: 17
  - Reflex: 16
  - Will: 14
skillsaves:
  - whale:
  - turtle: 
damage_vulnerabilities: 
damage_resistances: 
damage_immunities: 
condition_immunities: 
senses: Perception +3; tremorsense 10
languages: Common
spells:
  - 
  - 
  -  
traits:
  - name: 
    desc: 
  - name: 
    desc: 
actions:
  - name: Spiny Strike (single; at-will)
    desc: "`dice: 1d20+11|form` +11 vs. AC; 2d6+3 damage"
  - name: Pacification Spores (double; encounter) ✦ Poison
    desc: "Close Burst 1; `dice: 1d20+9|form` +9 vs. Will; 1d6+3 poison damage, and the target cannot take an attack action until the end of the myconid guard’s next turn."
legendary_actions:
  - name: 
    desc: 
  - name: 
    desc: 
bonus_actions:
  - name: Roots of the Colony (Free when the myconid guard is hit by an attack while a myconid ally is within 5 squares of it; at will)
    desc: "The myconid guard and the myconid ally both take half damage from the attack."
  - name: 
reactions:
  - name: 
    desc: 
  - name: 
    desc: 
```

> [!creature-tactics] Tactics
> When a colony comes under attack, myconid guards charge into combat. They use pacification spores to incapacitate enemies, and they attempt to subdue other enemies with spiny strike attacks.