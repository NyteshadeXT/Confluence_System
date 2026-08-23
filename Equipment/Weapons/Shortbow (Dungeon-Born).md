---
cssclasses:
  - dnd4e-item
art: 
rank: iron
rarity: common
type: permanent
alias: 
---

```base
views:
  - type: cards
    name: View
    filters:
      and:
        - if(this.art, art == this.art, false)
    order: []
    image: note.art
    limit: 1
  - type: table
    name: Table

```

# Battleaxe

> [!metadata]
> **Iron** • **Marital** • **Ranged** • **Common** • **25 gp**

*A bow is a shaft of strong, supple material with a string stretched between its two ends. It’s a projectile weapon that you use to fire arrows. Bows take training to use effectively, and they can be extremely deadly in expert hands.*

> [!power|weapon]-
> **Weapon Group:** Bow
> 
> **Damage** 1d8 slashing
> **Range** 15/30
> 
> **Expert Bonus** +2
> **Master Bonus** *Pin* If the target of a critical hit is adjacent to a surface, it gets stuck to that surface by the missile. The target is [[Conditions#Immobilized|Immobilized]] and must spend an action to attempt a DC 10 Athletics check to pull the missile free; it can't move from its space until it succeeds. The creature doesn't become stuck if it is incorporeal, is liquid or could otherwise escape without effort.
> 
> **Weight** 2
> **Hands** 2
