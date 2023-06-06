---
obsidianUIMode: preview
cssclass: pf2e,pf2e-hazard
tags:
- compendium/src/pf2e/gmg
- trait/complex
- trait/environmental
aliases: ["Perilous Flash Flood"]
---
# Perilous Flash Flood *Hazard 10*  
[complex](rules/traits/complex.md)  [environmental](rules/traits/environmental.md)  

- **Complexity** Complex
- **Stealth** +22 expert  

Whether made up of water rushing through the streets that sweeps up dangerous debris along the way or a less natural substance bursting free of its container, this relentless flood batters everything in its path.

- **Disable** three DC 35 [Athletics](compendium/skills.md#Athletics), [Crafting](compendium/skills.md#Crafting), or [Survival](compendium/skills.md#Survival) checks to move or construct barricades strong enough to create a shelter from the flood. While this creates a safe place to stand, creatures outside of the barricaded area may still be in danger depending on the nature and the source of the flood.  
     
```ad-embed-ability
title: Burst Free [R](rules/core-rulebook/chapter-9-playing-the-game.md#Actions "Reaction")

- **Trigger**: A creature or effect breaks the flood's containment

**Effect** The hazard rolls initiative as the flood surges forth.
```

```ad-pf2-summary
title: Routine
(1 action) The flood advances forward 60 feet, crashing into all creatures within its area. Each creature must attempt a DC 30 Fortitude save as the floodwaters pummel them and pull them downstream. The amount and type of damage dealt are based on the nature of the flood, and certain types of floods impose additional effects. The turbulent waters mean creatures within the area of the flood must attempt a DC 20 [Athletics](compendium/skills.md#Athletics) check to [Swim](rules/actions/swim.md) in order to move, and those who do not succeed at a check to [Swim](rules/actions/swim.md) each round may drown.

> [!success-degree] 
> - **Critical Success** The creature takes no damage.
> - **Success** The creature takes half damage.
> - **Failure** The creature takes full damage and is moved 10 feet along with the water.
> - **Critical Failure** The creature takes double damage and is moved 20 feet along with the water.

- Acidic Runoff This caustic flood dissolves flesh as it moves, dealing `1d12` bludgeoning damage and `1d12+8` acid damage. Additionally, it deals `2d6` [persistent acid damage](rules/conditions.md#Persistent%20Damage) to creatures who critically fail their Fortitude saves.
- Battering Waves This flood of rushing water deals `2d12+10` bludgeoning damage.
- Repulsive Refuse This flood has picked up tainted or disease-ridden objects like sewer runoff or rotting food.

It deals `2d12+8` bludgeoning damage. Each creature exposed to the flood must attempt a DC 29 Fortitude save, becoming [sickened](rules/conditions.md#Sickened) on a failure or [sickened](rules/conditions.md#Sickened) on a critical failure. Additionally, creatures who come into contact with the flood waters are exposed to filth fever (DC 20 Fortitude, Bestiary 258).

- Sharp Debris The waters have picked up various objects, some of which are particularly sharp. The flood deals `1d12` bludgeoning damage and `1d12+12` piercing damage.
- Sticky Goo The substance is particularly sticky. It deals `2d12+6` bludgeoning damage. Additionally, each creature in the flood must attempt a DC 29 Reflex save at the beginning of their turn each round. On a failed saving throw, they take a –10-foot circumstance penalty to all their Speeds for 1 round. On a critical failure, they are instead [immobilized](rules/conditions.md#Immobilized) for 1 round.
```
^routine

*Source: Gamemastery Guide p. 80*