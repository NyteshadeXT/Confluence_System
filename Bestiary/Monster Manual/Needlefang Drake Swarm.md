---
cssclasses:
  - creature-note
noteType: creature
tags:
  - creature/type/beast
  - creature/role/encounter/soldier
  - creature/role/standard
  - creature/size/medium
  - creature/rank/iron
  - creature/level/2
statblock: inline
name: Needlefang Drake Swarm
level: 2
---

> [!creature-description] Description
> Savage marauders the size of cats, needlefang drakes swarm over their victims, pull them to ground, and strip them to the bone in seconds.

> [!creature-lore] Needlefang Drake Lore
> A character knows the following information with a successful Nature check.
> - **DC 15:** Humanoids keep needlefang drakes as exotic pets or as living traps—sometimes both.

```statblock
layout: Basic Dungeon Layout
image: needlefang-drake-swarm.png
name: Needlefang Drake Swarm
size: Small
rank: Iron
level: 2
encounter_role: Standard
type: Beast
subtype: Natural
prim_essence: Gathering
sec_essence: Hunt, Swift
assoc_essence: Pursuit, Devouring, Ambush, Blood
ac: 18
hp: 38
speed: 7
modifier: 7
stats: [15, 18, 14, 2, 12, 10]
fage_stats: 
saves:
  - Fortitude: 15
  - Reflex: 17
  - Will: 14
skillsaves:
  - raptor: 
  - turtle: 
damage_vulnerabilities: area attacks 5
damage_resistances: slashing 5, bludgeoning 5, piercing 5
damage_immunities: 
condition_immunities: fear, prone
senses: Perception +7
languages: -
spells:
  - 
  - 
  -  
traits:
  - name: Swarm Vulnerability (While not bloodied)
    desc: "A missed melee or ranged attack can be rerolled, at –2 to hit. Use the second roll, even if it’s lower."
  - name: Swarm Mobility
    desc: "A swarm cannot be knocked prone, and ignores difficult terrain."
actions:
  - name: Swarm of Teeth (single; at-will)
    desc: "`dice: 1d20+8|form` +8 vs. AC; `dice: 2d4+4|form` damage, or `dice: 4d4+4|form` damage against a prone target."
  - name: Pull Down (single; at-will)
    desc: "`dice: 1d20+7|form` +7 vs. Fortitude; the target is knocked [[Conditions#Prone|Prone]]."
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
> Incited by hunger, needlefang drakes fearlessly rush toward their prey, knock it prone (using pull down), and use their swarm of teeth to feast upon it.