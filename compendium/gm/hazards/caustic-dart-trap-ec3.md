---
obsidianUIMode: preview
cssclass: pf2e,pf2e-hazard
tags:
- compendium/src/pf2e/ec3
- trait/complex
- trait/mechanical
- trait/trap
aliases: ["Caustic Dart Trap"]
---
# Caustic Dart Trap *Hazard 11*  
[complex](rules/traits/complex.md "Complex Hazard Trait")  [mechanical](rules/traits/mechanical.md "Mechanical Hazard Trait")  [trap](rules/traits/trap.md "Trap Hazard Trait")  

- **Complexity** Complex
- **Stealth** +20 expert or DC 30 (expert) to notice the three launching mechanisms built into the wall.  

Three launching mechanisms built into the mudbrick walls expel darts containing acidic chemicals.

All three launching mechanisms must be disabled or destroyed to deactivate the trap.

- **Disable** DC 32 [Thievery](compendium/skills.md#Thievery) (master) to sufficiently jam the tubes to make the trap unable to attack creatures in a single 5-foot square in the room, or DC 34 [Crafting](compendium/skills.md#Crafting) (master) to alter one of the three launching mechanisms.  

- **AC** 31 , **Fort** +24, **Ref** +15
- **Hardness** 20, **HP** 80 (BT 40) per launching mechanism
- **Immunities** critical hits; object immunities; precision damage
- **Resistances** 
- **Weaknesses** 
     
```ad-embed-ability
title: Dart Barrage [R](rules/core-rulebook/chapter-9-playing-the-game.md#Actions "Reaction")
[attack](rules/traits/attack.md "Attack Combat Trait")  

- **Trigger**: A creature reaches the midpoint of the hall

**Effect** The trap makes an acid dart against three different random creatures in the hall. The trap then rolls initiative.  
%% #trait/attack %%
```

````ad-pf2-summary
title: Routine
[>>>](rules/core-rulebook/chapter-9-playing-the-game.md#Actions "Three-Action") The trap uses each action for a caustic dart [Strike](rules/actions/strike.md). The trap loses 1 action for each launching mechanism that is [broken](rules/conditions.md#Broken) or destroyed.

```ad-inline-attack
title: Ranged [>](rules/core-rulebook/chapter-9-playing-the-game.md#Actions "Single Action") Caustic Dart (28)
**Damage** `2d4+5` piercing and `4d4+8` acid 
 
**Effects**
```
````
^routine

**Reset** The trap deactivates and resets 1 minute after no creatures are in area C7.  

*Source: Extinction Curse #3: Life's Long Shadows p. 29*