# Placement Rules

Placement rules determine where a mandatory object is generated within its zone. A target is the reference point used by the rule: `MainObject` is the zone's town or other primary object, `Crossroads` is its internal road hub, and `Connection` is the specified exit to another zone.

| Object | Zone(s) | Target | Range (min/max distance to target) | Weight |
|---|---|---|---|---:|
| Sawmill, Ore Mine | Spawn-A/B | Starting town (`MainObject 0`) | 0.05-0.18 | 10 |
| Research Laboratory | Center-A/B | Crossroads | 0.45-1.00 | 10 |
| Dragon Utopia | Center | Crossroads | 0.45-1.00 | 10 |
| Research Laboratory | Center | Crossroads | 0.45-1.00 | 10 |
| Spawn World Mirror | Spawn-A/B | Starting town (`MainObject 0`) | 0.00-0.06 | 30 |

Other mandatory elements, including mana wells, destination mirrors, and portal ends, use named connections so that their location corresponds to a specific exit.
