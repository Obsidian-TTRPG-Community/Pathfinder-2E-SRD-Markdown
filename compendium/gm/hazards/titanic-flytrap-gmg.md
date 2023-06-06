---
obsidianUIMode: preview
cssclass: pf2e,pf2e-hazard
tags:
- compendium/src/pf2e/gmg
- trait/environmental
aliases: ["Titanic Flytrap"]
---
# Titanic Flytrap *Hazard 4*  
[environmental](rules/traits/environmental.md)  

- **Complexity** Simple
- **Stealth** DC 25 trained  

On the surface, a titanic flytrap appears to be a patch of the more common flytrap plant, but beneath murky waters it hides a far larger set of jaws, reaching 10 feet across and reinforced with woody branches and lined with paralytic hairs.

- **Disable** DC 22 [Survival](compendium/skills.md#Survival) (trained) to mislead the flytrap's sense of weight and pressure  

- **AC** 21 , **Fort** +15, **Ref** +8
- **HP** 56 (BT 28)
- **Immunities** [mental](rules/traits/mental.md)
- **Resistances** acid 20; fire 10
- **Weaknesses** 
     
```ad-embed-ability
title: Snap Shut [R](rules/core-rulebook/chapter-9-playing-the-game.md#Actions "Reaction")

- **Trigger**: A Small or Medium creature moves into a square that is within reach of the flytrap's [hidden](rules/conditions.md#Hidden) jaws

**Effect** The flytrap's jaws snap shut, making a jaws [Strike](rules/actions/strike.md) against the triggering creature.
```
````ad-embed-ability
title: Devour

The target is trapped by the flytrap's jaws, gaining the [grabbed](rules/conditions.md#Grabbed) condition until it Escapes (DC 21). Additionally, it is exposed to the titanic flytrap toxin from the hundreds of tiny hairs that line the inside of its leaves. If the flytrap's jaws [Strike](rules/actions/strike.md) was a critical success, the target takes a –2 circumstance penalty to its saving throws against this poison. At the end of each of target's turns that it remains [grabbed](rules/conditions.md#Grabbed), the target takes `3d6` acid damage.

```ad-inline-affliction
title: Titanic Flytrap Toxin

[contact](rules/traits/contact.md)  [poison](rules/traits/poison.md)  
- **Saving Throws**: DC 21 Fortitude
- **Maximum Duration**: 4 rounds

## Stages

**Stage 1** `2d6` poison damage and [stunned](rules/conditions.md#Stunned) (1 round)

**Stage 2** `3d6` poison damage and [stunned](rules/conditions.md#Stunned) (1 round)

**Stage 3** `4d6` poison damage and [paralyzed](rules/conditions.md#Paralyzed) (1 round)


%% #trait/contact #trait/poison %%
```
````

**Reset** 1 hour (or longer, after a large meal)  

*Source: Gamemastery Guide p. 78*