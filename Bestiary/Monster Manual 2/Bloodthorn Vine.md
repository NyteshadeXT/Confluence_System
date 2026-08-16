---
cssclasses:
  - creature-note
noteType: creature
tags:
  - creature/type/beast
  - creature/type/plant
  - creature/role/soldier
  - creature/size/medium
  - creature/rank/iron
  - creature/level/2
statblock: inline
name: Bloodthorn Vine
level: 2
---

> [!creature-description] Description
> Deadly bloodthorn vines creep through forests seeking the life fluids of other creatures to draw up through their hollow thorns.

> [!creature-lore] Bloodthorn Vine Lore
> A character knows the following information with a successful Nature check.
> - **DC 10:** A bloodthorn vine attacks by grabbing a foe and sucking its blood through a sharp, hollow thorn. When a bloodthorn vine feeds, its pale leaves turn the color of its victim’s blood.

```statblock
layout: Basic Dungeon Layout
image: bloodthorn-vine.png
name: Bloodthorn Vine
size: Medium
rank: Iron
level: 2
type: Beast (plant)
subtype: Natural
prim_essence: Growth
sec_essence: Plant, Spike
assoc_essence: Blood, Hunger, Ambush, Trap
ac: 18
hp: 41
speed: 5 (forest walk)
modifier: 3
stats: [17, 10, 17, 2, 14, 6]
fage_stats: 
saves:
  - Fortitude: 15
  - Reflex: 12
  - Will: 14
skillsaves:
  - salamander:
  - turtle: 
damage_vulnerabilities: 
damage_resistances:
damage_immunities: 
condition_immunities:
senses: Perception +3; blindsight 10
languages: string
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
  - name: Striking Vine (single; at-will)
    desc: "`dice: 1d20+9|form` +9 vs. AC; `dice: 1d8+5|form` damage"
  - name: Impaling Thorn (single; recharges when the bloodthorn vine doesn’t have a creature grabbed; Healing)
    desc: "The vine impales the target’s flesh with a thorn: `dice: 1d20+9|form` +9 vs. Fortitude; `dice: 1d8+4|form` damage, and the target is grabbed. **Sustain** *Double* The vine sustains the grab, the target takes `dice: 2d8+4|form` damage, and the vine regains 5 hit points."
  - name: Pulling Vines (single free; at-will)
    desc: "The bloodthorn vine shifts 1 square, pulling any creature grabbed by it into a space adjacent to it."
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
