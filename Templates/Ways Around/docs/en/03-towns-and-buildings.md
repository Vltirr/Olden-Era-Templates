# Towns and Buildings

| Zone | Type | Preset | Setup |
|---|---|---|---|
| Spawn-A / Spawn-B | Spawn | `ways_around_spawn_buildings_construction` | Default construction profile with Mage Guild I |
| Side-A / Side-B | City | `ways_around_side_buildings_construction` | Tier 1 and Tier 2 creature buildings, Tavern, Mage Guild II |
| Center | City | `ways_around_center_buildings_construction` | Main building III, Mage Guild V, Bank, Treasury, Market, Artifact Merchant, Resource Silo, Alchemy Silo |

The Center also uses `ways_around_center_buildings_ban`, blocking every construction not included in its preset.

The neutral Center town can be Necropolis, Grove, Hive, or Dungeon, and must differ from both players' starting factions. Temple and Schism are excluded because their towns cannot provide the complete Mage Guild V reward required for Center.

Building presets are supplied by `WaysAroundAssets.zip` in `DB/buildings_constructions/ways_around_buildings_presets.json`; the Center ban list is in `DB/buildings_bans/ways_around_buildings_bans.json`.
