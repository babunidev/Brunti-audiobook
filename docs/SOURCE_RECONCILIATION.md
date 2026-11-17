# Source reconciliation — 17 November 2026

During Stage 2, the game repository's encounter JSON changed after the first source index was pinned. A direct comparison was made between:

- **Initial atlas source:** [`58576f063627`](https://github.com/babunidev/Morkahja/blob/58576f063627752f77cdf99514baad875d509114/server/game/encountersdata.json), JSON blob `10c493c35d9c82e3a3f0e7776d2b5b9d0ca65358`.
- **Newer current source reviewed:** [`5b0d73e550ca`](https://github.com/babunidev/Morkahja/blob/5b0d73e550ca123adcb095b45febeba4330a9fdf/server/game/encountersdata.json), JSON blob `1e67cc21a5cfb16b299d417e25082935b472abd7`.

## Verified differences

Both snapshots contain **203 encounters**, with identical IDs, titles, gameplay metadata and explicit follow-link relationships. Exactly **19** IDs have a different `mEncounterText` string; **no other field differed** in the JSON comparison:

`20056 · 20057 · 20058 · 20059 · 20060 · 20061 · 20062 · 20063 · 20064 · 20065 · 20066 · 20067 · 20068 · 20069 · 20070 · 20072 · 20073 · 20074 · 20075`

The descriptions retain their broad characters or places. A particularly important difference occurs in **20070 — Enigmatic Prairies**, where the earlier wandering-landscape/treasure rumor has been replaced with **soft notes, still flowers and a luminous moss-covered stone**. Its specific literary hook in the placement matrix has been updated accordingly. Other entry descriptions should still be rechecked in full when constructing chapter prose, especially Grimnir physiology, Evergrove geographical language and whether a line states fact or rumor.

## Status and limits

The original 203-row [source atlas](../story/ENCOUNTER_ATLAS.md) is preserved as an index created against the initial snapshot; its metadata-driven categories and counts remain valid under the later source. The [placement matrix](../story/PLACEMENT_MATRIX.md) now points to the newer text baseline and still covers all 203 unique IDs. No world canon or game files were altered by this audiobook project.

The reconciliation is a **structural and text-field comparison**, not a complete literary close edit of the 19 replacements, a confirmation of runtime game state, or a guarantee that the game will not change after the reviewed commit. New source updates require another deliberate reconciliation.
