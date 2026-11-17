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

## Third source update — 17 November 2026

The subsequent [game `main` at `13a5d134c8e6`](https://github.com/babunidev/Morkahja/blob/13a5d134c8e63855894436e4f1b09910c5c50b95/server/game/encountersdata.json) had encounter JSON blob `71f490d7ef70f916c896e6f3f78fe247ccfd8a34`. A full per-ID, per-field comparison against `e0bc99c51c74` (blob `d447c5e73729b05d04f15f17a5eabe958cb00a04`) found **one more prose-only change**:

- **20081 — Arcadian Hills:** expanded the wildflowers concealing the engraved **A**, the roots following its lines, the buried border marker and old treasure tales. No letter value changed, and Chapter 4's plan still respects the clue.

Both sources contain exactly **203 encounters**. No record ID, title, follow link or gameplay metadata changed. The five encounters in the **Chapter 2 manuscript draft** (20015, 20018, 20055, 20056, 20128) were unchanged. The literary working source baseline is now `13a5d134c8e63855894436e4f1b09910c5c50b95`.

**Original atlas remains pinned to its historical source snapshot.** This update is source comparison, not a full literary re-edit of all 203 descriptions. The game repository has not been modified.

## Fourth source update — 17 November 2026

A per-ID per-field comparison between [game `13a5d134c8e6`](https://github.com/babunidev/Morkahja/blob/13a5d134c8e63855894436e4f1b09910c5c50b95/server/game/encountersdata.json) (blob `71f490d7ef70f916c896e6f3f78fe247ccfd8a34`) and [game `096c99bdf5ac`](https://github.com/babunidev/Morkahja/blob/096c99bdf5ac8af5174b26a337914f573263ab72/server/game/encountersdata.json) (blob `04403ba5be5a3e00501d8c3078edde0b5edc9557`) found exactly **two additional `mEncounterText` changes**, with **203 unchanged IDs, titles and other fields**.

- **20082 — Alluring Fens:** revised and expanded the delicate singing across mist, black water, mossy trees and distant shifting melody. This remains planned for Chapter 15; use the updated description there.
- **20083 — Enchanted Gardens:** expanded flower and twilight atmosphere; the deliberate **H** remains unchanged, but a **solitary note** now follows the garden's brief silence after the magical flicker. The drafted [Chapter 4](../manuscript/chapters/04-letters-without-a-word.md) was amended accordingly, without changing letter order or explanation.

The cumulative literary source-review differences from the atlas are **19 + 5 + 1 + 2**, all prose-only at their respective updates. Current reviewed source baseline: `096c99bdf5ac8af5174b26a337914f573263ab72`. The 24 encounter descriptions drafted in Chapters 5 and 6 were read from this same revision. Neither the original game nor the established world repository was changed by audiobook development.

## Fifth source update — 17 November 2026

The game `main` at [`734f439b1699`](https://github.com/babunidev/Morkahja/blob/734f439b1699ac144909462d31ca3e045cb4d811/server/game/encountersdata.json) had encounter JSON blob `99ce4bf061d0870353db7246d531889e372fa7f8`. A complete per-ID, per-field comparison against game [`096c99bdf5ac`](https://github.com/babunidev/Morkahja/blob/096c99bdf5ac8af5174b26a337914f573263ab72/server/game/encountersdata.json) (blob `04403ba5be5a3e00501d8c3078edde0b5edc9557`) found **one additional text-only change**:

- **20084 — Mystical Vale:** expanded summer landscape, long shadow of the huge boulder, returning cloud, and the old carved **K**. The letter itself and all game metadata remain unchanged. [Chapter 4](../manuscript/chapters/04-letters-without-a-word.md) now explicitly notes the long shadow and cloud crossing; its word count rose from **3,714 to 3,741**.

**All 203 encounter records and other fields remained unchanged.** Running cumulative changed prose counts compared to the source atlas: **19 + 5 + 1 + 2 + 1**, with latest literary baseline `734f439b1699ac144909462d31ca3e045cb4d811`. The five Chapter 9 encounter descriptions were read in full against this baseline and did not change during the diff. Game and world source repositories were not modified.

## Sixth source update — 17 November 2026

The game `main` at [`ad34afb686ef`](https://github.com/babunidev/Morkahja/blob/ad34afb686efa017cd43ffeccc554afb43d79b22/server/game/encountersdata.json) had encounter JSON blob `b0a3c99ad5ec5ac5f898fac6039c9aee9de8bc67`. A complete per-ID, per-field comparison against [`734f439b1699`](https://github.com/babunidev/Morkahja/blob/734f439b1699ac144909462d31ca3e045cb4d811/server/game/encountersdata.json) (blob `99ce4bf061d0870353db7246d531889e372fa7f8`) found **one `mEncounterText` change**:

- **20085 — Bucolic Dale:** the revised description specifically shows **two small creatures playing**; one scrambles onto the **J**-inscribed half-buried stone, then leaps away and scatters petals, while a larger creature grazes nearby. The carved **J** remains unchanged. [Chapter 4](../manuscript/chapters/04-letters-without-a-word.md) now dramatizes that action and keeps the **A H K J O M A** sequence. The updated Chapter 4 is **3,776 words including its heading**.

Both snapshots have **203** identical records/IDs; **no other metadata or follow-link changed**. Game encounter **20188** continues to follow to **19444**, and Chapter 10 respects this order. Cumulative newer `mEncounterText` differences compared in successive game updates: **19 + 5 + 1 + 2 + 1 + 1**. Current source baseline: `ad34afb686efa017cd43ffeccc554afb43d79b22`. Neither the game nor established world repositories were changed by this audiobook work.
