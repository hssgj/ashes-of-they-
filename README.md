# Ashes of Thay — Persistent Memory Core

This repository is the persistent memory layer for **Ashes of Thay (AOT)**.

## Core rule

> **GitHub remembers. ChatGPT plays.**

ChatGPT remains the live game engine, narrator, adjudicator, and continuity partner. This repository stores durable project state so the game can be reconstructed across sessions.

## Memory priority

1. `CHECKPOINT/` — current live game state
2. `CANON/` — locked canon and continuity rules
3. `CHARACTERS/` — current character/crew state
4. `WORLD/` — established world/lore
5. `SYSTEMS/` — mechanics and engines
6. `MODULES/` — playable modules
7. `ITEMS/` and `LOCATIONS/` — reference data
8. `FUTURE_CANON/` — deliberately future/hidden material
9. `RESEARCH/` — evidence, research, unresolved questions, source comparison
10. `FORGE/` — literary drafts and source material awaiting canon promotion
11. `ARCHIVE/` — superseded or recovered legacy material

## Continuity pipeline

`HARVEST → RESEARCH → FORGE → CANON`

Harvest preserves raw evidence. Research tests or compares evidence. Forge develops usable creative/source material. Canon contains only explicitly locked material.

## Operating rules

- Unknown is not invented.
- Old is not automatically canon.
- Canon ≠ idea.
- Do not silently retcon established material.
- Preserve unfinished material as unfinished.
- When sources conflict, flag the conflict instead of guessing.
- DM-only information remains separate from player-facing material.
- Current live state outranks static module defaults.

## Recovery status

This repository is being reconstructed from the existing Ashes of Thay project history. Original local source files are temporarily inaccessible, so recovered material is entered only when supported by existing project records or recovered source material.
