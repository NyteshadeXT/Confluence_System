---
cssclasses:
- dnd4e-item  
art: ironroot.png  
rank: Iron  
rarity: Common  
type: Ingredient  
alias:
---
![[Pasted image 20260816112234.png]]
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

# Ironroot

> [!metadata]  
> **Iron** • **Ingredient** • **Common** • **Variable Value**

_A hardy ground-growing herb whose broad, dark leaves conceal thick rust-red roots threaded with metallic-looking fibers. When cut, Ironroot releases a sharp, earthy scent and a bitter sap known to invigorate tired muscles and stave off exhaustion. Alchemists prize the root as a foundation for draughts that restore physical endurance._

> [!power|passive]-  
> **Crafting Resource**
> Ironroot is consumed when brewing stamina-restoring potions and other alchemical creations. It counts as an Ingredient for any recipe requiring stamina-restorative herbs.
> 
> **Harvest** A successful Nature (DC 15) check allows the root to be harvested intact. On a failure, portions of the root are damaged, yielding only half the normal value.

> [!Info|sources & usage]-
> ## Sources
> Ironroot thrives in magically enriched soil, frequently growing among ancient roots, mineral-rich earth, and areas subjected to persistent Dungeon manifestations.
> 
> Freshly harvested roots retain their potency for several weeks when properly dried and stored.
> 
> ## Uses
> - Brewing Potions of Stamina
> - Endurance elixirs
> - Fatigue-resistant alchemical preparations
> - Advanced stamina-regenerative alchemical recipes

> [!info|notes]-
> ## Notes
> Ironroot is among the most common stamina-restorative plants harvested from Iron Rank Dungeons. Its dense root system makes intact specimens more difficult to remove from the surrounding soil than their unassuming leaves suggest.