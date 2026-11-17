# Source reconciliation — 17 November 2026

During Stage 2, the game repository's encounter JSON changed after the first source index was pinned. A direct comparison was made between:

- **Initial atlas source:** [`58576f063627`](https://github.com/babunidev/Morkahja/blob/58576f063627752f77cdf99514baad875d509114/server/game/encountersdata.json), JSON blob `10c493c35d9c82e3a3f0e7776d2b5b9d0ca65358`.
- **Newer current source reviewed:** [`5b0d73e550ca`](https://github.com/babunidev/Morkahja/blob/5b0d73e550ca123adcb095b45febeba4330a9fdf/server/game/encountersdata.json), JSON blob `1e67cc21a5cfb16b299d417e25082935b472abd7`.

## Verified differences

Both snapshots contain **203 encounters**, with identical IDs, titles, gameplay metadata and explicit follow-link relationships. Exactly **19** IDs have a different `mEncounterText` string; **no other field differed** in the JSON comparison:

`20056 · 20057 · 20058 · 20059 · 20060 · 20061 · 20062 · 20063 · 20064 · 20065 · 20066 · 20067 · 20068 · 20069 · 20070 · 20072 · 20073 · 20074 · 20075`

The descriptions retain their broad characters or places. A particularly important difference occurs in **20070 — Enigmatic Prairies**, where the earlier wandering-landscape/treasure rumor has been replaced with **soft notes, still flowers and a luminous moss-covered stone**. Its specific literary hook in the placement matrix has been updated accordingly. Other entry descriptions should still be rechecked in full when constructing chapter prose, especially Grimnir physiology, Evergrove geographical language and whether a line states fact or rumor.

## Status and limits

The original 203-row [source atlas](../story/ENCOUNTER_ATLAS.md) is preserved as an index created against the initial snapshot; its metadata-driven categories and counts remain valid under the later source. The [placement matrix](../story/PLACEMENT_MATRIX.md) now points to the newer text baseline and still covers all 203 unique IDs. No world canon or game files were altered by this audiobook project.

The reconciliation is a **structural and text-field comparison**, not a complete literary close edit of the 19 replacements, a confirmation of runtime game state, or a guarantee that the game will not change after the reviewed commit. New source updates require another deliberate reconciliation.

## Second source update — 17 November 2026

A subsequent comparison of [game commit `5b0d73e550ca`](https://github.com/babunidev/Morkahja/blob/5b0d73e550ca123adcb095b45febeba4330a9fdf/server/game/encountersdata.json) (blob `1e67cc21a5cfb16b299d417e25082935b472abd7`) against the later [game `e0bc99c51c74`](https://github.com/babunidev/Morkahja/blob/e0bc99c51c74bb088f27a8252082b41c61629cf7/server/game/encountersdata.json) (blob `d447c5e73729b05d04f15f17a5eabe958cb00a04`) found **five more records changed**, again **only `mEncounterText`**. All **203** IDs, titles, other fields and follow links remained identical.

| ID | Name | Prose change relevant to adaptation |
| ---: | --- | --- |
| 20076 | Aevis Merchant | Expanded the Celesterra-threshold stall and keepsake story; remains an independently reported visit in chapter 9 |
| 20077 | Quicksilver Quagmire | More detailed uncanny stars and reflection; chapter 15 must not frame them as certain prophecy |
| 20078 | Unhinged Gobbl | More detailed bodily distortion and gestures; chapter 22 remains an observed individual |
| 20079 | Fearfeaster Gobbl | A stronger account of vegetation-like limbs and apparent appetite for fear; chapter 22 preserves separate testimony |
| 20080 | Dreamy Valley | More detailed hidden passage among pink blossoms and great rocks; chapter 3 scenic cue was updated |

**Current literary scene-input baseline:** `e0bc99c51c74bb088f27a8252082b41c61629cf7`. The original atlas remains historically pinned, and no game files were modified. If game `main` advances again, the working edition requires another explicit comparison, not silent rewriting.

## Third source update — 17 November 2026

The subsequent [game `main` at `13a5d134c8e6`](https://github.com/babunidev/Morkahja/blob/13a5d134c8e63855894436e4f1b09910c5c50b95/server/game/encountersdata.json) had encounter JSON blob `71f490d7ef70f916c896e6f3f78fe247ccfd8a34`. A full per-ID, per-field comparison against `e0bc99c51c74` (blob `d447c5e73729b05d04f15f17a5eabe958cb00a04`) found **one more prose-only change**:

- **20081 — Arcadian Hills:** expanded the wildflowers concealing the engraved **A**, the roots following its lines, the buried border marker and old treasure tales. No letter value changed, and Chapter 4's plan still respects the clue.

Both sources contain exactly **203 encounters**. No record ID, title, follow link or gameplay metadata changed. The five encounters in the **Chapter 2 manuscript draft** (20015, 20018, 20055, 20056, 20128) were unchanged. The literary working source baseline is now `13a5d134c8e63855894436e4f1b09910c5c50b95`.

**Original atlas remains pinned to its historical source snapshot.** This update is source comparison, not a full literary re-edit of all 203 descriptions. The game repository has not been modified.

## Fourth source update — 17 November 2026

A per-ID per-field comparison between [game `13a5d134c8e6`](https://github.com/babunidev/Morkahja/blob/13a5d134c8e63855894436e4f1b09910c5c50b95/server/game/encountersdata.json) (blob `71f490d7ef70f916c896e6f3f78fe247ccfd8a34`) and [game `096c99bdf5ac`](https://github.com/babunidev/Morkahja/blob/096c99bdf5ac8af5174b26a337914f573263ab72/server/game/encountersdata.json) (blob `04403ba5be5a3e00501d8c3078edde0b5edc9557`) found exactly **two additional `mEncounterText` changes**, with **203 unchanged IDs, titles and other fields**.

- **20082 — Alluring Fens:** revised and expanded the delicate singing across mist, black water, mossy trees and distant shifting melody. This remains planned for Chapter 15; use the updated description there.
- **20083 — Enchanted Gardens:** expanded flower and twilight atmosphere; the deliberate **H** remains unchanged, but a **solitary note** now follows the garden's brief silence after the magical flicker. The drafted [Chapter 4](../manuscript/chapters/04-letters-without-a-word.md) was amended accordingly, without changing letter order or explanation.

The cumulative literary source-review differences from the atlas are **19 + 5 + 1 + 2**, all prose-only at their respective updates. Current reviewed source baseline: `096c99bdf5ac8af5174b26a337914f573263ab72`. The 24 encounter descriptions drafted in Chapters 5 and 6 were read from this same revision. Neither the original game nor the established world repository was changed by audiobook development.

## Fifth source update — 17 November 2026

The game `main` at [`734f439b1699`](https://github.com/babunidev/Morkahja/blob/734f439b1699ac144909462d31ca3e045cb4d811/server/game/encountersdata.json) had encounter JSON blob `99ce4bf061d0870353db7246d531889e372fa7f8`. A complete per-ID, per-field comparison against game [`096c99bdf5ac`](https://github.com/babunidev/Morkahja/blob/096c99bdf5ac8af5174b26a337914f573263ab72/server/game/encountersdata.json) (blob `04403ba5be5a3e00501d8c3078edde0b5edc9557`) found **one additional text-only change**:

- **20084 — Mystical Vale:** expanded summer landscape, long shadow of the huge boulder, returning cloud, and the old carved **K**. The letter itself and all game metadata remain unchanged. [Chapter 4](../manuscript/chapters/04-letters-without-a-word.md) now explicitly notes the long shadow and cloud crossing; its word count rose from **3,714 to 3,741**.

**All 203 encounter records and other fields remained unchanged.** Running cumulative changed prose counts compared to the source atlas: **19 + 5 + 1 + 2 + 1**, with latest literary baseline `734f439b1699ac144909462d31ca3e045cb4d811`. The five Chapter 9 encounter descriptions were read in full against this baseline and did not change during the diff. Game and world source repositories were not modified.

## Sixth source update — 17 November 2026

The game `main` at [`ad34afb686ef`](https://github.com/babunidev/Morkahja/blob/ad34afb686efa017cd43ffeccc554afb43d79b22/server/game/encountersdata.json) had encounter JSON blob `b0a3c99ad5ec5ac5f898fac6039c9aee9de8bc67`. A complete per-ID, per-field comparison against [`734f439b1699`](https://github.com/babunidev/Morkahja/blob/734f439b1699ac144909462d31ca3e045cb4d811/server/game/encountersdata.json) (blob `99ce4bf061d0870353db7246d531889e372fa7f8`) found **one `mEncounterText` change**:

- **20085 — Bucolic Dale:** the revised description specifically shows **two small creatures playing**; one scrambles onto the **J**-inscribed half-buried stone, then leaps away and scatters petals, while a larger creature grazes nearby. The carved **J** remains unchanged. [Chapter 4](../manuscript/chapters/04-letters-without-a-word.md) now dramatizes that action and keeps the **A H K J O M A** sequence. The updated Chapter 4 is **3,776 words including its heading**.

Both snapshots have **203** identical records/IDs; **no other metadata or follow-link changed**. Game encounter **20188** continues to follow to **19444**, and Chapter 10 respects this order. Cumulative newer `mEncounterText` differences compared in successive game updates: **19 + 5 + 1 + 2 + 1 + 1**. Current source baseline: `ad34afb686efa017cd43ffeccc554afb43d79b22`. Neither the game nor established world repositories were changed by this audiobook work.

## Seventh source update — 17 November 2026

Game `main` advanced from [`ad34afb686ef`](https://github.com/babunidev/Morkahja/blob/ad34afb686efa017cd43ffeccc554afb43d79b22/server/game/encountersdata.json) (blob `b0a3c99ad5ec5ac5f898fac6039c9aee9de8bc67`) to [`e826fa46d3ff`](https://github.com/babunidev/Morkahja/blob/e826fa46d3ff3f27628eec54ebfd193b597f731a/server/game/encountersdata.json) (blob `759c149c73e14cab98d941b44ca879a78f8b32ea`). Full 203-ID and per-field comparison found **eight changes, all to `mEncounterText`**: **20086, 20087, 20088, 20089, 20090, 20091, 20092 and 20093**. No record IDs, titles, metadata or `mEncounterFollow` fields changed. All eight source descriptions were read in full.

- **20086 Captivating Downs:** wind falls silent while a ribbon of grass moves in sequence, circular motion around the stone bearing **O** and distance-muddling haze. [Chapter 4](../manuscript/chapters/04-letters-without-a-word.md) adds those details; **O unchanged**.
- **20087 Radiant Heath:** bees, butterflies and wildflowers, with butterfly alighting in the **M** stroke and opening golden wings. Chapter 4 adds the specific motion; **M unchanged**.
- **20088 Mesmerizing Hillsides:** a small creature briefly pauses with ears raised before disappearing down the grass, and the cloud shadow climbs off the hillsides. Chapter 4 gives the creature's movement more specificity. This encounter **still has no carved letter**.
- **20089 Magical Glens:** a moss-edged rock bearing **A**, leaves murmuring, light remaining bright even as clouds shift, faint earth vibration and second patch without visible canopy opening. Chapter 4 adds the light's independence and moss detail; **A unchanged**.
- **20090 Ethereal Glades:** cool, luminous flowers, a pale near-root radiance and a falling leaf whose veins show briefly before the light fades. Chapter 4 adds the leaf action.
- **20091 Nagar Berserk:** tusks, violent charge, flying earth, hot breath and lowered head. [Chapter 5](../manuscript/chapters/05-the-lives-of-the-vale.md) enriches Mara's *attributed description* without turning the encounter into a new on-scene fight.
- **20092 Nagar Boar:** mottled boar's watchful eyes, flared nostrils, tusks catching vegetation, hoof pressure and muscles tightening. Chapter 5 gives these features to Mara's account.
- **20093 Bonecrusher:** pale scarred hide, worn horn edges, red eyes, branch breaking under hoof and lowered head. Chapter 5 includes those movements in Mara's testimony.

**Manuscript reconciliation word counts:** Chapter 4 **3,776 → 3,895**, Chapter 5 **3,825 → 3,900** including headings. The seven inscribed letters retain **A H K J O M A**; their established positions and undetermined meaning remain unchanged. Combined **+194** words. This source update was **not** a revision to the other 195 records, and the literature remains a novel adaptation, not a change to Morkahja's game or world canon.

Successive game prose change counts: **19 + 5 + 1 + 2 + 1 + 1 + 8**; latest reviewed baseline `e826fa46d3ff3f27628eec54ebfd193b597f731a`. Chapter 14's four Ohgar encounters have no changes relative to the preceding source but were reread from the latest game snapshot.

## Eighth source update — 17 November 2026

Game `main` advanced from [`e826fa46d3ff`](https://github.com/babunidev/Morkahja/blob/e826fa46d3ff3f27628eec54ebfd193b597f731a/server/game/encountersdata.json) (blob `759c149c73e14cab98d941b44ca879a78f8b32ea`) to [`92b97aef8706`](https://github.com/babunidev/Morkahja/blob/92b97aef8706dabfcd8d8d80c0477a70e3336097/server/game/encountersdata.json) (blob `a4c32c0cdba89bb6e6cd80e635ba5f8a7ec82744`). A full per-record/per-field comparison of all 203 IDs found **exactly five changed fields**, each `mEncounterText` for encounter **20094, 20095, 20096, 20097, 20098**. All other encounter fields, IDs and follow links were unchanged.

- **20094 — Nagar Humpback:** enormous rounded hump, tusk catches low branch between trees, impatient head twist frees it and showers leaves over hide, heavy uneven hooves shifting stones. Mara's **attributed testimony in Chapter 5** now includes this specific branch incident.
- **20095 — Nagar Razorback:** jagged horn ridge, swift turn around a **fallen trunk** with hind feet digging into earth and dust thrown backward. Chapter 5's **attributed testimony** now includes that movement without claiming an on-page fight.
- **20096 — Thunderhoof:** windless pebbles tremble ahead of slow, deliberate hoofbeats; twig snaps; animal turns and holds one hoof suspended before its fall makes the bank shed grit. Chapter 5's testimony now depicts the distinctive restrained force.
- **20097 — Yowler:** mottled grey-brown wolf stands on narrow outcrop, gives two ragged cries and receives broken echoes; ears turn in different directions, pale eyes search the valley and a low growl follows. Chapter 5's **direct scene** now shows those actions without merging Yowler and Silvermane.
- **20098 — Common Chest:** small **acorn** taps scratched dark polished lid beneath an old tree; smooth-worn tarnished brass lock, fine **spiderweb**, narrow keyhole and unopened interior. [Chapter 7](../manuscript/chapters/07-things-that-are-kept.md) now includes these new details and leaves the chest locked/unclaimed.

**Count effect:** [Chapter 5](../manuscript/chapters/05-the-lives-of-the-vale.md) **3,900 → 4,044** words including heading; Chapter 7 **3,504 → 3,554**. Combined +**194** words. The six Chapter 15 sources are **unchanged** compared with the prior game baseline, but all were reread from current game text. Previous seven-letter sequence **A H K J O M A**, encounter delivery modes, provenance and existing canon remain unchanged.

**Cumulative later game prose differences (successive revisions): 19 + 5 + 1 + 2 + 1 + 1 + 8 + 5**. Current reviewed baseline `92b97aef8706dabfcd8d8d80c0477a70e3336097`. No game or world files were changed in the novel repo.

## Ninth source update — 17 November 2026

Game `main` advanced from [`92b97aef8706`](https://github.com/babunidev/Morkahja/blob/92b97aef8706dabfcd8d8d80c0477a70e3336097/server/game/encountersdata.json) (blob `a4c32c0cdba89bb6e6cd80e635ba5f8a7ec82744`) to [`525d26bc8b4d`](https://github.com/babunidev/Morkahja/blob/525d26bc8b4d745ca0e4e7c2b3c86c20d9829df6/server/game/encountersdata.json) (blob `1ae39adad0dc6ef0c09a84b8a9c9cd0868fe766b`). Full comparison of **203 JSON records, every known field** found exactly **five `mEncounterText`-only changes**: **20099, 20100, 20101, 20102, 20103**. Record IDs, titles, descriptions of the other 198, follow links, metadata and expansion associations were unchanged.

- **20099 Cliffs of Sarga:** more explicitly harmonious two-note cliff chorus, falling stones echoing down a fissure, wind stopping then sounding again. **Chapter 17 still planned**; use the revised description during drafting.
- **20100 Mountain Pass:** high sea of clouds below jagged icy passage, snow-blown dark fissure at a sheltered bend and old hoard tale. **Chapter 17 still planned**; read this current description before authoring.
- **20101 Rocks of Ohgar:** specifically deep ground-traveling groan, immense weathered monoliths, continuously inward-moving sand beneath an enormous formation, dark cleft and old treasure rumors. [Chapter 14](../manuscript/chapters/14-words-in-the-sand.md) already contained nearly all these details; its monolith scene was **updated with a continuing inward fall of sand beneath the immense stone**. Length **4,828 → 4,853** words including heading.
- **20102 Frostwind Slopes:** frozen river in a sunlit valley, narrow ledge grotto exposed by gust and **faint crystalline ticking** within. **Chapter 17 planned**.
- **20103 Strange Boulder:** moss on precariously balanced boulder, strange **warm floral fragrance** drawn from concealed opening under immense weight, green valley far below. **Chapter 17 planned**.

**All twelve Chapter 16 source encounters `20019–20030` were unchanged** and fully reread at latest `525d26bc8b4d`; each is authored as separately identifiable **Archive** content. No game or world repo edit was performed.

**Historical cumulative game prose change counts: 19 + 5 + 1 + 2 + 1 + 1 + 8 + 5 + 5**. The four future Chapter 17 sources were *reviewed for changes*, **not yet placed in manuscript prose**; do not mark them drafted. Seven carved letters remain **A H K J O M A**.

## Tenth source update — 17 November 2026

The game `main` at [`92cd8dc140c5`](https://github.com/babunidev/Morkahja/blob/92cd8dc140c5a73fce11f8ad3b5d87a488b3fd7b/server/game/encountersdata.json) has encounter JSON blob `ec27f8ef04095906ab811f3a21aa2378dfe48d46`. Comparing all **203 records and every field** with the [prior reviewed `525d26bc8b4d`](https://github.com/babunidev/Morkahja/blob/525d26bc8b4d745ca0e4e7c2b3c86c20d9829df6/server/game/encountersdata.json) (blob `1ae39adad0dc6ef0c09a84b8a9c9cd0868fe766b`) found **exactly four changed `mEncounterText` fields**. No encounter ID, title, expansion, follow link or other metadata changed.

- **20104 Sudden Rockslide:** more detailed fracture racing through the upper cliff, boulders, snow and dust; belongs to **Chapter 18**, still planned. Chapter 17's ice-shelf failure is independent novel fiction and does **not** count 20104.
- **20105 The Giant:** more explicit vertical monolith, person-like weathering, hollow resonance, cloud/light and falling stone; integrated in [Chapter 17](../manuscript/chapters/17-the-mountain-has-a-voice.md) without making the formation animate.
- **20106 Sarga Lioness:** expanded tawny movement, green eyes, separately turning ears, raised forepaw and pebble; integrated into Chapter 17 with an original noncanonical hare pursuit and a safe retreat.
- **20107 Silver Wolf:** expanded silver-furred she-wolf at northern Vale / southeastern Keldor wooded boundary, still belonging to **Chapter 21**; not drafted here.

All eleven Chapter 17 encounters were reread at this baseline and integrated as distinct Lived scenes. The game/world sources were not edited. **Current reviewed source baseline: `92cd8dc140c5a73fce11f8ad3b5d87a488b3fd7b`**. Across successive reconciliations: **19 + 5 + 1 + 2 + 1 + 1 + 8 + 5 + 5 + 4** prose-only revisions. See [Chapter 17 source and continuity review](CHAPTER_17_REVIEW.md).
