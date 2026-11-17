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

## Second source update — 17 November 2026

A subsequent comparison of [game commit `5b0d73e550ca`](https://github.com/babunidev/Morkahja/blob/5b0d73e550ca123adcb095b45febeba4330a9fdf/server/game/encountersdata.json) (blob `1e67cc21a5cfb16b299d417e25082935b472abd7`) against the later [game `e0bc99c51c74`](https://github.com/babunidev/Morkahja/blob/e0bc99c51c74bb088f27a8252082b41c61629cf7/server/game/encountersdata.json) (blob `d447c5e73729b05d04f15f17a5eabe958cb00a04`) found **five more records changed**, again **only `mEncounterText`**. All **203** IDs, titles, other fields and follow links remained identical.

| ID | Name | Prose change relevant to adaptation |
| ---: | --- | --- |
| 20076 | Aevis Merchant | Expanded the Celesterra-threshold stall and keepsake story; remains an independently reported visit in chapter 9 |
| 20077 | Quicksilver Quagmire | More detailed uncanny stars and reflection; chapter 15 must not frame them as certain prophecy |
| 20078 | Unhinged Gobbl | More detailed bodily distortion and gestures; chapter 22 remains an observed individual |
| 20079 | Fearfeaster Gobbl | A stronger account of vegetation-like limbs and apparent appetite for fear; chapter 22 preserves separate testimony |
| 20080 | Dreamy Valley | More detailed hidden passage among pink blossoms and great rocks; chapter 3 scenic cue was updated |

**Current literary scene-input baseline:** `e0bc99c51c74bb088f27a8252082b41c61629cf7`. The original atlas remains historically pinned, and no game files were modified. If game `main` advances again, the working edition requires another explicit comparison, not silent rewriting.
