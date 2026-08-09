---
cssclasses:
  - dnd4e-item
art: 
rank: 
rarity: common
type: consumable
alias: "Training Manual - Perception"
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
> **Training Manual** • **??? gp**

*This weathered tome contains far more than ink and parchment. As you read its pages, the accumulated wisdom of countless arcanists flows through your mind. You instinctively begin to recognize the patterns that govern magical energy, decipher ancient runes, and unravel the principles behind spells, enchantments, and magical phenomena. Mysteries that once seemed incomprehensible reveal an underlying order, and your understanding of the arcane deepens with every page. When the final page is turned, the knowledge settles into your memory, granting proficiency in Arcana forever.*

> [!power|consumable]-
> **10 minutes**
>
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Arcana Skill. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to absorb.  Become [[Stupefied]] 3 for the next 10 minutes.