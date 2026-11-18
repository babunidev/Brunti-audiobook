# Stage 5 — manuscript verification audit, first evidence pass

**18 November 2026 | Status: IN PROGRESS, NOT editorially accepted.**

**Latest continuation, same date:** [Semantic A](REVISION_STAGE_5_SEMANTIC_REVIEW.md) inspected **54 distinct encounters**, [continuation B](REVISION_STAGE_5_CONTINUATION_02.md) added **20**, [continuation C](REVISION_STAGE_5_CONTINUATION_03.md) added **34**, and [continuation D, Chapters 9–14](REVISION_STAGE_5_CONTINUATION_04.md) added **21** while rechecking 13 prior IDs. **129/203 unique encounters** now have targeted scene-hook reviews and **74** remain individually unchecked. The current game source is `2ba61f5a6bc`, 37 text-only changes against baseline `952437c5c59d`. After one Ch14 wording edit the **30 complete chapters were recounted at 146,741 words**. Historical figures below reflect earlier audit moments and remain reproducible. The **full 203-source, consecutive literary/canon/atlas, human read-aloud and independent editorial acceptance gates remain OPEN**.

**Book revision at start:** audiobook `df0fbe8f370981ec870d8da621435fcda27f8c68` (end of Stage 4), [original revision plan](MANUSCRIPT_REVISION_PLAN.md). **Revised manuscript:** 30 chapters, **146,637 counted words** including chapter headings after the Stage 5 Chapter 3 copyedit. Method: whitespace-separated tokens containing at least one Unicode letter or numeral, as in the [chapter index](../manuscript/chapters/README.md). This is **−22** counted words from 146,659 at Stage 4. Source encounter matrix remains unmodified.

## 1. Source revisions and structural provenance — verified

