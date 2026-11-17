# Manuscript draft review — provenance and editorial register

**Date:** 17 November 2026. **Status:** Internal AI-authored *first draft*, not a human line edit or accepted final text. **Human creative direction:** Babuni's young Grimnir warrior, all 203 encounters integrated into a coherent novel, stepwise development. **AI contribution:** ChatGPT (GPT-6) drafted chapter prose and prepared this source/continuity comparison.

## Opening two chapters — first completed review stage

**This section describes Chapters 1–2 only.** See [the separate Chapters 3–4 source review](CHAPTERS_03_04_REVIEW.md) for the subsequent Vale manuscript, and [the live manuscript index](../manuscript/chapters/README.md) for current book-wide totals.

## Chapters 1–2 coverage

| Chapter | Prose link | Scene source | Encounter adaptations | Literary drafting status | Editorial status |
| ---: | --- | --- | --- | --- | --- |
| 1 | [Skyland Morning](../manuscript/chapters/01-skyland-morning.md) | [01.1–01.3](../story/scenes/MOVEMENT_I.md) | No game encounter; original Skyland opening | **Draft v1**, 3,249 words | Not independently reviewed |
| 2 | [The Weight of Other Stones](../manuscript/chapters/02-the-weight-of-other-stones.md) | [02.1–02.3](../story/scenes/MOVEMENT_I.md) | **5 distinct game encounters**, all mediated as testimony | **Draft v1**, 3,313 words | Not independently reviewed |

**Historical stage totals when this initial review was written:** two chapters; six opening scenes as prose; five source encounter IDs drafted; 198 game encounter IDs then still planned. The latest totals now also include [Chapters 5–6](CHAPTERS_05_06_REVIEW.md): **twelve chapters, 87 source integrations drafted and 116 planned**. This opening review records the earlier stage as well. **Zero manuscript encounters independently editorial-verified**.

## Chapter 1 — what is actually in the manuscript

- Brunti teaches **Nemi** (a novel-only Grimnir child) to repair a practice hammer, establishing craft through living activity rather than exposition.
- The constructed, moving Skyland has ordinary workshops, mineral-based meals, living architectural resonance, and memorial stones retaining **echoes** of deceased Grimnir.
- A second rhythm appears at a damaged old join. Brunti inserts a bridge brace **without checking the adjacent resting chamber**. The resonance is transmitted toward healing residents.
- She removes the brace, admits her act, and enlists **Darrik**, a novel-only Grimnir anchor-craft steward. He isolates the memorial's support and safeguards the rest area.
- The council permits investigation in principle. A repaired wall is a legitimate safety requirement; moving and conserving the memorial is not framed as erasure or evil.

**Canon checks consulted:** [Grimnir](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Races/Grimnir.md), [Skylands](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Grimnir_Skylands.md), [birth/community](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Traditions/Grimnir_Birth_and_Community.md), [life/care](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Traditions/Grimnir_Life_and_Care.md), [Grimnir arts](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Magic/Grimnir_Arts.md). The exact memorial-support architecture and the characters' responses are **original fiction**, not canon mechanics.

## Chapter 2 — source-to-prose comparison

