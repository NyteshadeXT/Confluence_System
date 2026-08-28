## Confluence Power Entry Cheat Sheet

### 1. Base Power

Enter the Power as it functions at **Rank 1**. Rank 3, 6, and 9 improvements belong in **Rank-Up Effects**, not in the base Power text.

|Field|What to Enter|Example|
|---|---|---|
|Power Type / Concept|Slot concept|`Core Concept`|
|Keywords|Power traits, comma separated|`At-Will, Martial, Weapon`|
|Dungeon Resonance|Resonance behavior|`Neutral`|
|Action Type|Action requirement|`Single`|
|Attack Type & Range|Delivery/range|`Melee Weapon`, `Ranged 10`|
|Target|Targeting text|`One creature`|
|Description / Flavor|Player-facing flavor|`You strike through one foe...`|
|Trigger|Only for triggered Powers|`An enemy enters an adjacent square.`|
|Requirements|Requirements to use Power|`You must be wielding a blade.`|
|Attack|Base attack instruction|`Power Attack vs. AC`|
|Hit|Rank 1 hit result|`1[W] + your Essence ability modifier damage.`|
|Miss|Miss result|`No damage.`|
|Effect|Happens independently of Hit/Miss|—|
|Special|Exceptional rules|—|
|Sustain|Ongoing/sustain instructions|—|

Whenever possible, use **Power Attack vs. [Defense]** rather than manually writing the attack modifier. The character sheet calculates the actual modifier.

---

## 2. Rank-Up Effects

Iron Powers receive improvements at **Ranks 3, 6, and 9**.

Each milestone has:

**Name** — player-facing milestone name.  
**Description** — explanation shown to the player.  
**Mechanical Effects** — instructions telling the application how the Power itself changes.

The Description does **not** cause the Power to change. If the Power card needs to change, add a Mechanical Effect.

### Common Mechanical Effects

|You want the milestone to…|Use|
|---|---|
|Increase the Power's attack|**Add Attack Bonus**|
|Change its damage die|**Replace Damage Dice**|
|Add another consequence on a hit|**Add Hit Effect**|
|Add something that happens on a miss|**Add Miss Effect**|
|Add a general Effect|**Add Effect**|
|Change a named bonus/effect already present|**Modify Existing Effect Value**|
|Change one particular phrase/expression|**Modify Existing Text Value**|

---

## 3. Modify Existing Text Value

Use this when the milestone changes **part of an existing sentence** rather than adding another effect.

Format:

`Section | Existing Text | Replacement Text`

The match is exact, including punctuation.

### Cleave example

Base Hit:

> 1[W] + your Essence ability modifier damage, and one enemy adjacent to you takes damage equal to your Essence ability modifier.

Rank 3 should increase only the secondary damage.

Enter:

`Hit | damage equal to your Essence ability modifier. | damage equal to your Essence ability modifier + 2.`

Resolved Hit:

> 1[W] + your Essence ability modifier damage, and one enemy adjacent to you takes damage equal to your Essence ability modifier + 2.

This is preferable to **Add Hit Effect**, because the original secondary damage is actually being replaced.

---

## 4. Add Hit/Miss Effects

Use these when the original effect remains intact and the milestone gives the Power **something additional**.

### Cleave Rank 6

**Sweeping Follow-Through**

Mechanical Effect:

**Add Hit Effect**

`If the primary attack reduces a creature to 0 HP, you may shift 1 square.`

The resolved Hit contains both the original Cleave damage and this new ability.

### Cleave Rank 9

**Relentless Momentum**

Mechanical Effect:

**Add Hit Effect**

`If you hit the primary target, you gain a +1 power bonus to damage rolls against enemies adjacent to you until the end of your next turn.`

---

## 5. Attack Bonuses

Power Rank already provides the Power's normal attack progression.

A milestone should use **Add Attack Bonus** only when it grants an attack bonus **in addition to normal Power Rank progression**.

For example:

**Rank 3 — Disciplined Aim**

> Increase the attack bonus by +1.

Mechanical Effect:

**Add Attack Bonus:** `1`

Don't manually rewrite:

> `Power Rank +3 vs. AC`

The character sheet should calculate the resolved Power Attack.

---

## 6. Damage Die Changes

If a milestone changes:

> `1d6 + modifier`

to:

> `1d8 + modifier`

use:

**Replace Damage Dice:** `1d8`

rather than adding a Hit effect saying that the damage increases.

This allows the actual Power card to display the new damage.

Example:

**Lance of Faith — Rank 3**

`Replace Damage Dice | 1d8`

The player should simply see the new Rank 3 damage on the resolved card.

---

## 7. Existing Named Effects

Use **Modify Existing Effect Value** when a Power already contains a recognizable named effect whose numerical value changes.

Example:

Lance of Faith has:

> **Expose:** ... gains a +2 bonus...

Rank 6 changes Expose to +3.

Use:

**Modify Existing Effect Value**

`Expose | +2 | +3`

This is better than appending:

> Expose is now +3.

The resolved Power should instead display the original Expose effect with **+3**.

