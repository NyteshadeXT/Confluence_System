---
cssclasses:
  - dnd4e-item
art: 
rank: iron
rarity: common
type: consumable
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
  - type: table
    name: Table

```

# Potion of Healing

> [!metadata]
> **Iron** • **Potion** • **Common** • **50 gp**

*A crimson elixir brewed from restorative herbs and infused with a measure of Quintessence. The potion rapidly accelerates the body's natural healing, allowing injuries to mend with remarkable speed.*

> [!power|consumable]-
> **Single Action**
>
> Drink this potion and spend a healing surge. 
> 
> After use, the potion is destroyed.

## Arcane Pattern
**Discipline** Alchemy (Trained)
**Pattern** Potion of Healing
**Complexity** Simple

**Crafting DC** 15 (Iron)
**Crafting Progress** 10
**Batch Size** 1 potion

**Supplies**
- Healing Herbs ×3
- [[Crystal Water]] ×1
- [[Quintessence]] x1
- Gold 15 gp
