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

## Files

```
FolktailsTubeways/
├── manifest.json
└── TemplateCollections/
    └── TemplateCollection.Buildings.Folktails.blueprint.json
```