The **five complete source `mEncounterText` records** were reread from [game commit 13a5d134c8e6](https://github.com/babunidev/Morkahja/blob/13a5d134c8e63855894436e4f1b09910c5c50b95/server/game/encountersdata.json). Their text was unchanged across the later revision checked. They appear through different witnesses at a craft council, **not** as five simultaneous places Brunti personally visits.

| ID / original title | Source's unique scene content | Draft location and method | Editorial note |
| --- | --- | --- | --- |
| **20015 — Weakened Grimnir** | Female Grimnir warrior on one knee in a dim cave, wounded armor, weapon holding her upright | Orven transmits a scout's description, including cave, kneeling, damage and uncertainty about aftermath | Literal human **sweat / hair / breathing** from game prose not copied verbatim into Grimnir physiology |
| **20018 — Stonefist Ironwill** | Wounded warrior under ruined temple arch, battered armor, side injury, weapon still held | Orven transmits a separate temple traveler's testimony and partial follow-up | **Source contradiction:** game scene uses she/her and blood; [world People entry](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/People/Travellers_and_Witnesses.md) refers to Stonefist as **he/him** and mineral-bodied Grimnir. Novel uses **he**, following established world lore. Requires human editorial awareness |
| **20055 — Wounded Grimnir** | Warrior injured amid stone damage after Crumblegheist struggle; narrow cave passage to light | Separate worker testimony preserves broken cave, Crumblegheist, fracture and visible escape opening | Source specifies literal **dark blood**; novel renders a fractured **mineral seam** to honor world physiology. The outcome remains incomplete |
| **20056 — Venerable Grimnir** | Hungry elderly Grimnir outside emptied underground dwelling after Urcogor raid, holding an empty bowl | Kelna recounts the dwelling and carries the bowl; supplies, food and temporary aid are novel-specific aftermath | The game describes **Urcogors** responsible for this raid; nothing establishes a universal mastermind or guilt of all older peoples |
| **20128 — Grimnir Rebels** | Stoneguard around a dim fire under cave stalactite, exhausted and quiet | Kelna carries second-hand report and cave-wall rubbing; their political aims remain unknown | Novel does **not** define opposition, homeland or desired intervention; council sends a request for more information |

### Source conflicts — explicit, not silently harmonized

Several early encounter descriptions depict injured Grimnir as ordinary humanoids with sweat, loose hair, breathing and bleeding. The canonical [Grimnir physiology](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Races/Grimnir.md) and [life/care](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Traditions/Grimnir_Life_and_Care.md) describe bodies of mineral, metal, crystal and geomantic maintenance. The adaptation keeps their **hurt, restraint, armor, helplessness and scene geometry**, replacing some human-default physical details with fractures or material strain. The game descriptions remain unchanged. The gender-pronoun conflict in **20018** is also not resolved in world canon by the novel's choice.

## Narrative and audio editorial checklist

| Check | Current evidence | Status |
| --- | --- | --- |
| Opening is an experienced moment, not an encyclopedia | Brunti and Nemi repairing a practice hammer; Skyland in motion | Drafted, review pending |
| Brunti's error and accountability are dramatized | The bridge brace transfers vibration into resting area; Darrik isolates it | Drafted, review pending |
| Darrik has a legitimate opposing duty | Residents' safe rest is prioritized over keeping memorial stones in an active wall | Drafted, review pending |
| Five source encounters have separate identities and framing | Three reports from Orven; two from Kelna, with clear provenance limits | Drafted; five full source texts compared |
| No magical prophecy or global solution | Local craft record trail; Skyland and elsewhere remain independent | Drafted, review pending |
| Narration remains understandable without production cues | Main prose files contain headings and natural scene breaks, no editorial metadata | Structural check pending |
| Physical form of Grimnir respects world archive | Mineral body, seam fractures, geomantic care, prepared mineral nourishment | Source-informed adaptation, conflict recorded |
| Chapter 2 connects to chapter 3 | A council-authorized search and forthcoming trade descent to the roads below | Drafted, geography check remains |
| Independent prose/editing review | No second editor or human approval recorded | **Not completed** |
| Audio and narration production | No generated recording or voice master | **Not started** |

## Matters for manuscript revision

1. **First chapter length and pacing:** Chapter 1 is a complete dramatic chapter, but its measured entry and lengthy craft discussion should be judged aloud, not merely on a page.
2. **Testimony density:** Chapter 2 adapts five cases through spoken reports. An audio edit must preserve each person's specific danger and the present council's tension, not simply enumerate names.
3. **Skyland record provenance:** The transport-ledger symbol is only a circumstantial lead. Chapter 11 may corroborate a composite memorial sketch but must not turn the Chapter 2 mark into conclusive proof retroactively.
4. **Convergence timing:** No exact travel interval is yet established. Ensure eventual long-distance travel does not contradict the safe transfer deadline.
5. **Nemi continuity:** A novel-only Grimnir child introduced in Chapter 1 can become the young listener in Chapter 30; this creates a return image, **not an established game person**.
6. **Geographic next scene:** Chapter 3 needs explicit ordinary transfer from Skyland to the Vale when trade descent is possible; no instantaneous drop or geographically invented road.
7. **Original text voice:** The novel is in close third-person past tense, with distinct testimony; the game's encounter standard remains third-person present and stops before player action. These are separate media conventions.

**Pending completion criteria:** human editorial review of these chapters, full continuity check of subsequent chapters, remaining **116** encounter adaptations in actual prose, independent source coverage verification, and a narrator-friendly approved edition. Do not convert a Draft v1 marker to “verified” based solely on this document.
