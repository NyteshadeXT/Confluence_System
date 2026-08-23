---
cssclasses:
  - creature-note
noteType: creature
tags:
  - creature/type/beast
  - creature/type/aquatic
  - creature/role/encounter/controller
  - creature/role/standard
  - creature/size/small
  - creature/rank/iron
  - creature/level/2
statblock: inline
name: Sporeback Frog
level: 2
---

> [!creature-description] Description
> The sluggish sporeback frogs have developed a symbiotic relationship with a swamp fungus. The fungus grows on the backs of the frogs, gaining nourishment from their skin while providing natural camouflage and defense against any creatures that would prey on the frogs. When a sporeback dies, the fungus releases spores that cloud the mind and blur vision. This natural defense encourages predators to seek other quarry. 

> [!creature-lore] Frog Lore
> A character knows the following information with a successful Nature check.
> - **DC 10:** After a frog kills its prey, it swallows the body whole. Afterward, the frog returns to a safe location where it regurgitates any indigestible bits. In the case of animals, this material usually amounts to little more than bones and fur, but a sentient creature often has items such as gold and jewelry, which the frog cannot process. Thus, a frog’s home can be a treasure trove of rings, necklaces, and coins. Adventurers willing to brave the swamps to find a frog den can reap a significant return for their efforts. Occasionally a family offers a reward to adventurers willing to recover an irreplaceable heirloom lost when a family member fell victim to a frog.

```statblock
layout: Basic Dungeon Layout
image: sporeback-frog.png
name: Sporeback Frog
size: Medium
rank: Iron
level: 2
encounter_role: Standard
type: Beast (aquatic)
subtype: Natural
prim_essence: Fungus
sec_essence: Water, Venom
assoc_essence: Trap, Ambush, Growth
ac: 16
hp: 42
speed: 3, swim 5
modifier: 4
stats: [15, 16, 18, 3, 15, 9]
fage_stats: 
saves:
  - Fortitude: 14
  - Reflex: 13
  - Will: 12
skillsaves:
  - Stealth: 9
  - turtle: 
damage_vulnerabilities: 
damage_resistances: 
damage_immunities: 
condition_immunities: 
senses: Perception +3; Low-light vision
languages: -
spells:
  - 
  - 
  -  
traits:
  - name: Aquatic
    desc: "The sporeback can breathe underwater. In aquatic combat, it gains a +2 bonus to attack rolls against nonaquatic creatures"
  - name: 
    desc: 
actions:
  - name: Bite (single; at-will)
    desc: "*Attack* melee (one creature); `dice: 1d20+7|form` +7 vs. AC; *Hit* `dice: 1d8+6|form` damage, and the target is [[Conditions#Slowed|Slowed 1]]."
  - name: Barbed Tongue (double; at-will)
    desc: "*Attack* melee (one creature, reach 3); `dice: 1d20+5|form` +5 vs Reflex; *Hit* `dice: 2d6+2|form` damage, and the sporeback pulls the target 2 squares knocking it [[Conditions#Prone|Prone]] in the process."
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
  - name: Spore Release ✦ Poison
    desc: "*Trigger* The sporeback drops to 0 hit points. *Attack* (free) Close burst 2 (creatures within burst); `dice: 1d20+5|form` +5 vs fortitude *Hit* `dice: 1d6+7|form` poison damage, and the target takes a -2 penalty to attack rolls (save ends)."
  - name: 
    desc: 
```

> [!creature-tactics] Tactics
> Quite possibly the laziest hunter imaginable, a sporeback frog is content to stay in one place and pull an enemy closer. Most creatures that would pose a threat to sporebacks learned long ago to avoid them, so these frogs seldom feel a pressing need to avoid conflict. When a sporeback does find itself in danger, it retreats to the nearest body of water, where it gains a slight mobility advantage. Otherwise, a sporeback lashes out with its tongue, pulling prey close enough to devour it.