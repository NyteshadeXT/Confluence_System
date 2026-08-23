---
cssclasses:
  - dnd4e-item
art: training-manual.png
rank: iron
rarity: common
type: consumable
alias: "Training Manual - Chainmail"
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

# Treatise of Iron Links

> [!metadata]
> **Training Manual** • **??? gp**

*This weathered tome contains far more than ink and parchment. As you read its pages, the practiced movements of countless veterans flow through your mind. You instinctively learn how to bear the weight of interlocking steel, distribute its burden across your body, and move with steady confidence without sacrificing balance or endurance. Every step, turn, and guarded stance becomes second nature, allowing the armor to protect without hindering your resolve. When the final page is turned, the knowledge settles into your memory, granting proficiency with chainmail forever.*

> [!power|consumable]-
> **10 minutes**
>
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Chainmail Armor Skill Group. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to absorb.  Become [[Stupefied]] 3 for the next 10 minutes.