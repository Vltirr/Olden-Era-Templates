# Ways Around

<img src="./WaysAround.png" alt="Ways Around preview" width="360">

`Ways Around` is a 2-player `Single Hero` random map template for *Heroes of Might and Magic: Olden Era* built around two distinct attack routes: an outer flank and a central breakthrough. The map combines direct high-value crossings, return portals back to each player's home side, and a tournament win condition that keeps pressure high even when both players avoid direct contact.

## Summary

- 2 players
- `Single Hero` mode
- Best-of-3 tournament victory
- 7 zones: 3 per player plus 1 neutral central zone
- No Pandora's Boxes
- Neutral world magic limited to `Second Wind`; starting heroes also receive `Back to Town!` and `Relocation` at 0 cost
- Return portals from contested zones back to each player's spawn side

## Victory Conditions

- Best-of-3 tournament victory
- Tournament battles are scheduled for days `12`, `19`, and `26`
- A player can also win by defeating the enemy hero on the adventure map
- A player also loses by losing their starting town

## Gameplay

Each player starts in a home zone with access to two forward options:

- an outer route through their side city
- a more direct route through their linked central treasure zone

Both routes eventually open into contested territory and toward the opposing player. The center is the highest-value area on the map, but it is also the most heavily defended and easiest to contest. The side paths create a longer attack arc, while the central access points create faster contact and more direct pressure.

Return portals reduce dead time after committing outward. They let players project force into contested zones while still preserving a route back toward their home side.

## Map Topology

The map has 7 zones:

- `Spawn-A`
- `Side-A`
- `Center-A`
- `Center`
- `Center-B`
- `Side-B`
- `Spawn-B`

Direct ground connections:

- `Spawn-A <-> Side-A`
- `Spawn-A <-> Center-A`
- `Side-A <-> Center`
- `Side-A <-> Center-B`
- `Center <-> Center-A`
- `Center <-> Center-B`
- `Side-B <-> Center`
- `Side-B <-> Center-A`
- `Spawn-B <-> Center-B`
- `Spawn-B <-> Side-B`

One-way return portals:

- `Side-A -> Spawn-A`
- `Center-A -> Spawn-A`
- `Side-B -> Spawn-B`
- `Center-B -> Spawn-B`

## Zone Roles

| Zone | Role | Main Features | Expected Reward Profile |
|---|---|---|---|
| `Spawn-A`, `Spawn-B` | Home/start zones | Starting town, early mines, early banks, one-time faction T1/T2 dwellings, World Mirror | Early economy and safe first clears |
| `Side-A`, `Side-B` | Outer pressure zones | Side town, economy package, guarded T3 banks, World Mirror, route toward enemy treasure/center | Strong midgame economy and pressure route |
| `Center-A`, `Center-B` | Forward treasure zones | No town, Research Laboratory, Celestial Spire, one-time faction T5/T6 dwellings, World Mirror | High-value treasure and advanced tempo tools |
| `Center` | Core conflict zone | Neutral town with Mage Guild V prebuilt and all other construction blocked, Dragon Utopia, Research Laboratory, multiple magic structures, 4 mana wells | Highest-value and most contested area |

## Reward Expectations

Relative zone value is intentionally uneven:

- `Center` is the premium zone
- `Center-A` and `Center-B` are strong treasure zones, but below `Center`
- `Side-A` and `Side-B` are rich side zones with town control and strong bank access
- `Spawn-A` and `Spawn-B` are streamlined opening zones with guaranteed economy and lower overall ceiling

## Installation

The template needs three installation targets:

1. Template folder:
   Copy the full folder `Ways Around` into the game's `StreamingAssets/map_templates/` directory.

2. Assets zip:
   Place [`WaysAroundAssets.zip`](./WaysAroundAssets.zip) in the root of `StreamingAssets/`.

Expected result:

- `StreamingAssets/map_templates/Ways Around/...`
- `StreamingAssets/WaysAroundAssets.zip`

Restart the game after updating the zip.

## Files

- [`WaysAround.rmg.json`](./WaysAround.rmg.json): main template
- [`WaysAround.png`](./WaysAround.png): preview image
- [`WaysAroundAssets.zip`](./WaysAroundAssets.zip): DB asset package
