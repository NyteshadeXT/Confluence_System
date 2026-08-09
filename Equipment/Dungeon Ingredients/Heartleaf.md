---
cssclasses:
  - dnd4e-item
art: heartleaf.png
rank: Iron
rarity: Common
type: Ingredient
alias:
---

```dataviewjs
const art = dv.current().art;
if (art) {
	dv.container.classList.add("item-card-art");
	dv.paragraph(`![[${art}]]`); 
} 
```

# `=this.file.name`

> [!metadata]
> **Iron** • **Ingredient** • **Common** • **Variable Value**

*A broad-leafed woodland herb distinguished by its deep green leaves traced with crimson veins. When crushed, Heartleaf releases a fragrant sap prized for its remarkable restorative properties. It is the foundation of countless healing draughts and remains one of the most sought-after medicinal plants found within Dungeons.*

> [!power|passive]-
> **Crafting Resource**
>
> Heartleaf is consumed when brewing restorative potions and other alchemical creations. It counts as an Ingredient for any recipe requiring medicinal herbs.
> 
> **Harvest** A successful Nature (DC 15) check allows the flower to be harvested intact. On a failure, the delicate petals are damaged, yielding only half the normal value.

> [!Info|sources & usage]-
> ## Sources
> Heartleaf thrives in areas rich with natural or magical vitality, often growing beside ancient roots, crystal-fed streams, and Dungeon springs.
>
> Freshly harvested leaves retain their potency for several weeks when properly dried and stored.
>
> ## Uses
> - Brewing Potions of Healing 
> - Restorative elixirs 
> - Healing poultices 
> - Advanced regenerative alchemical recipes

> [!info|notes]-
> ## Notes
> Heartleaf is among the most common medicinal plants harvested from Iron Rank Dungeons and is valued by adventurers, herbalists, and alchemists alike.
