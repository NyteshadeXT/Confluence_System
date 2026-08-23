---
cssclasses:
  - dnd4e-item
art: training-manual.png
rank: iron
rarity: common
type: consumable
alias: "Training Manual - Leather Armor"
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

# Treatise of the Hidebound

> [!metadata]
> **Training Manual** • **??? gp**

*This weathered tome contains far more than ink and parchment. As you read its pages, the practiced movements of countless warriors flow through your mind. You instinctively learn how to fasten each strap, shift your weight, roll with incoming blows, and move with effortless agility while clad in leather armor. When the final page is turned, the knowledge settles into your memory, granting proficiency with leather armor forever.*

> [!power|consumable]-
> **10 minutes**
>
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Leather Armor Skill Group. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to absorb.  Become [[Stupefied]] 3 for the next 10 minutes.