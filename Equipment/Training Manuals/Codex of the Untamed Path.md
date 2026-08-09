---
cssclasses:
  - dnd4e-item
art: 
rank: 
rarity: common
type: consumable
alias: "Training Manual - Athletics"
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

*This weathered tome contains far more than ink and parchment. As you read its pages, the hard-earned instincts of countless hunters, explorers, and wanderers flow through your mind. You instinctively learn how to read the subtle signs of the wilderness, follow tracks across broken ground, navigate without a trail, and find food, water, and shelter where others would see only an unforgiving wild. Every footprint, shifting wind, and distant call begins to carry meaning, allowing you to endure and find your way through even the harshest environments. When the final page is turned, the knowledge settles into your memory, granting proficiency in Survival forever.*

> [!power|consumable]-
> **10 minutes**
>
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Survival Skill. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to absorb.  Become [[Stupefied]] 3 for the next 10 minutes.