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

## Chapter 15 — five lived Karrhu scenes, one attributed central-land song (17 November 2026)

ChatGPT (**GPT-6**) authored [Beneath the Reeds](../manuscript/chapters/15-beneath-the-reeds.md) as **4,914 words of actual first-draft novel prose** under Babuni's delegated literary direction. The game source [`92b97aef8706`](https://github.com/babunidev/Morkahja/blob/92b97aef8706dabfcd8d8d80c0477a70e3336097/server/game/encountersdata.json) was read for **all six assigned encounters** (20037, 20038, 20057, 20077, 20082, 20116). Five are **Lived**; the Alluring Fens are **Testimony** from a person passing through **central lands**, rather than relocated into Karrhu. [Source scene review](CHAPTER_15_REVIEW.md).

Direct action includes the Inferno Duck's fire, Aradia's still dangerous venom, **Leta's** hunger and reunion with her aunt by a supported crossing, a living red-eyed huge fly inside Flytrap Grotto and a locally approved hazard notice, and the unclaimed mystery of the Quicksilver pool. The company uses actual causeways and ferry stages. At chapter end a courier delivers **separate** packets to Velen and Sira, but **Sira remains physically with the trio**. Novel-only ferryman/keeper/guide and the child's family are not game-canon additions.

The game source moved from `e826fa46d3ff` to `92b97aef8706` with **exactly five `mEncounterText` updates (20094–20098)**, all reconciled in old first-draft Chapters 5 and 7 without new source IDs or follow-link changes. Their new lengths: Chapter 5 **4,044 words**, Chapter 7 **3,554**. [Source reconciliation](SOURCE_RECONCILIATION.md).

**Current project:** **203 distinct assigned encounter IDs, 107 adapted as first-draft prose, 96 planned, 0 independently editorial-verified**, manuscript **15 chapters / 63,149 words including headings / 63,061 prose-only**. No audio, releases or changes to the game or world source files.

## Chapter 16 — corrupted forms kept separate by original witness (17 November 2026)

ChatGPT (**GPT-6**) wrote [Chapter 16 — Witnesses of Corruption](../manuscript/chapters/16-witnesses-of-corruption.md), **4,951 words of first-draft novel prose**, under Babuni's existing creative delegation. All **twelve assigned game descriptions 20019–20030** were read at `525d26bc8b4d`, where none of these twelve had changed. They appear as **twelve attributed Archive records**, not physical journeys or a new series of attacks: three **Ashen Revenants (20019, 20020, 20030)**, three **Blightwraiths (20021, 20024, 20029)**, three **Crumblegheists (20022, 20025, 20026)** and three **Tempestwailers (20023, 20027, 20028)**. [Full source and canon review](CHAPTER_16_REVIEW.md) distinguishes observed forms from witness inference and preserves the *Roughian/Berserk* nomenclature tension.

The story uses a roof leak that blurs a copied date to make provenance matter; Velen builds a practical **Seen / Inferred / Unknown** register. The chapter moves Sira's independent duty into actual travel: novel-only courier **Rava** identifies a western registry location, the trio travels together another three days, and Sira leaves by **ordinary western mail caravan** while Brunti/Velen take the northern road. The older displaced child with a carved stick remains of **unconfirmed whereabouts**. This is novel-only connecting fiction, not new game canon.

Game source `525d26bc8b4d` changed only **20099–20103** relative to `92b97aef8706`. **20101 Rocks of Ohgar** was reconciled in Chapter 14 (+25 words; **4,853**); four others are **still planned Chapter 17**. [Source diff](SOURCE_RECONCILIATION.md).

**Coverage now:** 203 distinct encounter IDs; **119 actual first-draft integrations, 84 planned, none independently editorial-verified**. Manuscript **16 chapters / 68,125 words including headings / 68,032 prose-only**. No audio production or game/world changes.

## Chapter 17 — different voices of mountain stone (17 November 2026)

ChatGPT (**GPT-6**) drafted [Chapter 17 — The Mountain Has a Voice](../manuscript/chapters/17-the-mountain-has-a-voice.md), **4,639 first-draft words**, using all eleven assigned game descriptions 20061, 20099, 20100, 20102, 20103, 20105, 20106, 20109 and 20120–20122. All eleven remain **Lived** scenes; the chapter does not claim a discovered treasure, a speaking mountain, an awakened stone giant, a moving golem, or an identified link to Brunti's memorial. Sarga appears on an earlier separate travel leg. **Sira is absent physically**, honoring her Chapter 16 departure, and Brunti/Velen continue by ordinary roads with local guides. The Grimnir junkyard's paired fitting is only a possible resemblance; practical cold-weather supplies are purchased instead.

