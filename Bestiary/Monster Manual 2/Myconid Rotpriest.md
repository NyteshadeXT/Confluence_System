---
cssclasses:
  - creature-note
noteType: creature
tags:
  - creature/type/fey
  - creature/type/humanoid
  - creature/type/plant
  - creature/role/encounter/leader
  - creature/role/standard
  - creature/size/medium
  - creature/rank/iron
  - creature/level/3
statblock: inline
name: Myconid Rotpriest
level: 3
---

> [!creature-description] Description
> The myconid rotpriest is the colony's healer and scapegoat, taking the damage of others so that the colony as a whole can survive.

> [!creature-lore] Myconid Lore
> A character knows the following information with a successful Arcana check.
> - **DC 12** Myconids are plant creatures touched by the madness of the fomorians. Although not necessarily evil, myconids strive to expand their territory and numbers, which pits them against other creatures competing for the same resources. Myconids like dark places and often prefer the Underdark and the Shadowdark to their home plane. Because of the inherent resilience of a colony of myconids, other races cultivate them for cheap labor or enslave them. Drow, fomorians, and shadar-kai command myconids in great numbers.
> - **DC 17** Vast mushroom forests sprawl over tracts of the Feywild and areas of the Underdark and the Shadowdark, providing myconids with ideal conditions under which to thrive and to multiply. Other fungal creatures represent a full range of predators of and prey for myconids.
> - **DC 19** Myconids communicate with each other by releasing spores. These spores convey raw emotions such as fear, satisfaction, and desire. A colony’s sovereign is the only myconid that can communicate with other types of creatures, which it does by using its telepathy.

```statblock
layout: Basic Dungeon Layout
image: myconid-rotpriest.png
name: Myconid Rotpriest
size: Medium
rank: Iron
level: 4
encounter_role: Standard
type: Humanoid (plant)
subtype: Fey
prim_essence: Fungus
sec_essence: Growth, Plant
assoc_essence: Gathering, Life
ac: 15
hp: 48
speed: 5
modifier: 3
stats: [10, 12, 18, 10, 15, 18]
fage_stats: 
saves:
  - Fortitude: 16
  - Reflex: 13
  - Will: 16
skillsaves:
  - whale:
  - turtle: 
damage_vulnerabilities: radiant (if the myconid rotpriest takes radiant damage, its regeneration does not function until the end of the rotpriest’s next turn)
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
  - name: Stipe Staff (single; at-will) ✦ Weapon
    desc: "`dice: 1d20+6|form` +6 vs. AC; 2d10+3 damage"
  - name: Decomposing Spray (double; at-will) ✦ Necrotic
    desc: "Close Burst 3; `dice: 1d20+6|form` +6 vs. Fortitude; 1d10+3 necrotic damage."
legendary_actions:
  - name: 
    desc: 
  - name: 
    desc: 
bonus_actions:
  - name: Roots of the Colony (Free when the myconid rotpriest is hit by an attack while a myconid ally is within 5 squares of it; at will)
    desc: "The rotpriest and the myconid ally both take half damage from the attack."
  - name: Sacrifice for the Colony (free, when a myconid ally uses roots of the colony to deal damage to the myconid rotpriest; at-will)
    desc: "The rotpriest takes the damage dealt to the ally, and the ally takes none."
reactions:
  - name: Life Burst (when reduced to zero hit points) ✦ Healing
    desc: "Close burst 1; targets all living creatures including self; the target regains 10 hit points. If this brings the Myconid Priest above zero hit points it may continue the battle, but the use of this ability is expended."
  - name: 
    desc: 
```

> [!creature-tactics] Tactics
> A rotpriest positions itself among allies in combat, absorbing their damage with roots of the colony and sacrifice for the colony and then regenerating. It uses decomposing spray when it can hit multiple targets. Otherwise, it uses its stipe staff to bludgeon enemies into submission.