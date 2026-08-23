---
cssclasses:
  - dnd4e-item
art: training-manual.png
rank: iron
rarity: common
type: consumable
alias: "Training Manual - Plate Armor"
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

# Manual of the Bulwark

> [!metadata]
> **Training Manual** • **??? gp**

*This weathered tome contains far more than ink and parchment. As you read its pages, the practiced movements of countless champions flow through your mind. You instinctively learn how to secure each plate, distribute its immense weight, and advance with unwavering purpose despite the burden of steel. Every measured step, guarded stance, and disciplined movement transforms the armor from an encumbrance into an unyielding bulwark. When the final page is turned, the knowledge settles into your memory, granting proficiency with plate armor forever.*

> [!power|consumable]-
> **10 minutes**
>
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Plate Armor Skill Group. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to absorb.  Become [[Stupefied]] 3 for the next 10 minutes.