---
cssclasses:
- dnd4e-item  
art: training-manual.png
rank: iron
rarity: common
type: consumable  
alias: "Training Manual - Bow Weapon Group"
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

# The Archer's Measure

> [!metadata]  
> **Training Manual** • **??? gp**

_This weathered tome contains far more than ink and parchment. As you read its pages, the practiced movements of countless archers flow through your mind, teaching proper stance, draw, anchor, release, and the subtle judgment of distance and trajectory. When the final page is turned, the knowledge settles into your memory, granting proficiency with bows forever._

> [!power|consumable]-  
> **10 minutes**
> 
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Bow Weapon Skill Group. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to process. Become [[Stupefied]] 3 for the next 10 minutes.