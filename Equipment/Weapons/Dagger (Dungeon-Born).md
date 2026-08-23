---
cssclasses:
  - dnd4e-item
art: 
rank: iron
rarity: common
type: permenant
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

# Dagger

> [!metadata]
> **Iron** • **Simple** • **Melee** • **Common** • **1 gp**

*Light blades reward accuracy as much as force. Pinpoint attacks, lunges, and agile defenses are the strong points of these weapons.*

> [!power|weapon]-
> **Weapon Group:** Light Blade
> 
> **Damage** 1d4 piercing
> **Range** 5/10
> 
> **Expert Bonus** +3
> **Master Bonus** *Bleed* The target takes 1d6 persistent bleed damage. You gain an item bonus to this bleed damage equal to the weapon's item bonus to attack rolls.
> 
> **Weight** 1
> **Hands** 1
