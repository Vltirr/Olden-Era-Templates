# Guards

## Generated Encounter Guards

Random guarded content is placed into encounter layouts that may contain several locations or pickups behind one army. The generator adds the `guardValue` of every filled slot in that encounter, applies the zone's guard multiplier, and then applies the configured randomization and weekly growth.

The following table shows the guard multiplier, randomization, and weekly growth applied to generated encounters in each zone.

| Zone | Guard multiplier | Randomization | Weekly growth |
|---|---:|---:|---:|
| Spawn-A / Spawn-B | 1.00 | 0.05 | 0.20 |
| Side-A / Side-B | 1.25 | 0.05 | 0.20 |
| Center-A / Center-B | 1.25 | 0.05 | 0.20 |
| Center | 1.25 | 0.05 | 0.20 |

These values apply to guards generated for zone content. Connection and town guards use their own explicit values shown below.

## Endless Scroll Guards

Each mandatory Endless Scroll has a reward value of 30000. The template overrides its base guard value to 24000 without changing that reward value. After Center's 1.25 multiplier, each scroll encounter has a nominal initial guard strength of 30000, subject to Center's randomization and weekly growth.

## Ground Connections

| Connection | Guard value | Weekly growth |
|---|---:|---:|
| Spawn-A - Side-A | 14000 | 0.20 |
| Spawn-A - Center-A | 20000 | 0.20 |
| Side-A - Center | 40000 | 0.20 |
| Side-A - Center-B | 50000 | 0.20 |
| Spawn-B - Side-B | 14000 | 0.20 |
| Spawn-B - Center-B | 20000 | 0.20 |
| Side-B - Center | 40000 | 0.20 |
| Side-B - Center-A | 50000 | 0.20 |
| Center - Center-A | 35000 | 0.20 |
| Center - Center-B | 35000 | 0.20 |

The template deliberately supports more than one progression route. In a typical break order, the 14000 Side access is the lightest opening, the 20000 direct treasure access follows, and the Center and cross-route guards demand a larger army. Return portals have no guards.

## Town Guards

| Zone | Chance | Strength | Weekly growth |
|---|---:|---:|---:|
| Side-A / Side-B | 100% | 10000 | 0.10 |
| Center | 100% | 15000 | 0.10 |
