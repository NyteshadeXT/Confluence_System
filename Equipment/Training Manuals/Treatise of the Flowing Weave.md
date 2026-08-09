---
cssclasses:
  - dnd4e-item
art: 
rank: 
rarity: common
type: consumable
alias: "Training Manual - Cloth Armor"
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

*This weathered tome contains far more than ink and parchment. As you read its pages, the practiced movements of countless monks, mystics, and battle mages flow through your mind. You instinctively learn how to secure flowing robes and layered garments without restricting movement, maintain perfect balance through every step, and fight with grace unburdened by heavy armor. Every motion becomes fluid and deliberate, allowing body, mind, and magic to move as one. When the final page is turned, the knowledge settles into your memory, granting proficiency with cloth armor forever.*

> [!power|consumable]-
> **10 minutes**
>
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Cloth Armor Skill Group. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to absorb.  Become [[Stupefied]] 3 for the next 10 minutes.