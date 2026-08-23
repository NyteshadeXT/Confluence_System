---
cssclasses:
  - creature-note
noteType: creature
tags:
  - creature/type/beast
  - creature/type/blind
  - creature/type/ooze  
  - creature/role/encounter/skirmisher
  - creature/role/standard
  - creature/size/small
  - creature/rank/iron
  - creature/level/2
statblock: inline
name: Gray Ooze
level: 2
---

> [!creature-description] Description
> Wretched piles of stinking pus, gray oozes seek to dissolve the bones of other creatures into slime, which they use to increase their bulk.

> [!creature-lore] Gray Ooze Lore
> A character knows the following information with a successful Nature check.
> - **DC 15:** Gray oozes are especially dangerous in numbers or in close proximity to monsters that can take advantage of their bone-softening threat. 

```statblock
layout: Basic Dungeon Layout
image: gray-ooze.png
name: Gray Ooze
size: Small
rank: Iron
level: 2
encounter_role: Standard
type: Beast (blind, ooze)
subtype: Natural
prim_essence: Devouring
sec_essence: Water, Growth
assoc_essence: Venom, Hunger, Trap, Stone, Fungus
ac: 15
hp: 42
speed: 5, climb 3
modifier: 2
stats: [11, 15, 19, 1, 11, 1]
fage_stats: 
saves:
  - Fortitude: 13
  - Reflex: 15
  - Will: 13
skillsaves:
  - Stealth: 12
  - turtle: 
damage_vulnerabilities: 
damage_resistances: acid 5
damage_immunities: 
condition_immunities: gaze attacks
senses: Perception +2; blindsight 10, tremorsense 10
languages: -
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
  - name: Bone Melt (single; at-will) ✦ Acid
    desc: "*Attack* melee (one creature); `dice: 1d20+5|form` +5 vs. Fortitude; *Hit* `dice: 1d6+5|form` acid damage, and the target takes a cumulative -2 penalty ot Fortitude each time it hits (save ends)."
  - name: Slimy (single; at-will)
    desc: "The gray ooze is able to shift two squares instead of the normal one."
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
  - name: Stench (poison)
    desc: "*Trigger* An enemy ends its turn adjacent to the gray ooze. *Effect (once per round)* Close burst 2. Each enemy in the burst takes a –2 penalty to attack rolls until the end of its next turn."
  - name: 
    desc: 
```

> [!creature-tactics] Tactics
> Gray oozes attack in groups, softening up enemies with bone melt so their attacks are increasingly likely to hit.