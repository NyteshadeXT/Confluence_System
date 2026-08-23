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
> **Iron** • **Common** • **5 gp**

*You need to use your shield hand to wield a light shield properly. You can still use that hand to hold another item, to climb, or the like. However, you can’t use your shield hand to make attacks..*

> [!power|weapon]-
> **Armor Group:** Shields
> 
> **AC Bonus** +1
> **Check Penalty** -
> **Speed Penalty** -
> 
> **Expert Bonus** +1 AC
> **Master Bonus** 
> 
> **Weight** 6
