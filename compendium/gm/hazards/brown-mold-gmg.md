---
obsidianUIMode: preview
cssclass: pf2e,pf2e-hazard
tags:
- compendium/src/pf2e/gmg
- trait/environmental
- trait/fungus
aliases: ["Brown Mold"]
---
# Brown Mold *Hazard 2*  
[environmental](rules/traits/environmental.md "Environmental Hazard Trait")  [fungus](rules/traits/fungus-b1.md "Fungus Creature Type Trait")  

- **Complexity** Simple
- **Stealth** DC 21 trained  

This unassuming fungus leeches heat out of the air.

- **Disable** DC 18 [Survival](compendium/skills.md#Survival) (trained) to safely remove the mold  

- **AC** 18 , **Fort** +11, 
- **HP** 30 (BT 15)
- **Immunities** critical hits; [fire](rules/traits/fire.md "Fire Energy & Element Trait"); object immunities; precision damage
- **Resistances** 
- **Weaknesses** cold 10
     
```ad-embed-ability
title: Emit Cold
[aura](rules/traits/aura.md "Aura Combat Trait")  [cold](rules/traits/cold.md "Cold Energy & Element Trait")  

5 feet. Brown mold deals `2d6` cold damage to nearby creatures.  
%% #trait/aura #trait/cold %%
```
```ad-embed-ability
title: Leech Warmth [R](rules/core-rulebook/chapter-9-playing-the-game.md#Actions "Reaction")

- **Trigger**: Fire comes within 5 feet of the brown mold

**Effect** The brown mold expands into every square adjacent to its space. As it grows, it pulls more heat from its surroundings, dealing `2d6+6` cold damage (DC 18 basic Fortitude save) to creatures within 10 feet after it expands.
```

**Reset** After expanding, the brown mold can't grow again for 1 day.  

*Source: Gamemastery Guide p. 77*