# Layout and Placement

## Global Layout

- Map size: `112 x 112`.
- Orientation: `BoundingCircle`, anchored on `Spawn-A`.
- Rotation: disabled.
- Lakes: `lakesFill: 0.05` on every layout.
- Outer border: `cornerRadius: 0.6`; obstacle width: `2`.

## Zone Layouts

| Layout | Used by | Relevant settings |
|---|---|---|
| `zone_layout_spawn` | Spawn-A/B | Main object centered; reduced elevation scale `0.08` |
| `zone_layout_sides` | Side-A/B | Main object centered; reduced elevation scale `0.08` |
| `zone_layout_treasure` | Center-A/B | Crossroads-based treasure layout |
| `zone_layout_center` | Center | Neutral-city central layout |

`roadClusterArea` is `160` and `roadAttraction` is `0.5` across layouts. These settings influence internal partitioning and road attraction but do not guarantee an identical shape on every seed.

## Biomes

- Center is always `Sand`.
- Center-A and Center-B share one non-Sand biome, different from both player Spawn biomes.
- Each Side uses the biome of its linked Spawn.
