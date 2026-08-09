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

*This weathered tome contains far more than ink and parchment. As you read its pages, the practiced movements of countless athletes, warriors, and explorers flow through your mind. You instinctively learn how to leverage your strength, control your momentum, and push your body beyond obstacles that once seemed insurmountable. Every climb, leap, swim, and feat of raw physical exertion becomes more deliberate and assured, teaching you to trust your body even when strength and endurance are tested to their limits. When the final page is turned, the knowledge settles into your memory, granting proficiency in Athletics forever.*

> [!power|consumable]-
> **10 minutes**
>
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Athletics Skill. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to absorb.  Become [[Stupefied]] 3 for the next 10 minutes.