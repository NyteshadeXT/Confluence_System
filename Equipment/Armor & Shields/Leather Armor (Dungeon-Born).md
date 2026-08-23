---
cssclasses:
  - dnd4e-item
art: 
rank: iron
rarity: common
type: permanent
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
    limit: 1
  - type: table
    name: Table

```
# Battleaxe

> [!metadata]
> **Iron** • **Light** • **Common** • **25 gp**

*Leather armor is sturdier than cloth armor. It protects vital areas with multiple layers of boiled-leather plates, while covering the limbs with supple leather that provides a small amount of protection.*

> [!power|weapon]-
> **Armor Group:** Leather
> 
> **AC Bonus** +2
> **Dexterity Cap** +4
> **Check Penalty** -
> **Speed Penalty** -
> 
> **Expert Bonus** +1 AC
> **Master Bonus** *Resistance* The thick second skin of the armor disperses blunt force to reduce bludgeoning damage. You gain resistance to bludgeoning damage equal to the AC bonus of the armor.
> 
> **Weight** 15
