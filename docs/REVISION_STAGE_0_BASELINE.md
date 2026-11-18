# Stage 0 — fixed manuscript inventory and verification baseline

**18 November 2026 — recorded baseline, not an edited literary edition.** ChatGPT (GPT-6) collected this inventory from the actual chapter files, the [chapter index](../manuscript/chapters/README.md), the [203-ID placement matrix](../story/PLACEMENT_MATRIX.md), [scene index](../story/scenes/README.md), and [source ledger](SOURCES.md) under Babuni's direction.

## Immutable revision anchor

- **Audiobook repository:** `babunidev/audiobookGrimnir`.
- **Starting `main` commit:** [`0916221b5940d1a48229c4dc216207bd523202e0`](https://github.com/babunidev/audiobookGrimnir/tree/0916221b5940d1a48229c4dc216207bd523202e0). Subsequent documentation commits do not modify the manuscript baseline.
- **Reviewed game-source revision:** [`952437c5c59da26a2f873f1a18590496f88a2354`](https://github.com/babunidev/Morkahja/tree/952437c5c59da26a2f873f1a18590496f88a2354) from the project source ledger.
- **Checked game `main` at Stage 0:** `66245f2f5ca4fcddc21e9fd4d0c44290760c6c58`. The compare endpoint reports **10 newer commits** and edits to `server/game/encountersdata.json` (10 line additions and 10 deletions). **The changed encounter contents have not yet been reconciled against the manuscript**; this is a flagged Stage 5/source-edit dependency, not a statement of which IDs changed.
- **Novel status:** first draft (30 chapters), independently editorial-approved chapters **0**, audiobook scripts/audio **not complete**. All 203 matrix rows say `Draft v1`, not independently verified source fidelity.

## Audited chapter-file manifest

The word column is a newly reproducible **whitespace-token count** (`content.trim().split(/\s+/)`), *not* the chapter index's historical counting convention. Hashes are chapter-content Git blob SHAs read from GitHub (first 12 characters shown). Links target the current visible chapter paths; the immutable starting commit above is the audit anchor.

| Chapter | Chapter file | Mapped IDs | Whitespace tokens | Git blob SHA |
| ---: | --- | ---: | ---: | --- |
| 01 | [01-skyland-morning](../manuscript/chapters/01-skyland-morning.md) | 0 | 3,254 | `7837441ddc5d` |
| 02 | [02-the-weight-of-other-stones](../manuscript/chapters/02-the-weight-of-other-stones.md) | 5 | 3,375 | `c4c08108c450` |
| 03 | [03-a-road-made-of-grass](../manuscript/chapters/03-a-road-made-of-grass.md) | 11 | 3,233 | `1f22eff05169` |
| 04 | [04-letters-without-a-word](../manuscript/chapters/04-letters-without-a-word.md) | 11 | 3,901 | `79847d69779b` |
| 05 | [05-the-lives-of-the-vale](../manuscript/chapters/05-the-lives-of-the-vale.md) | 16 | 4,125 | `cee7a66463ea` |
| 06 | [06-under-eldertree](../manuscript/chapters/06-under-eldertree.md) | 8 | 3,878 | `a89dbbabd656` |
| 07 | [07-things-that-are-kept](../manuscript/chapters/07-things-that-are-kept.md) | 12 | 3,609 | `4e83ab3f5f4f` |
| 08 | [08-at-the-green-boundary](../manuscript/chapters/08-at-the-green-boundary.md) | 4 | 3,198 | `6ab0a39e15a5` |
| 09 | [09-where-stories-are-sold](../manuscript/chapters/09-where-stories-are-sold.md) | 5 | 3,889 | `dd3d3ea9f566` |
| 10 | [10-the-shelter-beyond-the-veil](../manuscript/chapters/10-the-shelter-beyond-the-veil.md) | 6 | 5,084 | `2d1819f3a5a4` |
| 11 | [11-the-city-of-listening](../manuscript/chapters/11-the-city-of-listening.md) | 5 | 5,205 | `8c0af490ce11` |
| 12 | [12-where-water-is-guarded](../manuscript/chapters/12-where-water-is-guarded.md) | 4 | 5,505 | `09ad1600348e` |
| 13 | [13-after-the-raid](../manuscript/chapters/13-after-the-raid.md) | 10 | 5,593 | `c68ae91cc903` |
| 14 | [14-words-in-the-sand](../manuscript/chapters/14-words-in-the-sand.md) | 4 | 4,864 | `7cd2c8696bd6` |
| 15 | [15-beneath-the-reeds](../manuscript/chapters/15-beneath-the-reeds.md) | 6 | 4,947 | `ea9bc19d3138` |
| 16 | [16-witnesses-of-corruption](../manuscript/chapters/16-witnesses-of-corruption.md) | 12 | 4,963 | `f890b8064c22` |
| 17 | [17-the-mountain-has-a-voice](../manuscript/chapters/17-the-mountain-has-a-voice.md) | 11 | 4,827 | `0c7d86b46d9a` |
| 18 | [18-the-last-warm-bowl](../manuscript/chapters/18-the-last-warm-bowl.md) | 5 | 5,269 | `96a55b4103ed` |
| 19 | [19-ice-that-remembers](../manuscript/chapters/19-ice-that-remembers.md) | 7 | 4,861 | `5657bdbb0851` |
| 20 | [20-the-broken-frostweaver-record](../manuscript/chapters/20-the-broken-frostweaver-record.md) | 9 | 6,491 | `c55656998f17` |
| 21 | [21-before-the-cursed-trees](../manuscript/chapters/21-before-the-cursed-trees.md) | 5 | 4,579 | `575746726d71` |
| 22 | [22-the-price-of-warning](../manuscript/chapters/22-the-price-of-warning.md) | 5 | 4,879 | `f0dd0cba56a4` |
| 23 | [23-those-who-still-tend-the-forest](../manuscript/chapters/23-those-who-still-tend-the-forest.md) | 12 | 7,190 | `ada4e445dc26` |
| 24 | [24-paths-among-the-dead](../manuscript/chapters/24-paths-among-the-dead.md) | 20 | 5,741 | `b8aa590f6024` |
| 25 | [25-the-door-in-the-cliff](../manuscript/chapters/25-the-door-in-the-cliff.md) | 3 | 5,461 | `9a6bce485cc4` |
| 26 | [26-the-voices-beneath](../manuscript/chapters/26-the-voices-beneath.md) | 3 | 5,369 | `4c5fce10b90d` |
| 27 | [27-what-the-throne-keeps](../manuscript/chapters/27-what-the-throne-keeps.md) | 2 | 5,371 | `b07c32b4bde1` |
| 28 | [28-a-story-about-the-end](../manuscript/chapters/28-a-story-about-the-end.md) | 1 | 5,799 | `ef1017997f3b` |
| 29 | [29-the-work-of-bringing-back](../manuscript/chapters/29-the-work-of-bringing-back.md) | 0 | 5,676 | `c2c2d83ede34` |
| 30 | [30-the-note-that-remains](../manuscript/chapters/30-the-note-that-remains.md) | 1 | 5,567 | `9337ab9bc727` |
| **Total** | **30 present** | **203** | **145,703** | — |

The manuscript index records **145,383 words including headings** under its original counting method. The whitespace-token computation above yields **145,703** (320 more): this is a **counting-method discrepancy**, not evidence of missing chapters or an unauthorized rewrite. Retain the established 145,383 figure as the existing editorial baseline until one explicit counting convention is selected and recomputed in a later revision.

**Verification performed:** unique matrix IDs **203/203**; manuscript status rows **203/203 Draft v1**; chapter index **30 entries**; mapped encounter totals across chapters **203**; no duplicate encounter ID in the matrix. Source-specific prose fidelity and the actual 109 scene briefs' accuracy were **not** revalidated here; the [scene plan](../story/scenes/README.md) currently reports 109.

## Immutable story constraints for later stages

- Keep [Blackwood follow-chain](../story/PLACEMENT_MATRIX.md): `20050 → 19666 → 19667 → 19668 → 19669 → 19670 → 19671 → 19672`, chapters 25–27.
- Keep three other follows: `20188 → 19444` (chapter 10), `20192 → 19001` (chapter 12), `20130 → 20131` (chapter 19).
- Keep engraved letters in order `A H K J O M A` (chapter 4); **do not invent a decoding**.
- ID `1` Atranor is secondhand testimony in chapter 28; ID `2` Level up! is a narrative metaphor in chapter 30.
- Keep Brunti a living Grimnir **warrior**, not an armored human; preserve world lore's deliberate unknowns.
- The composite memorial is a **novel-only** local mystery; memory stones retain fixed echoes, not living speakers; Tavra/Korrum first identification is intended for chapter 29 and is presently contradicted by earlier prose.

## Stage 0 status and traceability

- **Completed:** exact repository anchor; 30-file chapter inventory and blob IDs; independent matrix/index structural checks; identification of a newer unreconciled game source.
- **Companion ledgers:** [chronology, knowledge and objects](../story/REVISION_CHRONOLOGY_AND_OBJECTS.md); [chapter functions](../story/REVISION_CHAPTER_FUNCTIONS.md).
- **Not claimed:** full game diff reconciliation, exhaustive line-by-line literary audit, independent source/canon approval, corrections to chapter text, narrator readiness.

**No manuscript chapter, source game or world-canon file was edited in Stage 0.**
