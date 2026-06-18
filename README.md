# Olden Era Templates

Repository storing my custom created *Heroes of Might and Magic: Olden Era* templates and the helper assets needed to build and ship them.

## Repository Structure

- [`Templates/`](./Templates/): playable templates and their bundled assets

## Included Templates

Currently the repository includes:

- [`Ways Around`](./Templates/Ways%20Around/): 2-player `Single Hero` template focused on outer flanks, central breakthrough pressure, and scheduled tournament battles

Each template folder may contain:

- the main `.rmg.json` template file
- preview and diagram images
- asset zips or helper source files used to build them
- template-specific installation notes

## Purpose

This repository is meant to serve two roles:

1. A distribution point for finished custom templates.
2. A versioned workspace for iterating on those templates over time.

## Notes

- The repository is organized for GitHub first, not as a direct drop-in game folder.
- Template folders include installation instructions describing what needs to be copied into `StreamingAssets/`.
