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

## Forest possessions and Liani boundary — 17 November 2026

ChatGPT (**GPT-6**) wrote [Chapter 7](../manuscript/chapters/07-things-that-are-kept.md) (**3,504 words**) and [Chapter 8](../manuscript/chapters/08-at-the-green-boundary.md) (**3,131 words**) as actual first-draft novel prose. The full **16 game encounter descriptions** were reread. **20008 and 20009 are northern Frostwind/Deepstone records**, not artifacts physically located in Eldertree; both are used through Teren's historical survey copies, and their matrix modes changed from Lived to Archive. Chapter 8 preserves the distinct dark Shadowwolf, emerald Guardian, reported Predator and directly seen Thunderfly Matriarch. [Detailed review](CHAPTERS_07_08_REVIEW.md) records the source evidence and limits.

Progress is now **8 draft chapters, 27,832 words including headings, 67 draft-integrated IDs, 136 planned and zero editorially verified**. The earlier 109-scene architecture still covers all 203 records in one primary scene each; only their drafted status and two delivery modes changed.

## Chapter 9 — trade and source attribution, 17 November 2026

[Chapter 9, Where Stories Are Sold](../manuscript/chapters/09-where-stories-are-sold.md), is a **3,882-word** full prose draft incorporating game IDs **20012, 20031, 20059, 20060, 20076**. All five full descriptions were read from the latest game source; the [source-fidelity register](CHAPTER_09_REVIEW.md) documents which details are directly witnessed and which belong to trade and pilgrim testimony. Pel, Orena and Thalen are novel-only named characters. An ordinary craft-reference from Thalen advances the inquiry without inventing a clue resolution. The latest game diff added one prose revision to 20084 Mystical Vale, reconciled into Chapter 4's carved **K** scene.

**Current coverage:** **9 drafted chapters, 31,741 words including headings, 72 drafted IDs, 131 planned, 0 independently editorial-verified**.

## Chapter 10 — refuge and protected passage, 17 November 2026

ChatGPT (**GPT-6**) wrote [The Shelter Beyond the Veil](../manuscript/chapters/10-the-shelter-beyond-the-veil.md) (**5,073 words, first-draft prose**) under the existing delegated novel-writing direction. The chapter integrates six full game source descriptions: **20187, 20189, 20190, 20191, 20188 and 19444**, preserving the **20188 → 19444** linked threshold-to-chamber order. Aru the Rokur pilgrim and Tessan the Aevis courier are invented novel identities, and the local fitting used to open the barrier is a **fictional chapter-specific solution**, not a universal magic law. [Source fidelity and unresolved limitations](CHAPTER_10_REVIEW.md) are documented separately.

The latest game source changed only **20085 Bucolic Dale** prose, adding a small animal climbing the **J** stone and jumping away through scattered petals; Chapter 4 was updated to follow that detail. The original letter **J** and overall **A H K J O M A** clue remain intact.

**Current source-to-prose status:** **203 unique source IDs, 78 drafted, 125 planned, none editorially independently verified**. **10 full first-draft chapters, 36,849 words including headings**. No audio or game/world-canon files were changed.

## Chapter 11 — civic collaboration and an incomplete archival lead (17 November 2026)

ChatGPT (**GPT-6**) wrote [The City of Listening](../manuscript/chapters/11-the-city-of-listening.md) as **5,195 words** of clean first-draft novel prose. The five complete source encounter descriptions **20062, 20181–20184** were read from the same unchanged game snapshot (`ad34afb686ef`) and integrated as separate **direct visits** to Aetherion's Market, Archive, Forge, Concert and Garden. [Chapter 11 source review](CHAPTER_11_REVIEW.md) documents each source feature, world boundaries and invented fiction.

Original literary development: **Velen**, the Aevis cataloguer, finds a damaged, source-compatible **two-compartment restoration drawing** and prepares a measured copy with attribution; a Rokur forge illustrates acoustic coupling but proves no specific memorial solution; a concert holds distinct voices together; the Garden's faltering rhythm is **not declared** to share the Skyland wall's cause. Velen's travel leave is only **requested**, not yet approved. No game record, world-canon article or narrator track was changed.

**Coverage now:** **203 unique source encounters; 83 in first-draft prose; 120 planned; 0 independently editorial-verified. Manuscript: 11 chapters / 42,044 words including headings.**

## Chapter 12 — Nereval's guarded waters and Sira's choice, 17 November 2026

