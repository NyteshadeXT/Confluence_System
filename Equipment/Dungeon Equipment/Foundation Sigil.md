---
cssclasses:
  - dnd4e-item
art: zz_attachments/foundation-sigil.png
rank: iron
rarity: uncommon
type: consumable
alias: 
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

# Foundation Sigil

> [!metadata]  
> **Iron+** • **Crafting Material** • **Uncommon** • **Variable Value**

_The stone bears a perfectly circular sigil carved into its surface, its weathered grooves filled with gleaming veins of gold. At its heart rests a radiant golden orb cradled within an intricate lattice of roots and crystal, while four empty diamond-shaped sockets hang above it as though waiting to be filled. Though motionless, the symbol hums with restrained power, giving the unmistakable impression that it is not merely an inscription, but the foundation of something ancient._

> [!power|consumable]-
> **10 Minutes**
> 
> Affix a Foundation Sigil to a nonmagical weapon, armor, shield, or implement while within a Sanctuary or other suitable crafting location. The sigil is consumed, transforming the item into a **Foundation Item**. Foundation Items are considered Dungeon-compatible and can be enhanced through Dungeon crafting, Essences, and other magical processes. A Foundation Sigil has no effect on an item that has already been transformed.

> ### Lore
> 
>> _"Every enchanted weapon begins with power. Every legendary weapon begins with a Foundation."_  
>> —Attributed to an unknown Dungeon Forger
>
> No surviving civilization claims to have created Foundation Sigils. Every known specimen has been recovered from within a Dungeon, often found untouched in forgotten vaults or alongside ancient forges. Scholars debate whether they are tools, keys, or fragments of a much greater magical design, but all agree on one point: **without a Foundation, no item can truly become part of the Dungeon.**