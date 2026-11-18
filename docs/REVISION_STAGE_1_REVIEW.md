# Stage 1 — cross-chapter continuity repair review

**18 November 2026 | Implementation and internal verification by ChatGPT (GPT-6) under Babuni's previously delegated novel-drafting direction and instruction to proceed to the next revision stage.** This is a **committed literary draft revision**, not a human-approved final edition, new MorkahjaWorld canon, or a produced audiobook.

**Issue scope:** [R1–R4](MANUSCRIPT_REVISION_PLAN.md), plus the Chapter 27 phrase that depended on the convergence fix. **Baseline:** [Stage 0 snapshot](REVISION_STAGE_0_BASELINE.md), starting audiobook commit `0916221b5940d1a48229c4dc216207bd523202e0` (and Stage 0 completed at `5ee0a87c41e469f58236659bfcb6e60f12f03906`). Source game prose remained pinned at `952437c5c59d` for this targeted fictional continuity change; its newer source-text changes remain unreviewed.

## Repairs actually written

### R1 — Restore the first verified memorial identification to Chapter 29

- [Chapter 25](../manuscript/chapters/25-the-door-in-the-cliff.md): the rhythm Brunti hears in Blackwood recalls **two unnamed notes** at home, not already known Tavra/Korrum. Even the existence of two separate stones is presented as a working inference until uncasing.
- [Chapter 26](../manuscript/chapters/26-the-voices-beneath.md): both early name insertions were removed, including the false line claiming Velen had taught Brunti the identities. Velen's drawing remains an **incomplete two-position structural clue**, not a genealogical proof.
- [Chapter 27](../manuscript/chapters/27-what-the-throne-keeps.md): the memory of the shared casing and different rhythms has no names or verified original occupants.
- [Chapter 28](../manuscript/chapters/28-a-story-about-the-end.md): the Atranor conversation refers to anonymous deceased people and fixed echoes, without specific owner names.
- [Chapter 29](../manuscript/chapters/29-the-work-of-bringing-back.md): the **first physically verified identifications remain the exposed Tavra and Korrum inscriptions**, checked against local evidence; [Chapter 30](../manuscript/chapters/30-the-note-that-remains.md) names them afterward.

**Internal verification:** inspected the prose of Chapters 1–24 and revised Chapters 25–28 for literal `Tavra` / `Korrum`; **zero occurrences before Chapter 29**. Chapters 29 and 30 retain those names appropriately. No Blackwood encounter mechanics, order or mythic answers were added. This checks the **named identity leak**, not all possible indirect allusions or a full literary approval.

### R2 — Make convergence a genuine prerequisite for the permanent repair

- [Chapters 1–2](../manuscript/chapters/01-skyland-morning.md) are **unchanged**: convergence is when the necessary safe outer access and materials become available; temporary isolation continues in the interim.
- [Chapter 20](../manuscript/chapters/20-the-broken-frostweaver-record.md) retains Darrik's safe-transfer plan at convergence. [Chapter 27](../manuscript/chapters/27-what-the-throne-keeps.md) now also says the repair is needed **when** convergence arrives, not *before* it.
- [Chapter 28](../manuscript/chapters/28-a-story-about-the-end.md) retains the report that convergence **is approaching** as Brunti returns.
- [Chapter 29](../manuscript/chapters/29-the-work-of-bringing-back.md): Brunti's council testimony and project planning occur **before** convergence; the required fittings and access arrive with temporary **stone-and-light bridges** between neighboring Skylands, and Darrik verifies a service platform and independent living-room supports **before** authorizing the permanent work. A few days of preparation separate council discussion from convergence. Subsequent acceptance and modest gathering take place **during** the wider convergence work, not while it still approaches.
- [Chapter 30](../manuscript/chapters/30-the-note-that-remains.md): Velen is asked about staying through the **rest of the ongoing convergence**, not a future event that would contradict the preceding repair.

**Lore boundary:** the pinned [Grimnir Skylands](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Grimnir_Skylands.md) entry explicitly mentions bridges of stone and light at convergence and potentially linked Skylands. The memorial's specific work platform, labor and material delivery are **novel-local fictional logistics**, not a world rule imposed on all Skylands.

**Internal verification:** cross-read the affected opening rule, Chapter 20, end of Chapter 27, Chapter 28 incoming letter and Chapters 29–30. Permanent opening/replacement now happens **after** arriving materials/access. Precise **whole-book elapsed chronology remains R5/Stage 2**; no unearned calendar is claimed.

### R3 — Clarify the document Brunti carries in Everwinter

