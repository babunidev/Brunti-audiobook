# Brunti — manuscript revision change and verification log

**Status: editorial change-control ledger.** The audit identifies narrative issues; the [revision plan](MANUSCRIPT_REVISION_PLAN.md) orders the work; this file records **actual** proposals, modifications, checks and remaining gates. Prepared by ChatGPT (GPT-6) under Babuni's creative direction. No source-game/world-canon updates are implied.

| Issue | Planned editorial concern | Status | Verification / reference |
| --- | --- | --- | --- |
| R1 | Tavra/Korrum early name leak (Ch25–28 vs Ch29) | **Draft repaired; targeted check passed; human approval pending** | [Stage 1 review](REVISION_STAGE_1_REVIEW.md) |
| R2 | Convergence access vs premature repair (Ch1–2/29–30) | **Draft repaired; targeted check passed; human approval pending** | [Stage 1 review](REVISION_STAGE_1_REVIEW.md) |
| R3 | Darrik letter provenance | **Draft repaired; targeted check passed; human approval pending** | [Stage 1 review](REVISION_STAGE_1_REVIEW.md) |
| R4 | Nemi's Earthsinger keepsake | **Draft repaired; targeted check passed; human approval pending** | [Stage 1 review](REVISION_STAGE_1_REVIEW.md) |
| R5 | Global travel/calendar anchors | **Draft revised; targeted internal check passed; independent review pending** | [Stage 2 review](REVISION_STAGE_2_REVIEW.md) |
| R6 | Durable flaw despite Chapter 20 growth | **Draft revised; targeted internal check passed; independent review pending** | [Stage 2 review](REVISION_STAGE_2_REVIEW.md) |
| R7 | Concrete cost of Chapter 24 Blackwood choice | **Draft revised; targeted internal check passed; independent review pending** | [Stage 2 review](REVISION_STAGE_2_REVIEW.md) |
| R8 | Ordinary recovery chain from Blackwood | **Draft revised; targeted internal check passed; independent review pending** | [Stage 2 review](REVISION_STAGE_2_REVIEW.md) |
| R9 | Visible warrior/protector identity | **Draft revised; targeted internal check passed; independent review pending** | [Stage 2 review](REVISION_STAGE_2_REVIEW.md) |
| R10 | Anonymous individuality of memorial owners | **Draft revised; targeted internal check passed; human acceptance pending** | [Stage 4 review](REVISION_STAGE_4_REVIEW.md) |
| R11 | Secondary rescue, relationships, keepsake payoff | **Draft revised; targeted internal check passed; human acceptance pending** | [Stage 4 review](REVISION_STAGE_4_REVIEW.md) |
| R12 | Sira/Velen/Darrik relationship consequences | **Draft revised; targeted internal check passed; human acceptance pending** | [Stage 4 review](REVISION_STAGE_4_REVIEW.md) |
| R13 | Late Atranor interlude pacing | **Draft revised; targeted internal check passed; human acceptance pending** | [Stage 4 review](REVISION_STAGE_4_REVIEW.md) |

## Stage history

### 2026-11-18 — Stage 0: repository baseline and dependencies

**Human creative direction:** proceed to the next staged manuscript-revision task. **AI work:** ChatGPT (GPT-6) read the audiobook repository rules, documentation, source/prose index, source matrix and relevant chapter files, then assembled three prose-backed editorial records:

- [30 chapter-file inventory and matrix check](REVISION_STAGE_0_BASELINE.md), starting `main` commit `0916221b5940d1a48229c4dc216207bd523202e0`.
- [Chronology, travel, cast movement, letters, evidence and object custody](../story/REVISION_CHRONOLOGY_AND_OBJECTS.md).
- [30 chapter narrative functions and repetitive-scene risks](../story/REVISION_CHAPTER_FUNCTIONS.md).