| Source | Revision actually inspected | Finding |
| --- | --- | --- |
| Game prose, original pinned | [Morkahja `952437c5c59da26a2f873f1a18590496f88a2354`](https://github.com/babunidev/Morkahja/tree/952437c5c59da26a2f873f1a18590496f88a2354) | 203 JSON objects in `server/game/encountersdata.json` |
| Game prose, latest observed `main` | [Morkahja `cf7c285a469ce9db44583e034ec7bf45e272bd84`](https://github.com/babunidev/Morkahja/tree/cf7c285a469ce9db44583e034ec7bf45e272bd84) | **37 commits newer**; 203 JSON objects |
| Game JSON object-to-object diff | Both revisions above, direct parsed-field comparison | **Exactly 33 changed descriptions: IDs 20158–20190, inclusive; ONLY `mEncounterText` changed.** No additions, removals, changed ID/title, solution, difficulty, image, expansion, reward or `mEncounterFollow` fields |
| World authority | [MorkahjaWorld `f56a7c3d2034652e1c5961f0ece9c3ef52b52b48`](https://github.com/babunidev/MorkahjaWorld/tree/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48) | Same commit as book's established world pin, according to branch comparison |
| Novel | [`story/PLACEMENT_MATRIX.md`](../story/PLACEMENT_MATRIX.md) | **203 rows, 203 distinct numeric IDs** |
| Novel scene briefs | [Five movement files](../story/scenes/README.md) parsed by their **actual** `- **ID — Title**` bullets | **203 briefs' ID entries, 203 unique IDs; each matches the matrix chapter.** No missing, extra, duplicate or assigned-to-wrong-chapter ID |
| Game key normalization | Raw JSON `00001` and `00002` | Numeric IDs **1 (Atranor)** and **2 (Level up!)** exist in the source using zero-padded string keys, and correspond to novel Chapters 28 and 30 |

**Novel coverage caveat:** matching the matrix and brief IDs is a **planning cross-reference**, not proof of prose fidelity. [The complete candidate locator register](STAGE_5_ENCOUNTER_LOCATORS.md) adds **203 automated best-match manuscript paragraphs**, with **24 low textual-overlap flags (score below 0.100)** requiring individual review. It deliberately marks every row as **pending semantic editorial judgment**. Lexical similarity is not a substitute for checking each encounter's identity, clue and role; especially IDs **1** and **2**, which were intentionally adapted as **Testimony** and **Metaphor**.

### Current-description delta by assigned novel chapter

| Chapters | Current-text changes (IDs) | Count | Review treatment |
| --- | --- | ---: | --- |
| 3 | 20185 | 1 | Earthsinger's invitation and stone-gift narrative examined |
| 4 | 20186 | 1 | Sira's Verdani dance introduction checked as a lived encounter |
| 10 | 20187–20190 | 4 | Rokur traveler, mystic hearth, Aevis defense and Veilwalker references located |
| 11 | 20181–20184 | 4 | Archive of Echoes, forge, concert and garden checked for characteristic motifs |
| 18 | 20176 | 1 | Frostclaw Behemoth scene remains in its chapter |
| 23 | 20162, 20167–20175, 20177 | 11 | Keldor's scholar, guardians, rescued people, wardens and mystic located in scene plan/prose |
| 24 | 20158–20161, 20163–20166, 20178–20180 | 11 | Keldor hazard path and altered creatures/locked gateway located |
| **Total** | **33 text-only descriptions** | **33** | **No final per-ID literary certification** |

The current descriptions broadly preserve their prior encounter identities and signature observable events in the inspected examples; the novel appears to stage the Earthsinger's invitation, Skyheart's fragile shelter, the Skylore Scholar's lost food and drawing, Keldor's fire-corrupted figures, and Aetherion's conflicting book voices. Because the game has revised **all 33 strings**, final comparison of **each full current passage** to its complete adapted scene remains open. **Do not silently switch the manuscript's previously reviewed prose pin** to the newer revision or imply its scenes were re-edited to match the new wording.

## 2. Explicit follow chains and protected source details — structural check

The current game source includes **10 nonzero `mEncounterFollow` links**. Every link target exists in the 203-ID matrix; mapped chapters respect order:

- Blackwood's eight encounters: **20050 → 19666 → 19667 → 19668 → 19669 → 19670 → 19671 → 19672** in Chapters **25–27**.
- Mystic Hearth / Hearthguard: **20188 → 19444**, Chapter **10**.
- Nereval entry / sanctuary: **20192 → 19001**, Chapter **12**.
- Everwinter follow pair: **20130 → 20131**, Chapter **19**.

Focused manuscript inspections found the original Blackwood portal and root maze in Chapter 25, the Choir / Mire / Procession material in Chapter 26, and the Silent Throne followed by the Verdani healer and ordinary post-abyss care in Chapter 27. A direct paragraph-by-paragraph inspection of [Chapter 4](../manuscript/chapters/04-letters-without-a-word.md) found the seven engraved letters in sequence: **A** (paragraph 6), **H** (44), **K** (62), **J** (80), **O** (94), **M** (110) and **A** (133). Paragraph 137 actually assembles **A H K J O M A**. Brunti offers no established decoding. This check used the chapter prose itself, not only the matrix.

**Special modes:** [Chapter 28](../manuscript/chapters/28-a-story-about-the-end.md) presents Atranor as **Tarnel's inherited secondhand story**, not Brunti's eyewitness experience. [Chapter 30](../manuscript/chapters/30-the-note-that-remains.md) uses game ID 2 as a **change in craft judgment**, not a numerical or game-system level-up.

## 3. World lore and anatomy — targeted canonical comparison

The following **actual pinned world files** were reopened and compared with manuscript details (not merely inferred from earlier chat): [Grimnir race](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Races/Grimnir.md), [Grimnir Life and Care](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Traditions/Grimnir_Life_and_Care.md), [Grimnir Skylands](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Grimnir_Skylands.md), [Verdani](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Races/Verdani.md), [Evergrove](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Evergrove.md), [Aetherion](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Aetherion.md), [Keldor](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Keldor.md), [Keldor Landmarks](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Keldor_Landmarks.md), [Blackwood Abyss](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Blackwood_Abyss.md), [Verdani's Vigil](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Verdanis_Vigil.md), [Atranor](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Atranor.md) and [Divine Laws](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Pantheon/Divine_Laws.md).

- **Grimnir:** living, mineral/metal/crystal-based bodies, repair and mineral food, resonant resting stones, preserved *fixed* memory echoes and engineered drifting Skylands are compatible with observed novel passages. A scan of **all 30 chapters** for explicit human-body physiology terms (blood loss, lungs, sweat, heartbeat, etc.) found no direct unambiguous claim that Brunti has conventional human organs. “For a heartbeat” appears as an ordinary time metaphor, not anatomy. This is a **text-pattern check**, not comprehensive physiology approval.
- **Skyland convergence:** source explicitly mentions temporary bridges of stone and light; the novel's local about-six-month travel estimate is fiction, not a general recurrence law. Permanent memorial opening requires convergence supplies/access.
- **Evergrove:** established **Verdani desert/oasis heartland**, not an evergreen forest. The novel's Karrhu/Evergrove travel remains to be checked against a fully verified atlas.
- **Keldor and Blackwood:** permanent fog, disorientation, uncertain portal access, distorted reflections, Choir, Mire, Procession and throne match the source's unresolved questions. The outer wardens/ridge-post/wagon are **novel-only external transport**, not an asserted explanation of how Brunti exited the impossible underground hall.
- **Atranor:** established **three relevant judges** (Aerisara, Sylvanus and the last-essence deity); resurrection requires at least one god's gift; every soul has an unconditional right to reincarnate and new lives do not retain conscious old memories. The story is **secondhand**, and this targeted lore comparison identified no new divine law. **Destiny does not exist** in Morkahja; do not convert old prophecies or the memorial echoes into factual foresight.

**Boundary:** no claim of complete place-by-place global route verification, every world article, new canon approval or full-proof from selected passages. Original novel-specific memorial biographies, calendar and character histories must remain explicitly **fiction**, not world rules.

## 4. Literary and audio-readability check — provisional

All **30 chapter files were reopened** in grouped scans for passage structure, duplicate neighboring paragraphs, weak source-specific lexical matches, obvious human-anatomy mistakes, and paragraph length. No verbatim consecutive paragraph duplicates were found by this automated check. Most single paragraphs are below 100 whitespace words; Chapter 19 contains one approximately **123-word testimony paragraph** worth a live read-aloud check, but this is not by itself a literary defect.

**Actual manuscript corrections from Stage 5:**

1. [**Chapter 3 — A Road Made of Grass**](../manuscript/chapters/03-a-road-made-of-grass.md) initially let a trader add a *silver handle* while the preceding narration said he had improvised a *silver box and golden clasp*. His following dialogue then denied ever mentioning a handle. The passage now refers consistently to the invented **box, clasp and name**, and the trader asks about the **clasp**. A sequential opening/ending check also found the chapter **closed its notebook and immediately left a page open under a cup**. The contradictory last sentence was removed; the chapter now ends naturally with Brunti **closing the notebook**. Overall chapter change **3,221 → 3,207 counted words** (−14).
2. [**Chapter 11 — The City of Listening**](../manuscript/chapters/11-the-city-of-listening.md) repeated nearly the same gesture on adjacent lines at its ending: feeling a folded drawing through its cloth, then touching the same folded paper through that cloth. The redundant gesture was removed without changing the source sketch, Velen's role or the scene's meaning. Chapter change **5,211 → 5,203 counted words** (−8).

**Book total after these copyedits: 146,637 counted words** (−22 from Stage 4's 146,659). All edits are actual GitHub commits, not only proposals.

**Chapter-transition check performed:** The **first three and final five substantive paragraphs of all thirty chapter files** were viewed in book order. Adjacent chapter handoffs, including Ch16 → Ch17 (Sira's departure), Ch17 → Ch18 (mountain fire/post), Ch20 → Ch21 (southbound return), Ch23 → Ch24 (safe wagon declined), Ch24 → Ch27 (Blackwood escalation), Ch28 → Ch29 (Skyland lift) and Ch29 → Ch30 (court settled), were cross-checked for obvious timing and party breaks. A seeming Ch13 → Ch14 contradiction was **resolved by opening Chapter 14's actual text**: Chapter 13 sends Brunti and Velen *out* for a replacement feeder pipe; Chapter 14 begins after they **return** to the same village to install it. This was **not** an omission or timeline error; no speculative patch was made. The handoff scan is still **less than the required uninterrupted full 30-chapter literary read**.

**Not performed:** an uninterrupted **full 146,637-word human-like literary close-read**, listening to all of it spoken, professional line/copyedit, pronunciation checks, narrator files or finished audio. Paragraph/term scans cannot substitute for those tasks.

### Internal Markdown link-path test — 18 November 2026

A repository-wide GitHub tree listing at `main` identified **100 Markdown files**. Every one was fetched; basic Markdown inline-link targets were extracted; absolute HTTP(S), hash-only and mailto links were excluded; relative `..`/`.` segments and URL escapes were resolved against the tracked tree. **1,498 local link destinations resolved to existing files; no missing local file targets found.** This tests **file existence only**, not whether a heading fragment exists, whether external URLs load, or whether all possible Markdown link syntaxes are captured. No production files were created.

## 5. Current gate status — deliberately not certified

| Stage 5 gate | Evidence so far | Status |
| --- | --- | --- |
| 30 indexed manuscript chapters and standardized word recount | Chapter sources + index, latest total **146,672** | **Checked structurally** |
| 203 game records vs 203 matrix assignments vs 203 scene-brief ID entries | Direct machine parses, all numeric IDs match and chapter assignments agree | **Checked structurally** |
| 33 newer source prose records compared by JSON field | **Only** `mEncounterText` changed at IDs 20158–20190 | **Checked field-by-field** |
| 203 manuscript integration identities/faithfulness | [54 actual current-source and scene hook comparisons](REVISION_STAGE_5_SEMANTIC_REVIEW.md) (24 low-overlap + 33 changed-source − 3 overlap); **149 more IDs outstanding**, no final human approval | **PARTIAL: targeted AI review only, final gate open** |
| Canon physiology, Atranor, Keldor and Skyland boundaries | Pinned lore references and targeted manuscript inspections | **Partial** |
| Full chronology, travel, injury, letters and character positions after Stage 4 | Prior stage ledgers, all 30 chapter openings/endings in order, selected inner passages (not the full continuous text) | **OPEN: not yet complete consecutive read** |
| Read-aloud flow and whole-book dialogue/style consistency | Paragraph lengths and targeted samples | **OPEN: no performed listening test** |
| Local Markdown link-path integrity | Most recent rescan: **all 101 Markdown files**, **1,543 relative link destinations** resolve to existing tracked files; heading fragments/external URL availability not checked | **Path targets checked; remaining checks open** |
| Narrator export integrity | No narrator-ready prose export, chapter-to-track mapping or audio file was generated | **OPEN** |
| Separate human editorial acceptance | No explicit human approval of revised full prose | **OPEN** |

### Remaining editorial action register

1. **E5-01 — Blocking:** independent, consecutive read of all 30 chapter files and a signed chapter-transition ledger for all characters, messages, injuries, props and chronology. A paragraph search is not sufficient.
2. **E5-02 — Blocking:** semantic source-to-scene verification for **all 203** entries at the **current game source**, including the 33 rewritten descriptions; use the locator register to find candidate passages but do not auto-approve them.
3. **E5-03 — Blocking:** complete atlas/geography, lore and read-aloud review, including the special Atranor/Level up! modes, the seven letters and preserved follow chains, with any discovered conflicts recorded instead of silently changing canon.
4. **E5-04 — Blocking final approval:** **separate human editorial acceptance** of a definite frozen manuscript revision. No assistant-generated report may impersonate it.
5. **E5-05 — Subsequent production only:** narrator-ready segmentation, pronunciation and attribution review, rights clearance, voice tests, audio mastering and release after manuscript acceptance.

**Conclusion:** Stage 5 has produced **real new source reconciliation evidence, an automated 203-ID passage-locator aid, targeted lore checks and one manuscript copyedit**, but its **final gate remains unpassed**. Stages 0–4 remain internally revised drafts. **No audiobook has been recorded, approved or published** and no Morkahja/MorkahjaWorld file was changed.

## 6. Continued Stage 5 source and literature pass — 18 November 2026

[Targeted source-to-scene ledger](REVISION_STAGE_5_SEMANTIC_REVIEW.md) records **54 distinct IDs** reviewed against actual game encounter text at `cf7c285`, including all **24 low lexical matches** and all **33 newly changed descriptions** (three overlaps). A low score is not automatically an omission: the Zeelai is actually in Mara's Ch5 testimony, and the Skylore Scholar is in the Ch23 on-page fieldwork after an unrelated supply-list paragraph that the machine matched. Both special IDs **1** and **2** remain purposeful testimony/metaphor.

The semantic review uncovered and corrected the female identity of **Stonefist Ironwill (ID 20018)** in Ch2. Current source's newly exposed **sheltered foothold (20161)** and the Flamecrazed Wanderer's **startled cry (20164)** now appear in Ch24. The Veilwalker (20190) in Ch10 is more clearly depicted as a vast, indefinite, tree-crown-height hovering presence in the witness's telling, a **novel-only visualization** rather than a newly established game-species rule. Ch24/26/29 remove three unnecessary literal stopped/held-breath gestures without declaring Grimnir respiration canonically impossible. No lore source was altered.

**Changed manuscript files in this package:** Chapters **2, 10, 24, 26 and 29**. Added counted words **0 + 8 + 21 + 3 + 3 = 35**. Latest indexed corpus **146,637 → 146,672** including 30 chapter headings. All **203 original matrix placements remain intact**.

**Current semantic coverage:** **54/203 targeted AI source-hook comparisons** (not human-reviewed) and **149/203 still to compare directly with their scenes**. **Full continuous manuscript pass, the 149 outstanding semantic comparisons, comprehensive atlas/canon and read-aloud checks, and independent human acceptance remain OPEN.** The presence of 54 evidence rows does not mean final Stage 5 readiness.

### Repo-wide relative link-path recheck after source-review additions — 18 November 2026

After adding [54-ID semantic ledger](REVISION_STAGE_5_SEMANTIC_REVIEW.md) and revising the roadmap, source documents and README, a new repository-tree read found **101 Markdown files**. All 101 were fetched in seven bounded groups. A basic Markdown inline-link scan resolved **1,543 relative link destinations** against the current set of tracked files: **zero missing file targets**. This replaces the earlier snapshot's 100 files/1,498 links **for the current branch**. It still does **not** verify link-fragment anchors, HTTP(S) destinations, unusual Markdown syntax or audiovisual outputs; it is an integrity check, not acceptance of prose or source fidelity.

## 7. Continued current-source verification — 18 November 2026

[Stage 5 continuation B](REVISION_STAGE_5_CONTINUATION_02.md) records 17 new Chapter 3–4 passage/source comparisons, three newly checked IDs (20191–20193), rechecks of 20190 and numeric ID 2, and corrections in Chapters 10/12. The latest Morkahja game revision changes the wording of five descriptions after the earlier `cf7c285` audit. The book preserves its **203** source IDs, while Chapter 12's nonliteral reading of Nereval's river-mark entry condition remains flagged for a human literary-fidelity decision. Book-wide certification and any audiobook-readiness claim remain withheld.

## 8. Chapters 5–8 source-to-scene continuation — 18 November 2026

[Continuation C](REVISION_STAGE_5_CONTINUATION_03.md) documents all **40** source-matched Chapter 5–8 encounters, with correct lived/testimony/archive modes, reopened pinned lore and transition checks. **34** were not in the preceding 74-ID reviewed union, bringing the running total to **108**, and **95** remain unreviewed individually. No new hard prose error required alteration: the original Chapter 5 and 7 passages were left unchanged rather than replaced speculatively. Ch5's eight sequential Nagar campfire descriptions and Ch7's multiple containers have been logged as **listening/pacing risks**, not verified omissions. The unresolved Ch12 Nereval entry rule is still open. These checks do **not** mark Stage 5 accepted.

## 9. Chapters 9–14 current-game continuation — 18 November 2026

[Continuation D](REVISION_STAGE_5_CONTINUATION_04.md) documents direct matching for all **34 source IDs** assigned to Chapters 9–14: **21 new distinct comparisons**, **13 rechecks**, for a **129/203** union and **74 pending**. It identifies source-authority tension rather than a manuscript-only Nereval error: world [Nereval sanctuary lore](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Nerevals_Sanctuary.md) specifies healing-act entry, while game `20192` requires a mark-bearing entrant; the game follows to `19001` where healing illuminates the restoration symbol. Ch12's healing response is therefore supported by the world source and linked game encounter, but the literal bearer statement has not been erased or editorially ratified. Chapter 9 keeps Celesterra subterranean despite the game market's open-sky wording; Ch13 keeps Evergrove a cultivated oasis in desert, and distinct remote wound reports remain distinct. Ch13's `20014` was corrected to **Archive** mode in the matrix. One Chapter 14 duplicate-wrapper phrase was removed (**−1 word**); all thirty chapter files were refetched and recounted to **146,741**. Ch13's clustered reports join Ch5/7 as spoken-density risks, with **no listening verification**. Stage 5 remains in progress without human approval, game edit, or audio.
