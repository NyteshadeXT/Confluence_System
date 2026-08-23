---
cssclasses:
  - dnd4e-item
art: training-manual.png
rank: iron
rarity: common
type: consumable
alias: "Training Manual - Spears"
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

# Treatise of the Long Reach

> [!metadata]
> **Training Manual** • **??? gp**

*This weathered tome contains far more than ink and parchment. As you read its pages, the practiced movements of countless spearmen, hunters, and battlefield veterans flow through your mind. You instinctively learn how to control the distance between yourself and an opponent, shift smoothly between thrust and guard, and use the spear's length to strike while keeping danger at bay. Every thrust, sweep, and measured step becomes second nature, transforming the weapon's reach into an extension of your awareness. When the final page is turned, the knowledge settles into your memory, granting proficiency with spears forever.*

> [!power|consumable]-
> **10 minutes**
>
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Spear Weapon Group. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to absorb.  Become [[Stupefied]] 3 for the next 10 minutes.