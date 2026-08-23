---
cssclasses:
  - dnd4e-item
art: training-manual.png
rank: iron
rarity: common
type: consumable
alias: "Training Manual - Perception"
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

# Codex of the Open Eye

> [!metadata]
> **Training Manual** • **??? gp**

*This weathered tome contains far more than ink and parchment. As you read its pages, the sharpened instincts of countless scouts, hunters, and sentinels flow through your mind. You learn to notice the nearly imperceptible—the faint scrape of stone, the subtle shift of shadow, the distant rustle of leaves, and the hidden signs others overlook. Every sense becomes honed through patient observation until vigilance itself becomes second nature. When the final page is turned, the knowledge settles into your memory, granting proficiency in Perception forever.*

> [!power|consumable]-
> **10 minutes**
>
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Perception Skill. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to absorb.  Become [[Stupefied]] 3 for the next 10 minutes.