- [Chapter 2](../manuscript/chapters/02-the-weight-of-other-stones.md) already places **Darrik's original written measurements** in Brunti's separate sleeve.
- [Chapter 20](../manuscript/chapters/20-the-broken-frostweaver-record.md) now explicitly refers to those **original measurements** twice, rather than an undocumented incoming letter.
- The actual **outgoing letters** in Chapters 14 and 20 are unchanged; the **incoming Darrik response** remains clearly received by ordinary relay in Chapter 28.

**Internal verification:** the two ambiguous Chapter 20 references have been removed, while the original Chapter 2 custody, outgoing correspondence and later incoming reply remain staged. A full day-by-day mail/route map remains R5/Stage 2.

### R4 — Deliver Nemi's promised small object

- [Chapter 2](../manuscript/chapters/02-the-weight-of-other-stones.md) establishes Nemi's request for something small from below, preferably a stone not from the Skyland.
- [Chapter 3](../manuscript/chapters/03-a-road-made-of-grass.md) has the Earthsinger give Brunti a dark pebble with a pale seam; [Chapter 16](../manuscript/chapters/16-witnesses-of-corruption.md) says she still carries it home for Nemi.
- [Chapter 30](../manuscript/chapters/30-the-note-that-remains.md), before their final ordinary meal, now shows Brunti **handing the same simple pebble to Nemi**. The child chooses to keep it beside her practice hammer.

**Internal verification:** on-page gift delivery exists, preserves the requested origin/appearance and does not invent a magic reward or a source-game action.

## Changed manuscript files and counts

All **seven** changed chapter files are:

| Chapter | Edited concern | Current word count* |
| ---: | --- | ---: |
| [20](../manuscript/chapters/20-the-broken-frostweaver-record.md) | R3 | 6,489 |
| [25](../manuscript/chapters/25-the-door-in-the-cliff.md) | R1 | 5,457 |
| [26](../manuscript/chapters/26-the-voices-beneath.md) | R1 | 5,343 |
| [27](../manuscript/chapters/27-what-the-throne-keeps.md) | R1, R2 | 5,373 |
| [28](../manuscript/chapters/28-a-story-about-the-end.md) | R1 | 5,783 |
| [29](../manuscript/chapters/29-the-work-of-bringing-back.md) | R2 | 5,738 |
| [30](../manuscript/chapters/30-the-note-that-remains.md) | R2, R4 | 5,654 |

*New counting convention applied uniformly to all 30 chapters in the [manuscript index](../manuscript/chapters/README.md): number of whitespace-separated tokens containing at least one Unicode letter or numeral; chapter headings included. The current resulting manuscript total is **145,584 counted words**. The historically reported baseline of **145,383** used an unspecified convention and is **not directly comparable** without a full baseline recount under the same method.

## Verification performed and outstanding limits

| Gate | Evidence | Status |
| --- | --- | --- |
| Changed-file scope | Compared audiobook GitHub from Stage 0 end (`5ee0a87`) to the completed prose changes: Chapter 20, 25–30 plus the manuscript index, no other chapter files. | **Checked** |
| Name reveal order | Literal owner-name scan across Chapters 1–28 yields none after edits; physical inscriptions remain in Ch29. | **Checked** |
| Convergence logistics | Opening requirement, Ch27 reminder, Ch28 reply, Ch29 arrival/transfer and Ch30 continuation are now mutually consistent. | **Targeted check passed; global clock remains open** |
| Letters and keepsake | Ch2 original Darrik measures; Ch14/20 outgoing messages; Ch28 reply; Ch30 actual pebble handover. | **Targeted check passed** |
| Encounter assignment structure | [Matrix](../story/PLACEMENT_MATRIX.md): **203 rows, 203 distinct IDs**; not altered; manuscript chapter index still has **30** entries. | **Checked structurally** |
| Full game prose refresh | Game `main` had advanced 10 commits from pinned snapshot and modified encounter JSON during Stage 0. | **Unresolved, Stage 5/source reconciliation** |
| Full manuscript line edit, travel/calendar, character motivations | Not performed by this targeted Stage 1 pass. | **Open, Stage 2–5** |
| Human independent editorial acceptance and audiobook | Not performed. | **Open** |

**Outcome:** R1–R4 have **implemented and internally checked draft repairs**. They are not automatically *human-approved final text*. Stage 1 is complete for its limited continuity scope; the [revision plan](MANUSCRIPT_REVISION_PLAN.md) Stage 2 (travel/calendar, Brunti's durable weakness and Blackwood causality) remains outstanding. Nothing changed in the Morkahja game or MorkahjaWorld lore repositories.
