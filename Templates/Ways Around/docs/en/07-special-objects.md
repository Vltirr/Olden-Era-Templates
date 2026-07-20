# Special Objects

## World Mirrors

Each Spawn mirror sits next to its starting town and reveals a radius of 10 around two remote mirrors.

| Starting mirror | Revealed mirrors |
|---|---|
| Spawn-A | Side-A and Center-A |
| Spawn-B | Side-B and Center-B |

The Side mirrors sit near the Spawn-Side connection. The Center-A/B mirrors sit near the corresponding Spawn-Center connection. They reuse the Flattering Mirror appearance but have template-specific object IDs and logic in the asset package.

## Return Portals

| From | To | Source placement | Spawn placement |
|---|---|---|---|
| Side-A | Spawn-A | Near town | Near Spawn-A - Center-A |
| Center-A | Spawn-A | Near crossroads | Near Spawn-A - Side-A |
| Side-B | Spawn-B | Near town | Near Spawn-B - Center-B |
| Center-B | Spawn-B | Near crossroads | Near Spawn-B - Side-B |

All are one-way, use range `0.00-0.08` with weight `20`, and have roads to both ends.

## Mana Wells

| Zone | Mandatory mana well placed near |
|---|---|
| Spawn-A | Spawn-A - Side-A |
| Side-A | Side-A - Center-B |
| Center-A | Spawn-A - Center-A |
| Spawn-B | Spawn-B - Side-B |
| Side-B | Side-B - Center-A |
| Center-B | Spawn-B - Center-B |
| Center | Side-A - Center; Side-B - Center; Center - Center-A; Center - Center-B |

Every non-Center zone has one mandatory mana well next to the listed exit. Center has four, one near each direct entrance. Center-A/B also contain a Celestial Spire; see [mandatory content](01-zones/07-mandatory-content.md).
