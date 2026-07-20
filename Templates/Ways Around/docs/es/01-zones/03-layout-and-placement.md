# Forma y colocacion

## Diseno global

- Tamano del mapa: `112 x 112`.
- Orientacion: `BoundingCircle`, anclada en `Spawn-A`.
- Rotacion: desactivada.
- Lagos: `lakesFill: 0.05` en todos los layouts.
- Borde exterior: `cornerRadius: 0.6`; ancho de obstaculos: `2`.

## Layouts de zona

| Layout | Zonas | Ajustes relevantes |
|---|---|---|
| `zone_layout_spawn` | Spawn-A/B | Objeto principal centrado; escala de elevacion reducida a `0.08` |
| `zone_layout_sides` | Side-A/B | Objeto principal centrado; escala de elevacion reducida a `0.08` |
| `zone_layout_treasure` | Center-A/B | Layout de tesoro basado en crossroads |
| `zone_layout_center` | Center | Layout central con ciudad neutral |

`roadClusterArea` es `160` y `roadAttraction` es `0.5` en todos los layouts. Influyen en la particion interna y la atraccion de carreteras, pero no garantizan la misma forma en cada semilla.

## Biomas

- Center siempre es `Sand`.
- Center-A y Center-B comparten un bioma no desertico, distinto de ambos Spawn.
- Cada Side usa el bioma de su Spawn vinculado.
