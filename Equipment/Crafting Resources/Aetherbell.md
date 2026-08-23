---
cssclasses:
- dnd4e-item  
art: aetherbell.png  
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
    limit: 1
  - type: table
    name: Table

```

# Aetherbell

> [!metadata]  
> **Iron** • **Ingredient** • **Common** • **Variable Value**

_A slender flowering herb distinguished by violet-blue blossoms that emit a faint glow when exposed to concentrated mana. Each bell-shaped flower stores trace amounts of magical energy within its crystalline nectar, producing a soft chiming sound when disturbed. Aetherbell is prized by alchemists for its ability to restore and stabilize depleted magical reserves._

> [!power|passive]-  
> **Crafting Resource**
> Aetherbell is consumed when brewing mana-restoring potions and other alchemical creations. It counts as an Ingredient for any recipe requiring mana-restorative herbs.
> 
> **Harvest** A successful Nature (DC 15) check allows the flower to be harvested intact. On a failure, the delicate blossoms are damaged, yielding only half the normal value.

> [!Info|sources & usage]-
> 
> ## Sources
> Aetherbell thrives in areas saturated with ambient mana, particularly near Dungeon crystals, mana wells, and other places where magical energy naturally accumulates.
> 
> Freshly harvested blossoms retain their potency for several weeks when properly dried and stored.
> 
> ## Uses
> - Brewing Potions of Mana
> - Mana-restorative elixirs
> - Magical recovery draughts
> - Advanced mana-regenerative alchemical recipes

> [!info|notes]-
> 
> ## Notes
> 
> Aetherbell is one of the most common mana-restorative plants harvested from Iron Rank Dungeons. The faint chiming of a mature patch is often audible before the flowers themselves are visible.