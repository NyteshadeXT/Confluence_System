---
cssclasses:
  - creature-note
noteType: creature
tags:
  - creature/type/beast
  - creature/type/spider
  - creature/role/encounter/skirmisher
  - creature/role/standard
  - creature/size/medium
  - creature/rank/iron
  - creature/level/4
statblock: inline
name: Deathjump Spider
level: 4
---

> [!creature-description] Description
> This feral hunting spider makes tremendous leaps as it chases down prey. It does not spin webs but has been known to lie in wait in dark crevices and under trap doors.

```statblock
layout: Basic Dungeon Layout
image: deathjump-spider.png
name: Deathjump Spider
size: Medium
rank: Iron
level: 4
encounter_role: Standard
type: Beast (spider)
subtype: Natural
prim_essence: Spider
sec_essence: Venom, Momentum
assoc_essence: Ambush, Trap, Hunt
ac: 20
hp: 55
speed: 6, climb 6 (spider climb); see also prodigious leap below
modifier: 8
stats: [17, 18, 15, 1, 14, 8]
fage_stats: 
saves:
  - Fortitude: 17
  - Reflex: 18
  - Will: 16
skillsaves:
  - Athletics: 10 (+20 when jumping)
  - Stealth: 11
damage_vulnerabilities: 
damage_resistances: 5 poison
damage_immunities: 
condition_immunities: 
senses: Perception +9; tremorsense 5
languages: -
spells:
  - 
  - 
  -  
traits:
  - name: Soft Fall
    desc: "The deathjump spider ignores the first 30 feet when determining damage from a fall."
  - name: 
    desc: 
actions:
  - name: Bite (single; at-will) ✦ Poison
    desc: "`dice: 1d20+6|form` +6 vs. AC; *Hit* `dice: 2d6+3|form` damage, and the target takes 5 persistent poison damage and is [[Conditions#Slowed|Slowed 1]] (save ends both)."
  - name: Prodigious Leap (double; move, encounter)
    desc: "The deathjump spider shifts 10 squares."
  - name: Death from Above (double; at-will) ✦ Poison
    desc: "The deathjump spider leaps at its prey, shifting 6 squares and making a bite attack. On a hit, it deals an extra `dice: 1d6|form` damage and also knocks the target [[Conditions#Prone|Prone]]."
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
> A deathjump spider often waits in ambush, hiding in a large tree or dark crevice, or under a thin layer of dirt and leaves resembling a trap door. It attacks by leaping at on prey using death from above. Once bloodied, it uses prodigious leap to make its escape.