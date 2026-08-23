---
cssclasses:
  - dnd4e-item
art: 
rank: iron
rarity: uncommon
type: enchantment
alias: "Wyrmtooth Enchantment"
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
````

# Wyrmtooth

> [!metadata]  
> **Iron** • **Melee Weapon Enchantment** • **Uncommon** • **??? gp**

_The weapon takes on subtle draconic characteristics as Dungeon Essence settles into its form. Blades develop pale, fang-like edges, axe heads grow tooth-like serrations, and striking surfaces develop ridges reminiscent of a wyrm's maw. Whatever its shape, a Wyrmtooth weapon bites through supernatural defenses that would turn aside lesser attacks._

> [!power|passive]-  
> ## Wyrmtooth
> 
> Attacks made with this weapon gain Resistance Penetration 5 against creatures of this item's Rank or lower.
> 
> Resistance Penetration reduces applicable Damage Resistance by the listed amount when resolving damage from the attack. It cannot reduce a resistance below 0.
> 
> **Example:** An attack made with an Iron Rank Wyrmtooth weapon against an Iron Rank creature with Resist 10 treats that creature as having Resist 5 for that attack. If the creature instead has Resist 5, the attack ignores the resistance completely. Resistance Penetration does not change the creature's actual Resistance; it only reduces how much applies against that attack.
> 
> **Critical:** +1d6 damage. In addition, the target's Damage Resistances are reduced by 5 (save ends).
>
> ## Wyrm's Hunger
> 
> **Free Action**
> 
> **Trigger:** You hit a creature of this item's Rank or lower with an attack using this weapon.
> 
> **Effect:** Until the end of the encounter, attacks made using this weapon have **Resistance Penetration 10** instead of Resistance Penetration 5 against creatures of this item's Rank or lower.

> [!Info|Arcane Pattern]-
> **Discipline** Blacksmith (Trained)  
> **Pattern** Wyrmtooth  
> **Complexity** Standard
> 
> **Crafting DC** 17 (Iron)  
> **Crafting Progress** 20  
> **Batch Size** 1 weapon
> 
> **Supplies**
> - Dungeon-bound Melee Weapon ×1
> - Iron Rank Creature Core (Dragon, Venom, or Might) ×1
> - [[Quintessence]] ×3
> - Gold 75 gp
> 
> **Notes**
> 
> The Wyrmtooth Pattern applies the Wyrmtooth enchantment to an existing Dungeon-bound melee weapon. The base weapon determines its Weapon Group, damage die, proficiency requirements, and other mundane properties.
> 
> The enchantment subtly alters the appearance of the weapon but does not otherwise change its mundane statistics.

> [!Info|sources & usage]-
> 
> ## Sources
> - Dungeon reward from a significant challenge or powerful manifestation.
> - An Arcane Pattern may be discovered as Dungeon treasure.
> - The Pattern may be learned by successfully reverse engineering an existing Wyrmtooth weapon.
> 
> ## Uses
> - Enchants a Dungeon-bound melee weapon with Wyrmtooth.
> - May serve as the basis for researching higher-Rank Wyrmtooth enchantments.

> [!info|notes]-
> 
> ## Notes
> 
> Wyrmtooth is an enchantment rather than a specific weapon. The resulting item's name incorporates its base weapon: Wyrmtooth Dagger, Wyrmtooth Battleaxe, Wyrmtooth Spear, and so forth.
> 
> The Pattern above creates an Iron Rank Wyrmtooth enchantment. Its Resistance Penetration only functions against creatures of Iron Rank or lower. Higher-Rank versions of the enchantment require an appropriate higher-Rank Pattern and materials.
> 
> Resistance Penetration and Resistance reduction are distinct. Penetration applies only while resolving the qualifying attack and does not alter the target's Resistance. The Critical effect actually reduces the target's Damage Resistances until the target succeeds on its saving throw.

> ### Lore
> 
> > _"A wyrm's fang does not overcome the hide by striking harder. It finds the weakness and teaches the rest of the weapon where to bite."_  
> > —Attributed to Master Artificer Edran Voss
> 
> The earliest Wyrmtooth weapons were believed to have been fashioned from the remains of dragons slain within ancient Dungeons. Modern artificers know that no actual dragon tooth is required. The enchantment instead reproduces the supernatural principle represented by the fang: finding purchase in defenses that should otherwise resist the blow.