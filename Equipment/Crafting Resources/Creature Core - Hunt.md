---
cssclasses:
  - dnd4e-item
art: zz_attachments/creature-core-hunt.png
rank: Iron
rarity: Rare
type: Crafting Resource
alias: "Hunt Core"
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

# Creature Core - Hunt

> [!metadata]  
> **Iron+** • **Crafting Resource** • **Rare** • **Variable Value**

_Dense crystal formed around the lingering instinct of the hunt. At its heart rests the Hunt sigil, its lines glowing faintly with primal green light as though tracking prey unseen. Each core contains a fragment of a Dungeon creature's predatory nature, preserved long after the manifestation itself has dissolved._

> [!power|passive]-  
> **Crafting Resource**
> 
> Hunt Creature Cores are used when crafting or enhancing equipment tied to pursuit, precision, survival, beasts, tracking, and predatory magic.
> 
> They are most commonly recovered from creatures aligned with the Hunt Attunement, though particularly powerful predators may yield larger or more refined cores. Skilled artisans can combine them with Quintessence and other crafting materials to imbue weapons, armor, and magical items with abilities inspired by the relentless instincts of the hunter.
> 
> Each Creature Core possesses a specific attunement and may only be substituted for recipes that require a matching core or a generic Creature Core. Different attunements grant access to different categories of magical creations.