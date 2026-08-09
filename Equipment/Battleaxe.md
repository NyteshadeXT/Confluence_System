---
cssclasses:
  - dnd4e-item
art: 
rank: iron
rarity: common
type: consumable
alias: 
---

```dataviewjs
const art = dv.current().art;
if (art) {
	dv.container.classList.add("item-card-art");
	dv.paragraph(`![[${art}]]`); 
} 
```

# `=this.file.name`

> [!metadata]
> **Iron** • **Marital** • **Melee** • **Common** • **15 gp**

*These axes are designed explicitly as weapons, rather than tools. They typically weigh less, with a shaft reinforced with metal bands or bolts, and have a sharper blade, making them ideal for chopping limbs rather than wood.*

> [!power|weapon]-
> **Weapon Group:** Axe
> 
> **Damage** 1d10 slashing
> **Range** -
> **Expert Bonus** +2
> **Master Bonus** *Sweep* This weapon makes wide swinging attacks. When you attack with this weapon, you gain a +2 circumstance bonus to your attack roll if you already attempted to attack a different target this turn using this weapon.
> 
> **Weight** 1
> **Hands** 1
