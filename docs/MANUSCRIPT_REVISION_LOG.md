# Brunti — manuscript revision change and verification log

**Status: editorial change-control ledger.** The audit identifies narrative issues; the [revision plan](MANUSCRIPT_REVISION_PLAN.md) orders the work; this file records **actual** proposals, modifications, checks and remaining gates. Prepared by ChatGPT (GPT-6) under Babuni's creative direction. No source-game/world-canon updates are implied.

| Issue | Planned editorial concern | Status | Verification / reference |
| --- | --- | --- | --- |
| R1 | Tavra/Korrum early name leak (Ch25–28 vs Ch29) | **Draft repaired; targeted check passed; human approval pending** | [Stage 1 review](REVISION_STAGE_1_REVIEW.md) |
| R2 | Convergence access vs premature repair (Ch1–2/29–30) | **Draft repaired; targeted check passed; human approval pending** | [Stage 1 review](REVISION_STAGE_1_REVIEW.md) |
| R3 | Darrik letter provenance | **Draft repaired; targeted check passed; human approval pending** | [Stage 1 review](REVISION_STAGE_1_REVIEW.md) |
| R4 | Nemi's Earthsinger keepsake | **Draft repaired; targeted check passed; human approval pending** | [Stage 1 review](REVISION_STAGE_1_REVIEW.md) |
| R5 | Global travel/calendar anchors | **Open — prose unchanged** | [Chronology ledger](../story/REVISION_CHRONOLOGY_AND_OBJECTS.md) |
| R6 | Durable flaw despite Chapter 20 growth | **Open — prose unchanged** | [Chapter function map](../story/REVISION_CHAPTER_FUNCTIONS.md) |
| R7 | Concrete cost of Chapter 24 Blackwood choice | **Open — prose unchanged** | [Chapter function map](../story/REVISION_CHAPTER_FUNCTIONS.md) |
| R8 | Ordinary recovery chain from Blackwood | **Open — prose unchanged** | [Chronology ledger](../story/REVISION_CHRONOLOGY_AND_OBJECTS.md) |
| R9 | Visible warrior/protector identity | **Open — prose unchanged** | [Chapter function map](../story/REVISION_CHAPTER_FUNCTIONS.md) |
| R10 | Anonymous individuality of memorial owners | **Open — prose unchanged** | [Chapter function map](../story/REVISION_CHAPTER_FUNCTIONS.md) |
| R11 | Secondary rescue, relationships, keepsake payoff | **Open — prose unchanged** | [Chronology ledger](../story/REVISION_CHRONOLOGY_AND_OBJECTS.md) |
| R12 | Sira/Velen/Darrik relationship consequences | **Open — prose unchanged** | [Chapter function map](../story/REVISION_CHAPTER_FUNCTIONS.md) |
| R13 | Late Atranor interlude pacing | **Open — prose unchanged** | [Chapter function map](../story/REVISION_CHAPTER_FUNCTIONS.md) |

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

## How to record subsequent work

For each later revision package add **date, issue IDs, proposal vs selected direction, changed chapter paths, exact Git commit, source-lore revision, passages affected, verification performed, unresolved dependencies and editorial approval status**. Stage completion does not alone imply publication readiness. Preserve the story world's unresolved questions; never silently supply an undocumented solution.
