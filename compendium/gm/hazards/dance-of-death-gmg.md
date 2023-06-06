---
obsidianUIMode: preview
cssclass: pf2e,pf2e-hazard
tags:
- compendium/src/pf2e/gmg
- trait/complex
- trait/haunt
aliases: ["Dance of Death"]
---
# Dance of Death *Hazard 16*  
[complex](rules/traits/complex.md)  [haunt](rules/traits/haunt.md)  

- **Complexity** Complex
- **Stealth** +32 master  

An eerie orchestra compels all who hear it to dance until they collapse from exhaustion.

- **Disable** DC 42 [Intimidation](compendium/skills.md#Intimidation) (expert) three times to frighten dancers and spectral musicians alike away from participating in the deadly performance, DC 40 [Performance](compendium/skills.md#Performance) (master) twice to produce a tune discordant enough to disrupt the compulsion, or DC 42 [Religion](compendium/skills.md#Religion) (master) three times to banish the spirits with prayers  
     
```ad-embed-ability
title: Prelude [R](rules/core-rulebook/chapter-9-playing-the-game.md#Actions "Reaction")
[auditory](rules/traits/auditory.md)  [enchantment](rules/traits/enchantment.md)  [incapacitation](rules/traits/incapacitation.md)  [occult](rules/traits/occult.md)  

- **Trigger**: A creature approaches within 30 feet of the orchestra

**Effect** The orchestra compels all creatures that can hear it to begin dancing. Each creature must attempt a  
%% #trait/auditory #trait/enchantment #trait/incapacitation #trait/occult %%
```
```ad-embed-ability
title: DC 41

Will save, with the following effects.

> [!success-degree] 
> - **Critical Success** The creature is unaffected.
> - **Success** The creature is [flat-footed](rules/conditions.md#Flat-footed) and cannot use reactions. Additionally, it must spend 1 of its actions each round dancing. Dancing is a move action that allows the creature to [Stride](rules/actions/stride.md) up to half its Speed.
> - **Failure** As success, except the creature must spend 2 of its actions each round dancing.
> - **Critical Failure** As failure, except the creature must spend 3 of its actions each round dancing.
```

```ad-pf2-summary
title: Routine
(1 action; auditory, enchantment, incapacitation, occult) The orchestra performs a raucous tune, compelling all creatures that can hear it to spend actions dancing.

Each round, creature must attempt a DC 37 Will save; the results of this save modify the number of actions that the creature must spend dancing each round. If this would cause the creature to spend more actions dancing than it can use on its turn, the creature takes `10d6` damage (or double that on a critical failure) from moving faster than its body can manage.

> [!success-degree] 
> - **Critical Success** The creature decreases the number of actions it must spend dancing by 1.
> - **Success** No effect.
> - **Failure** The creature increases the actions it must spend dancing by 1.
> - **Critical Failure** The creature increases the actions it must spend dancing by 2.
```
^routine

**Reset** The eerie orchestra spends an hour retuning its phantasmal instruments, after which it is ready to begin its routine again.  

*Source: Gamemastery Guide p. 81*