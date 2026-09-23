# Folktails Tubeways

Gives the **Folktails** faction access to tubeways (normally Iron Teeth only):
- Tubeway Station
- Tubeway
- Vertical Tubeway
- Impermeable Tubeway

## How it works

Timberborn decides which buildings a faction can build via the
`Buildings.Folktails` / `Buildings.IronTeeth` template collections.
This mod appends the four existing Iron Teeth tubeway blueprints to the
Folktails collection, reusing the base-game models, icons, costs, and
localization. No new assets or code required — pure JSON blueprint mod,
per https://github.com/mechanistry/timberborn-modding/wiki/Blueprints#modifying-blueprints.

## Install

Copy the `FolktailsTubeways` folder into your local mods directory:

- Windows: `Documents/Timberborn/Mods/FolktailsTubeways`
- The folder must contain `manifest.json` at its root.

Then restart the game (or refresh mods in the Mod Manager) and start a
Folktails playthrough. Tubeways appear under the Paths tool group.

## Files

```
FolktailsTubeways/
├── manifest.json
└── TemplateCollections/
    └── TemplateCollection.Buildings.Folktails.blueprint.json
```
