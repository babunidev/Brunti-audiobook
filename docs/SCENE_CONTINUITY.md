# Scene-level continuity register — working audit

**Date:** 17 November 2026. **Status:** source-informed **planning audit**, not a complete world-lore review or editorial sign-off. This register records constraints, the fixes already made in scene briefs, and unresolved proof obligations. It does **not** imply world canon has changed.

## Source baseline

| Purpose | Pinned source | What was checked |
| --- | --- | --- |
| Novel scene input | [Game `e0bc99c51c74`](https://github.com/babunidev/Morkahja/blob/e0bc99c51c74bb088f27a8252082b41c61629cf7/server/game/encountersdata.json) | 203 encounter IDs; five `mEncounterText` updates since `5b0d73e550ca`; IDs, titles, metadata and follow links unchanged |
| Game avatar and original atlas | [Game `58576f063627`](https://github.com/babunidev/Morkahja/tree/58576f063627752f77cdf99514baad875d509114) | Brunti avatar 104, frame 75; initial source inventory |
| Established world | [MorkahjaWorld `f56a7c3d2034`](https://github.com/babunidev/MorkahjaWorld/tree/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48) | Selected Grimnir, Aetherion, Evergrove, Everwinter, Ravage, Keldor, Blackwood, Atranor and Divine Laws records |

[Source reconciliation](SOURCE_RECONCILIATION.md) separately accounts for the original 19 text revisions and the five new ones.

## Confirmed canonical guardrails built into scenes

| Canon subject | Novel-scene implementation | Evidence |
| --- | --- | --- |
| Grimnir have living mineral/metal/crystal bodies; prepared minerals, water, resonance and communal care support them | Chapters 1, 14 and 29 use actual material needs and repairs; no human sweating/bleeding assumptions about Brunti | [Grimnir](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Races/Grimnir.md), [life and care](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Traditions/Grimnir_Life_and_Care.md) |
| Skylands are engineered moving homes; memorial stones hold **echoes** of deceased Grimnir | Chapters 1–2 and 29–30 build a strictly local material problem; stones never issue new prophecies | [Skylands](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Grimnir_Skylands.md) |
| Aevis Celesterra is a **subterranean sky-city**; Brunti's homeland is the Grimnir Skylands | Chapter 9 uses the Celesterra merchant as **testimony**, no direct jump to that city | [Celesterra](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Celesterra.md) |
| Evergrove is a desert heartland with oasis-gardens, root systems, and managed canals | Chapters 12–13 show oasis community and Verdani watercraft rather than a generic forest | [Evergrove](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Evergrove.md) |
| Aetherion holds market, forge, records, concert and Garden of Elements | Chapter 11 has independently different civic spaces; the garden's irregularity is **not** caused by Brunti's stone | [Aetherion](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Aetherion.md) |
| Urcogor Ravage is an older, recurring movement, with no confirmed mastermind | Chapter 13 keeps other survivors' reports separate; chapters 21–24 avoid treating all Gobbl/Ogru individuals as one enemy faction | [Ravage](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/WorldEvents/Urcogor_Ravage.md) |
| Keldor and Blackwood remain deep uncertainties, including the Portal's mechanism | Chapters 24–27 leave the passage and Guardian's yielding uncertain; Brunti's trauma does not prove a cause or a prophecy | [Keldor](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Keldor.md), [Blackwood](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Blackwood_Abyss.md) |
| Death, judgment and reincarnation obey shared divine laws | Chapter 28 uses a tradition/uncertain testimony, no provable first-hand mortal report or automatic resurrection | [Divine Laws](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Pantheon/Divine_Laws.md) |

## Ordered source relationships verified in planning

- **Blackwood:** **20050 → 19666 → 19667 → 19668 → 19669 → 19670 → 19671 → 19672** in chapter scenes 25.1–27.2, uninterrupted by an unrelated source encounter.
- **Hearth:** **20188 → 19444**, together in 10.3, with seal before accessible chamber.
- **Nereval:** **20192 → 19001**, together in 12.2, guardian before sanctuary.
- **Everwinter:** **20130 → 20131**, together in 19.2, guardian before cave.
- **Seven letters:** 20081 **A**, 20083 **H**, 20084 **K**, 20085 **J**, 20086 **O**, 20087 **M**, 20089 **A** in chapter 4 across several days. No decoding into a canonical word.

## Geography, travel and character continuity

| Concern | Current treatment | Remaining editorial test |
| --- | --- | --- |
| Distance from a Skyland to the Vale | Chapter 3 begins after ordinary Skyland trade/descent arrangements | Verify landing or descent site against established geography and Skyland practice; no invented instantaneous transfer |
| Vale letter stones | Chapter 4 covers several travel days and sites | Check each full text for precise location and assess whether a route can plausibly connect them |
| Liani boundary vs Eldertree/Aetherion | Chapter 8 is a detour that returns to the public road | Verify broad map relation without fabricating a continuous straight route |
| Celesterra's distant merchant | Chapter 9 uses **testimony** (20076), not physical displacement | Confirm storyteller access and time of report during prose |
| Evergrove and the southeastern Vale sanctuary | Chapter 12 keeps Nereval's border doorway separate from the Evergrove Umbrael tale | Verify exact position in full game descriptions |
| Ohgar → Karrhu → mountains | Chapters 14–17 include distinct travel intervals; no adjoining-place assertion | Still needs sourced route geography, travel duration and season logic |
| Cliffs of Sarga (20099) | Chapter 17 stages an *earlier separate leg* before Frostwind | **Unresolved:** regional position relative to northbound route; could require a reframe as remembered experience with correct chronology |
| Sira's separated itinerary | Leaves after Karrhu to help displaced people; ordinary communications reunite the company near Keldor | Define intermediate stops and credible exchange of news; do not use unlicensed messaging or convenient teleportation |
| Missing Verdani child | Chapter 13 recalls an earlier displaced group; chapter 23 obtains first-hand confirmation from the child with a walking stick | **Original fiction** linking events 20125 and 20170; cannot be represented as source canon, nor is the stick alone proof |
| Archive drawing at Aetherion | Velen finds a partial sketch of a **local** Grimnir memorial-casing type | Clarify why the specific Skyland's craft records were duplicated there (e.g. trade/convergence filing) and how Darrik verifies them |
| Convergence deadline | A bounded future **craft decision**, not a prophecy or falling-Skyland emergency | Travel duration and exact interval remain unspecified; must allow a multi-region journey |
| Brunti's choice after the rescue | Chapter 23 concludes the living-person duty; 24 begins a separate **unnecessary** Blackwood quest | Show cost of relapse and companions' objections without moralizing or calling the abyss a reward |

## Dramaturgy and audio checks

- Avoid reading ten boar names or twelve corrupted-creature names as an inventory. Chapters 5 and 16 use specific witnesses and differentiated descriptions; final prose still needs drama and cadence.
- A source **“Lived”** entry may be observed without combat, and a **“Testimony”** entry needs a credible speaker/occasion. The matrix forms are planning decisions, not confirmed manuscript integrations.
- Chapters 1 and 29 have **no primary game encounter IDs**; they are necessary original bridge and resolution chapters, not missing coverage.
- Brunti is the dominant close-third viewpoint. A quoted, performed or archived story needs a clear entrance and exit for listeners.
- The Blackwood account can portray a frightening lived sequence while keeping the source's competing interpretations open.
- The outcome of an encounter in game data is not a dictated novel outcome. Any saved character, consumed item, opened door, imagined family relationship or new utterance belongs to fiction and cannot be backported as lore.

## Verification and status

**Programmatic structural verification:** 5 movement files; 30 chapter headings; 109 individually labeled scene briefs; 203 distinct source-ID annotations. Comparison against [placement matrix](../story/PLACEMENT_MATRIX.md) found **0 missing**, **0 extras**, **0 duplicates** and **0 wrong chapter assignments**.

**Manual/source-limited review:** The particular canonical references above and targeted source excerpts were consulted. **Not completed:** final location-by-location geographical route proof; paragraph-by-paragraph comparison of all 203 full encounter descriptions; exact timeline; independent editorial review; drafted chapter prose; narration or audio production. Therefore mark **scene plan drafted**, not **scene plan fully canon-verified**.

## Manuscript progress and season correction — 17 November 2026

**Superseding the earlier “no drafted prose” planning status:** [four chapters](../manuscript/chapters/README.md) now exist as first-draft manuscript prose. The [review register](MANUSCRIPT_REVIEW.md) and [Chapter 3–4 source review](CHAPTERS_03_04_REVIEW.md) document **27** drafted source integrations; **176** remain planned. The plan itself still has **109 scenes** and **203** unique assignments, independent of draft status.

A verified chronological tension between source scenes **20069** (warm summer butterflies) and **20072** (autumn, fox under falling ochre leaves) is solved by delivery-mode adjustment, not by claiming geography shifts the season: 20072 is **Eda's past-tense testimony** in Chapter 3, while Brunti travels through summer meadows. This is an explicit departure from the original “Lived” proposal and has been changed in the matrix and scene plan.

The Skyland-to-Vale descent uses documented trade-descent practice, but its precise landing location is original literary connective fiction. The seven distinct marked stones have no verified canonical route or decoded message. Chapter 4 keeps them separate over multiple travel days, with their sequence and uncertainty intact.

## Drafted wildlife and Eldertree scenes — 17 November 2026

**Current manuscript:** [six first drafts](../manuscript/chapters/README.md) with **51** planned source IDs integrated into prose; **152** remain planned. Chapters 5 and 6 have [dedicated source-fidelity notes](CHAPTERS_05_06_REVIEW.md); none has received independent human line editing.

**Species/identity cautions:** The source distinguishes Bloodfang, Goldhorn, Nagar Charger, Elder, Berserk, Boar, Bonecrusher, Humpback, Razorback, Thunderhoof, Zeelai, Silvermane, Yowler, Mother Wolf and Redeye. The chapter's field tracker is original novel fiction. Mother Wolf **20110** is **not proven** to be mother of the Redeye **20111**; the draft keeps the pup a separate sighting. The other Nagar are not turned into one hostile army or a chain of obligatory fights.

**Unresolved Aevis crest:** Game `20007` calls the crest royal; world Aevis governance centers Resonance Councils. Chapter 6 keeps the engraved crest but reports the royal association as uncertain merchant language—no new Aevis crown is canonized. Game `20040` describes “dworv tools,” while established world notes older terminology as unresolved; the draft depicts toolmarks without asserting an otherwise invented dworv civilization. The rumored Enchanted Hollow remains separate from the visited Sylvan Sanctuary.

**New game revision:** `096c99bdf5ac` changed only the prose of 20082 and 20083. Chapter 4's letter **H** and newly added fading note were reconciled; 20082 remains pending in Chapter 15. [Reconciliation](SOURCE_RECONCILIATION.md) records exact old/new revision IDs.

## Chapters 7–8 manuscript additions — 17 November 2026

With [Chapters 7–8 drafted](../manuscript/chapters/README.md), the current manuscript status is **8 chapters, 67 source IDs integrated in draft prose, 136 planned, 0 independently editorial-verified**. The full [source and lore review](CHAPTERS_07_08_REVIEW.md) identifies two specific, material boundaries: northern source encounters **20008/20009** had been mistakenly placed as physical Eldertree finds in the working beat plan, so the prose uses attributed northern survey drawings and the matrix mode is corrected to **Archive**. The **Liani Guardian 20114**, **Shadowwolf 20036** and **Predator 20115** remain separate beings and the **Thunderfly 20117** is witnessed in its distinct dusk setting. No new Liani access rule or world-canon royal/geographic relationship was invented. The ordinary road and Celesterra merchant hearsay lead onward to Chapter 9.
