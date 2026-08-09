---
cssclasses:
  - creature-note
noteType: creature
tags:
  - creature/type/beast
  - creature/role/minion
  - creature/size/small
  - creature/rank/iron
  - creature/level/1
statblock: inline
name: Ankheg Broodling
level: 1
---

> [!creature-description] Description
> Loathsome insects with a taste for bipedal prey, ankhegs burst from hiding to seize the unwary. An ankheg moves with great stealth, but might be detected by the faint whiff of acid dripping from its twitching mandibles.

> [!creature-lore] Ankheg Lore
> A character knows the following information with a successful Nature check.
> - **DC 10:** Ankhegs dig mazelike networks of tunnels, which might contain other monsters that have claimed part of the tunnel network as their own.
> - **DC 15:** Ankhegs are found in nesting pairs, their broodlings rarely emerging from the safety of their tunnels.

```statblock
layout: Basic Dungeon Layout
image: ankheg-broodling.png
name: Ankheg Broodling
size: Small
rank: Iron
level: 1
encounter_role: Minion
type: Beast
subtype: Natural
prim_essence: Hunt
sec_essence: Stone, Venom
assoc_essence: Trap, Devouring, Ambush, Hunger
ac: 15
hp: 1
speed: 6, burrow 2 (tunneling)
modifier: 3
stats: [10, 16, 12, 13, 1, 2]
fage_stats: 
saves:
  - Fortitude: 12
  - Reflex: 14
  - Will: 12
skillsaves:
  - Stealth: 8
  - turtle: 
damage_vulnerabilities: 
damage_resistances: 5 acid
damage_immunities: 
condition_immunities: 
senses: Perception +1; tremorsense 5
languages: string
spells:
  - 
  - 
  -  
traits:
  - name: Brood Swarm
    desc: An ankheg broodling gains a +4 bonus to attack rolls against targets that are grabbed by any ankheg.
  - name: 
    desc: 
actions:
  - name: Claw (single; at-will)
    desc: "`dice: 1d20+5|form` +5 vs. AC; 4 damage"
  - name: Mandible Rip (double; at-will) [[acid]]
    desc: "`dice: 1d20+4|form` +4 vs. AC; 6 damage. If the ankheg broodling makes a critical hit against a target, each creature adjacent to that target takes 3 acid damage."
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
> An ankheg broodling remains in hiding until an adult ankheg has brought a grabbed victim near.