# Brunti — manuscript revision change and verification log

**Status: editorial change-control ledger.** The audit identifies narrative issues; the [revision plan](MANUSCRIPT_REVISION_PLAN.md) orders the work; this file records **actual** proposals, modifications, checks and remaining gates. Prepared by ChatGPT (GPT-6) under Babuni's creative direction. No source-game/world-canon updates are implied.

| Issue | Planned editorial concern | Status | Verification / reference |
| --- | --- | --- | --- |
| R1 | Tavra/Korrum early name leak (Ch25–28 vs Ch29) | **Open — prose unchanged** | [Audit A1](WHOLE_MANUSCRIPT_STORY_AUDIT.md) |
| R2 | Convergence access vs premature repair (Ch1–2/29–30) | **Open — prose unchanged** | [Audit A2](WHOLE_MANUSCRIPT_STORY_AUDIT.md) |
| R3 | Darrik letter provenance | **Open — prose unchanged** | [Chronology / correspondence ledger](../story/REVISION_CHRONOLOGY_AND_OBJECTS.md) |
| R4 | Nemi's Earthsinger keepsake | **Open — prose unchanged** | [Knowledge and objects ledger](../story/REVISION_CHRONOLOGY_AND_OBJECTS.md) |
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

## How to record subsequent work

For each later revision package add **date, issue IDs, proposal vs selected direction, changed chapter paths, exact Git commit, source-lore revision, passages affected, verification performed, unresolved dependencies and editorial approval status**. Stage completion does not alone imply publication readiness. Preserve the story world's unresolved questions; never silently supply an undocumented solution.
