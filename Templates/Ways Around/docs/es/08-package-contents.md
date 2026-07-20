# Contenido del paquete

## Archivos necesarios para la instalacion

| Elemento | Destino | Proposito |
|---|---|---|
| `WaysAround.rmg.json` | `HeroesOldenEra_Data/StreamingAssets/map_templates/` | Definicion principal de la plantilla. |
| `WaysAround.png` | `HeroesOldenEra_Data/StreamingAssets/map_templates/` | Imagen de vista previa mostrada por el juego. |
| `WaysAroundAssets.zip` | `HeroesOldenEra_Data/StreamingAssets/` | Archivo de assets requerido. |

## Ficheros fuente de `DB/`

Estos ficheros fuente ya estan incluidos dentro de `WaysAroundAssets.zip`. Se incluyen en el repositorio para inspeccion y modificacion, pero no son necesarios para la instalacion.

| Ruta fuente | Proposito |
|---|---|
| `DB/buildings_constructions/ways_around_buildings_presets.json` | Presets de construcciones para ciudades Spawn, Side y Center. |
| `DB/buildings_bans/ways_around_buildings_bans.json` | Lista de construcciones bloqueadas en la ciudad central. |
| `DB/map/objects/ways_around_flattering_mirrors.json` | Objetos Espejo del Mundo propios de la plantilla. |
| `DB/objects_logic/event_banks/vision_banks/ways_around_flattering_mirrors.json` | Comportamiento de revelado de los espejos. |
