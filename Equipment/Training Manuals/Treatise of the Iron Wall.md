---
cssclasses:
  - dnd4e-item
art: 
rank: 
rarity: common
type: consumable
alias: "Training Manual - Shields"
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

*This weathered tome contains far more than ink and parchment. As you read its pages, the practiced movements of countless guardians, sentinels, and shield bearers flow through your mind. You instinctively learn how to raise your shield at precisely the right moment, deflect the force of incoming blows, and position yourself to protect both yourself and those who stand beside you. Every block, brace, and measured step becomes second nature, transforming your shield into an extension of your will. When the final page is turned, the knowledge settles into your memory, granting proficiency with shields forever.*

> [!power|consumable]-
> **10 minutes**
>
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Shield Skill Group. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to absorb.  Become [[Stupefied]] 3 for the next 10 minutes.