---
cssclasses:
  - dnd4e-item
art: training-manual.png
rank: iron
rarity: common
type: consumable
alias: "Training Manual - Hide Armor"
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

# Treatise of Living Hide

> [!metadata]
> **Training Manual** • **??? gp**

*This weathered tome contains far more than ink and parchment. As you read its pages, the practiced movements of countless hunters and wilderness warriors flow through your mind. You instinctively learn how to secure each hardened hide, move with its rugged weight, and absorb the force of blows without losing your footing. Every stride, crouch, and defensive stance feels as natural as the creatures from which the armor was fashioned. When the final page is turned, the knowledge settles into your memory, granting proficiency with hide armor forever.*

> [!power|consumable]-
> **10 minutes**
>
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Hide Armor Skill Group. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to absorb.  Become [[Stupefied]] 3 for the next 10 minutes.