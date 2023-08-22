# Pathfinder 2E Community Vault

> Important: It is very helpful when starting with this vault, to learn what [Absolute Paths Are](https://www.redhat.com/sysadmin/linux-path-absolute-relative) and what [Markdown Links Are](https://help.obsidian.md/Linking+notes+and+files/Internal+links) and why both are used.

This is Obsidian TTRPG Community's Pathfinder 2E Vault, containing nearly everything you need to get started building your next campaign. 

## Repository Navigation

- `.obsidian/snippets/pf2-compendium.css`: A snippet meant to style various aspects of the `compendium` and `rules` folders.
- `compendium`: The individual nuts and bolts of the various PF2E rulebooks. Think spells, items, etc.
- `fantasy-bestiary`: [Fantasy Statblocks](https://github.com/javalent/fantasy-statblocks/) developed monster statblocks. When the `compendium` gains its markdown bestiary, this will be considered an optional feature.
- `optionals`: The optionals folder will contain specific and possibly redundant scripts, such as the [PF2E-Action-Link-Icons](optionals/action-icons/PF2E-Action-Link-Icons.css) snippet for those who do not want to use the `.pf2-compendium` CSS.
- `rules`: The rules contained within the PF2E rulesbooks.
- `all-index` and `src-index`: These are generated with every update for testing and reconciliation purposes. 
- `license`: The required licenses and disclaimers for the repository.


## Required Plugins and Scripts


### Admonitions

[Admonition](https://github.com/valentine195/obsidian-admonition) by [Javalent](https://github.com/valentine195). 

The Compendium and Rules Folders use custom admonitions to call out and format much of their content.

Without these Admonitions, you will see a lot of ugly text.

You can find the [Admonitions.json](https://github.com/ebullient/ttrpg-convert-cli/tree/main/examples) at the TTRPG-CLI repository. The specific admonitions file for this repository will have `pf2e` in the name. 

You can view instructions how to import the .json file at Javalent's [Plugins Documentation](https://plugins.javalent.com/admonitions/import-json#Obtain%20an%20Admonitions.Json%20File)  site.


### Fantasy Statblocks

[Fantasy Statblocks](https://github.com/javalent/fantasy-statblocks/) by  [Javalent](https://github.com/valentine195). 

Fantasy Statblocks makes the Bestiary usable and pretty. It also integrates nicely with [Initiative Tracker](https://github.com/javalent/initiative-tracker).

Having issues with the Pathfinder 2E layout? Report an issue at the [Pathfinder 2E Development Repository](https://github.com/Obsidian-TTRPG-Community/Pathfinder-2E-Statblocks-Development).

> **Hint**: If Using ITS Theme, turn off Statblock styling in Style Settings. This will make the Statblock look as it should. 


## Optional, But Highly Recommended


### Pathfinder CSS

The `compendium` and `rules` folders are styled with customized CSS. This repository now includes the `.obsidian/snippets/pf2-compendium.css` from the [TTRPG-Covert-CLI](https://github.com/ebullient/ttrpg-convert-cli) repository. The most up-to-date version can be found on the TTRPG-Convert repository, but this repository will 


### Force Note View in Frontmatter

[Obsidian force view mode of note](https://github.com/bwydoogh/obsidian-force-view-mode-of-note) by Bwydoogh

This plugin automatically switches a note to source or reading mode based off a key/value pair within the frontmatter of the note. 

The files within the `compendium` and `rules` folders are all equipped with this frontmatter setup.

## Optionals

The optionals folder will contain specific and possibly redundant scripts, such as an action icons link snippet for those who do not want to use the contained CSS. 

## Special Thanks
This community vault has been brought to you by the efforts of many individuals. 

- [eBullient](https://github.com/ebullient), for their [TTRPG-Covert-CLI](https://github.com/ebullient/ttrpg-convert-cli) that pulls the data from PF2ETools and converts it to Markdown Form.
- [Javalent](https://github.com/valentine195), for their useful plugins help make some painful parts of 
  this process much easier. 
- [Sigrunixia](https://github.com/sigrunixia), eventually, for their over-spazzing on the CSS and getting the thing uploaded onto the Vault.
- [Robinsving](https://github.com/robinsving), whose dataview spells will get re-added to the CLI spell format, soon. (I promise.)

If I forgot someone, poke me – Sigrunixia

## Changelog

- 2023-06-02: Switched to a Release Format, and made breaking changes with removal of some core content per Paizo request at PF2E Tools. Started working on re-addition for [Robinsving](https://github.com/robinsving) dataview enabled spells.
- 2023-04-28: Cleanup in preparation for major update
- 2023-03-02: Updated Broken Links, made relative to top-level folder thus enabling to be moved when consistent plugins are used. Merged Pathfinder 2E into TTRPGShare Pathfinder Vault.
- 2023-02-21: CLI Enabled Initial Load onto Share out of Testing Mode

## Legal Disclaimer

> "The Obsidian TTRPG Community uses trademarks and/or copyrights owned by Paizo Inc., used under [Paizo's Community Use Policy](http://paizo.com/communityuse). 
>
> We are expressly prohibited from charging you to use or access this content. __Obsidian TTRPG Community__ is not published, endorsed, or specifically approved by Paizo. 
>
> For more information about Paizo Inc. and Paizo products, visit [paizo.com](http://paizo.com/).