ChatGPT (**GPT-6**) authored [Where Water Is Guarded](../manuscript/chapters/12-where-water-is-guarded.md), a **5,493-word** completed literary **first draft** under Babuni's delegated creative direction. The four source encounters **20064, 20192, 19001, 20193** were read in full from unchanged game source `ad34afb686ef`, including **20192 → 19001** follow-sequence verification. The [Chapter 12 source review](CHAPTER_12_REVIEW.md) separates Sira's attributed account of Umbrael's Evergrove altar from the actually witnessed Nereval gateway, restored small water channel, opened seal and riverkeeper's humor.

Velen receives the **previously pending temporary archive travel leave** in the chapter's opening, as novel-only administration. The group's route moves from Aetherion through the southeastern Vale to the mapped oasis roads of **desert Evergrove**. Novel-only Riverkeeper **Iren** passes on a messenger's incomplete report of a raided oasis-village, which prompts Sira to lead the next leg toward survivors. The recovered **memorial drawing remains incomplete**; no source magic rule or world canon was changed.

**Current:** 203 unique source IDs; **87 drafted**, **116 planned**, none independently editorial-verified. Manuscript: **12 first-draft chapters / 47,537 words including headings**. No audio produced.

## Chapter 13 — recovery, testimony and village agency (17 November 2026)

ChatGPT (**GPT-6**) wrote [After the Raid](../manuscript/chapters/13-after-the-raid.md), **5,482 first-draft manuscript words**, from ten fully reread game encounters at unchanged `ad34afb686ef`. **20125**, **20053** and **20058** are staged as **directly witnessed** scenes in the cultivated Evergrove oasis. The other **seven IDs (20013, 20014, 20016, 20017, 20054, 20126, 20127)** arrive as distinct witness testimony or attributed written account. The source-confirmed **Ogru and Gobbl raid** is presented without declaring all other suffering part of one attack or magical corruption.

[Detailed Chapter 13 review](CHAPTER_13_REVIEW.md) records character and geography constraints: **Alen, Renn and Tavi are original fiction**, **three of four feeder channels are recovered**, a replacement pipe still has to be obtained, Sira stays with the community as Brunti and Velen leave briefly for supplies, and a previously displaced child with a carved stick has **unverified current whereabouts**, not a proved Keldor destination. The Eternal Twilight Grove is a **separate haunted forest**, never turned into an Evergrove feature.

**Coverage:** **203 unique encounter IDs, 97 in full first-draft prose, 106 assigned but unwritten, 0 independently editorial-verified**. **13 drafted chapters / 53,019 words including headings / 52,942 prose words excluding headings**. No recorded audio or modifications to Morkahja source repositories.

## Chapter 14 — desert routes, four direct encounters and earlier-source reconciliation (17 November 2026)

Under Babuni's existing literary direction, ChatGPT (**GPT-6**) wrote the complete [Chapter 14 — Words in the Sand](../manuscript/chapters/14-words-in-the-sand.md) as a **4,828-word novel first draft**. Source IDs **20101, 20035, 20066 and 20063** are each directly experienced on separate Ohgar desert journey beats, not just listed in prose. [Chapter-specific review](CHAPTER_14_REVIEW.md) records checked details, canonical physiology, invented characters and unresolved source constraints.

The previous chapter's party split is resolved by Brunti and Velen **rejoining Sira in the Evergrove oasis**, helping the fourth water feeder operate under village supervision, then taking **ordinary mapped multi-day caravans** through Ohgar. The monolith's treasure remains a rumor; the Skorpo is avoided without forced combat; young Grimnir **Nera** receives shade, mineral-rich water and a station for recovery rather than an instant cure; the ruined temple's disc remains **partly unreadable**. Brunti sends Darrik a **source-limited letter** with no verified delivery and no new proof of a memorial repair. The group later continues by guided roads toward Karrhu.

A full source diff between game `ad34afb686ef` and `e826fa46d3ff` found **eight `mEncounterText`-only edits** (20086–20093) and unchanged 203 IDs/metadata/follow links. Five Chapter 4 source passages and three Chapter 5 Nagar reports were rephrased to reflect the descriptions. Their updated counts are **3,895 and 3,900 words**; seven carved letters remain **A H K J O M A**. [Diff record](SOURCE_RECONCILIATION.md).

**Current draft coverage:** **203 unique encounter IDs**, **101 adapted**, **102 still planned**, **0 independently editorial-verified**. Novel manuscript **14 first-draft chapters / 58,041 words including headings / 57,958 prose-only**. No audio publication or game/world changes.
