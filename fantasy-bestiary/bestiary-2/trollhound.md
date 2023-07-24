---
obsidianUIMode: preview
noteType: pf2eMonster
aliases: "Trollhound"
tags: 
  - pf2e/creature/type/beast
  - pf2e/creature/level/3
statblock: inline
name: "Trollhound"
level: 3
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "B2"
name: "Trollhound"
level: "Creature 3"
alignment: "N"
size: "Medium"
trait_03: "Beast"
trait_04: "Troll"
modifier: 6
perception:
  - name: "Perception"
    desc: "Perception +6; __darkvision__, __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +6 (1d20+6); __Athletics__: +11 (1d20+11); __Stealth__: +8 (1d20+8); __Survival__: +6 (1d20+6); "
abilityMods: [4, 1, 5, -4, 1, -2]

abilities_bot:
  - name: "Bloodfire Fever"
    desc: " ([[disease]]);  __Saving Throw__ DC 18 Fortitude. __Stage 1__ carrier with no ill effect (1 day) __Stage 2__ [[rules/conditions.md#Enfeebled|enfeebled 1]] (1 day) __Stage 3__ [[rules/conditions.md#Enfeebled|enfeebled 1]] and [[rules/conditions.md#Clumsy|clumsy 1]] (1 day) __Stage 4__ [[rules/conditions.md#Enfeebled|enfeebled 2]] and [[rules/conditions.md#Clumsy|clumsy 2]] (1 day) __Stage 5__ [[rules/conditions.md#Enfeebled|enfeebled 2]], [[rules/conditions.md#Clumsy|clumsy 2]], and [[rules/conditions.md#Fatigued|fatigued]] (1 day)"
  - name: "Pack Attack"
    desc: "  The trollhound deals an extra 1d6 (1d6) damage to any creature within reach of at least two of the trollhound's allies."

speed: 35 feet

ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__: +14 (1d20+14); __Ref__: +8 (1d20+8); __Will__: +6 (1d20+6);"
hp: 65
health:
  - name: HP
    desc: "65; [[regeneration]] 15 (deactivated by acid or fire);"


attacks:
  - name: Melee
    desc: "⬻ jaws +11 __Damage__ 1d12+4 (1d12+4) piercing plus Knockdown and bloodfire fever"

sourcebook: "_Bestiary 2_, page 268."
```

```encounter-table
name: Trollhound
creatures:
  - 1: Trollhound
```
