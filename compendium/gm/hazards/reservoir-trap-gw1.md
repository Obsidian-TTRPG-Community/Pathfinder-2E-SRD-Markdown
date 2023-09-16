---
obsidianUIMode: preview
cssclasses: pf2e,pf2e-hazard
tags:
- compendium/src/pf2e/gw1
- trait/complex
- trait/mechanical
- trait/trap
aliases: ["Reservoir Trap"]
---
# Reservoir Trap *Hazard 2*  
[complex](rules/traits/complex.md "Complex Hazard Trait")  [mechanical](rules/traits/mechanical.md "Mechanical Hazard Trait")  [trap](rules/traits/trap.md "Trap Hazard Trait")  

- **Complexity** Complex
- **Stealth** DC 19 expert to notice the water tank bulging under the immense pressure  

Pipes extending from a pressurized water tank spray flesh-cutting jets of water at unwary passersby.

- **Disable** DC 18 [Thievery](compendium/skills.md#Thievery) (trained) to safely puncture a pipe, or DC 16 [Engineering Lore](compendium/skills.md#Lore) (trained) to find and turn a pressure release valve; any combination of three punctured pipes or turned valves disables the trap  

- **AC** 18, **Fort** +11, **Ref** +3
- **Pipe Hardness** 7, **Pipe HP** 30 (BT 15); **Tank Hardness** 7, **Tank HP** 50 (BT 25)
- **Immunities** critical hits; object immunities; precision damage

```ad-embed-ability
title: **Water Jets** [R](rules/core-rulebook/chapter-9-playing-the-game.md#Actions "Reaction")

- **Trigger**: A creature steps on a floor space in this room

**Effect** Seals on the water pipes burst, issuing forth high-pressure water jets in random directions. The hazard makes a water jet [Strike](rules/actions/strike.md) against the triggering creature. The hazard rolls initiative.
```
```ad-embed-ability
title: **Violent Deluge** [R](rules/core-rulebook/chapter-9-playing-the-game.md#Actions "Reaction")

- **Trigger**: The water tank is [broken](rules/conditions.md#Broken) or destroyed

**Effect** A torrent of water bursts from the shattered tank, dealing `3d8` bludgeoning damage to each creature within 15 feet (basic DC 22 Reflex save). The trap is then disabled.
```

```ad-pf2-summary
title: Routine

(3 actions) For each pipe destroyed or disabled, the trap loses 1 action. On each of the trap's actions, the trap targets a random creature in the room with a water jet [Strike](rules/actions/strike.md).
```
^routine

**Reset** The trap deactivates after 5 rounds. It cannot be reactivated until the reservoir is refilled, which takes an average of 5 days.  

*Source: Gatewalkers #1: The Seventh Arch p. 0*