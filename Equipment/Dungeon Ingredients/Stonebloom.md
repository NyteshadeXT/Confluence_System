---
cssclasses:
- dnd4e-item  
art: stonebloom.png  
rank: Iron  
rarity: Common  
type: Ingredient  
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

# Stonebloom

> [!metadata]  
> **Iron** • **Ingredient** • **Common** • **Variable Value**

_A squat, hardy flower distinguished by thick gray-green petals that overlap like scales of weathered stone. Despite their rigid appearance, the petals remain flexible and extraordinarily difficult to tear. When crushed, Stonebloom produces a dense mineral-scented sap prized for its ability to temporarily strengthen flesh and harden the body against injury._

> [!power|passive]-  
> **Crafting Resource**
> Stonebloom is consumed when brewing defensive potions and other alchemical creations. It counts as an Ingredient for any recipe requiring herbs associated with physical resilience or protection.
> 
> **Harvest** A successful Nature (DC 15) check allows the flower to be harvested intact. On a failure, the thick petals are damaged, yielding only half the normal value.

> [!Info|sources & usage]-
> ## Sources
> Stonebloom thrives in mineral-rich soil and areas saturated with earth-aspected magical energy, often growing among rocky outcroppings, exposed roots, and Dungeon crystal formations.
> 
> Freshly harvested flowers retain their potency for several weeks when properly dried and stored.
> 
> ## Uses
> - Brewing defensive potions
> - Resistance elixirs
> - Fortifying alchemical preparations
> - Advanced protective alchemical recipes

> [!info|notes]-
> ## Notes
> Stonebloom is a common protective herb harvested from Iron Rank Dungeons and is valued by alchemists for its ability to reinforce the body's natural resilience without sacrificing mobility.