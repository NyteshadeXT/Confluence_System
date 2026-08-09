---
cssclasses:
  - dnd4e-item
art: crystal-water.png
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

*Crystal-clear water infused with the latent magic of a Dungeon. Tiny motes of emerald light drift lazily beneath its surface, and when poured into a vessel they continue to shimmer for hours. Crystal Water serves as an ideal medium for brewing restorative potions and stabilizing delicate alchemical reactions.*

> [!power|passive]-
> **Crafting Resource**
>
> Crystal Water is consumed when crafting potions and other alchemical creations. It counts as an Ingredient for any recipe requiring magically infused water.
> 
> Crystal Water is found only where a Dungeon's magical energy has naturally saturated a body of water. Common sources include areas like enchanted pools, crystal-fed springs, underground reservoirs and sacred Dungeon fountains. Once removed from its source, Crystal Water retains its magical properties indefinitely when stored in a sealed alchemical flask. Crystal Water is valued for its purity rather than its magical power. Although it contains traces of Dungeon energy, it cannot replace Quintessence in a crafting recipe.
> 
>> 
> **Harvest** Harvest one vial per attempt.

> [!Info|sources & usage]-
> ## Sources
> Crystal Water forms where Dungeon Essence saturates naturally flowing water, most commonly in crystal-fed pools, underground springs, and tranquil basins untouched by corruption.
> 
> Once collected in a suitable vessel, Crystal Water retains its magical properties indefinitely, though exposure to powerful magic may slowly diminish its potency.
>
> ## Uses
> - Brewing Potions of Healing
> - Restorative elixirs
> - Stabilizing alchemical mixtures
> - Essence catalysts
> - Advanced restorative alchemical recipes

> [!info|notes]-
> ## Notes
> Crystal Water is prized for its exceptional purity and remarkable affinity for magical energy. Although harmless to drink, alchemists value it less as a beverage than as the ideal foundation for potions and other alchemical preparations, where its natural stability allows volatile ingredients to blend without losing their magical properties.