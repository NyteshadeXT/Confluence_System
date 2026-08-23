---
cssclasses:
  - dnd4e-item
art: training-manual.png
rank: iron
rarity: common
type: consumable
alias: "Training Manual - Axe Weapon Group"
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

# The Woodsman First Lessons

> [!metadata]
> **Training Manual** • **??? gp**

*This weathered tome contains far more than ink and parchment. As you read its pages, the movements of countless axe wielders flow through your mind, teaching proper grip, stance, balance, and the momentum behind every strike. When the final page is turned, the knowledge settles into your memory, granting proficiency with axes forever.*

> [!power|consumable]-
> **10 minutes**
>
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Axe Weapon Skill Group. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to absorb.  Become [[Stupefied]] 3 for the next 10 minutes.