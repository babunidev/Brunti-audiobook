# Chapter 17 — The Mountain Has a Voice: source and continuity review

**Date:** 17 November 2026. **Status:** [Chapter 17](../manuscript/chapters/17-the-mountain-has-a-voice.md) is **4,683 words including heading** after the Chapter 18 source refresh (original first draft: 4,639 words), written as first-draft novel prose by **ChatGPT GPT-6** under Babuni's standing creative delegation. This is an internal source and continuity check, **not independent human editorial approval, game/world canon, completed narration or audio**.

## Source verification

All **eleven** assigned full encounter texts were reread from [Morkahja `main` at `92cd8dc140c5`](https://github.com/babunidev/Morkahja/blob/92cd8dc140c5a73fce11f8ad3b5d87a488b3fd7b/server/game/encountersdata.json) (JSON blob `ec27f8ef04095906ab811f3a21aa2378dfe48d46`). Their IDs, titles, other metadata and follow links match the prior `525d26bc8b4d` review. All eleven are represented as **Lived** observations/encounters in prose; none is an invented compulsory fight or a treasure claim.

| ID | Source element retained in prose | Deliberate boundary |
| ---: | --- | --- |
| **20099 Cliffs of Sarga** | Low and high wind notes from fissures, broken shelves, rockfall into darkness, note returning when wind shifts, rumor of treasure | Natural wind explanation is likely but its exact interior remains unseen; no hoard recovered |
| **20106 Sarga Lioness** | Tawny lioness emerges onto a rocky ledge, green eyes, differently turned ears, slow tail, nostrils and raised forepaw | Original novel-only hare chase is an outcome, not a canonical account; travelers withdraw |
| **20100 Mountain Pass** | Cloud sea below icy narrow pass, exposed worn track, wind-blown snow, dark fissure, remote hoard rumor | The party chooses a shelter, and the fissure remains unentered |
| **20102 Frostwind Slopes** | Sun on frozen river, snow curtain and gust-exposed ledge recess, faint crystalline ticking | No declaration that ticking is magical treasure or a specific artifact |
| **20103 Strange Boulder** | Moss, precariously balanced enormous boulder, distant green valley, floral warmth beneath hidden opening | Unstable under-rock space is not entered; source gives no established origin for scent |
| **20105 The Giant** | Vertically standing monolith, weathered folds, hollow wind resonance, light crossing its summit, falling stone | **Updated game prose** integrated; rock shape is not declared a living giant |
| **20121 Frost Strider** | Apparent mid-step rock formation, swirling snow through 'legs,' golem/living-being rumor | No verified animation or treasure guardian |
| **20122 Rocky Tundra** | Yellow rocky tundra, moss and lichen, tiny quick life beneath a crag | Creature is not given an invented species name |
| **20109 Embersnout** | Bright fire-colored wolf, scent-tracking, careful footfall on ice, sharp turn, bared needle teeth | Original novel-only retreat and wind diversion; no kill or reward |
| **20120 Bronze Vault** | Detailed frost-filled etchings, heavy closed lock, unknown makers, light and crystal against bronze | Vault remains locked; no attribution to a lost people |
| **20061 Frostwind Junkyard** | Crevice shop by torchlight, cluttered runes and wares, Grimnir dealer shifts an object between categories and offers something on a cleared counter | **Ordo**, prices, paired fitting, trade, heat clasps and mineral paste are novel-only inventions. The fitting resembles known work but has no verified provenance |

## Continuity and literary choices

The chapter starts **after Sira's ordinary westbound caravan departure at the end of Chapter 16**. Sira is remembered, not magically reunited; Brunti and **Velen** continue together. Sarga is visited on an earlier leg, with explicit intervening journeys and settlements before the Frostwind ascent. The [Frostwind Landmarks](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Frostwind_Landmarks.md) archive explicitly leaves **Sarga's exact relation to Frostwind unsettled**; the novel avoids implying they share a ridge or immediate border. A final cartographic and seasonal route audit remains outstanding.

The [Grimnir](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Races/Grimnir.md) and [Grimnir Life and Care](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Traditions/Grimnir_Life_and_Care.md) documents support Brunti's mineral seams, chill-induced strain, replenishment and careful restoration; she is not portrayed as a human in armor. **Hesk** (Rokur guide), **Orena** (Sarga pathkeeper), **Ordo** (Grimnir junk dealer's personal name), their dialogue, the wayhouses, hare, repairing paste purchase and precise travel duration are original literary devices. Velen's gloves and notes are practical consequences, not a magical discovery. The junkyard object remains **weak circumstantial resemblance**, distinct from the archive's old composite drawing and Darrik's real repair obligation.

[World Frostwind](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Frostwind_Mountains.md) supports unstable routes, rockfalls and severe cold. [Everwinter Valley](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Everwinter_Valley.md) and [the southern trading post](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Everwinter_Trading_Post.md) support the **Chapter 18 handoff**: hospitality, limited supplies and a warm Rokur-operated refuge. The source game's rockslide **20104** belongs in Chapter 18, not this chapter. Do not retroactively count it as drafted merely because a path-ice loss occurs here.

## Later game change reconciliation

A comparison of all **203 records and fields** between game `525d26bc8b4d` (blob `1ae39adad0dc6ef0c09a84b8a9c9cd0868fe766b`) and game `92cd8dc140c5` (blob `ec27f8ef04095906ab811f3a21aa2378dfe48d46`) found exactly **four changed fields, all `mEncounterText`**: **20104 Sudden Rockslide** (Chapter 18 planned), **20105 The Giant** (this draft), **20106 Sarga Lioness** (this draft), and **20107 Silver Wolf** (Chapter 21 planned). The new text of 20105 and 20106 was integrated here; the other two updates remain future source obligations. All record IDs, titles, non-prose metadata, and follow links remained unchanged. Original game and world repositories were not modified.

## Verification status

**Checked:** full eleven current source descriptions; eleven identifiable prose integrations; source mode and chapter assignments; Sira/Velen continuity; relevant world lore; manuscript word count; current 203-record game delta; relative file references in this new review. **Not independently checked:** final line editing and literary pacing, exact map/geography/chronology, eventual manuscript-wide count semantics, pronunciation and read-aloud performance, narrator master, rights clearance, published recording.

**Historical ledger immediately after original Chapter 17:** **17 / 30 chapters**, **72,764 words including headings**, **130 / 203 encounter integrations drafted**, **73 planned**, **0 independently editorially approved**. This historical stage count precedes the 44-word Embersnout revision and Chapter 18.

## Chapter 18 source reconciliation addendum — 17 November 2026

The newer game `e8fbfc67cbb4` expands **20109 Embersnout** without changing identity or metadata. This chapter's direct scene was revised to show claws faintly scraping the exposed ice, an abrupt pause with one forepaw lifted, independently turning ears, more precise watchful movement, needle-like teeth and a pale breath cloud lingering in the air. Original retreat, lack of fight, and all eleven Chapter 17 encounter placements remain. Revised chapter word count: **4,683** (+44); overall book status after Chapter 18: **18 first drafts, 77,918 words including headings, 135 adaptations, 68 planned, no independent editorial approval**. See [eleventh game diff](SOURCE_RECONCILIATION.md) and [Chapter 18 review](CHAPTER_18_REVIEW.md).
