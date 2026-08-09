---
cssclasses:
  - dnd4e-item
art: zz_attachments/quintessence.png
rank: Iron
rarity: Common
type: Crafting Resource
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
> **Iron+** • **Crafting Resource** • **Common** • **Variable Value**

*A tiny crystalline droplet of condensed Dungeon magic that glows with soft violet and golden light. Quintessence is the universal magical energy used to create, enhance, and reshape enchanted items.*

> [!power|passive]-
> **Crafting Resource**
>
> Quintessence is consumed when crafting magical items, brewing alchemical creations, enhancing equipment, performing magical reforging and fueling advanced magical research
>
>It may be found as loot dropped by Dungeon creatures, within Dungeon treasure caches, condensed in areas of intense magical energy or even as rewards for overcoming Dungeon challenges.
>
> Quintessence has no magical affinity of its own and may be used in any recipe that requires it.

