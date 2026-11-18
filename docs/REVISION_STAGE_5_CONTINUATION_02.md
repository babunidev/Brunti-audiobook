# Stage 5 — continuation B: early-Vale source fidelity and refreshed game text

**18 November 2026 | AI-targeted editorial audit by ChatGPT (GPT-6), under Babuni's direction.** This is a source-to-passage review and limited draft correction, **not** a full-book read, human editorial approval, new game canon, narrator script, or recorded audio.

## Source and counting boundary

- Earlier [Stage 5 targeted semantic ledger](REVISION_STAGE_5_SEMANTIC_REVIEW.md): **54 distinct source IDs** inspected.
- This continuation individually compared **17 additional, previously uninspected IDs in Chapters 3–4**, plus **three newly inspected IDs 20191–20193** in Chapters 10/12. **20190 Veilwalker and special ID 2 Level up! were rechecked but already counted in the original 54.**
- **Current total: 74 of 203 distinct IDs inspected at a targeted semantic level; 129 not yet individually inspected.** The reviewed set still needs a consecutive literary, source-order, canon/atlas and human acceptance pass. Counts must not be interpreted as 74 approvals.
- Latest game source inspected: [Morkahja `2ba61f5a6bcde383ed2a931c3d2a06c87404dffd`](https://github.com/babunidev/Morkahja/blob/2ba61f5a6bcde383ed2a931c3d2a06c87404dffd/server/game/encountersdata.json). Previous Stage 5 game source: [`cf7c285a469ce9db44583e034ec7bf45e272bd84`](https://github.com/babunidev/Morkahja/blob/cf7c285a469ce9db44583e034ec7bf45e272bd84/server/game/encountersdata.json). The intervening comparison found **five `mEncounterText` changes: 20190–20193 and key `00002` (numeric ID 2)**, with no other fields or count changed.
- Compared directly against the book's previous [game baseline `952437c5c59d`](https://github.com/babunidev/Morkahja/blob/952437c5c59da26a2f873f1a18590496f88a2354/server/game/encountersdata.json), the new game source has **37 distinct description-only changes** (20158–20193 and numeric ID 2), **203 original records**, and unchanged encounter metadata, follow-link fields and IDs. Veilwalker 20190 changed twice across those game snapshots.
- The actual source text, assigned [placement matrix](../story/PLACEMENT_MATRIX.md), and the complete relevant [Chapter 3](../manuscript/chapters/03-a-road-made-of-grass.md) and [Chapter 4](../manuscript/chapters/04-letters-without-a-word.md) passages were read together. This comparison is a **scene-hook/fidelity check**, not word-for-word copying or independent line approval.

## A. Seventeen previously unchecked Chapter 3–4 source adaptations

| Encounter | Chapter / mode | Specific source-to-prose evidence | Result |
| --- | --- | --- | --- |
| 20001 Lovely Meadows | 3 / Lived | Uneven green ground, knee-to-shoulder moss stones, pale flowers, birdcalls and unseen creature; a possible buried ridge remains uncertain | Hook present |
| 20002 Enchanted Glades | 3 / Lived | Clear stream over pale stone, deer, fox, tall trees and weathered unreadable pillar marks | Hook present |
| 20003 Fae Pastures | 3 / Lived | Leaning, split and flower-hollow pillars; motion in still grass and a sound like laughter without an assigned maker | Hook present |
| 20004 Mystic Grass | 3 / Lived | Solitary summit pillar and contrary circling grass tested against an upright reed | Hook present |
| 20005 Seraphic Plains | 3 / Lived | Immense cracked pillars, hidden foundations and a low hollow wind-resonance | Hook present |
| 20069 Celestial Fields | 3 / Lived | Butterfly upon white flower, buzzing bees, exposed dark soil and unverified buried-treasure tales | Hook present |
| 20070 Enigmatic Prairies | 3 / Testimony | Trader reports oddly still flowers, northeast hollow, lower second note, mossy tree-stone and momentary delicate light-pattern | Hook present, explicitly attributed |
| 20071 Arcane Meadows | 3 / Testimony | Different traveler recounts shadowed meadow treasure rumor and delayed moving branch; invented silver-box elaboration is exposed as unreliable | Hook present, explicitly attributed |
| 20072 Tranquil Wilds | 3 / Testimony | Eda's autumn fox rests under ochre leaves; one falling leaf touches its ear. Brunti does not suddenly experience autumn during summer travel | Hook present, season protected |
| 20080 Dreamy Valley | 3 / Lived | Pink blossoms, giant boulders, spiraling petals and passage between leaning rocks into cooler sheltered flowers | Hook present |
| 20074 Mysterious Cube | 4 / Archive | Unidentified folio describes seamless translucent cube, edge-crossing symbols, cloudy core and pulsing joined lights; explicitly no proved relation to seven letters | Hook present, source provenance retained |
| 20081 Arcadian Hills | 4 / Lived | Wildflowers uncover deep A on buried stone, root-filled grooves and boundary/treasure uncertainty | Hook present |
| 20085 Bucolic Dale | 4 / Lived | Chasing small animals, one briefly perched upon a J-marked stone, evening petals | Hook present |
| 20086 Captivating Downs | 4 / Lived | Windless rippling grass, unusual distance haze, engraved O and circular motion around rock | Hook present |
| 20087 Radiant Heath | 4 / Lived | Inscribed M, bees and a butterfly perched in its shadowed stroke | Hook present |
| 20088 Mesmerizing Hillsides | 4 / Lived | Small animal vanishes into grass; passing cloud and returning sunlight re-color paired slopes; **no invented eighth letter** | Hook present |
| 20090 Ethereal Glades | 4 / Lived | Petals stay luminous under clouds, cool ground shimmers, fallen leaf's veins appear in borrowed light | Hook present |

**Cross-scene check:** Chapter 4's seven game-letter stones remain **A (20081), H (20083), K (20084), J (20085), O (20086), M (20087), A (20089)** in that narrated order. The already-reviewed H/K/final-A source IDs and Sira's 20186 dance were not double-counted in this package. Chapters 3–4 required **no prose change** in this targeted pass. The Cube is still an archival report rather than the solution.

## B. Five newly changed game descriptions reviewed against existing adaptation

| Encounter | Literary evidence and current-source delta | Editorial result |
| --- | --- | --- |
| **20190 Veilwalker** (already in original 54) | New game prose explicitly makes the being immense, translucent, tree-crown high, with forest distortion, countless floating tendrils and no contact with the ground. Ch10's prior witness understated the body. | **Ch10 corrected**: vast shifting body, distorted distant view, eyes within it, tendrils over flowers and still-air leaf tremor. The witness remains a witness, not an expert on origin. Recheck only, **not** a newly counted ID |
| **20191 Slumbering Ogru** (new review) | Willow, sleeping enormous grey Ogru, open gold pouch; updated source makes one coin slide toward the edge and the snore stop before resuming. | **Ch10 corrected** to stage the coin's movement and snore pause. Brunti still leaves the sleeping being undisturbed |
| **20192 Nereval Elite** (new review) | Game now explicitly shows water channels at the stone gate, interwoven root armor and a displayed winding river rune, and says only bearers of the mark enter. | **Ch12 corrected** for water grooves, armor and visible rune. **Open literary/canon question:** Ch12 uses Brunti's care for the neglected watercourse as its dramatic answer to the guardian's entry demand instead of establishing a literal rune carried by her. This remains a **deliberate novel-only access reinterpretation needing human source-fidelity acceptance**, not a verified game access rule |
| **20193 Joyful Riverkeeper** (new review) | Game adds a river-side elderly Verdani's hearty appetite joke, remembered names and fingers tracing a mark in the tree bark. | **Ch12 corrected** to show the bark mark. Existing Iren/Luma story is novel-only elaboration of his memory and laughter |
| **2 Level up!** (already in original 54) | Former game source `Levelup!` is now a fuller warm metaphor for the growth of experience with a literal **Level Up!** display. | **Ch30 rechecked, no change**: the nonliteral adaptation manifests matured practice, responsibility and Nemi's teaching. No visible RPG text is imposed on the novel; recheck only, **not** newly counted |

**Additional geography caution:** The game calls the Vale–Evergrove edge green/wooded, whereas the pinned world archive places Evergrove's Verdani heartland in a desert/oasis environment. Chapter 12 locates the sanctuary near waterways and **dry lands beyond**, not an invented continuous evergreen Evergrove. A final full atlas/canon comparison remains outstanding.

## C. Verified manuscript change and remaining gate

- Targeted prose edits committed only to **Ch10** and **Ch12**; Chapter 10 changes **5,063 → 5,110 words (+47)** and Chapter 12 **5,485 → 5,508 (+23)** using the existing Unicode-letter/number whitespace-count convention.
- **All 30 chapter files were fetched and recounted** after the corrections: **146,742 words including headings**, up from the prior 146,672 (**+70**). No chapter or source-ID placement was added or deleted.
- The previous [54-ID semantic review](REVISION_STAGE_5_SEMANTIC_REVIEW.md) and the automated [203 locator candidates](STAGE_5_ENCOUNTER_LOCATORS.md) remain their own historical evidence categories. This review does not retroactively turn locator matches into semantic approvals.
- **Open:** 129 source IDs still lack an individual targeted semantic reading; 109 scene-brief-to-prose context checks, comprehensive world/atlas distances, full uninterrupted read and read-aloud, independent human acceptance, narration/rights and recording remain outstanding. The Nereval entrance reinterpretation is a specific human editorial decision point, not an automatically resolved contradiction.

**Status: Stage 5 IN PROGRESS. No approval, audio rendering, deployment or publication claimed.**

## D. Repository verification after this package

On the audiobook `main` revision `b4a7d34ff906962b5c251630e2c01c135d1610fe`, the connected GitHub repository tree was retrieved with `recursive=1` and was not truncated. The 12 newly created or edited documentation/index Markdown files in this package were reopened and their **562 local relative Markdown link destinations** resolved against the current tree: **0 missing paths**. This path-existence check does not validate heading fragments, external sites, prose quality, narration, or previously unchanged Markdown links. All 30 chapters were fetched separately for the **146,742-word recount**. The Stage 5 acceptance gate remains open.
