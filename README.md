# Brunti — a Morkahja audiobook project

**Working title:** *Brunti*  
**Creative:** Babuni  
**Stage:** 3 — 30/30 draft chapters; Stages 1–4 targeted prose edits completed, Stage 5 verification IN PROGRESS; independent review outstanding; audio production under way, one episode at a time  
**Format:** Fantasy novel and narrated audiobook in progress; **thirty first-draft chapters** and **thirty derived ElevenLabs v3/v4 narration scripts** exist; **Chapters 1–7 are rendered as audio** with a cloned voice in ElevenLabs Studio; **Chapter 1 is published** on Indikin.online; Chapters 2–30 are not published.

Through this project, I am adapting the encounters of [Morkahja](https://github.com/babunidev/Morkahja) into one continuous fantasy journey, led by a young Grimnir warrior named Brunti. The story can draw on an encounter directly, pass it through a traveler's memory, or preserve it as a song, testimony or archived account. Game mechanics need not become the novel's plot.

The existing world lore belongs to [MorkahjaWorld](https://github.com/babunidev/MorkahjaWorld). This repository holds **original literary adaptation and draft prose**, not new game canon. The selected working fiction has not received independent human line-editing or world-canon approval.

## Listen

**Chapter One — Skyland Morning**, the first published episode of the audiobook, streams on [Babuni's Indikin.online page](https://indikin.online/share/storymaker/babuni?v=5.0). Every episode is meant to go out there, one at a time, each after I have listened to it myself. The audiobook will also come to babuni.dev once payments are set up on the site.

## Start here

| File | Purpose |
| --- | --- |
| [Concept](CONCEPT.md) | The book's scope, narrative aim and boundaries |
| [Story bible](story/STORY_BIBLE.md) | Protagonist, canon boundaries and preserved planning history |
| [Story spine](story/STORY_SPINE.md) | Current working premise, concrete conflict and planned resolution |
| [Character arcs](story/CHARACTER_ARCS.md) | Brunti, Darrik, Sira, Velen, relationships and growth |
| [Causal chain](story/CAUSAL_CHAIN.md) | Why each of the 30 chapters leads to the next |
| [Scene plan](story/scenes/README.md) | **109 concrete scene briefs** covering all 203 encounters across the 30 proposed chapters |
| [German literary edition](manuscript/translations/de/README.md) | Stage 1 translation foundation, German style guide, terminology worklist and 30-chapter status register (0 translated) |
| [Manuscript](manuscript/chapters/README.md) | **Chapters 1–30 draft prose** (146,816 counted words; Stages 1–4 targeted revision and Stage 5 map/source fixes); all planned chapters drafted, none independently editorially approved |
| [Manuscript review ledger](docs/MANUSCRIPT_REVIEW.md) · [Chapters 3–4 review](docs/CHAPTERS_03_04_REVIEW.md) · [Chapters 5–6 review](docs/CHAPTERS_05_06_REVIEW.md) · [Chapters 7–8 review](docs/CHAPTERS_07_08_REVIEW.md) · [Chapter 9 review](docs/CHAPTER_09_REVIEW.md) · [Chapter 10 review](docs/CHAPTER_10_REVIEW.md) · [Chapter 11 review](docs/CHAPTER_11_REVIEW.md) · [Chapter 12 review](docs/CHAPTER_12_REVIEW.md) · [Chapter 13 review](docs/CHAPTER_13_REVIEW.md) · [Chapter 14 review](docs/CHAPTER_14_REVIEW.md) · [Chapter 15 review](docs/CHAPTER_15_REVIEW.md) · [Chapter 16 review](docs/CHAPTER_16_REVIEW.md) · [Chapter 17 review](docs/CHAPTER_17_REVIEW.md) · [Chapter 18 review](docs/CHAPTER_18_REVIEW.md) · [Chapter 19 review](docs/CHAPTER_19_REVIEW.md) · [Chapter 20 review](docs/CHAPTER_20_REVIEW.md) · [Chapter 21 review](docs/CHAPTER_21_REVIEW.md) · [Chapter 22 review](docs/CHAPTER_22_REVIEW.md) · [Chapter 23 review](docs/CHAPTER_23_REVIEW.md) · [Chapter 24 review](docs/CHAPTER_24_REVIEW.md) · [Chapter 25 review](docs/CHAPTER_25_REVIEW.md) · [Chapter 26 review](docs/CHAPTER_26_REVIEW.md) · [Chapter 27 review](docs/CHAPTER_27_REVIEW.md) · [Chapter 28 review](docs/CHAPTER_28_REVIEW.md) · [Chapter 29 review](docs/CHAPTER_29_REVIEW.md) · [Chapter 30 review](docs/CHAPTER_30_REVIEW.md) | Drafted encounters, lore tensions, source-check evidence and editorial gaps |
| [Continuity register](docs/SCENE_CONTINUITY.md) | Source-confirmed constraints, scene-level safeguards and unresolved travel/lore checks |
| [Encounter atlas](story/ENCOUNTER_ATLAS.md) | All 203 source encounters, IDs, source groups, narrative categories and tracking |
| [Character dossier](story/CHARACTERS.md) | Brunti's game-data identity and proposed fiction |
| [Structural overview](story/STRUCTURE.md) · [30-chapter outline](story/OUTLINE_V1.md) | Five movements with proposed chapter briefs, not approved prose |
| [Encounter placements](story/PLACEMENT_MATRIX.md) | One proposed chapter, mode and literary function for each of the 203 encounters |
| [Literary survey](story/LITERARY_SURVEY.md) | Scene functions, atmosphere, and outstanding canon checks |
| [Source reconciliation](docs/SOURCE_RECONCILIATION.md) | Change audit between initial encounter index and current reviewed game prose |
| [Sources](docs/SOURCES.md) | Specific game and world references, revision identifiers, and artwork paths |
| [Content method](docs/CONTENT.md) | Encounter mapping rules, coverage evidence and explicit follow sequences |
| [Roadmap](ROADMAP.md) | Steps and what is complete versus deferred |
| [Whole-manuscript story audit](docs/WHOLE_MANUSCRIPT_STORY_AUDIT.md) | Found plot and continuity issues; targeted Stage 1–4 draft repairs implemented, final close-read still pending |
| [Manuscript area](manuscript/chapters/README.md) | Where eventual chapters will live |
| [Audio workflow](production/README.md) · [30 ElevenLabs v3/v4 chapter scripts](production/scripts/eleven-v3-v4/README.md) · [Narration guide](production/ELEVENLABS_V3_V4.md) | Separate chapter text with 271 scene-pause cues, 30 ending cues and 53 selective vocal-performance tags; rendered audio and timed joins not yet verified |

The [documentation guide](docs/DOCUMENTATION.md), [project rules](AGENTS.md), [decision log](docs/DECISIONS.md), [development journal](docs/DEVLOG.md), and [changelog](CHANGELOG.md) keep the work traceable.

## Source boundaries

The encounter atlas was indexed from `Morkahja/server/game/encountersdata.json` at commit `58576f063627752f77cdf99514baad875d509114`; later game sources changed **19**, then **5**, then **1**, then **2**, then **1**, then **1**, then **8**, then **5**, then **5**, then **4**, then **2**, then **8**, then **2**, then **4**, then **2**, then **5**, then **2**, then **2**, then **2**, then **7**, then **2**, then **6**, then **4** additional encounter descriptions and were [reviewed and reconciled where already drafted](docs/SOURCE_RECONCILIATION.md). The current reviewed literary baseline is `952437c5c59da26a2f873f1a18590496f88a2354`. It remains the source coverage ledger. The [scene plan](story/scenes/README.md) assigns all 203 records to specific scenes. **All 203** distinct source encounters have now been adapted into first-draft prose in Chapters 2–28 and 30, with Chapter 29 providing original connecting fiction. **0 remain planned and 0 have received independent editorial verification.** No encounter adaptation has passed independent editorial approval. World facts are checked against `MorkahjaWorld`; proposals in this repository never override that archive.

**Current limits:** A 30-chapter working story direction and cast now exist under delegated creative drafting, but they remain **novel-only fiction**, not additions to Morkahja canon or an editorially completed manuscript. The title is provisional, the existing poster has not been imported, and there is no final reviewed manuscript or media-rights clearance. Chapter 1 is the only published audio so far.

## Editorial revision status — 19 November 2026

**30 draft novel chapters · 146,816 counted words including headings · 203/203 distinct source encounters individually compared to their manuscript passages · 0 independent human editorial approvals.** Targeted [Stage 1 continuity](docs/REVISION_STAGE_1_REVIEW.md), [Stage 2 causality/chronology](docs/REVISION_STAGE_2_REVIEW.md), [Stage 3 pacing](docs/REVISION_STAGE_3_REVIEW.md) and [Stage 4 emotional continuity](docs/REVISION_STAGE_4_REVIEW.md) drafts remain internally verified, not final signed-off prose.

**Stage 5: source-scene comparison milestone completed; final editorial gate remains OPEN.** The [first semantic review](docs/REVISION_STAGE_5_SEMANTIC_REVIEW.md) checked **54** unique encounter IDs, [continuation B](docs/REVISION_STAGE_5_CONTINUATION_02.md) added **20**, [C (Ch5–8)](docs/REVISION_STAGE_5_CONTINUATION_03.md) added **34**, [D (Ch9–14)](docs/REVISION_STAGE_5_CONTINUATION_04.md) added **21**, [E (Ch15–20)](docs/REVISION_STAGE_5_CONTINUATION_05.md) added **48**, and [F (Ch2 and Ch21–25)](docs/REVISION_STAGE_5_CONTINUATION_06.md) completed the **final 26**. **203/203 original encounter descriptions have now been individually compared against their actual first-draft novel adaptations** at current game source `2ba61f5a6bc`; none remain unchecked at this *targeted* level. The current game has 37 description-only changes against literary baseline `952437c5c59d`, and none of the last 26 source objects changed.

**Approved source and adaptation policy:** Babuni explicitly allows compatible older lore to survive newer game encounter readability rewrites, while material creature identity, scale, form and behavior changes still demand comparison. The novel's Nereval watercourse-healing entry is approved as literature, supported by established world lore and game follow `19001`; it does **not** change live game `20192` or imply independent approval of the entire Chapter 12. See [Decisions](docs/DECISIONS.md).

**Latest manuscript edits:** At Babuni's explicit direction, the three [map-route orientation issues](docs/REVISION_STAGE_5_MAP_ROUTE_AUDIT.md) are now implemented in prose: Chapter 14 clarifies the **Ohgar→Vale southern approaches→east to Karrhu** multi-day caravan journey (+27 words); Chapter 17 names the **Karrhu northern crossings→outer Vale waystations→mountain trade routes** (+51), keeping Cliffs of Sarga geographically unplaced; Chapter 28 replaces a misleading **“northbound caravan”** with an explicit **upland Skyland landing-route destination** (+5). Earlier Ch22/25 copyedits and Ch17's Ressa/Orena distinction remain in force. **All 30 chapters were refetched and recounted at 146,816 words** (+83). No plot outcomes, source encounters or game/world canon changed.

**Stage 5 not yet accepted:** Full consecutive line-by-line literary read, [109 scene-brief](story/scenes/README.md) function comparison, complete atlas/canon/relative travel checks, real read-aloud/performer listening assessment (Ch5/7/13/16/20/24 density watchlist), and separate human final editorial approval are outstanding. **Narrator-ready scripts, media-rights clearance and game/world canon amendments are not claimed; apart from the published Chapter 1 episode, no audio is released.**
