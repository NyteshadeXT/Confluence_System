---
cssclasses:
  - dnd4e-item
art: corpseflower.png
rank: Iron
rarity: Uncommon
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

# Corpse Flower

> [!metadata]
> **Iron** • **Ingredient** • **Uncommon** • **Variable Value**

*When the Dungeon's magic is spent, the monstrous Corpseflower collapses into a single pale violet blossom no larger than a shield. Its waxy petals shimmer with faint violet-and-gold veins, while a sweet, earthy fragrance lingers in the air. Though harmless in this dormant state, the flower still holds traces of the Dungeon's remarkable power over life, decay, and renewal.*

> [!power|passive]-
> **Crafting Resource**
>
> A harvested Corpse Flower is consumed when crafting advanced alchemical reagents, restorative tonics, poisons, and items infused with **Fungus**, **Growth**, or **Devouring** Essence. It counts as an Ingredient for any recipe requiring rare fungal flora.
> 
> **Harvest** A successful Nature (DC 15) check allows the flower to be harvested intact. On a failure, the delicate petals are destroyed.

> [!Info|sources & usage]-
> ## Sources
> A Corpse Flower can only be harvested for a short time after a Corpseflower manifestation has been defeated. Within a few hours, the remaining Dungeon Essence disperses and the blossom withers into grey dust, leaving nothing behind.
> 
> The flower cannot be cultivated naturally. Every known specimen has originated within a Dungeon.
> 
> ## Uses
> - Advanced restorative elixirs
> - Potent fungal poisons
> - Essence catalysts
> - Rare alchemical reagents
> - Experimental transmutation recipes

> [!info|notes]-
> ## Notes
> Scholars believe the dormant blossom represents the Corpseflower's original biological form after the Dungeon withdraws the magic that sustained it. Many alchemists prize fresh specimens, claiming the petals retain a fleeting balance between growth and decay that cannot be replicated by any other known ingredient.