The newer game [`92cd8dc140c5`](https://github.com/babunidev/Morkahja/blob/92cd8dc140c5a73fce11f8ad3b5d87a488b3fd7b/server/game/encountersdata.json) changes **four descriptions, 20104–20107**, relative to the Chapter 16 baseline. Revisions to **20105 The Giant** and **20106 Sarga Lioness** inform this manuscript; **20104 Sudden Rockslide** and **20107 Silver Wolf** remain scheduled for Chapters 18 and 21. [Chapter 17 review](CHAPTER_17_REVIEW.md) records the full textual correspondence and map/chronology limits.

**Current coverage:** **203** unique assigned source IDs; **130** integrated into actual first-draft prose, **73** planned, **0** independent human editorial approvals. Manuscript **17 chapters / 72,764 words including headings / 72,664 prose-only**; no audio or source-game/world modifications.

## Chapter 18 — the measure of a warm meal (17 November 2026)

In the next part of my audiobook novel, the northern road's dangers are not a pretext for combat: a real Frostwind **rockslide (20104)** removes the trail and obliges Brunti, Velen and guide Hesk to take a lower route. At the southern **Everwinter Trading Post (20123)** a young flame-bodied Rokur woman, named **Aksa** only for this novel, makes room for travelers even as fresh supplies diminish. The **Frostfang Alpha (20124)** stays in attributed courier **Testimony**, its white body and sapphire eyes reported by the keeper; Brunti does not meet it. Friendly ice troll **Frostbite Fergus (20132)** joins the living day with hunger, laughter, a pine log and unforced company. The **Frostclaw Behemoth (20176)** becomes a distinct direct confrontation-without-fighting; orange-eyed white bear and dangerous claws compel the travelers to withdraw.

ChatGPT (**GPT-6**) drafted [Chapter 18 — The Last Warm Bowl](../manuscript/chapters/18-the-last-warm-bowl.md), **5,110 words** including heading, after rereading its five full game descriptions and relevant Everwinter, Rokur and Grimnir world records. Aksa's measured kitchen, the hungry courier, rockfall patrol warning and shared final stew are **novel-only connecting fiction** that gives the chapter a lived dramatic turn rather than a sequence of quest rewards. The keeper's accounts of **Everwinter Guardian → Everwinter Cave (20130 → 20131)** establish Chapter 19's actual linked sequence without asserting a supernatural shortcut.

The latest [game baseline `e8fbfc67cbb4`](https://github.com/babunidev/Morkahja/blob/e8fbfc67cbb487df4652b055f21afbc086676ff0/server/game/encountersdata.json) changes only the descriptions of **20108 Shena Alpha** (still planned Chapter 21) and **20109 Embersnout** (reconciled within [Chapter 17](../manuscript/chapters/17-the-mountain-has-a-voice.md), now **4,683 words**). Full verification and limits: [Chapter 18 review](CHAPTER_18_REVIEW.md) and [source reconciliation](SOURCE_RECONCILIATION.md).

**Current total:** **18 first-draft chapters / 77,918 words including headings / 135 of 203 source encounters adapted / 68 planned / 0 independently editorially verified**. Neither the game nor established world repository was changed; no audio master, rights approval or publication exists.

## Chapter 19 — what ice preserves and what records omit (17 November 2026)

Under my audiobook's current story direction, the frozen valley preserves astonishing traces without giving Brunti a universal answer about the Skyland memorial. ChatGPT (**GPT-6**) wrote [Chapter 19 — Ice That Remembers](../manuscript/chapters/19-ice-that-remembers.md) as **4,533 words** of first-draft prose, after reading the seven full game sources and accessible Everwinter world entries. **20129** is a warm yet ice-crusted chest left closed. The required linked order **20130 Guardian → 20131 Cave** is maintained: a watchful small ice troll and unexplained opening movement precede preserved ancient fossils, natural ice forms, and partly unreadable luminous script. **20136 Lost Souls** are living stranded travelers reached through a blizzard and helped by safe-route marking. **20135 Frostlace** and **20140 Misthowl** remain **attributed testimonies**, with unproven causes and no automatic prophecy. **20141 Winterwisp Warden** is physically encountered guarding the Queen's upper way, and the travelers retreat without a fight.

Original fiction includes Aevis guide **Enna**, a winter cord route, an ordinary patrol shelter, distinct rescued travelers and a tentative postal direction toward **Jorvald**. These are not new Morkahja world-canon roads, relationships or ritual instructions. Brunti and Velen remain together; Sira is absent as established in Chapter 16. The cave's partly hidden script is left uninterpreted; the preserved animals are not given guessed species or invented memories. The next chapter's Jorvald inquiry follows incomplete evidence rather than a magically unlocked answer.

The latest game revision [`fe29096e90ad`](https://github.com/babunidev/Morkahja/blob/fe29096e90ad2f524271a91ceb9cff318ac6b8b0/server/game/encountersdata.json) changes exactly eight prose descriptions **20110–20117**, and none of the Chapter 19 seven. The six previously drafted descriptions were reconciled in Chapters 5 (+73 words), 8 (+61), and 15 (+21). The revised **20112/20113** remain **planned** for Chapter 21. Full [Chapter 19 review](CHAPTER_19_REVIEW.md) and [twelfth source reconciliation](SOURCE_RECONCILIATION.md).

**Current ledger:** **19 chapters / 82,606 words including headings / 142 of 203 distinct encounter IDs adapted / 61 planned / 0 independently editorially verified**. No game/world code changes, audio production or release.

## Chapter 20 — where the unbroken answer cannot be found (17 November 2026)

In the last chapter of the northern movement, my working novel reaches the point where continued searching can no longer be mistaken for good stewardship. ChatGPT (**GPT-6**) drafted [Chapter 20 — The Broken Frostweaver Record](../manuscript/chapters/20-the-broken-frostweaver-record.md), **6,137 words**, from nine full current game descriptions. The cries of **Kaldric (20133)**, the vanishing melody of **Lyria (20139)** and the divided **Seer (20137)** are three separately *Lived* encounters, their original relationships and causes deliberately unresolved. The **Seal of Nekalos (20134)** is a layered, sensory inscription; **Frostfall Cascade (20142)** offers a glint in steep ice; the **Frostforged Vault (20143)** remains sealed. Their mysteries are not combined into one key. A distinct journey brings **Skyreach Peak (20138)** into view without an ascent, followed by the wounded **Spirit Stag (20145)**. Brunti chooses a windbreak and access to a qualified local caretaker over an attempt to gain a rumored relic or divine reward. The **scholar Jorvald (20144)** challenges the visitors' intentions among scattered texts and refuses to call their guessed reconstruction a witnessed history.

The ending belongs to Brunti's *novel-only* memorial dilemma. Jorvald cannot give a safe Frostweaver fix for the Grimnir wall, so she accepts Darrik's planned transfer intact and sends a letter with her checked information. After enough winter-route and relay travel, a separate ordinary message from **Sira** describes an *unverified* possible missing Verdani child near the Keldor border. Her lead is human and specific, not a prophecy or proof the child has been found. Sira remains physically separate until the later story movement. Site route, caretaker response, dialogue and private messages are original connecting fiction. No world-canon mechanism is resolved.

The full game-data check at [`4c7fcc7901f8`](https://github.com/babunidev/Morkahja/blob/4c7fcc7901f87f2b1fbf274e0cd46af49642b90f/server/game/encountersdata.json) found **two text-only changes, 20118/20119**. **20119** was reconciled in [Chapter 7](../manuscript/chapters/07-things-that-are-kept.md) (+47 words); **20118** remains assigned to future Chapter 22. All nine Chapter 20 texts were unchanged. Detailed [Chapter 20 review](CHAPTER_20_REVIEW.md), [thirteenth source reconciliation](SOURCE_RECONCILIATION.md). **Current: 20 first-draft chapters, 88,790 words including headings, 151 of 203 IDs adapted, 52 planned, no independent editorial approval**.

## Chapter 21 — before the cursed trees (17 November 2026)

In my novel's fourth movement, the journey turns from the Skyland's safe memorial repair toward a child who may still be somewhere along Keldor's outer paths. ChatGPT (**GPT-6**) wrote [Chapter 21 — Before the Cursed Trees](../manuscript/chapters/21-before-the-cursed-trees.md), **4,567 first-draft words**, after checking the five assigned game encounters and source lore for the Vale, Keldor, wolves, Liani, Darkwood Thicket and Verdani.

Brunti and **Velen** leave Enna at the winter patrol junction and travel by ordinary wagons and roads across the Vale. Their reunion with **Sira** is at an active relief station, after enough time has passed for the letter and subsequent journey. Sira's own displaced-family work matters independently of Brunti's presence. The witnesses provide an uncertain sighting of a **young Verdani carrying an adult-sized walking stick**; the child is not named or declared located, and even an inconclusive print is recorded only as a possible footprint. A two-day, **bounded** outer-road investigation is selected instead of an unplanned invasion of Blackwood.

The distinct direct scenes are **20107 Silver Wolf**, **20108 Shena Alpha**, **20044 Darkwood Thicket**, and **20112 Cursed Silvermane**. **20113 Cursed Liani** is **Sira's attributed written testimony from a named witness**. Neither the ordinary silver wolf nor the Shena Alpha guides the party to the missing child; the old fae banishment remains hearsay; the afflicted Silvermane is not defeated or healed; the cursed Liani's unintelligible murmurs never become an oracle. The earlier already-reviewed expansions to 20107/20108/20112/20113 were incorporated in actual draft prose for the first time. The different wolves' identities and curse origins remain unresolved as established in the MorkahjaWorld archive.

The latest game comparison `4c7fcc7901f8` → `2b4afe761c8b` found four new **text-only revisions 20120–20123**, not new Chapter 21 entries. **20120–20122 were reconciled in Chapter 17 (+136 words)**, **20123 in Chapter 18 (+45)**. Source detail and fictional routes are separated in [Chapter 21 review](CHAPTER_21_REVIEW.md) and [fourteenth source reconciliation](SOURCE_RECONCILIATION.md). **Current manuscript: 21 / 30 draft chapters, 93,538 words incl. headings, 156 of 203 encounters adapted, 47 planned, 0 independently editorially approved.**
