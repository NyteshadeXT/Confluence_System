---
cssclasses:
  - dnd4e-item
art: training-manual.png
rank: iron
rarity: common
type: consumable
alias: "Training Manual - Scale Armor"
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
  - type: table
    name: Table

```

# Manual of the Scaled Guard

> [!metadata]
> **Training Manual** • **??? gp**

*This weathered tome contains far more than ink and parchment. As you read its pages, the practiced movements of countless guardians and seasoned warriors flow through your mind. You instinctively learn how to secure each overlapping scale, shift your weight to preserve balance, and turn the force of incoming blows across the armor's layered protection. Every step, pivot, and defensive stance becomes deliberate, allowing the scales to move with you while shielding you from harm. When the final page is turned, the knowledge settles into your memory, granting proficiency with scale armor forever.*

> [!power|consumable]-
> **10 minutes**
>
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Scale Armor Skill Group. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to absorb.  Become [[Stupefied]] 3 for the next 10 minutes.