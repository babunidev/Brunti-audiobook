# Stage 5 — manuscript verification audit, first evidence pass

**18 November 2026 | Status: IN PROGRESS, NOT editorially accepted.** ChatGPT (**GPT-6**) conducted source-data comparison, 30-chapter structural and focused prose checks, lore-reference inspection and one documented copyedit under Babuni's instruction to proceed to Stage 5. **The final Stage 5 gate is NOT passed.** The required uninterrupted full-book read, individual semantic approval of every encounter, read-aloud performance check and separate human acceptance have **not** been completed.

**Book revision at start:** audiobook `df0fbe8f370981ec870d8da621435fcda27f8c68` (end of Stage 4), [original revision plan](MANUSCRIPT_REVISION_PLAN.md). **Revised manuscript:** 30 chapters, **146,662 counted words** including chapter headings after the Stage 5 Chapter 3 copyedit. Method: whitespace-separated tokens containing at least one Unicode letter or numeral, as in the [chapter index](../manuscript/chapters/README.md). This is **+3** counted words from 146,659 at Stage 4. Source encounter matrix remains unmodified.

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

Focused manuscript inspections found the original Blackwood portal and root maze in Chapter 25, the Choir / Mire / Procession material in Chapter 26, and the Silent Throne followed by the Verdani healer and ordinary post-abyss care in Chapter 27. The seven distinct letter-stone encounters remain in Chapter 4; their intended **A H K J O M A** order and absence of a decoding are retained in the prior continuity records, but a fresh independent letter-by-letter semantic acceptance remains outstanding.

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

**Actual correction:** [Chapter 3 — A Road Made of Grass](../manuscript/chapters/03-a-road-made-of-grass.md) initially said a second trader added a *silver handle* although the preceding narration added a *silver box and golden clasp*. The later question about an unmentioned handle contradicted the narrative. Stage 5 changed the paragraph to refer to the invented box, clasp and name, and changed the trader's question to **“Was the clasp wrong?”** Brunti answers that it had not appeared in the first account. This restores the joke's causal order without altering either source encounter. The word count is **3,221 → 3,224** (+3), book count **146,659 → 146,662**.

**Not performed:** an uninterrupted **full 146,662-word human-like literary close-read**, listening to all of it spoken, professional line/copyedit, pronunciation checks, narrator files or finished audio. Paragraph/term scans cannot substitute for those tasks.

## 5. Current gate status — deliberately not certified

| Stage 5 gate | Evidence so far | Status |
| --- | --- | --- |
| 30 indexed manuscript chapters and standardized word recount | Chapter sources + index, total **146,662** | **Checked structurally** |
| 203 game records vs 203 matrix assignments vs 203 scene-brief ID entries | Direct machine parses, all numeric IDs match and chapter assignments agree | **Checked structurally** |
| 33 newer source prose records compared by JSON field | **Only** `mEncounterText` changed at IDs 20158–20190 | **Checked field-by-field** |
| 203 manuscript integration identities/faithfulness | [Automated candidate locator register](STAGE_5_ENCOUNTER_LOCATORS.md), **24 low-overlap flags**; focused examples read | **OPEN: not semantically certified per ID** |
| Canon physiology, Atranor, Keldor and Skyland boundaries | Pinned lore references and targeted manuscript inspections | **Partial** |
| Full chronology, travel, injury, letters and character positions after Stage 4 | Prior stage ledgers, selected late-chapter cross-reads | **OPEN: not yet complete consecutive read** |
| Read-aloud flow and whole-book dialogue/style consistency | Paragraph lengths and targeted samples | **OPEN: no performed listening test** |
| Links and export integrity | Check pending; source/chapter index files have not been exported as narrator scripts | **OPEN** |
| Separate human editorial acceptance | No explicit human approval of revised full prose | **OPEN** |

### Remaining editorial action register

1. **E5-01 — Blocking:** independent, consecutive read of all 30 chapter files and a signed chapter-transition ledger for all characters, messages, injuries, props and chronology. A paragraph search is not sufficient.
2. **E5-02 — Blocking:** semantic source-to-scene verification for **all 203** entries at the **current game source**, including the 33 rewritten descriptions; use the locator register to find candidate passages but do not auto-approve them.
3. **E5-03 — Blocking:** complete atlas/geography, lore and read-aloud review, including the special Atranor/Level up! modes, the seven letters and preserved follow chains, with any discovered conflicts recorded instead of silently changing canon.
4. **E5-04 — Blocking final approval:** **separate human editorial acceptance** of a definite frozen manuscript revision. No assistant-generated report may impersonate it.
5. **E5-05 — Subsequent production only:** narrator-ready segmentation, pronunciation and attribution review, rights clearance, voice tests, audio mastering and release after manuscript acceptance.

**Conclusion:** Stage 5 has produced **real new source reconciliation evidence, an automated 203-ID passage-locator aid, targeted lore checks and one manuscript copyedit**, but its **final gate remains unpassed**. Stages 0–4 remain internally revised drafts. **No audiobook has been recorded, approved or published** and no Morkahja/MorkahjaWorld file was changed.
