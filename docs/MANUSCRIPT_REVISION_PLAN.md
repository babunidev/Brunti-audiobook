# Brunti — manuscript revision plan

**18 November 2026 | Status: living editorial work plan. Stages 0–4 have targeted implementation and internal checks; Stage 5 source-field/integrity/transition audit has begun, but full manuscript/source/canon/read-aloud/human approval gates remain OPEN.** Prepared by ChatGPT (GPT-6) under Babuni's direction to plan fixes after the [whole-manuscript story audit](WHOLE_MANUSCRIPT_STORY_AUDIT.md). The human creative's direction and the established Morkahja source repositories remain authoritative. This plan records sequencing and editorial options; **R1–R4 have now been implemented as internally checked draft revisions**, not separately human-approved final prose.

## Goal and fixed boundaries

Turn the **30-chapter manuscript** (now **146,733 counted words** after targeted Stage 5 source-fidelity and copyediting updates; the original index reported 145,383 under an unspecified earlier convention) into a coherent, varied, emotionally complete novel suitable for a separate narration-preparation phase. Retain all **203 source encounter IDs**, their significant imagery and required linked sequence, but do not privilege a one-encounter/one-beat formula over good storytelling. Preserve the local memorial solution, the distinct lives of the two deceased Grimnir, Brunti's living mineral/metal/crystal physiology, her identity as a warrior, the independence of Sira and Velen, and Morkahja's unresolved mythic questions.

