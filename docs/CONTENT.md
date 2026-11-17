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

## Working narrative spine — 17 November 2026

The [story spine](../story/STORY_SPINE.md), [character arcs](../story/CHARACTER_ARCS.md) and [causal chain](../story/CAUSAL_CHAIN.md) now specify the narrative motives linking the existing 30 chapter groups. These are **authored novel-fiction directions**, not world-canon modifications or manuscript coverage proof. The [placement matrix](../story/PLACEMENT_MATRIX.md) retains all 203 proposed primary source placements; no IDs or source encounters were changed by the spine work.

## Scene-level planning audit — 17 November 2026

The [30-chapter scene index](../story/scenes/README.md) now links five movement files with **109 individually labeled scenes** and **203 uniquely assigned source-ID annotations**. A structural comparison with the [placement matrix](../story/PLACEMENT_MATRIX.md) produced **0 missing, 0 extra, 0 duplicate and 0 chapter-mismatched IDs**. Story action, scene turns and human-scale consequences were drafted; this is **not** completed literary integration in prose, a human review, or a comprehensive source-to-canon audit. The [scene continuity register](SCENE_CONTINUITY.md) explicitly records remaining location, timing and provenance questions.

The game prose baseline was refreshed again at `e0bc99c51c74`; **five** further descriptions changed after the earlier nineteen, but no encounter ID or follow-link changed. Both comparisons are in [source reconciliation](SOURCE_RECONCILIATION.md).

## First manuscript integration — 17 November 2026

[Chapter 1 and Chapter 2](../manuscript/chapters/README.md) are now actual **first-draft literary prose**, totaling **6,562 words**. Chapter 1 is novel-only connecting fiction. Chapter 2 adapts **20015, 20018, 20055, 20056 and 20128** through attributed testimony; the five complete game descriptions were compared against the reviewed source. The [placement matrix](../story/PLACEMENT_MATRIX.md) records **5 Draft v1** entries, **198 Planned**, **0 editorially verified**. The [manuscript review](MANUSCRIPT_REVIEW.md) records physical and gender-description tensions against the world archive. The earlier encounter atlas retains historical source-inventory labels; its original 'Unplaced' status should not be used to infer present manuscript progress.

The game baseline subsequently advanced one further encounter text (20081 Arcadian Hills), for a cumulative sequence of **19 + 5 + 1** text-only differences since the atlas. All 203 IDs remain.

## Ethera's Vale manuscript development — 17 November 2026

[Chapter 3](../manuscript/chapters/03-a-road-made-of-grass.md) and [Chapter 4](../manuscript/chapters/04-letters-without-a-word.md) have been drafted in actual prose (a further **6,906 words including headings**), adapting **22 unique** source encounters. The first four chapters total **13,468 words including headings**; [matrix](../story/PLACEMENT_MATRIX.md): **27 Draft v1**, **176 Planned**, **0 independently verified**. All 22 full game encounter texts and selected established Vale lore entries were read in the [chapter review](CHAPTERS_03_04_REVIEW.md).

Encounter **20072 Tranquil Wilds** is delivered as **Eda's testimony of autumn** rather than witnessed during Brunti's summer road journey. Its matrix mode changed from Lived to Testimony; this is a literary framing adjustment, not a game source edit. All seven original carved letters **A H K J O M A** remain in Chapter 4. Source encounter **20074 Mysterious Cube** appears as a second-hand archive account, preserving the distinction from firsthand discovery.

## Wildlife and Eldertree manuscript draft — 17 November 2026

ChatGPT (**GPT-6**) drafted [Chapter 5](../manuscript/chapters/05-the-lives-of-the-vale.md) and [Chapter 6](../manuscript/chapters/06-under-eldertree.md) as full novel prose, adding **24 distinct** encounter integrations to the first **27**. The [matrix](../story/PLACEMENT_MATRIX.md) now records **51 Draft v1** / **152 Planned** / **0 independently editorial-verified**, across 203 unchanged source IDs. [Source fidelity review](CHAPTERS_05_06_REVIEW.md) distinguishes actual sightings, tracker accounts and keeper reports, and records the Aevis royal-crest and older “dworv” terminology tensions.

A fourth source refresh changed **two** additional prose descriptions (20082 Alluring Fens; 20083 Enchanted Gardens); the letter **H** remains the same, and Chapter 4 was revised to include its new final note. Six prose chapters now total **21,197 words including headings**. These are first drafts, not a completed audiobook or approved canon.
