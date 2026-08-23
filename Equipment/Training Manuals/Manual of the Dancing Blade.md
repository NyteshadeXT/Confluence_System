---
cssclasses:
  - dnd4e-item
art: training-manual.png
rank: iron
rarity: common
type: consumable
alias: "Training Manual - Light Blades"
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

# Manual of the Dancing Blade

> [!metadata]
> **Training Manual** • **??? gp**

*This weathered tome contains far more than ink and parchment. As you read its pages, the practiced movements of countless duelists, skirmishers, and knife fighters flow through your mind. You instinctively learn how to wield a light blade with speed and precision, turn subtle movements into sudden attacks, and recognize the fleeting openings in an opponent's guard. Every feint, parry, and precise strike becomes second nature, allowing the blade to move as quickly and naturally as your own hand. When the final page is turned, the knowledge settles into your memory, granting proficiency with light blades forever.*

> [!power|consumable]-
> **10 minutes**
>
> Spend 10 minutes studying this training manual. At the end of that time, you become Trained 1 with the Light Blades Weapon Skill Group. The knowledge becomes a permanent part of your training, and the manual crumbles into shimmering purple-and-gold motes that quickly fade away.
> 
> The amount of information absorbed is difficult for the mind to absorb.  Become [[Stupefied]] 3 for the next 10 minutes.