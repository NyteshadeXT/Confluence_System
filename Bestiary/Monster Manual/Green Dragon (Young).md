---
cssclasses:
  - creature-note
noteType: creature
tags:
  - creature/type/magical_beast
  - creature/type/dragon
  - creature/role/encounter/skirmisher
  - creature/role/solo
  - creature/size/large
  - creature/rank/iron
  - creature/level/5
statblock: inline
name:
level:
---

> [!creature-description] Description
> Masters of negotiation and deceit, green dragons primarily live in forests or other places with strong ties to the Feywild. They breathe clouds of poisonous gas.

> [!creature-lore] Creature Lore
> A character knows the following information with a successful Nature check.
> - **DC 15** Green dragons live primarily in forests and are often drawn to locations connected to the Feywild.
> - **DC 20** Green dragons are manipulative creatures well versed in the art of deception. They like to bargain with other creatures while manipulating the situation to gain some hidden advantage. They breathe clouds of poisonous gas and use their tails to sweep enemies off their feet.

```statblock
layout: Basic Dungeon Layout
image: green-dragon.png
name: Green Dragon (Young)
size: Large
rank: Iron
level: 5
encounter_role: Solo
type: Magical Beast (dragon)
subtype: Natural
prim_essence: Venom
sec_essence: Mind, Dragon
assoc_essence: Lizard, Might, Dominion, Malign, Wing
ac: 21
hp: 260
speed: 8, fly 10 (hover), overland flight 15; see also flyby attack
modifier: 7
stats: [15, 20, 17, 15, 16, 17]
fage_stats: 
saves:
  - Fortitude: 17
  - Reflex: 19
  - Will: 17
skillsaves:
  - Bluff: 15
  - Diplomacy: 10
  - Insight: 15
  - Intimidate: 10
damage_vulnerabilities: 
damage_resistances: Poison 15
damage_immunities: 
condition_immunities: 
senses: Perception +10; darkvision
languages: Common, Draconic
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
  - name: Bite (single; at-will) ✦ Poison
    desc: "Reach 2; `dice: 1d20+10|form` +10 vs. AC; *Hit* `dice: 1d8+5|form` damage, and 5 persistant damage."
  - name: Claw (single; at-will)
    desc: "Reach 2; `dice: 1d20+10|form` +10 vs. AC; *Hit* `dice: 1d6+5|form` damage."
  - name: Double Attack (double; at-will)
    desc: "The dragon make two claw attacks which do not suffer the multi-attack penalty.  MAP applies as normal for follow up attacks."
  - name: Flyby Attack (double; recharge 5-6)
    desc: "The dragon flies up to 10 squares and makes a bite attack at any point during the move without provoking an opportunity attack from the target."
  - name: Breath Weapon (double; recharge 5-6) ✦ Poison
    desc: "Close blast 5; `dice: 1d20+8|form` +8 vs. Fortitude; `dice: 1d10+3|form` 1d10 + 3 poison damage, and the target takes 5 persistent poison damage and is [[Conditions#Slowed|Slowed 1]] (save ends both). Aftereffect: The target is [[Conditions#Slowed|Slowed 1]] (save ends). Once per encounter, when the dragon is first bloodied, it's breath weapon recharges and the dragon uses it immediately."
  - name: Frightful Presence (double; encounter) ✦ Fear
    desc: "Close burst 5; targets enemies; `dice: 1d20+8|form` +8 vs. Will; the target is [[Conditions#Stunned|Stunned 1]] until the end of the dragon’s next turn. Aftereffect: The target is [[Conditions#Frightened|Frightened 2]] for the remainder of the encounter."
legendary_actions: 
  - name: The dragon can take 1 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The dragon regains spent legendary actions at the start of its turn.
    desc: 
  - name: Tail Sweep 
    desc: "`dice: 1d20+8|form` +8 vs. Reflex; `dice: 1d8+5|form` damage, and the target is knocked [[Conditions#Prone|Prone]]."
  - name: Luring Glare ✦ Charm, Gaze
    desc: "Ranged 10; `dice: 1d20+8|form` +8 vs. Will; the target slides 2 squares. This attack does not provoke opportunity attacks."
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
> A green dragon uses flyby attack and its breath weapon to wear down enemies before landing and engaging in melee. Once per round, it uses luring glare to either move a target into the area of its breath weapon or put the target within reach of its melee attacks.
> 
> An adult, elder, and ancient green dragon uses its lashing tail to confound opponents that try to engage it in melee. The ancient green dragon uses mind poison as often as it can, attacking enemy defenders first.