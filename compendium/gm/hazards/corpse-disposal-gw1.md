---
obsidianUIMode: preview
cssclass: pf2e,pf2e-hazard
tags:
- compendium/src/pf2e/gw1
- trait/mechanical
- trait/trap
aliases: ["Corpse Disposal"]
---
# Corpse Disposal *Hazard 2*  
[mechanical](rules/traits/mechanical.md "Mechanical Hazard Trait")  [trap](rules/traits/trap.md "Trap Hazard Trait")  

- **Complexity** Simple
- **Stealth** DC 21 (or 0 if the trapdoor is disabled or [broken](rules/conditions.md#Broken))  

A wooden trapdoor conceals a spike-filled pit 10 feet square and 20 feet deep. The DC to [Climb](rules/actions/climb.md) out of the pit is 10.

- **Disable** DC 18 [Thievery](compendium/skills.md#Thievery) (trained) to jam the trapdoor open  

- **AC** 18, **Fort** +7, **Ref** +7
- **Trapdoor Hardness** 9, **Trapdoor HP** 30
- **Immunities** critical hits; object immunities; precision damage

````ad-embed-ability
title: **Dispose** [R](rules/core-rulebook/chapter-9-playing-the-game.md#Actions "Reaction")

- **Trigger**: A creature steps onto the trapdoor (marked "T" on the map)

**Effect** The triggering creature falls into the pit. The creature can use the [Grab an Edge](rules/actions/grab-an-edge.md) reaction to avoid falling. Failing that, the creature falls 20 feet (taking 10 bludgeoning damage from the fall) and takes `3d6` piercing damage from the metal spikes jutting up from the pit's floor. A creature who takes damage from the spikes is exposed to tetanus.

```ad-inline-affliction
title: Tetanus

[disease](rules/traits/disease.md "Disease Effect Trait")  
- **Saving Throws**: DC 14 Fortitude
- **Onset**: 10 days

## Stages

**Stage 1** [clumsy](rules/conditions.md#Clumsy) (1 week)

**Stage 2** [clumsy](rules/conditions.md#Clumsy) and can't speak (1 day)

**Stage 3** [paralyzed](rules/conditions.md#Paralyzed) with spasms (1 day)

**Stage 4** death


%% #trait/disease %%
```
````

*Source: Gatewalkers #1: The Seventh Arch p. 0*