# Brunti — manuscript revision plan

**18 November 2026 | Status: living editorial work plan. Stage 0 documentation and Stage 1 targeted continuity edits are complete; Stages 2–5 and independent editorial approval remain outstanding.** Prepared by ChatGPT (GPT-6) under Babuni's direction to plan fixes after the [whole-manuscript story audit](WHOLE_MANUSCRIPT_STORY_AUDIT.md). The human creative's direction and the established Morkahja source repositories remain authoritative. This plan records sequencing and editorial options; **R1–R4 have now been implemented as internally checked draft revisions**, not separately human-approved final prose.

## Goal and fixed boundaries

Turn the **30-chapter manuscript** (now **145,584 counted words** after the Stage 1 edits; the original index reported 145,383 under an unspecified earlier convention) into a coherent, varied, emotionally complete novel suitable for a separate narration-preparation phase. Retain all **203 source encounter IDs**, their significant imagery and required linked sequence, but do not privilege a one-encounter/one-beat formula over good storytelling. Preserve the local memorial solution, the distinct lives of the two deceased Grimnir, Brunti's living mineral/metal/crystal physiology, her identity as a warrior, the independence of Sira and Velen, and Morkahja's unresolved mythic questions.

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

**Priority: structural; should precede large prose polish.**

| Work item | Chapter targets | Required story effect |
| --- | --- | --- |
| **R5. One believable journey clock** | 1–2, 10–14, 16–21, 23–24, 28–30 | Use the Stage 0 chronology to choose a realistic convergence window and a few plain-language time anchors. Sira's westward journey, Velen's approved leave, northern research, the Keldor rescue, courier travel and Brunti's injury recovery must fit. Show the cost of delay without making the safely isolated wall an imminent catastrophe. |
| **R6. Brunti's durable blind spot** | 1–2, 11, 14, **20**, 23–24, 27–30 | Her competence and consideration for strangers develop early; her *personal* fear of admitting an incomplete answer to her Skyland remains. Clarify that in Chapter 20 she intellectually accepts Darrik's safe transfer yet still struggles with public accountability and the wish to bring home something exceptional. Show this contradiction in action rather than repeating a moral explanation. |
| **R7. The choice after rescuing the child** | **23–24**, 27–28 | Make the safe journey home unambiguously available. Brunti's choice to leave it is conscious, particular and costly: it strains trust with Sira and Velen and threatens her ability to meet the communal obligation. Never reward Blackwood with the memorial solution. |
| **R8. Plausible external rescue** | **25–27** | Keep the abyss crossing and collapse mysterious. Give the healer a modest verifiable report: who encountered Brunti **outside the inexplicable inner passage**, approximate condition/place/time, how she was transported to care, and how the companions received notice. These are a proposed **novel-only** recovery chain, not an explanation of Blackwood's workings. |
| **R9. Warrior-protector identity** | 1–3, 10, 13, 17–18, 21–24, 29–30 | Show trained vigilance, protection, strength under restraint, risk appraisal and responsibility to others. Keep crafting and scholarship as part of her identity, not substitutes for it; do not add gratuitous battles. |

**Gate 2:** A reader can trace why Brunti leaves, why she does not immediately return, why she knowingly goes astray in Chapter 24, why she survives without a magical answer, and why returning requires accountability. Every time/letter/companion transfer is feasible.

## Stage 3 — Rebuild scene functions and chapter pacing

**Priority: literary architecture, then prose.**

- [ ] Re-read every full chapter as narrative, not only chapter openings/endings. For each encounter passage, tag its actual function: discovery, hazard, comic turn, community, conflict, loss, relationship change, witness testimony, respite or thematic echo. Check [109 scene briefs](../story/scenes/README.md) and the 203-entry source ledger when combining or reframing beats.
- [ ] **Chapters 3–9:** reduce the recurring “unusual sign → speculative interpretation → restraint → notebook” pattern; keep the region's wonder, living animals, humor and social interactions. Not every scene must advance the memorial puzzle.
- [ ] **Chapters 17–20:** avoid giving each Frostwind/Everwinter fragment the same concluding lesson. Differentiate physical survival, friendship, Jorvald's scholarship, Frostweaver loss and the turning point of accepting Darrik's plan.
- [ ] **Chapters 21–24:** keep the child's rescue causal and emotionally specific. Chapter 24's **20 encounter IDs** must still be traceable, but transitions can carry multiple experiences and not every one needs its own moral summary. Preserve the deliberate, wrong decision to enter deeper Keldor.
- [ ] **Chapters 25–28:** distinguish Blackwood's escalating sensory unreliability from repeated explanatory reminders; let Chapter 28's Atranor testimony breathe but trim any material that postpones the homecoming without changing Brunti's relationship to loss.
- [ ] Vary chapter-end movement: resolve a local kindness, end with a consequence, a complication, silence, conversation or earned rest. Cut redundant statements of “not proof,” “not an answer,” and “cannot know” where events already communicate the limit.

**Gate 3:** Every chapter has a distinctive purpose; consequential scenes change a relationship, task, location or understanding, while quiet scenes are allowed to remain quiet. All 203 IDs retain faithful literary placement; no accidental duplicate or skipped required follow-link.

## Stage 4 — Make the ending emotionally earned

- [ ] **R10. Anonymous memorial identities:** Foreshadow two distinct lives through original toolmarks, handling, separate resonances or contextually credible unnamed archival traces in Chapters 1–2 and 11. Do **not** pre-name the owners or make the memory echoes speak new words. Let Chapter 29's inscriptions answer a question the reader has felt.
- [ ] **R11. Secondary consequences:** Ensure Nemi's gift and changing craft judgment pay off in Chapters 29–30. Confirm whether the rescued Verdani child actually reaches family in established prose; if not, include only a truthful on-page message/update or acknowledge the continuing uncertainty. Do not manufacture a reunion as historical fact.
- [ ] **R12. Relationships:** Let Sira retain legitimate disagreement and independent relief work; provide a small concrete sign of the changed trust rather than automatic full forgiveness. Let Velen's record-keeping remain distinct from Brunti's experience; give Darrik a meaningful role in the final safe repair rather than making him an antagonist proved wrong.
- [ ] **R13. Atranor / grief:** Preserve the inherited, secondhand status of Tarnel's story and the established divine laws. Refine its connection to mortality and memory so it enriches rather than stalls the return.
- [ ] Re-read Chapters **1–2 and 29–30 together**: the early hammer, unsafe brace, memorial, craft obligation and Nemi's questions must close without overexplaining the theme.

**Gate 4:** The local memorial conflict and character relationships resolve at the level the story actually establishes. Unsolved world mythology stays open by design.

## Stage 5 — Full manuscript, canon and audiobook-readiness verification

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

**Historical status when first created:** Planning document only. **Current status:** Stage 0 completed; Stage 1 draft prose repairs committed and internally verified. No human line approval or audio produced.