**Verification:** 30 chapter-file blob IDs examined, 30 chapter index entries, 203 matrix rows with 203 distinct IDs and 203 Draft v1 statuses. Whitespace-token audit computed 145,703; historical index states 145,383 words under a different unspecified counting convention. A source comparison of game `main` vs the recorded encounter baseline identified 10 newer commits and one modified encounter JSON file, **not yet content-reconciled**. No manuscript patches, new creative lore, audio render or external review were performed.

**Gate:** Stage 0 documentation/structural verification complete; substantive R1–R13 repairs remain open. The baseline does not mean complete paragraph-level reading or source fidelity verification, which remain Stage 5.

### 2026-11-18 — Stage 1: hard continuity repairs committed

**Human direction:** proceed to the next documented revision stage under the existing delegated literary-drafting direction. **AI work:** ChatGPT (**GPT-6**) edited prose in **Chapter 20 and Chapters 25–30** to address R1–R4, then cross-checked the changed passages and [recorded evidence](REVISION_STAGE_1_REVIEW.md). Primary commits include Ch20 `b4e63976` (Darrik measures), Ch25–28 corrections culminating `47397d66`, Ch29 `813b9847` (convergence access and repair), Ch30 `6da2d1d5` (Nemi's gift and convergence reference), and Ch27 follow-up `96b61387`. Chapter-index recount finalized at `d60f4dd1` before documentary updates.

**Verified scope:** GitHub comparison from Stage 0 documentation commit `5ee0a87` to Stage 1 prose: **seven chapter files plus chapter index**; no changed game/world source files or 203-ID matrix. Literal Tavra/Korrum names no longer appear in Chapters 1–28; Chapter 29's revealed inscriptions are the first identifications. The original Ch1–2 convergence access rule now matches the Ch29 permanent repair; Ch27 and Ch30 references were reconciled. Brunti has Darrik's measurements in Ch20 (as packed in Ch2), and Nemi receives the dark Earthsinger pebble in Ch30. The count across 30 chapters is **145,584** by a specified Unicode-letter-or-number whitespace-token rule; historical 145,383 is a different original convention.

**Limits:** These four are **internally checked, revised first-draft passages**, not independently approved final prose. Stage 2's full calendar/character causality, Stage 3's pacing, Stage 4's emotional breadth and Stage 5's whole-book/source/canon/line verification remain open. The newer game encounter JSON revisions still need comparison.

### 2026-11-18 — Stage 2: chronology, Blackwood causality and protection

**Human direction:** advance to the next revision stage under existing delegated literary-drafting authorization. **AI work:** ChatGPT (**GPT-6**) made targeted prose edits to **13 chapters** (Ch1, 2, 11, 13, 14, 16, 20, 21, 23, 24, 27, 28, 29), with review evidence in [Stage 2 report](REVISION_STAGE_2_REVIEW.md).

**Selected novel-only draft direction:** convergence anticipated about **six months** after departure, with cross-chapter month markers (around month 2 Ch14, over 2 Ch16, four elapsed Ch20, a little over one remaining Ch23, a dated approach notice Ch28 and physical arrival Ch29). Brunti's fear of facing her own caretaker with an incomplete record remains despite growth in Chapter 20; Chapter 23 offers a credible homebound wagon and Chapter 24 shows her refusing its held seat. In Chapter 27 outer-route wardens find her unconscious at an old boundary marker, carry her to a ridge post, and transfer her to a lazaret by wagon. The **path out of the Silent Throne remains unknown**. The warden report reaches Elda's shelter by ordinary messenger, explaining how Sira learns that Brunti may be alive. Warrior training is visible through guard stances, beam risk checks, escort positions and litter protection rather than added fights; Chapter 29 reconciles recovery testimony and culpability.

**Verification boundary:** affected passages reread and the revised cross-chapter causal sequence reviewed; source encounter matrix remains 203 unique assignments, manuscript index remains 30 chapters. Updated word counts total **146,505** under the same declared counting convention (+921 from Stage 1's 145,584). Neither a complete atlas travel audit, full 203-source comparison, line-level literary edit nor separate human approval was performed. Stages 3–5 remain open.

### 2026-11-18 — Stage 3: all-travel-chapter pacing revision

**Direction:** advance the next planned literary revision stage. **AI work:** ChatGPT (**GPT-6**) inspected prose openings, endings and selected substantive scene passages across all **30** chapters and scanned the chapter texts for repeated explanatory patterns. It made targeted paragraph/scene-ending revisions to **all 26 travel chapters (Ch3–28)**; **Ch1–2 and 29–30 unchanged** because their opening council accident and closing craft resolution have distinct functions. See [Stage 3 review and 30-chapter function register](REVISION_STAGE_3_REVIEW.md).

**Revision effect:** the repeated “strange sign → speculative memorial connection → no-proof disclaimer → notebook lesson” pattern was reduced. More scenes close on travelers' humor, small animal behavior, working hands, communal relief, mountain survival, children singing, an actual departure, route disorientation and Blackwood sensory consequences. Jorvald's principled refusal and the ordinary safe return remain central decisions, not more sermons. The Atranor testimony, named encounter imagery and the novel's unresolved mythology are retained.

**Checks:** all 30 current chapter counts recalculated under the same published Unicode-letter/number whitespace convention: **145,771 words** (−734 from Stage 2's 146,505); 203/203 unique encounter assignments still in matrix; 30 chapter index rows; seven engraved letters `A H K J O M A`; Blackwood 8-ID and three smaller follow chains unchanged in assignment. R1–R9's targeted continuity links remain intact.

**Explicit limits:** **no uninterrupted line-by-line read** of the full 145,771-word novel, **no 203-source-by-source fidelity audit or 109 scene-brief full tagging**, no independent editorial sign-off and no completed audio. These are **provisional, targeted narrative edits** under delegated writing authority, not final acceptance. Stage 4 emotional pass and Stage 5 exhaustive close-read/source/canon checks are open.

### 2026-11-18 — Stage 4: memorial individuality, relationships and grief

**Direction:** continue to the next approved workflow stage under existing delegated creative-draft authority. **AI work:** ChatGPT (**GPT-6**) changed **seven chapter files—Ch1, 2, 11, 23, 28, 29 and 30**—and documented evidence in [Stage 4 review](REVISION_STAGE_4_REVIEW.md).

**R10:** Unnamed contrasting craft marks are now visible in Chapter 1, copied by Darrik in Chapter 2 and analogous to unequal fixing marks in Chapter 11's incomplete Aetherion diagram. **Tavra and Korrum remain first physically named only in Chapter 29**; ordinary recorded acts distinguish correcting a family's name from widening a lived-in landing. No fresh testimony from memory echoes, prophecy or world-canon changes.

**R11:** The Keldor girl asks whether she will be woken if relatives arrive. Chapter 23 now correctly prepares the sealed family letter **before** next-morning dispatch, while Chapter 28 confirms continued supervised relay care and a delivered family address but **does not claim a reunion**. Nemi's on-page pebble delivery in Chapter 30 now acknowledges the long absence without making the stone magical.

**R12–R13:** Sira retains justified anger, asks Brunti for her own account after the safe repair, and continues independent relief work; Brunti sends that letter in Chapter 30. Velen keeps inscription evidence separate from Brunti's unverified private Blackwood testimony and requests a teller's permission to attribute oral recollections. Darrik independently designs accessible archive access and protects the occupied chambers. Tarnel's secondhand Atranor story receives a small keepsake/clasp exchange with no changed divine rules.

**Verification performed:** targeted cross-chapter reading; literal owner-name scan across Chapters 1–28 yields **zero** Tavra/Korrum occurrences; seven chapter-file word counts updated with the established convention; **30 chapters and 203 distinct placement-matrix encounter IDs** retained. New draft count **146,659** (+888 relative to Stage 3). **Still open:** uninterrupted full line edit, per-ID comparisons with changed source encounter JSON, lore/atlas/read-aloud review, human editorial acceptance, narrator files and audio.

### 2026-11-18 — Stage 5 started: latest game source, manuscript-boundary and integrity audit

**Human direction:** proceed to Stage 5. **AI contribution:** ChatGPT (**GPT-6**) reopened the current book, its instructions, full encounter source JSON at two revisions, the 203-row matrix, all five scene-brief movement files, relevant pinned MorkahjaWorld lore and the thirty manuscript chapter files in grouped scans. [Stage 5 audit](REVISION_STAGE_5_AUDIT.md) explicitly records which gates are checked and which remain unverified.

**Source delta:** game `main` at `cf7c285a469ce9db44583e034ec7bf45e272bd84` is **37 commits newer** than previously reviewed `952437c5c59da26a2f873f1a18590496f88a2354`. The encounter JSON still has **203 records**, with exactly **33 `mEncounterText`-only edits at IDs 20158–20190**. Titles/other fields and **10 follow edges** are unchanged. Numeric encounter IDs 1/2 are keyed `00001`/`00002` in source. [Detailed source addendum](SOURCE_RECONCILIATION.md#stage-5-source-field-comparison--18-november-2026-current-game-cf7c285).

**Placement:** all 203 unique matrix assignments match the 203 distinct source ID bullets of the 109 scene briefs, including chapters. [Automated passage locators](STAGE_5_ENCOUNTER_LOCATORS.md) provide a *candidate* paragraph for every ID; 24 candidates have weighted similarity below 0.100 and require a semantic check. **Not a 203-passage editorial acceptance.**

**Literal and technical checks:** Ch4's seven letter stones read A H K J O M A in sequence; Blackwood's eight steps and three additional follow pairs retain their chapter order; all 100 Markdown files/1,498 relative links resolve to existing files (not anchors/external sites); all 30 chapter openings and closings inspected in book order; targeted world source comparisons (living Grimnir, Verdani desert, Keldor/Blackwood mystery, Atranor laws) showed no new outright blocking contradiction in the inspected sections. The apparent Ch13/14 time jump was checked against Ch14's actual return-with-pipe explanation and is consistent.

**Actual copyedits:** Ch3's invented **silver-handle vs silver-box/clasp** mismatch was replaced with a consistent treasure-clasp exchange; the same chapter's contradiction **closed notebook → still-open page** was removed; Ch11's doubled touching of a folded drawing through cloth was removed. Ch3 **3,221→3,207**, Ch11 **5,211→5,203**, corpus **146,659→146,637** counted words including 30 headings.

**Final Stage 5 gate remains OPEN:** a continuous all-word edit, current-source semantic verification of all 203 encounters, complete 109-brief dramatic audit, final atlas/canon and spoken rhythm test, independent human approval, narrator prep and audio production have **not** been performed. Do not mark the novel reviewed/published from these checks alone.

### 2026-11-18 — Stage 5 continuation: 54 direct game-source-to-scene checks

**Instruction:** continue the existing Stage 5 audit. **AI work:** ChatGPT (**GPT-6**) reread current source text at `cf7c285a469c` alongside the assigned prose for all **24 low automated paragraph matches**, plus all **33 changed game descriptions**, with **three IDs overlapping**. The [54-ID targeted semantic ledger](REVISION_STAGE_5_SEMANTIC_REVIEW.md) reports source-specific scene evidence and limits; the previously [automated locators](STAGE_5_ENCOUNTER_LOCATORS.md) remain unchanged as original machine output. **149 of 203 unique encounters still require targeted human-like source-to-scene comparison**.

**Genuine source fix:** ID **20018 — Stonefist Ironwill** is a **female** Grimnir warrior, but Orven's recounting in Chapter 2 used male pronouns. Three direct prose anchors were corrected to she/her, without importing a human blood-loss mechanism. Low lexical overlaps for the Zeelai feline (**20065**, actually Ch5 **Mara's testimony**, not the Silvermane) and Skylore Scholar (**20172**, Ch23 **§209 onward**, not the automatically chosen supply list at §44) were false-negative locators, not absent scenes.

**Current game text refinements:** Ch24 now includes the **Skullstone Pass sheltered foothold (20161)** and **Flamecrazed Wanderer's startled cry (20164)**. The Ch10 Veilwalker testimony (**20190**) now depicts its enormous, barely defined form around the tree-crown height, with tendrils feeling through flowers but not trailing on the ground: an explicitly **novel-only** visualization consistent with the creative direction and the source's enormous eyes/uncertain body, **not** a new universal lore rule. Ch24/26/29 also replace a few unnecessary literal stopped/held-breath beats with visible actions, without asserting anything categorically about Grimnir respiration.

**Actual edited chapter files this package:** Ch**2, 10, 24, 26, 29**. Current word-count convention: Ch2 **3,465** (unchanged), Ch10 **5,055→5,063** (+8), Ch24 **5,848→5,869** (+21), Ch26 **5,276→5,279** (+3), Ch29 **6,058→6,061** (+3). Total novel **146,637→146,672** (+35) in **30 chapters**. The source-to-chapter matrix is untouched, all **203 source IDs** retained. The [Stage 5 audit](REVISION_STAGE_5_AUDIT.md), [living plan](MANUSCRIPT_REVISION_PLAN.md) and [current manuscript index](../manuscript/chapters/README.md) reflect the results.

**Status:** specific 54-ID source-hooks **target-reviewed by AI**, but no 203/203 semantic acceptance, uninterrupted full-manuscript reading, exhaustive atlas/canon review, spoken-performance verification, narrator export, independent human approval or audio. **Stage 5 remains open**.

## How to record subsequent work

For each later revision package add **date, issue IDs, proposal vs selected direction, changed chapter paths, exact Git commit, source-lore revision, passages affected, verification performed, unresolved dependencies and editorial approval status**. Stage completion does not alone imply publication readiness. Preserve the story world's unresolved questions; never silently supply an undocumented solution.

## 18 November 2026 — Stage 5 semantic comparison complete; manuscript R12/R13 minor clarity fixes

**Direction/proposal/implementation:** Under Babuni's already delegated literary drafting authority and approved compatibility policy for older lore, ChatGPT (**GPT-6**) directly compared all **26** previously unreviewed current-game descriptions to their actual manuscript paragraphs (Ch**2, 21–25**), completing **203/203 targeted source-scene ID checks** in [continuation F](REVISION_STAGE_5_CONTINUATION_06.md). The 26 source objects are unchanged between `Morkahja` `952437c5c59d` and `2ba61f5a6bc`; no source-game or world-canon edits were proposed or made. **No line-by-line human approval** was obtained.

**Confirmed line-level defects and selected edits:**
- **Chapter 22**, [`25600724774f788e693fc09ba3e2d5f9adb258c9`](https://github.com/babunidev/Brunti-audiobook/commit/25600724774f788e693fc09ba3e2d5f9adb258c9): opening “warning cost them a button” contradicted the actual later return of the button and Sira's money payment. Changed to **“almost cost”**, **4,813 → 4,814 words** (+1). All five Ch22 source placements unchanged.
- **Chapter 25**, [`10748fbe7bfcdaf15230c3de76f10faceaf07a46`](https://github.com/babunidev/Brunti-audiobook/commit/10748fbe7bfcdaf15230c3de76f10faceaf07a46): two consecutive descriptions of Brunti sitting against identical damp root wood repeated the same action. Consolidated into one rest beat and retained wrist pain and distant crack, **5,407 → 5,398 words** (−9). Blackwood's `20050 → 19666 → 19667 → 19668` follow order, missing-time passage ambiguity and unknown guardian condition are unchanged.

**Verification:** After both prose commits, all **30 chapter files refetched** from GitHub. Whitespace-token count (token must contain Unicode letter or number): **37,570 + 52,476 + 56,687 = 146,733 total**. Compared all 26 source records against two game revisions; structural ID ledger verification and Markdown path checks are detailed in [continuation F](REVISION_STAGE_5_CONTINUATION_06.md).

**Remaining blocked acceptance:** Even with **203/203 targeted source hooks checked**, Stage 5 still requires an uninterrupted full-novel line read, 109 scene briefs/functions, comprehensive canon/calendar/atlas/props review, real spoken-performance/audio-listening evaluation, and **separate human final literary approval**. This is draft review, not publication or narration certification.

## 19 November 2026 — route repairs P1–P3, user-directed and committed

**Direction / proposal / selection:** The [map-based 30-chapter audit](REVISION_STAGE_5_MAP_ROUTE_AUDIT.md) found **no confirmed impossible geography**, but named three route-orientation gaps. Babuni then explicitly directed ChatGPT (**GPT-6**) to **“fix those 3.”** This authorized a narrowly scoped literary revision, not a cartographic source amendment or chapter-by-chapter final approval.

**Actually edited and committed:**
- **P1 (Chapter 14→15):** [commit `3f1cf789a7a53b8dd53282c33d5469b97fa2620d`](https://github.com/babunidev/Brunti-audiobook/commit/3f1cf789a7a53b8dd53282c33d5469b97fa2620d) replaces the end-of-Ohgar rain paragraph with a **multi-day caravan journey by southern Ethera's Vale roads**, **eastward to Karrhu**, change to wetter-country wagons, and existing bridge-report detour. **Ch14: 4,863→4,890 (+27)**. Ch15's ferry arrival/boot remains unchanged.
- **P2 (Chapter 16→17):** [commit `7798aa51f526eeca9d16eae25f3e80c718e7a9c4`](https://github.com/babunidev/Brunti-audiobook/commit/7798aa51f526eeca9d16eae25f3e80c718e7a9c4) adds a **Karrhu northern-crossings → outer Vale farm/waystation → northern mountain trade-road** bridge at Ch17's first shelter. **Ch17: 4,797→4,848 (+51)**. The unscaled Sarga trader-map notation, Ressa and subsequent caravan delays are preserved; Sarga's precise location **remains unknown**. Ch16 unaffected.
- **P3 (Chapter 28):** [commit `f97f6b2a41c18c84fecfac924dc01b8224c267a3`](https://github.com/babunidev/Brunti-audiobook/commit/f97f6b2a41c18c84fecfac924dc01b8224c267a3) replaces **“northbound caravan”** with **“caravan ... bound for the upland landing routes”**. **Ch28: 5,928→5,933 (+5)**. Later separate wagon, docking confirmation and Skyland lift unchanged.

**Internal verification:** All 30 manuscript chapter files fetched again after the commits, counted by whitespace tokens with a Unicode letter or digit: **37,570 + 52,554 + 56,692 = 146,816 words**; **net +83**. Verified neighboring entry/exit prose in Chapters 15, 16, 17 and 28–29 in the map audit and manuscript. Detailed [map-audit status addendum](REVISION_STAGE_5_MAP_ROUTE_AUDIT.md#19-november-2026--explicitly-requested-map-route-fixes-implemented). No game/world repository updates, no new source IDs, exact roads, compass-fixed moving Skyland, time-distance measurements or confirmed Sarga coordinate.

**Editorial status:** Three issues implemented and internally checked, **no final human line approval**. **203/203 targeted source-scene comparison** complete but full 109 scene functions, continuous literary, final atlas/chronology, read-aloud and independent acceptance remain OPEN.
