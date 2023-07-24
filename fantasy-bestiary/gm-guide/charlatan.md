---
obsidianUIMode: preview
noteType: pf2eMonster
aliases: "Charlatan"
tags: 
  - pf2e/creature/type/humanoid
  - pf2e/creature/level/3
statblock: inline
name: "Charlatan"
level: 3
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "GMG"
name: "Charlatan"
level: "Creature 3"
alignment: "NE"
size: "Medium"
trait_03: "Human"
trait_04: "Humanoid"
modifier: 6
perception:
  - name: "Perception"
    desc: "Perception +6;"
languages: "Common; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +8 (1d20+8); __Deception__: +11 (1d20+11); __Diplomacy__: +9 (1d20+9); __Occultism__: +7 (1d20+7); __Society__: +7 (1d20+7); __Stealth__: +8 (1d20+8); __Thievery__: +8 (1d20+8); __Underworld lore__: +9 (1d20+9); "
abilityMods: [0, 3, 0, 2, 1, 4]

abilities_top:
  - name: "Versatile Performance"
    desc: "  The charlatan can use [[compendium/skills.md#Performance|Performance]] instead of [[compendium/skills.md#Diplomacy|Diplomacy]] to [[Make-an-Impression|Make an Impression]] and instead of [[compendium/skills.md#Intimidation|Intimidation]] to [[Demoralize]]. They can also use an acting [[compendium/skills.md#Performance|Performance]] instead of [[compendium/skills.md#Deception|Deception]] to [[Impersonate]]."
  - name: Items
    desc: "disguise kit, lute, sap, shortsword, thieves' tools;"
abilities_bot:
  - name: "Sneak Attack"
    desc: "  The charlatan deals an extra 1d6 (1d6) precision damage to [[rules/conditions.md#Flat-Footed|flat-footed]] creatures."

speed: 25 feet

ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__: +5 (1d20+5); __Ref__: +8 (1d20+8); __Will__: +10 (1d20+10);"
hp: 40
health:
  - name: HP
    desc: "40; "


attacks:
  - name: Melee
    desc: "⬻ shortsword +10 ([[agile]], [[versatile|versatile s]]); __Damage__ 1d6+2 (1d6+2) piercing"
  - name: Melee
    desc: "⬻ sap +7 ([[agile]], [[nonlethal]]); __Damage__ 1d6+2 (1d6+2) bludgeoning"

spellcasting:
  - name: "Occult Spontaneous Spells"
    desc: "DC 20, attack +10; __Cantrips (2nd)__ [[daze]], [[ghost-sound|ghost sound]], [[mage-hand|mage hand]], [[message]], [[prestidigitation]]; __1st__ (3 slots) [[illusory-disguise|illusory disguise]], [[magic-aura|magic aura]], [[unseen-servant|unseen servant]], [[ventriloquism]]; __2nd__ (2 slots) [[charm]], [[illusory-disguise|illusory disguise]], [[invisibility]];"
  - name: "Bard Composition Spells"
    desc: "DC 19, attack +10; __Cantrips (1st)__ [[inspire-courage|inspire courage]]; __1st__ [[counter-performance|counter performance]];"
sourcebook: "_Gamemastery Guide_, page 210."
```

```encounter-table
name: Charlatan
creatures:
  - 1: Charlatan
```
