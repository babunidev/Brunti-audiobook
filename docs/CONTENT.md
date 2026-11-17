# Encounter coverage and categorization method

The [encounter atlas](../story/ENCOUNTER_ATLAS.md) indexes **203 distinct source records** from the [game data snapshot 58576f063627](https://github.com/babunidev/Morkahja/blob/58576f063627752f77cdf99514baad875d509114/server/game/encountersdata.json).

## By game expansion association

| Association | Encounter count |
| --- | ---: |
| 0 — Base / unspecified | 130 |
| 1001 — Keldor | 48 |
| 1003 — Everwinter | 20 |
| 1004 — Aetherion | 5 |
| **Total** | **203** |

Base/unspecified is not a geographical location. The Urcogor Ravage expansion exists in the catalog but has no assigned encounter in this snapshot.

## By game type — preliminary literary categories

| Code | Game label | Count | First-pass story function |
| --- | --- | ---: | --- |
| 1 | Combat | 61 | Conflict, threat, obstacle |
| 2 | Trick | 73 | Exploration, discovery, journey |
| 3 | Help | 47 | Aid, meeting, relationship |
| 4 | Learn | 11 | Lore, revelation, ritual |
| 5 | Trade | 9 | Exchange, social life |
| 66 | Atranor event | 1 | Mortality and the afterlife |
| 77 | Level up! | 1 | Mechanical milestone needing literary treatment |

These are **metadata-derived categories**, not a claim that every encounter text has received detailed literary interpretation. Combat categories may ultimately be told peacefully or as second-hand accounts.

## Explicit follow-links

**Ten nonzero follow fields** were read from the source:

- 20050 → 19666 → 19667 → 19668 → 19669 → 19670 → 19671 → 19672 — Blackwood/ Keldor sequence.
- 20130 → 20131 — Everwinter Guardian / Everwinter Cave.
- 20188 → 19444 — Mystic Hearth's Seal / Hearthguard Sanctuary.
- 20192 → 19001 — Nereval Elite / Nerevals Sanctuary.

The [game's encounter revision note](https://github.com/babunidev/Morkahja/blob/58576f063627752f77cdf99514baad875d509114/docs/ENCOUNTER_REVISION.md) also identifies letter clues across 20081, 20083, 20084, 20085, 20086, 20087 and 20089. They deserve connected treatment when the full prose is analyzed.

The special entries **1 Atranor** and **2 Level up!** should be handled on their actual literary merits, not invented as ordinary geographical stops.

## Placement standard for Stage 2

Every source ID eventually needs a named chapter/scene, a narrative delivery mode (lived scene, testimony, document, song, memory, etc.), and a status of proposed, approved, drafted or verified in manuscript. Multiple encounters may share a scene; a single encounter may recur. A mere title mention is not sufficient.

All atlas placements remain **Unplaced** until actual outlining occurs. Neither inclusion in the atlas nor an expansion label constitutes narrative integration.

## Structural proposal — 17 November 2026

A [literary survey](../story/LITERARY_SURVEY.md) now describes the scene types and canon cautions, and the [placement matrix](../story/PLACEMENT_MATRIX.md) assigns each of the **203** source encounter IDs to exactly one proposed primary chapter with a delivery mode and specific narrative role. Completeness was checked by comparing IDs against the pinned JSON: **zero missing, zero extras, zero duplicates**. These are **proposed placements**, not approved source adaptations or completed manuscript passages. The earlier atlas retains its Unplaced labels as an approved/drafted-status ledger until individual chapters are accepted.

## Source refresh — 17 November 2026

The current game main at `5b0d73e550ca123adcb095b45febeba4330a9fdf` has a different encounter JSON blob from the originally pinned atlas. A field-level comparison found **19 changes, all to encounter text only**, without ID, title, follow-link or other metadata differences. The [source reconciliation](SOURCE_RECONCILIATION.md) records both revisions and affected IDs. The [placement matrix](../story/PLACEMENT_MATRIX.md) uses the later prose baseline and remains complete, but literary close editing remains pending.
