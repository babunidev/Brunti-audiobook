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

## Eleventh source update — 17 November 2026

At [Morkahja `e8fbfc67cbb4`](https://github.com/babunidev/Morkahja/blob/e8fbfc67cbb487df4652b055f21afbc086676ff0/server/game/encountersdata.json) the 203-record encounter file has blob `6be97e1141f00c3c7b1c86577937ba09c0d9b291`. Comparing all 203 IDs and every record field with the previous pinned [`92cd8dc140c5`](https://github.com/babunidev/Morkahja/blob/92cd8dc140c5a73fce11f8ad3b5d87a488b3fd7b/server/game/encountersdata.json) (blob `ec27f8ef04095906ab811f3a21aa2378dfe48d46`) found **exactly two `mEncounterText`-only differences**:

- **20108 — Shena Alpha:** expanded moonlit mossy hillock scene and wolf posture where Ethera's Vale meets Keldor; remains assigned to unwritten **Chapter 21**, not retroactively included.
- **20109 — Embersnout:** expanded Frostwind wolf movement on exposed ice: audible claw scrape, one forepaw raised on hearing a noise, ears and head turning, watchful eyes, needle-like teeth and lingering pale breath. [Chapter 17](../manuscript/chapters/17-the-mountain-has-a-voice.md) was amended accordingly from **4,639 to 4,683 words** with its existing **eleven encounter IDs unchanged**.

No record IDs, encounter names, expansions, `mEncounterFollow` values or other gameplay fields changed. All **five Chapter 18** assigned descriptions were reread from this current game source and were unchanged relative to the prior baseline. Source-to-novel modes remain **Lived** for 20104, 20123, 20132 and 20176; **Testimony** for 20124. See [Chapter 18 source and continuity review](CHAPTER_18_REVIEW.md). The game and world repositories were not edited by this literary work.

**Cumulative successive text changes:** 19 + 5 + 1 + 2 + 1 + 1 + 8 + 5 + 5 + 4 + 2. **Current reviewed baseline:** `e8fbfc67cbb487df4652b055f21afbc086676ff0`. **Current draft coverage:** 135 adapted / 68 planned of 203.

## Twelfth source update — 17 November 2026

The game `main` at [`fe29096e90ad`](https://github.com/babunidev/Morkahja/blob/fe29096e90ad2f524271a91ceb9cff318ac6b8b0/server/game/encountersdata.json) has encounter-data blob `199d00e37ca66d9311f8c053b5e8cee3da57bd56`. Full comparison of **all 203 records, all fields** with [`e8fbfc67cbb4`](https://github.com/babunidev/Morkahja/blob/e8fbfc67cbb487df4652b055f21afbc086676ff0/server/game/encountersdata.json) (blob `6be97e1141f00c3c7b1c86577937ba09c0d9b291`) found **exactly eight `mEncounterText` changes: 20110–20117**. All 203 IDs, titles, type, elemental, expansion and `mEncounterFollow` fields remain unchanged.

- **20110 Mother Wolf:** expanded cub whimper, round ears, clumsy large paw, mother's protective move and growl. Reconciled in [Chapter 5](../manuscript/chapters/05-the-lives-of-the-vale.md), retaining direct scene, protective behavior and no fight.
- **20111 Young Redeye:** added undignified tumble, asymmetrical ears, butterfly, flower and large sneeze. Reconciled in Chapter 5 without proving kinship to Mother Wolf. Chapter 5 **4,044 → 4,117 words** (+73).
- **20112 Cursed Silvermane:** more detailed involuntary spasm, spectral muzzle-light and rising windless leaves. **Chapter 21 remains planned**, do not mark drafted.
- **20113 Cursed Liani:** expanded cyan-eyed shadow wolf and broken, uninterpretable whispers; distinct from an ordinary Liani Shadowwolf. **Chapter 21 remains planned**.
- **20114 Liani Guardian:** richer emerald glow, measured steps, jade eyes and leaf movement. Reconciled in [Chapter 8](../manuscript/chapters/08-at-the-green-boundary.md), retaining direct protective boundary and no unearned passage.
- **20115 Liani Predator:** more detailed nearly invisible movement through ferns, leaves briefly exposing its back and one lifted paw. Reconciled in Chapter 8 as **Halven's attributed testimony**, not a second live sighting.
- **20116 Aradia's Perch:** metallic buzz, iridescent body, four wings, disturbed pool, curved venom sting and droplet. Reconciled in [Chapter 15](../manuscript/chapters/15-beneath-the-reeds.md) without a sting/venom outcome. Chapter 15 **4,914 → 4,935 words** (+21).
- **20117 Thunderfly Matriarch:** added blue antenna sparks and forceful descending wing gust; reconciled as lived observation in Chapter 8. Chapter 8 **3,131 → 3,192 words** (+61).

**Net +155 words** across already drafted Chapters 5, 8 and 15, **no encounter placement changes**. All seven Chapter 19 source descriptions (**20129, 20130, 20131, 20135, 20136, 20140, 20141**) were fully reread against the newer source and unchanged, including ordered link **20130 → 20131**. Neither game nor world repository was modified by the audiobook project. Current literary source baseline: `fe29096e90ad2f524271a91ceb9cff318ac6b8b0`. Historical cumulative changed prose counts: **19 + 5 + 1 + 2 + 1 + 1 + 8 + 5 + 5 + 4 + 2 + 8**. Manuscript total after Chapter 19: **19 first drafts / 82,606 words including headings / 142 adapted / 61 planned**.

## Thirteenth source update — 17 November 2026

The game encounter file at [`4c7fcc7901f8`](https://github.com/babunidev/Morkahja/blob/4c7fcc7901f87f2b1fbf274e0cd46af49642b90f/server/game/encountersdata.json) has blob `8768959971bfd48a63d03a9c8875e267c52cee79`. Compared with [`fe29096e90ad`](https://github.com/babunidev/Morkahja/blob/fe29096e90ad2f524271a91ceb9cff318ac6b8b0/server/game/encountersdata.json), blob `199d00e37ca66d9311f8c053b5e8cee3da57bd56`, all **203 records and every field** were checked. **Exactly two text-only changes** appeared; IDs, titles, types, elements, expansion flags and follow links remain unchanged.

- **20118 Firecrest Bloodbeak:** the Keldor black rooster's proud strut, proffered scraps, bandit sentinel role, sharp spurs and arrested pre-alarm cry are more richly staged. This encounter remains **planned for Chapter 22**; no assertion that it has been narrated or adapted yet.
- **20119 Simple Treasure:** the meadow's light brown chest shows finely carved wandering figures, trees and old buildings, a gleaming brass lock and narrow shadowed keyhole, with its contents still unseen. ChatGPT (**GPT-6**) reconciled these details in [Chapter 7](../manuscript/chapters/07-things-that-are-kept.md); the chest remains closed and its ownership unclaimed. **Chapter 7 words: 3,554 → 3,601 (+47)**.

The **nine Chapter 20 encounters (20133/20134/20137–20139/20142–20145)** were reread from this new baseline and were unchanged in all fields; their prose draft is separately documented in [Chapter 20 review](CHAPTER_20_REVIEW.md). No game/world repository was edited.

**Historical cumulative text-only changes:** 19 + 5 + 1 + 2 + 1 + 1 + 8 + 5 + 5 + 4 + 2 + 8 + 2. **Current literary source baseline:** `4c7fcc7901f87f2b1fbf274e0cd46af49642b90f`. **Manuscript status:** 20 first drafts, 88,790 words including headings, 151 adapted encounter IDs, 52 still planned, none independently editorially verified.

## Fourteenth source update — 17 November 2026

A complete field-by-field comparison of all **203** game encounter records was performed between [Morkahja `4c7fcc7901f8`](https://github.com/babunidev/Morkahja/blob/4c7fcc7901f87f2b1fbf274e0cd46af49642b90f/server/game/encountersdata.json) (blob `8768959971bfd48a63d03a9c8875e267c52cee79`) and [current `2b4afe761c8b`](https://github.com/babunidev/Morkahja/blob/2b4afe761c8b80f8c0f9414a800fc683ec9b109d/server/game/encountersdata.json) (blob `72ec74d4835f10dce66e70da91ba0188f7955458`). Exactly **four `mEncounterText`-only differences** were found; no IDs, titles, elements, types, `mEncounterFollow` or other metadata changed.

- **20120 Bronze Vault** — expanded metallic ice-strike sound, half-buried bronze, frost-lined engraving, precise nearly invisible lock seam and keyhole. Already [Chapter 17](../manuscript/chapters/17-the-mountain-has-a-voice.md); revised that direct sighting without opening the door.
- **20121 Frost Strider** — stronger enormous shadow, giant-like raised limb, cracked ledges, stone-ice fall and concealed towering summit. Already Chapter 17; revised direct scene without asserting a true living golem.
- **20122 Rocky Tundra** — new yellow grass, skittering pebbles, mossy wind-sheltered hollow with retained sunlight warmth and twitching nose. Already Chapter 17; revised scene without inventing a species. **Chapter 17: 4,683 → 4,819 words (+136 for the three).**
- **20123 Everwinter Trading Post** — expanded stew aroma, wood fire, dried herbs, Rokur keeper's quiet remark, stirring pot and a clean wooden bowl in warm firelight. Already [Chapter 18](../manuscript/chapters/18-the-last-warm-bowl.md); reconciled while keeping Aksa's previously established novel-only name. **Chapter 18: 5,110 → 5,155 words (+45).**

Net **+181 words** to earlier first-draft prose, without changing encounter placements or adding reward outcomes. Five complete **Chapter 21** sources (**20044/20107/20108/20112/20113**) were checked from the newer game baseline, unchanged against prior; previously refreshed **20107/20108/20112/20113** are now written in Chapter 21 with their updated descriptions (the Cursed Liani remains **Testimony**). The game and world repositories were **not changed** by these novel edits.

**Cumulative successive text-only diffs:** 19 + 5 + 1 + 2 + 1 + 1 + 8 + 5 + 5 + 4 + 2 + 8 + 2 + 4. **Current reviewed game commit:** `2b4afe761c8b80f8c0f9414a800fc683ec9b109d`. **Book:** 21 first-draft chapters, 93,538 words including headings, 156 drafted IDs, 47 planned.

## Fifteenth source update — 17 November 2026

A full **203-record, all-field comparison** of the game encounter JSON between [`2b4afe761c8b`](https://github.com/babunidev/Morkahja/blob/2b4afe761c8b80f8c0f9414a800fc683ec9b109d/server/game/encountersdata.json) (blob `72ec74d4835f10dce66e70da91ba0188f7955458`) and [`c227753b59d0`](https://github.com/babunidev/Morkahja/blob/c227753b59d037c6fef66c4b96d181487713e41f/server/game/encountersdata.json) (blob `e611d3dd676776ff494dfa35bb32edf8f61a8f6d`) found **exactly two `mEncounterText` differences**, with every other ID, title, expansion, element, type and follow metadata unchanged.

- **20124 Frostfang Alpha** — expanded two piercing blue eyes in drifting snow, powder falling from immense white shoulders, ears tracking the slopes, pale breath, deep commanding howl/echo, long fangs and wide paws. Already adapted as **Aksa's report of a courier's testimony** in [Chapter 18](../manuscript/chapters/18-the-last-warm-bowl.md); the source description was reconciled in that narrated report without inventing a personal sighting or battle. **Chapter 18: 5,155 → 5,193 words (+38).**
- **20125 Raided Verdani Village** — expanded soot-darkened survivor retrieving a small wooden keepsake from collapsed timbers, nearby path-clearing survivors, elder tree with gathered belongings, and still-unsafe beams. Already adapted directly in [Chapter 13](../manuscript/chapters/13-after-the-raid.md); reconciled the keepsake rescue and placement under the unharmed elder tree. The village's raid account remains attributed to its survivors, and their rebuilding continues. **Chapter 13: 5,482 → 5,526 words (+44).**

Net **+82 words** to previously drafted Chapters 13/18; no changes to the encounter assignment ledger. All five current Chapter 22 encounters (**20075, 20078, 20079, 20118, 20155**) were reread and are **unchanged** against the previous reviewed game source; prior Firecrest expansion is now integrated in Chapter 22. Full [Chapter 22 review](CHAPTER_22_REVIEW.md). Neither game nor world repository was modified.

**Cumulative successive prose-only diffs:** 19 + 5 + 1 + 2 + 1 + 1 + 8 + 5 + 5 + 4 + 2 + 8 + 2 + 4 + 2. **Current source commit:** `c227753b59d037c6fef66c4b96d181487713e41f`. **Book:** 22 first-draft chapters, 98,450 words including headings, 161 IDs adapted, 42 planned, none independently editor-approved.

## Sixteenth source update — 17 November 2026

The entire game encounter file was compared **field by field across all 203 records** between [`c227753b59d0`](https://github.com/babunidev/Morkahja/blob/c227753b59d037c6fef66c4b96d181487713e41f/server/game/encountersdata.json) (blob `e611d3dd676776ff494dfa35bb32edf8f61a8f6d`) and [`9cddb72157a5`](https://github.com/babunidev/Morkahja/blob/9cddb72157a5d68563e4023af4ed3dcf25b00c5f/server/game/encountersdata.json) (blob `a4aac891f36ce5312139188c4597ec7f37f3b5f6`). Exactly **five `mEncounterText` changes**, IDs **20126–20130**, with **no changed IDs, names, types, elements, expansions, follow links or other fields**.

- **20126 Disheartened Rokur** — richer ruined walls and the body of volcanic stone and ice crystal, dim eyes, unfinished saga and Battledance gesture that stops halfway. Already Chapter 13 as **a Rokur witness's oral testimony**. Updated the report while retaining its secondary mode.
- **20127 Eternal Twilight Grove** — motionless stars, luminous spectral leaves, a spirit scattering into a thousand wisps through a tree, a fleeting joint melody that breaks into laments. Already Chapter 13 through **a different traveler's testimony**; updated without moving the haunted grove into Evergrove. **Chapter 13: 5,526 → 5,579 (+53 words for both)**.
- **20128 Grimnir Rebels** — dying fire, close stone-bodied rebels, one carefully adding fuel and an elderly warrior moving a stone closer to the hearth's empty space, silently inviting speculation without confirming motives. Already Chapter 2 as **Kelna showing a report and cave-rubbing from a distant traveler**; revised in the same archive/testimony framing. **Chapter 2: 3,313 → 3,369 (+56)**.
- **20129 Everwinter Treasurechest** — floral-and-leaf carving, warm blossom scent, iron-bound icicle at locked center, new snow hiding and then revealing glowing runes. Already Chapter 19 as **direct lived observation**; updated, chest still unopened.
- **20130 Everwinter Guardian** — frost puff from cave first, independently moving oversized ears, shaggy glacial-blue body, little nose wrinkle, seeming surprise at its own snow squall, and renewed guarding. Already Chapter 19 as **direct lived**, updated without force or inventing speech. Critically, the unchanged **20130 → 20131 Everwinter Cave** follow chain remains staged in sequence. **Chapter 19: 4,533 → 4,643 (+110 for the pair)**.

The changes add **219 words to previously drafted chapters** with zero new encounter IDs and no change of status. All **12** assigned Chapter 23 source entries were read from the newer game file and **none changed**. They were adapted in [Chapter 23](../manuscript/chapters/23-those-who-still-tend-the-forest.md) as **12 direct Lived scenes** involving aid workers, two separate lost children, an injured escapee, guardians, scholars, Rokur defenders and a trader. See [Chapter 23 review](CHAPTER_23_REVIEW.md).

**Cumulative successive text-only source revisions:** 19 + 5 + 1 + 2 + 1 + 1 + 8 + 5 + 5 + 4 + 2 + 8 + 2 + 4 + 2 + 5. **Current source commit:** `9cddb72157a5d68563e4023af4ed3dcf25b00c5f`. **Manuscript:** 23 first-draft chapters, 105,799 words including headings, 173 distinct IDs adapted, 30 planned, no independent editorial review.

## Seventeenth game source update — 17 November 2026

The **complete game encounter JSON (203 distinct IDs)** was compared **field by field** between [`9cddb72157a5`](https://github.com/babunidev/Morkahja/blob/9cddb72157a5d68563e4023af4ed3dcf25b00c5f/server/game/encountersdata.json), blob `a4aac891f36ce5312139188c4597ec7f37f3b5f6`, and current [`f949602a0a21`](https://github.com/babunidev/Morkahja/blob/f949602a0a210a9486e26b222a872e58665f87a7/server/game/encountersdata.json), blob `2608913e7e9f94a316c17f641fefa6f64147d266`. **Exactly two `mEncounterText`-only differences**, no ID, title, type, expansion, element, `mEncounterFollow` or other metadata changes.

- **20132 Frostbite Fergus**, already in **Chapter 18 as a direct Lived meeting**: updated his pine-log laughter and rumbling belly, brief serious attention, broad toothy grin, twitching nose detecting food, oversized ears turning in opposite directions, wide invitation seat and patting hand. The book's original novel-only conversation with Aksa and Brunti is maintained. **Chapter 18: 5,193 → 5,261 words (+68)**.
- **20133 Kaldric of Nekalos**, already **Chapter 20 directly seen**: updated his intricate incomplete hand patterns reflected in snow, their dispersal under localized gale, repeated attempt to complete a gesture, and distinctly broken phrase *“The Nekalos Mechanism—”*. The novel still does **not** supply the mechanism's actual working or identify any causal connection to the Grimnir memorial. **Chapter 20: 6,137 → 6,187 words (+50)**.

Net **+118 older chapter words**, no reassignment or new source integration from these revisions. **All twenty Chapter 24 encounter texts unchanged** against the former game source, reread and directly adapted across intentionally separated scenes. No game-world files changed. See [Chapter 24 review](CHAPTER_24_REVIEW.md).

**Cumulative successive text-only deltas:** 19 + 5 + 1 + 2 + 1 + 1 + 8 + 5 + 5 + 4 + 2 + 8 + 2 + 4 + 2 + 5 + 2. **Current game commit:** `f949602a0a210a9486e26b222a872e58665f87a7`. **Manuscript:** 24 first drafts, 111,305 words including headings, 193 adapted IDs, 10 planned, zero independent editorial acceptances.

## Chapter 25 no-change verification — 17 November 2026

The live game [`server/game/encountersdata.json`](https://github.com/babunidev/Morkahja/blob/f949602a0a210a9486e26b222a872e58665f87a7/server/game/encountersdata.json) was fetched again at commit `f949602a0a210a9486e26b222a872e58665f87a7` and compared **across all 203 records and all fields** to the previously pinned same commit. Both blobs are **`2608913e7e9f94a316c17f641fefa6f64147d266`**; **zero changes**. There was **no eighteenth game prose revision** to reconcile and no earlier chapter was modified in this step.

Current novel source chain **20050 Blackwood Portal → 19666 Tangled Depths → 19667 Blackwood Guardian** was reread in full and staged in **Chapter 25** (`Lived`, 5,447 words). Its unchanged outgoing links to **19668 The Hollow Choir → 19669 The Weeping Mire → 19670 Forgotten Procession → 19671 Silent Throne → 19672 Verdani's Vigil** were validated and remain planned Chapters 26–27. The world/game discrepancy over the Guardian password/item rule is **not silently resolved**; see [Chapter 25 review](CHAPTER_25_REVIEW.md).

**Current status:** **25 first-draft chapters, 116,752 words including headings, 196 adapted distinct source IDs, 7 planned, no independent editor approval**.

## Eighteenth source update — 17 November 2026

The entire **203-record Morkahja encounter file** was compared **field by field** between [`f949602a0a21`](https://github.com/babunidev/Morkahja/blob/f949602a0a210a9486e26b222a872e58665f87a7/server/game/encountersdata.json), blob `2608913e7e9f94a316c17f641fefa6f64147d266`, and [`3c14072c05be`](https://github.com/babunidev/Morkahja/blob/3c14072c05be06453ec09473d467c4ca1e0087c8/server/game/encountersdata.json), blob `b103b24a3dc1f76916cf84d958d3d0230da89a80`. Exactly **two `mEncounterText` changes, 20134 and 20135**, and no ID, title, type, element, expansion, `mEncounterFollow` or other field changed.

- **20134 Seal of Nekalos**, already directly experienced in **Chapter 20**: added the sustained illuminated base glyph, an independent second sequence, thin lines of icy-blue light separated by crystal layers, suspended glyphs and brief unfamiliar shapes that vanish with the sun's shift. Kept the artifact as an unresolved Knowledge Seal, **not a functioning key or decoded mechanism**. **Chapter 20: 6,187 → 6,239 (+52 words)**.
- **20135 Frostlace**, already **Testimony** in **Chapter 19**: updated a traveler's account with deceptive hearth-like warmth where no fire burns, graceful silver-white hair and crystalline strands, soft blue eyes, hardened snow and frost creeping across stones, a dark unlit passage and cold-fingered beckoning. **The speaker still says she did not see Frostlace directly**, so the book does not reclassify an attributed story as a lived meeting. **Chapter 19: 4,643 → 4,704 (+61)**.

**Net +113 words to previous drafts**, zero encounter status changes. The **three Chapter 26 source records (19668, 19669, 19670)** remained unchanged and are now written as separate direct scenes in [Chapter 26 — The Voices Beneath](../manuscript/chapters/26-the-voices-beneath.md), preserving the complete sequence from the Guardian **19667 → 19668 → 19669 → 19670 → 19671 Silent Throne → 19672 Verdani's Vigil**. The two latter scenes remain planned for Chapter 27. See [Chapter 26 review](CHAPTER_26_REVIEW.md).

**Cumulative successive prose-only source revisions:** 19 + 5 + 1 + 2 + 1 + 1 + 8 + 5 + 5 + 4 + 2 + 8 + 2 + 4 + 2 + 5 + 2 + 2. **Current game commit:** `3c14072c05be06453ec09473d467c4ca1e0087c8`. **Manuscript:** 26 first drafts, 122,216 words including headings, 199 adapted IDs, four planned, no independent human editorial approval.

## Nineteenth game source refresh — 17 November 2026

The game `server/game/encountersdata.json` was read and **all 203 IDs / all JSON fields compared** between [`3c14072c05be`](https://github.com/babunidev/Morkahja/blob/3c14072c05be06453ec09473d467c4ca1e0087c8/server/game/encountersdata.json), blob `b103b24a3dc1f76916cf84d958d3d0230da89a80`, and [`507cd0d738d5`](https://github.com/babunidev/Morkahja/blob/507cd0d738d51e433102b19885bca6df2d8e243d/server/game/encountersdata.json), blob `d05ae9f6961c643c7a97a351d512753913778836`. **Exactly two text-only `mEncounterText` changes**; titles, IDs, types, element, expansion, `mEncounterFollow` and all other fields remain identical.

- **20136 Lost Souls of Everwinter**, **Chapter 19 directly Lived**: expanded the lost group's blizzard conditions with an elderly traveler's voice failing in a whisper, a companion steadying them by the shoulder and a faltering familiar hum before the group follows Enna's safer approach to shelter. The leading traveler already dragged a frozen hem through the snow. **Chapter 19: 4,704 → 4,754 words (+50)**.
- **20137 The Shattered Seer**, **Chapter 20 directly Lived**: enriched the Seer of Snows shrine description with a spectral shoulder fragment and brief pale outline of a regal woman; the partially manifest guiding hand reaches out, dissolves until only pale fingers hover, then vanishes. The impossible fragment ordering remains unrepairable and no complete Seer history is claimed. **Chapter 20: 6,239 → 6,292 words (+53)**.

Net **+103 older-chapter words**. **19671 Silent Throne** and **19672 Verdani's Vigil**, both unchanged from prior source, were read in full and staged as distinct direct scenes in [Chapter 27](../manuscript/chapters/27-what-the-throne-keeps.md), completing the original follow sequence **20050→19666→19667→19668→19669→19670→19671→19672→0** across Chapters 25–27. The old game-source lists and modes remain distinct from the new literary storyline. No game/world source edit occurred.

**Cumulative successive `mEncounterText`-only updates:** 19 + 5 + 1 + 2 + 1 + 1 + 8 + 5 + 5 + 4 + 2 + 8 + 2 + 4 + 2 + 5 + 2 + 2 + 2. **Current game commit `507cd0d738d51e433102b19885bca6df2d8e243d`**. **Manuscript:** 27 drafted chapters, 127,674 words including headings, 201 unique encounter IDs adapted, 2 planned, 0 independent human approvals.

## Twentieth game source update — 18 November 2026

The whole [Morkahja `encountersdata.json` at `f62708ce2dd4`](https://github.com/babunidev/Morkahja/blob/f62708ce2dd455f0fd77b183a87c705888bc4a59/server/game/encountersdata.json), blob `8d5f254a5aa9078cc91e3c0d8d4e6c4022f6712f`, was **compared across all 203 records and every JSON field** against the prior reviewed [`507cd0d738d5`](https://github.com/babunidev/Morkahja/blob/507cd0d738d51e433102b19885bca6df2d8e243d/server/game/encountersdata.json), blob `d05ae9f6961c643c7a97a351d512753913778836`. Exactly **seven `mEncounterText` values differ**: 20138 Skyreach Peak, 20139 Lyria of Nekalos, 20140 Misthowl, 20141 Winterwisp Warden, 20142 Frostfall Cascade, 20143 Frostforged Vault and 20144 The Scholar. **Zero differences** in ID, title, type, element, expansion, follow pointers or every other field.

- **Chapter 19**, already directly staging **20141 Winterwisp Warden** and **testimony 20140 Misthowl**: added the Warden's snow-crystal formation, constantly shifting towering shape, floating movement, the spun veil barring the Queen's pass and fixed blue eyes; as *Enna's secondhand account*, Misthowl's luminous eyes, translucent mist-washed fur, the faint rumble and ears turning toward the mountains, **without turning it into a direct sighting or confirmed storm forecast**. **4,754 → 4,854 words (+100).**
- **Chapter 20**, already directly staging **20138 Skyreach Peak, 20139 Lyria of Nekalos, 20142 Frostfall Cascade, 20143 Frostforged Vault and 20144 The Scholar Jorvald**: added the summit's transient sunlit path through snow, Lyria's raised spectral hand and trembling nearby frost, frozen waterfall's many jagged polished layers and unattainable glint, the great metal door's frosted worked patterns and incomplete windborne chant, and Jorvald's protected old diagrams, page strips and boot-stopped parchment, while leaving all old mysteries unsolved. **6,292 → 6,432 (+140).**

The current original game **Atranor** source is stored under JSON key **`00001`**, numeric encounter ID **1**; complete text read and found unchanged, with `mEncounterFollow=0`. It is now **Testimony in Chapter 28** (5,780 words), not a firsthand divine visit. The other unadapted game record is **`00002`, numeric ID 2, Level up!**, still reserved for Chapter 30 in **Metaphor** mode, not a literal advancement display.

**All seven revised descriptions remain in their original assigned chapters; +240 words to existing manuscript.** Current total **28 first drafts, 133,694 words including headings, 202/203 adapted source IDs, one planned, no independent human editorial approval**. [Chapter 28 source and law review](CHAPTER_28_REVIEW.md) gives complete provenance. No Morkahja or MorkahjaWorld file was edited.

## Twenty-first game source revision — 18 November 2026

The complete **203-record** encounter JSON at [Morkahja `8e4857737f9b`](https://github.com/babunidev/Morkahja/blob/8e4857737f9bef3b6560fdf2159bca8e2c61f457/server/game/encountersdata.json), blob `3f72e26cac0c11b6ef86c92a7ff5706a08487007`, was compared **field by field** with [`f62708ce2dd4`](https://github.com/babunidev/Morkahja/blob/f62708ce2dd455f0fd77b183a87c705888bc4a59/server/game/encountersdata.json), blob `8d5f254a5aa9078cc91e3c0d8d4e6c4022f6712f`. **Exactly two changes, both `mEncounterText`-only:** **20145 Spirit Stag**, **20146 Eldritch Stronghold**. No changed record IDs, title, expansion, type, element, `mEncounterFollow` or other metadata; **`00002` Level up!** unchanged.

- **20145 Spirit Stag**, original **Chapter 20 direct Lived** scene: adjusted the wounded stag's head movement and momentary foreleg collapse/recovery, luminous eyes and cold blue pulse of the embedded azure arrow, with an existing longer night-watch/caretaker episode kept intact. **Chapter 20: 6,432 → 6,482 words (+50)**; no miraculous healing or removal of the wound.
- **20146 Eldritch Stronghold**, original **Chapter 24 direct Lived** scene: a heavy falling droplet sounds hollow against the ancient iron fitting, then trickles into a rusted seam; pale fungus and crawling insects mark the immense moss-bound cube of darksteel and ironwood beneath a dead Keldor tree. **Chapter 24: 5,388 → 5,422 (+34)**. Chest remains locked, unopened and unexplained.

**Chapter 29** has **no assigned game encounter ID**. Its inspection/restoration of the composite Tavra/Korrum memorial and the Skyland's safe walls is **original novel fiction**, not a retroactive canonical scene; consult [Chapter 29 internal review](CHAPTER_29_REVIEW.md). The independently source-attested original game **`00002` / ID 2 Level up!** remains **planned for Chapter 30**, metaphor mode. One non-game continuity correction also renamed **Chapter 28's mourner Orven to Tarnel**, resolving the accidental duplication with **Chapter 2's Orven the Skykeeper**, without changing the chapter's 5,780 words.

**Twenty-one consecutive `mEncounterText`-only source refreshes:** 19 + 5 + 1 + 2 + 1 + 1 + 8 + 5 + 5 + 4 + 2 + 8 + 2 + 4 + 2 + 5 + 2 + 2 + 2 + 7 + 2. **Manuscript:** 29 chapters, 139,437 words including headings, 202 adapted unique game IDs, one planned ID 2, no human editorial ratification or audio.