**Source hierarchy:** [MorkahjaWorld](https://github.com/babunidev/MorkahjaWorld) for lore; [Morkahja](https://github.com/babunidev/Morkahja) for encounters and follow-links; [source ledger](SOURCES.md) and [placement matrix](../story/PLACEMENT_MATRIX.md) for pinned review state. The last reconciled game baseline is `952437c5c59d`. New plot details are **novel-only proposals**, not lore amendments. No new all-purpose villain, prophecy, Blackwood explanation, Ravage cure or sentient-ghost behavior for memory-stone echoes.

## Working rules

1. **Change only the smallest necessary scenes first.** Treat contradictions as blocking, structure as second, line/audio polish as third. Make related chapter edits together so an earlier change does not create a later conflict.
2. **Preserve evidence and revision traceability.** For each pass record before/after chapter references, why the story changed, source IDs affected, provenance/canon constraints and what was checked. Update the manuscript index and development records after actual edits; never mark a proposed item complete on drafting alone.
3. **Make the revision read as a novel.** Atmosphere, discovery, comedy, kindness, danger and companionship all belong. Do not turn every encounter into another explicit lesson about uncertainty.
4. **Keep editorial gates separate.** GPT-6 may draft proposed revisions under the existing delegated fiction work; an internal check is not independent human approval, source-canon adoption or audio release clearance.

## Stage 0 — Lock the baseline and map the dependencies

**Completed 18 November 2026 as a documentation and structural baseline (not a prose revision).** See [30-file/203-ID snapshot](REVISION_STAGE_0_BASELINE.md), [chronology/knowledge/objects ledger](../story/REVISION_CHRONOLOGY_AND_OBJECTS.md), [chapter-function map](../story/REVISION_CHAPTER_FUNCTIONS.md), and [revision log](MANUSCRIPT_REVISION_LOG.md). The game source has advanced by ten commits since the pinned reviewed encounter baseline; individual new prose changes remain to be reconciled before source-specific manuscript changes.

- [x] Snapshot the 30 draft paths/word counts and confirm the [203-entry encounter placement matrix](../story/PLACEMENT_MATRIX.md) against the current manuscript. Record exact starting commit and source revision; check for later game-text changes before each source-specific edit.
- [x] Build a **chronology and travel ledger** from Chapter 1 through Chapter 30: departure, settlements and regions, time elapsed, seasonal references, Sira/Velen separations/reunions, messages sent and received, convergence preparations, Blackwood recovery and arrival home.
- [x] Build a **clue/knowledge/prop ledger**: anonymous two-stone observation, Aetherion drawing, first verified owner names, who knows what when, Brunti's tools, Nemi's pebble and letters to/from Darrik and Sira.
- [x] Prepare a short **chapter-function map**: for each chapter, the changed circumstances, principal dramatic function and consequence for the next chapter; flag repeats without assuming every source encounter needs an independent scene.
- [x] Establish a small change log for revision passes, including proposed vs accepted choices.

**Gate 0 (documentation check passed):** All 30 chapters are inventoried, the 203-row matrix is structurally validated, and relative chronology/knowledge/props/functions are catalogued with unresolved gaps explicit. No finalized calendar or source-fidelity sign-off is asserted.

## Stage 1 — Repair the hard contradictions

**Implemented as a targeted draft continuity pass on 18 November 2026.** See [Stage 1 verification](REVISION_STAGE_1_REVIEW.md) and [change log](MANUSCRIPT_REVISION_LOG.md). The table below preserves the original issue targets for traceability.

| Work item | Primary chapters | Proposed approach | Acceptance check |
| --- | --- | --- | --- |
| **R1. First identification of Tavra and Korrum** | 11, 20, **25–29** | Remove named knowledge from Chapters 25–28 and the false claim that Velen assigned the names. Preserve two distinct, **anonymous** rhythms and records. Chapter 29's exposed inscriptions provide the first verified identification, corroborated with surviving local material. | Search narrative prose for both names: first verified owner-name use appears only in Chapter 29; earlier descriptions do not accidentally reveal identities. |
| **R2. Convergence access and repair** | **1–2, 14, 20, 28–30** | **Implemented in revised draft:** keep the original requirement that convergence supplies safe access/materials. Brunti may arrive and present evidence **before** the event, but the actual permanent opening/replacement occurs **during** the convergence work. Make the approach, arrival, preparation, repair and later ordinary-life epilogue chronological. Do not invent an unexplained early supply. | No permanent replacement happens before available access/materials; the council deadline, isolation and final repair all agree. |
| **R3. Letter provenance** | **1–2, 14, 20, 28** | Determine if Chapter 20's “Darrik's letter” is an initial written brief/measurement sheet or a real incoming message; if no delivery is supported, relabel it accurately. Distinguish Brunti's earlier outgoing dispatch, Chapter 20 confirmation and Darrik's later reply. | Each important letter has sender, recipient, approximate dispatch/delivery order and a scene or credible relay explaining possession. |
| **R4. Nemi's keepsake** | **2–3, 5, 16, 29–30** | Preserve the Earthsinger pebble and its promise; add a restrained on-page handover, or acknowledge an actual loss if a later scene supports it. Prefer the quiet handover over invented magical significance. | The promised object has a clear end state and Nemi is present to receive/understand it. |

**Gate 1 (targeted check passed):** R1–R4 are addressed in Chapters 20 and 25–30. The repair now takes place during convergence, the named identities first appear in Chapter 29, Darrik's Ch20 measurements are correctly identified, and Nemi receives the pebble. [Evidence and limits](REVISION_STAGE_1_REVIEW.md). Independent human acceptance and whole-book chronology remain outstanding.

## Stage 2 — Strengthen the clock, character causality and Blackwood stakes

**Implemented as an internally checked targeted structural draft pass on 18 November 2026;** [Stage 2 review](REVISION_STAGE_2_REVIEW.md) records the decisions, chapter evidence and remaining limits. The table retains the original requirements as change-control history.

| Work item | Chapter targets | Required story effect |
| --- | --- | --- |
| **R5. One believable journey clock** | 1–2, 10–14, 16–21, 23–24, 28–30 | Use the Stage 0 chronology to choose a realistic convergence window and a few plain-language time anchors. Sira's westward journey, Velen's approved leave, northern research, the Keldor rescue, courier travel and Brunti's injury recovery must fit. Show the cost of delay without making the safely isolated wall an imminent catastrophe. |
| **R6. Brunti's durable blind spot** | 1–2, 11, 14, **20**, 23–24, 27–30 | Her competence and consideration for strangers develop early; her *personal* fear of admitting an incomplete answer to her Skyland remains. Clarify that in Chapter 20 she intellectually accepts Darrik's safe transfer yet still struggles with public accountability and the wish to bring home something exceptional. Show this contradiction in action rather than repeating a moral explanation. |
| **R7. The choice after rescuing the child** | **23–24**, 27–28 | Make the safe journey home unambiguously available. Brunti's choice to leave it is conscious, particular and costly: it strains trust with Sira and Velen and threatens her ability to meet the communal obligation. Never reward Blackwood with the memorial solution. |
| **R8. Plausible external rescue** | **25–27** | Keep the abyss crossing and collapse mysterious. Give the healer a modest verifiable report: who encountered Brunti **outside the inexplicable inner passage**, approximate condition/place/time, how she was transported to care, and how the companions received notice. These are a proposed **novel-only** recovery chain, not an explanation of Blackwood's workings. |
| **R9. Warrior-protector identity** | 1–3, 10, 13, 17–18, 21–24, 29–30 | Show trained vigilance, protection, strength under restraint, risk appraisal and responsibility to others. Keep crafting and scholarship as part of her identity, not substitutes for it; do not add gratuitous battles. |

**Gate 2 (targeted internal check passed; full geographic verification outstanding):** Brunti has a relative six-month convergence clock, a personal accountability wound distinct from her earlier learning, a feasible wagon home she knowingly declines, a visible cost to companionship and her body, an ordinary rescue/courier route, and guard training expressed through care. [Stage 2 review](REVISION_STAGE_2_REVIEW.md). Independently verified travel times, full scene-source fidelity and human line approval remain Stage 5.

## Stage 3 — Rebuild scene functions and chapter pacing

**Targeted prose implementation completed 18 November 2026, internal checks recorded.** See [Stage 3 edited-chapter/function report](REVISION_STAGE_3_REVIEW.md). The **full uninterrupted 30-chapter close-read and per-encounter function/source tagging originally specified below remain uncompleted** and are tracked for Stage 5; do not mistake programmatic chapter scans plus selected scene close-reads for that final gate.

- [ ] Re-read every full chapter as narrative, not only chapter openings/endings. For each encounter passage, tag its actual function: discovery, hazard, comic turn, community, conflict, loss, relationship change, witness testimony, respite or thematic echo. Check [109 scene briefs](../story/scenes/README.md) and the 203-entry source ledger when combining or reframing beats.
- [x] **Chapters 3–9:** reduce the recurring “unusual sign → speculative interpretation → restraint → notebook” pattern; keep the region's wonder, living animals, humor and social interactions. Not every scene must advance the memorial puzzle.
- [x] **Chapters 17–20:** avoid giving each Frostwind/Everwinter fragment the same concluding lesson. Differentiate physical survival, friendship, Jorvald's scholarship, Frostweaver loss and the turning point of accepting Darrik's plan.
- [x] **Chapters 21–24:** keep the child's rescue causal and emotionally specific. Chapter 24's **20 encounter IDs** must still be traceable, but transitions can carry multiple experiences and not every one needs its own moral summary. Preserve the deliberate, wrong decision to enter deeper Keldor.
- [x] **Chapters 25–28:** distinguish Blackwood's escalating sensory unreliability from repeated explanatory reminders; let Chapter 28's Atranor testimony breathe but trim any material that postpones the homecoming without changing Brunti's relationship to loss.
- [x] Vary chapter-end movement: resolve a local kindness, end with a consequence, a complication, silence, conversation or earned rest. Cut redundant statements of “not proof,” “not an answer,” and “cannot know” where events already communicate the limit.

**Gate 3 — targeted implementation checked, exhaustive fidelity pending:** Chapters 3–28 have paragraph-level pacing revisions; Chapters 1–2 and 29–30 retain distinct framing/craft functions. The matrix still has 203 unique IDs, and the explicit letter/follow-link placements are intact. **Not yet verified:** actual literary function and refreshed source fidelity of each 203 encounter passage, all 109 brief-to-prose alignments, or an uninterrupted close-read of all 145,771 words. Those checks remain Stage 5.

## Stage 4 — Make the ending emotionally earned

**Targeted Stage 4 prose edits applied and internally checked 18 November 2026.** See [Stage 4 revision evidence](REVISION_STAGE_4_REVIEW.md). The issue list below is the original editing brief, not a claim of independent human acceptance.

- [x] **R10. Anonymous memorial identities:** Foreshadow two distinct lives through original toolmarks, handling, separate resonances or contextually credible unnamed archival traces in Chapters 1–2 and 11. Do **not** pre-name the owners or make the memory echoes speak new words. Let Chapter 29's inscriptions answer a question the reader has felt.
- [x] **R11. Secondary consequences:** Ensure Nemi's gift and changing craft judgment pay off in Chapters 29–30. Confirm whether the rescued Verdani child actually reaches family in established prose; if not, include only a truthful on-page message/update or acknowledge the continuing uncertainty. Do not manufacture a reunion as historical fact.
- [x] **R12. Relationships:** Let Sira retain legitimate disagreement and independent relief work; provide a small concrete sign of the changed trust rather than automatic full forgiveness. Let Velen's record-keeping remain distinct from Brunti's experience; give Darrik a meaningful role in the final safe repair rather than making him an antagonist proved wrong.
- [x] **R13. Atranor / grief:** Preserve the inherited, secondhand status of Tarnel's story and the established divine laws. Refine its connection to mortality and memory so it enriches rather than stalls the return.
- [x] Re-read Chapters **1–2 and 29–30 together**: the early hammer, unsafe brace, memorial, craft obligation and Nemi's questions must close without overexplaining the theme.

**Gate 4 (targeted internal check passed):** Anonymous craft patterns foreshadow the two distinct memorial histories; names remain first verified in Chapter 29; the girl has a safe relay and an unconfirmed reunion; Sira's anger is not erased, Velen's source authority remains distinct, Darrik owns the safety work, Nemi receives her promised stone, and Tarnel's secondhand Atranor account retains its original divine rules. See [Stage 4 review](REVISION_STAGE_4_REVIEW.md). Full human/source/lore verification remains Stage 5.

## Stage 5 — Full manuscript, canon and audiobook-readiness verification

**Stage 5 progress, 18 November 2026:** Targeted current-game encounter/source-to-draft-scene comparisons now cover **all 203 of the 203 distinct source IDs**, across [semantic A (54)](REVISION_STAGE_5_SEMANTIC_REVIEW.md), [B (+20)](REVISION_STAGE_5_CONTINUATION_02.md), [C (+34)](REVISION_STAGE_5_CONTINUATION_03.md), [D (+21)](REVISION_STAGE_5_CONTINUATION_04.md), [E (+48)](REVISION_STAGE_5_CONTINUATION_05.md), and [F (+26)](REVISION_STAGE_5_CONTINUATION_06.md). **No individual original game encounter remains unchecked at this targeted level.** Last 26 game JSON objects are identical in `952437c5c59d` and `2ba61f5a6bc`. Chapter 22 button cost/return corrected (+1 word), Chapter 25 duplicate sitting phrase removed (−9); **all 30 draft chapters refetched and recounted at 146,733 words**. The story retains Babuni-approved older lore and Chapter 12 Nereval healing-access literary interpretation without altering current game rules. **Do not mark Stage 5 complete:** full 109-scene brief/function check, uninterrupted 30-chapter literary/canon/time/atlas read, actual read-aloud/spoken listening assessment, and independent human final editorial acceptance are still OPEN. Potential listening density: Ch5, Ch7, Ch13, Ch16, Ch20, Ch24. No narrator export or audio production.

- [ ] **Narrative pass:** Read all 30 chapters consecutively; build a chapter transition report for chronology, geography, cast whereabouts, injury recovery, messages, prop custody and knowledge leaks. Sample-searches are insufficient for final sign-off.
- [ ] **Source fidelity pass:** Check all **203 distinct encounter IDs** against the pinned/reconciled current game prose, explicit follow chains and the [placement matrix](../story/PLACEMENT_MATRIX.md). Verify each has a real narrative presence rather than a catalog mention. Record any source updates after the baseline separately.
- [ ] **World lore pass:** Check named places, races, Grimnir anatomy/culture, Skylands engineering, Atranor and Blackwood against [MorkahjaWorld](https://github.com/babunidev/MorkahjaWorld). Log unresolved source conflicts; do not silently recanonize novel fiction.
- [ ] **Style pass:** Read scene transitions and paragraphs aloud for rhythm, overexplaining, repeated motifs, weak dialogue differentiation and excessive negative framing. Maintain the chosen **close third-person past tense** of the novel; do not impose the game's encounter-text present tense.
- [ ] **Integrity checks:** Recount all chapters/words; validate internal links, consistent character names/pronouns, presence/order of the seven letter stones **A H K J O M A**, Blackwood's **eight-step** sequence, smaller follow pairs, and intended metaphor for game encounter **ID 2 — Level up!**.
- [ ] **Acceptance:** Obtain **separate human editorial review/approval** of the revised complete book, with concerns logged explicitly. Only then prepare narrator scripts, pronunciation guide, rights checks, recording tests and audio mastering in the already separate [roadmap](../ROADMAP.md).

**Final gate:** 30 coherent revised chapters; 203/203 encounter placements independently checked; no known blocking contradictions; character and calendar continuity verified; human editorial acceptance recorded. Audio production/release remain separate milestones.

## Proposed execution order and revision tracking

1. Baseline ledgers (**Stage 0**) → continuity repairs (**Stage 1**).
2. Causal/chronology rewrite (**Stage 2**) → encounter and pacing rewrite (**Stage 3**).
3. Emotional closing pass (**Stage 4**) → complete verification (**Stage 5**).

Prefer **small, reviewable chapter-group commits** with a brief editorial note for each package (issue IDs R1–R13, chapters changed, before/after, source changes, check performed, unresolved questions). A pass is complete only after the affected earlier and later chapters have been reread together. If a proposed solution collides with lore or chronology, document the conflict and revise the proposal rather than hiding it.

**Historical status when first created:** Initial planning artifact. **Current stage classification (18 November 2026):** 0–4 targeted revisions internally reviewed. **Stage 5 individual source-to-scene verification milestone 203/203 complete; Stage 5 editorial final gate still OPEN.** All 30 full chapter files recount **146,733 counted words** after the Ch22/25 copyedits. **Next internal checks are substantive:** all 109 scene briefs and their performed dramatic functions, uninterrupted novel read, calendar/route/canon integrity, actual spoken comprehension, and separate human editorial approval. The novel-only Nereval healing-entry adaptation and compatible older lore retention are explicitly human-directed. None of these records modifies live game mechanics or establishes audiobook release approval.
