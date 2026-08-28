## Always-On Mechanical Effects Cheat Sheet

Each effect uses a pipe-delimited format:

`effect type | target | value`

Multiple effects go on separate lines.

|Effect Type|What It Does|Format|Examples|
|---|---|---|---|
|**attack**|Adds a bonus to qualifying attack rolls. Best used with a specific weapon group or recognized attack scope.|`attack \| Target \| Bonus`|`attack \| Light Blade \| 1`|
|**power_attack**|Adds a bonus specifically to Power Attack calculations.|`power_attack \| Target \| Bonus`|`power_attack \| Implement \| 1`|
|**ability**|Adds a bonus to an ability **modifier**, rather than changing the underlying attribute score.|`ability \| Ability \| Bonus`|`ability \| Strength \| 1`|
|**attribute**|Permanently increases an actual attribute score.|`attribute \| Attribute \| Increase`|`attribute \| Dexterity \| 1`|
|**defense**|Adds directly to AC, Fortitude, Reflex, or Will.|`defense \| Defense \| Bonus`|`defense \| Reflex \| 1`|
|**initiative**|Adds directly to Initiative.|`initiative \| Initiative \| Bonus`|`initiative \| Initiative \| 1`|
|**skill**|Adds a numerical bonus to a specific skill. This is a bonus, **not Training**.|`skill \| Skill \| Bonus`|`skill \| Athletics \| 1`|
|**training**|Grants a specified Training proficiency.|`training \| Training Entry \| Proficiency`|`training \| Athletics \| Trained`|

### Common examples

**+1 Reflex**

```text
defense | Reflex | 1
```

**+1 Fortitude and +1 Will**

```text
defense | Fortitude | 1
defense | Will | 1
```

**Increase Dexterity by 1**

```text
attribute | Dexterity | 1
```

**+1 Initiative**

```text
initiative | Initiative | 1
```

**+1 Athletics**

```text
skill | Athletics | 1
```

**Grant Athletics Training**

```text
training | Athletics | Trained
```

Those last two are deliberately different. `skill` modifies the numerical result; `training` changes proficiency.

---

## Weapon Attack Bonuses

For weapon-group bonuses, use the **actual weapon group** whenever possible.

For example:

```text
attack | Light Blade | 1
```

means +1 to attacks using the Light Blade group.

Likewise:

```text
attack | Hammer | 1
```

### Avoid broad categories the engine doesn't understand

Don't currently use something like:

```text
attack | Bludgeon weapons | 1
```

unless we've specifically added `Bludgeon weapons` as a recognized attack scope.

Instead, if the character needs to choose between Hammer and Mace, use a **Permanent Milestone Choice**.

---

# Permanent Milestone Choices

These are appropriate when the Essence says **choose one** rather than granting everything automatically.

A Permanent Choice can contain the same mechanical effects.

### Example: Killing Precision

Always-on:

```text
defense | Reflex | 1
```

Permanent choice:

**Light Blade**

- Effect: **Weapon / General Attack**
    
- Target: `Light Blade`
    
- Bonus: `1`
    

**OR**

**Heavy Blade**

- Effect: **Weapon / General Attack**
    
- Target: `Heavy Blade`
    
- Bonus: `1`
    

This produces:

> +1 Reflex, and permanently choose +1 attacks with Light Blades or Heavy Blades.

That is preferable to:

```text
attack | Blade weapons | 1
```

when the actual rule requires the character to choose one group.

---

# Training Choices

We now have two different ways of granting Training.

### Grant a fixed proficiency

Use:

**Grant Training**

For example:

```text
training | Athletics | Trained
```

This means:

> Athletics becomes Trained.

It does **not** mean "increase Athletics one step."

### Increase Training One Step

Use the newer:

**Increase Training One Step**

with a configurable **Maximum**.

For example:

> Target: `Light Blade`  
> Maximum: `Expert`

This produces:

|Current|Result|
|---|---|
|Untrained|Trained|
|Trained|Expert|
|Expert|Expert|

This is ideal for Essence effects such as Blade's weapon specialization.

It can also be placed inside a Permanent Milestone Choice:

> **Light Blade** → Increase Training One Step → Maximum Expert  
> **OR**  
> **Heavy Blade** → Increase Training One Step → Maximum Expert

---

# Things the Framework Does Not Currently Handle Well

There are several effects I would **not** try to force into Always-On Mechanical Effects.

**Conditional bonuses** aren't generally suitable. For example:

> +1 attack against enemies that haven't acted yet.

We simplified Swift's version of this rather than building a conditional targeting engine.

**Broad conceptual weapon categories** aren't automatically understood. For example:

> +1 attacks with bludgeoning weapons.

Use specific groups or a Permanent Choice instead.

**Triggered effects** don't belong here either:

> When you become bloodied, gain +2 Reflex.

That's a conditional/triggered mechanic and needs Power/feature text or future automation support.

Likewise, **temporary effects** such as "gain +1 AC until the end of your next turn" aren't always-on milestone effects.

And **complex resource manipulation** generally needs its own rules support rather than an Always-On entry.
