# Ciudades y construcciones

| Zona | Tipo | Preset | Configuración |
|---|---|---|---|
| Spawn-A / Spawn-B | Spawn | `ways_around_spawn_buildings_construction` | Construcciones por defecto con Cofradía de Magos I |
| Side-A / Side-B | City | `ways_around_side_buildings_construction` | Moradas de criaturas Tier 1 y Tier 2, Taberna y Cofradía de Magos II |
| Center | City | `ways_around_center_buildings_construction` | Edificio principal III, Cofradía de Magos V, Banco, Tesorería, Mercado, Mercader de Artefactos, Silo de recursos y Silo alquímico |

Center usa también `ways_around_center_buildings_ban`, que bloquea cualquier construcción fuera de su preset.

La ciudad neutral de Center puede pertenecer a Necrópolis, Foresta, Colmena o Mazmorra, y debe ser distinta de las dos facciones iniciales. Templo y Cisma quedan excluidos porque sus ciudades no pueden ofrecer la recompensa completa de Cofradía de Magos V requerida en Center.

Los presets están en `DB/buildings_constructions/ways_around_buildings_presets.json` dentro de `WaysAroundAssets.zip`; la lista de baneos de Center está en `DB/buildings_bans/ways_around_buildings_bans.json`.
