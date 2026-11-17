# Scene-level continuity register — working audit

**Date:** 17 November 2026. **Status:** source-informed **planning audit**, not a complete world-lore review or editorial sign-off. This register records constraints, the fixes already made in scene briefs, and unresolved proof obligations. It does **not** imply world canon has changed.

## Source baseline

| Purpose | Pinned source | What was checked |
| --- | --- | --- |
| Novel scene input | [Game `e0bc99c51c74`](https://github.com/babunidev/Morkahja/blob/e0bc99c51c74bb088f27a8252082b41c61629cf7/server/game/encountersdata.json) | 203 encounter IDs; five `mEncounterText` updates since `5b0d73e550ca`; IDs, titles, metadata and follow links unchanged |
| Game avatar and original atlas | [Game `58576f063627`](https://github.com/babunidev/Morkahja/tree/58576f063627752f77cdf99514baad875d509114) | Brunti avatar 104, frame 75; initial source inventory |
| Established world | [MorkahjaWorld `f56a7c3d2034`](https://github.com/babunidev/MorkahjaWorld/tree/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48) | Selected Grimnir, Aetherion, Evergrove, Everwinter, Ravage, Keldor, Blackwood, Atranor and Divine Laws records |

[Source reconciliation](SOURCE_RECONCILIATION.md) separately accounts for the original 19 text revisions and the five new ones.

## Confirmed canonical guardrails built into scenes

| Canon subject | Novel-scene implementation | Evidence |
| --- | --- | --- |
| Grimnir have living mineral/metal/crystal bodies; prepared minerals, water, resonance and communal care support them | Chapters 1, 14 and 29 use actual material needs and repairs; no human sweating/bleeding assumptions about Brunti | [Grimnir](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Races/Grimnir.md), [life and care](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Traditions/Grimnir_Life_and_Care.md) |
| Skylands are engineered moving homes; memorial stones hold **echoes** of deceased Grimnir | Chapters 1–2 and 29–30 build a strictly local material problem; stones never issue new prophecies | [Skylands](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Grimnir_Skylands.md) |
| Aevis Celesterra is a **subterranean sky-city**; Brunti's homeland is the Grimnir Skylands | Chapter 9 uses the Celesterra merchant as **testimony**, no direct jump to that city | [Celesterra](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Celesterra.md) |
| Evergrove is a desert heartland with oasis-gardens, root systems, and managed canals | Chapters 12–13 show oasis community and Verdani watercraft rather than a generic forest | [Evergrove](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Evergrove.md) |
| Aetherion holds market, forge, records, concert and Garden of Elements | Chapter 11 has independently different civic spaces; the garden's irregularity is **not** caused by Brunti's stone | [Aetherion](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Aetherion.md) |
| Urcogor Ravage is an older, recurring movement, with no confirmed mastermind | Chapter 13 keeps other survivors' reports separate; chapters 21–24 avoid treating all Gobbl/Ogru individuals as one enemy faction | [Ravage](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/WorldEvents/Urcogor_Ravage.md) |
| Keldor and Blackwood remain deep uncertainties, including the Portal's mechanism | Chapters 24–27 leave the passage and Guardian's yielding uncertain; Brunti's trauma does not prove a cause or a prophecy | [Keldor](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Keldor.md), [Blackwood](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Blackwood_Abyss.md) |
| Death, judgment and reincarnation obey shared divine laws | Chapter 28 uses a tradition/uncertain testimony, no provable first-hand mortal report or automatic resurrection | [Divine Laws](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Pantheon/Divine_Laws.md) |

## Ordered source relationships verified in planning

- **Blackwood:** **20050 → 19666 → 19667 → 19668 → 19669 → 19670 → 19671 → 19672** in chapter scenes 25.1–27.2, uninterrupted by an unrelated source encounter.
- **Hearth:** **20188 → 19444**, together in 10.3, with seal before accessible chamber.
- **Nereval:** **20192 → 19001**, together in 12.2, guardian before sanctuary.
- **Everwinter:** **20130 → 20131**, together in 19.2, guardian before cave.
- **Seven letters:** 20081 **A**, 20083 **H**, 20084 **K**, 20085 **J**, 20086 **O**, 20087 **M**, 20089 **A** in chapter 4 across several days. No decoding into a canonical word.

## Geography, travel and character continuity

| Concern | Current treatment | Remaining editorial test |
| --- | --- | --- |
| Distance from a Skyland to the Vale | Chapter 3 begins after ordinary Skyland trade/descent arrangements | Verify landing or descent site against established geography and Skyland practice; no invented instantaneous transfer |
| Vale letter stones | Chapter 4 covers several travel days and sites | Check each full text for precise location and assess whether a route can plausibly connect them |
| Liani boundary vs Eldertree/Aetherion | Chapter 8 is a detour that returns to the public road | Verify broad map relation without fabricating a continuous straight route |
| Celesterra's distant merchant | Chapter 9 uses **testimony** (20076), not physical displacement | Confirm storyteller access and time of report during prose |
| Evergrove and the southeastern Vale sanctuary | Chapter 12 keeps Nereval's border doorway separate from the Evergrove Umbrael tale | Verify exact position in full game descriptions |
| Ohgar → Karrhu → mountains | Chapters 14–17 include distinct travel intervals; no adjoining-place assertion | Still needs sourced route geography, travel duration and season logic |
| Cliffs of Sarga (20099) | Chapter 17 stages an *earlier separate leg* before Frostwind | **Unresolved:** regional position relative to northbound route; could require a reframe as remembered experience with correct chronology |
| Sira's separated itinerary | Leaves after Karrhu to help displaced people; ordinary communications reunite the company near Keldor | Define intermediate stops and credible exchange of news; do not use unlicensed messaging or convenient teleportation |
| Missing Verdani child | Chapter 13 recalls an earlier displaced group; chapter 23 obtains first-hand confirmation from the child with a walking stick | **Original fiction** linking events 20125 and 20170; cannot be represented as source canon, nor is the stick alone proof |
| Archive drawing at Aetherion | Velen finds a partial sketch of a **local** Grimnir memorial-casing type | Clarify why the specific Skyland's craft records were duplicated there (e.g. trade/convergence filing) and how Darrik verifies them |
| Convergence deadline | A bounded future **craft decision**, not a prophecy or falling-Skyland emergency | Travel duration and exact interval remain unspecified; must allow a multi-region journey |
| Brunti's choice after the rescue | Chapter 23 concludes the living-person duty; 24 begins a separate **unnecessary** Blackwood quest | Show cost of relapse and companions' objections without moralizing or calling the abyss a reward |

## Dramaturgy and audio checks

- Avoid reading ten boar names or twelve corrupted-creature names as an inventory. Chapters 5 and 16 use specific witnesses and differentiated descriptions; final prose still needs drama and cadence.
- A source **“Lived”** entry may be observed without combat, and a **“Testimony”** entry needs a credible speaker/occasion. The matrix forms are planning decisions, not confirmed manuscript integrations.
- Chapters 1 and 29 have **no primary game encounter IDs**; they are necessary original bridge and resolution chapters, not missing coverage.
- Brunti is the dominant close-third viewpoint. A quoted, performed or archived story needs a clear entrance and exit for listeners.
- The Blackwood account can portray a frightening lived sequence while keeping the source's competing interpretations open.
- The outcome of an encounter in game data is not a dictated novel outcome. Any saved character, consumed item, opened door, imagined family relationship or new utterance belongs to fiction and cannot be backported as lore.

## Verification and status

**Programmatic structural verification:** 5 movement files; 30 chapter headings; 109 individually labeled scene briefs; 203 distinct source-ID annotations. Comparison against [placement matrix](../story/PLACEMENT_MATRIX.md) found **0 missing**, **0 extras**, **0 duplicates** and **0 wrong chapter assignments**.

**Manual/source-limited review:** The particular canonical references above and targeted source excerpts were consulted. **Not completed:** final location-by-location geographical route proof; paragraph-by-paragraph comparison of all 203 full encounter descriptions; exact timeline; independent editorial review; drafted chapter prose; narration or audio production. Therefore mark **scene plan drafted**, not **scene plan fully canon-verified**.

## Manuscript progress and season correction — 17 November 2026

**Superseding the earlier “no drafted prose” planning status:** [four chapters](../manuscript/chapters/README.md) now exist as first-draft manuscript prose. The [review register](MANUSCRIPT_REVIEW.md) and [Chapter 3–4 source review](CHAPTERS_03_04_REVIEW.md) document **27** drafted source integrations; **176** remain planned. The plan itself still has **109 scenes** and **203** unique assignments, independent of draft status.

A verified chronological tension between source scenes **20069** (warm summer butterflies) and **20072** (autumn, fox under falling ochre leaves) is solved by delivery-mode adjustment, not by claiming geography shifts the season: 20072 is **Eda's past-tense testimony** in Chapter 3, while Brunti travels through summer meadows. This is an explicit departure from the original “Lived” proposal and has been changed in the matrix and scene plan.

The Skyland-to-Vale descent uses documented trade-descent practice, but its precise landing location is original literary connective fiction. The seven distinct marked stones have no verified canonical route or decoded message. Chapter 4 keeps them separate over multiple travel days, with their sequence and uncertainty intact.

## Drafted wildlife and Eldertree scenes — 17 November 2026

**Current manuscript:** [six first drafts](../manuscript/chapters/README.md) with **51** planned source IDs integrated into prose; **152** remain planned. Chapters 5 and 6 have [dedicated source-fidelity notes](CHAPTERS_05_06_REVIEW.md); none has received independent human line editing.

**Species/identity cautions:** The source distinguishes Bloodfang, Goldhorn, Nagar Charger, Elder, Berserk, Boar, Bonecrusher, Humpback, Razorback, Thunderhoof, Zeelai, Silvermane, Yowler, Mother Wolf and Redeye. The chapter's field tracker is original novel fiction. Mother Wolf **20110** is **not proven** to be mother of the Redeye **20111**; the draft keeps the pup a separate sighting. The other Nagar are not turned into one hostile army or a chain of obligatory fights.

**Unresolved Aevis crest:** Game `20007` calls the crest royal; world Aevis governance centers Resonance Councils. Chapter 6 keeps the engraved crest but reports the royal association as uncertain merchant language—no new Aevis crown is canonized. Game `20040` describes “dworv tools,” while established world notes older terminology as unresolved; the draft depicts toolmarks without asserting an otherwise invented dworv civilization. The rumored Enchanted Hollow remains separate from the visited Sylvan Sanctuary.

**New game revision:** `096c99bdf5ac` changed only the prose of 20082 and 20083. Chapter 4's letter **H** and newly added fading note were reconciled; 20082 remains pending in Chapter 15. [Reconciliation](SOURCE_RECONCILIATION.md) records exact old/new revision IDs.

## Chapters 7–8 manuscript additions — 17 November 2026

With [Chapters 7–8 drafted](../manuscript/chapters/README.md), the current manuscript status is **8 chapters, 67 source IDs integrated in draft prose, 136 planned, 0 independently editorial-verified**. The full [source and lore review](CHAPTERS_07_08_REVIEW.md) identifies two specific, material boundaries: northern source encounters **20008/20009** had been mistakenly placed as physical Eldertree finds in the working beat plan, so the prose uses attributed northern survey drawings and the matrix mode is corrected to **Archive**. The **Liani Guardian 20114**, **Shadowwolf 20036** and **Predator 20115** remain separate beings and the **Thunderfly 20117** is witnessed in its distinct dusk setting. No new Liani access rule or world-canon royal/geographic relationship was invented. The ordinary road and Celesterra merchant hearsay lead onward to Chapter 9.

## Trade, temple and book provenance — Chapter 9 draft, 17 November 2026

The first-draft manuscript now has **9 chapters / 72 source encounter IDs integrated / 131 planned** ([index](../manuscript/chapters/README.md)). [Chapter 9's source review](CHAPTER_09_REVIEW.md) separates **Pel's Hidden Market testimony (20012)** and **Aevis Merchant recollection (20076)** from Brunti's actual route; **Celesterra is subterranean with artificial skies**, not an aboveground Skyland. The direct **Pantheon Temple (20031)** visit takes the travelers to a temple **south of Eldridia near Eldertree**, not an invented Aetherion shrine. Rokur smith 20059 remains an **attributed pilgrim report**; canonical Rokur bodies are elemental flame, so hunger/exhaustion do not justify invented human anatomy or divine curses. The **Verdani Treasury (20060)** stays a small Eldertree woodland bookshop and does not become a state treasury. Its old bookbinder Thalen introduces the [Archive of Echoes](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Aetherion_Landmarks.md) as a catalog-research lead; this **does not** resolve the original Skyland mystery before Chapter 11.

New source prose revision **20084 K** from `734f439b1699` was reconciled in Chapter 4 without changing the seven-letter sequence. Exact overland distances, travel duration and Brunti's convergence deadline remain unchecked. Independent line editing not completed.

## Chapter 10 — northern shelter and independent choices (17 November 2026)

[Chapter 10 draft](../manuscript/chapters/10-the-shelter-beyond-the-veil.md) is complete, bringing manuscript status to **10 draft chapters / 78 game encounter IDs drafted / 125 planned**. Source review: [Chapter 10](CHAPTER_10_REVIEW.md).

**Explicit chain:** encounter **20188 Mystic Hearth's Seal** has `mEncounterFollow=19444`. The sanctuary (**19444**) appears only after the seal is passed. World [Hearthguard Sanctuary](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Hearthguard_Sanctuary.md) locates the barrier among standing stones of **northern Ethera's Vale**. The manuscript's smooth stone fitting and patient timing are **novel-only specific local unlocking fiction**; world lore does not establish that mechanism as a transferable technique. The refuge is not looted or replaced by an alternate site.

**No identity conflation:** The weary Rokur pilgrim of **20187** (female Aru in novel fiction) is not the earlier Rokur smith from **20059**. The Aevis in **20189** is novel-only courier Tessan, threatened by bandits in the **eastern Vale**, and her pressured form is described according to Aevis elemental physiology. The Veilwalker (**20190**) remains a **different, reported creature of uncertain origin**. The sleeping Ogru and exposed gold (**20191**) remain a witnessed, unrobbed scene. Unplanned relationships between these figures are never canonized.

**Travel:** The party takes ordinary eastern and then northern Vale roads over additional days before heading toward Aetherion. The distances are **not verified** against precise cartography; the accumulated time must eventually be reconciled against the Skyland convergence. The latest game edit to **20085 Bucolic Dale** was incorporated into Chapter 4's **J** scene without changing the seven-letter order.

## Chapter 11 — Aetherion and the incomplete composite drawing (17 November 2026)

[Chapter 11](../manuscript/chapters/11-the-city-of-listening.md) introduces **Velen**, a novel-only Aevis archivist/copyist (**they/them**), and directly stages source **20062 Market of Aetherion, 20181 Archive of Echoes, 20182 Aetherion Forge, 20183 Harmonic Concert and 20184 Garden of Elements**. Their five full game descriptions were checked against the prose at source `ad34afb686ef`. [Review details](CHAPTER_11_REVIEW.md).

**Incomplete evidence:** A torn archive **restoration drawing** plausibly shows *two intended positions beneath one shared casing*. Its partly similar mark and Brunti's earlier Skyland ledger are **not an identity proof**. The missing portions remain blank; makers, inscriptions, dates and final repair method are not known. Velen measures and copies the original under library custody. The resulting evidence narrows Brunti's local problem but never unlocks the world's unrelated mysteries.

**Garden continuity:** The Aetherion Garden of Elements has its own observed irregular pulses and brook/wind disturbance. Velen separates **analogy from cause**: this is not established as the same phenomenon as the memorial, or as a common cause of Ravage or Keldor's problems.

**Character/travel continuity:** The city has four distinct quarters under an Elemental Assembly, with the Archive, forge and concert reached by ordinary city streets over more than one day. Sira remains a message bearer with independent promises. **Velen requests leave; its approval and actual departure are still unresolved by Chapter 11's end** and must be addressed before Chapter 12 assumes they have joined. **Current draft status: 11 chapters, 83 adapted source IDs, 120 planned; no human editorial approval or audio.**

## Chapter 12 — the water sign, the restored channel and news east (17 November 2026)

[Chapter 12](../manuscript/chapters/12-where-water-is-guarded.md) adapts four full game texts, 20064/20192/19001/20193, in **one Sira testimony and three sequential direct encounters**. Source and lore: [Chapter 12 review](CHAPTER_12_REVIEW.md).

**20192 Nereval Elite → 19001 Nerevals Sanctuary** is an explicit game `mEncounterFollow` and must retain its direction. The **Verdani guardian** asks for a **river rune** before stepping aside; only then do the **moss-hidden blue runes, dark restoration mark, hidden water melody** and subsequent opening occur. The novel's practical repair of a small spring-bank feeding a distressed plant is **one local act of care**, not a general-purpose Nereval entry key. Canon confirms the sanctuary's seal responds to healing instead of force. **Geographic tension:** game 20192 places its gate on the **southeastern Vale border with Evergrove**, while [world Nereval sanctuary lore](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Nerevals_Sanctuary.md) describes **central Vale meadows**; the novel follows game wording for the approached border meadows but does **not** resolve precise coordinates for canon.

**Umbrael altar 20064** is **Sira's earlier personal testimony**, situated in Evergrove's **cultivated desert-oasis grove** with old trees and candles. It is not a simultaneous northern forest excursion; worship of Terran Umbrael by Verdani is permissible cross-tribunal devotion. **Joyful Riverkeeper 20193** becomes novel-only **Iren**, an elderly Verdani who jokes about food, interrupts himself to remember a deceased storyteller and reports second-hand messages about a damaged Verdani oasis-village. The report's named villagers and precise chain are invented plot background; no attacker, casualty list or universal Ravage explanation is independently established here.

**Velen continuity resolved:** the Archive of Echoes has granted the **temporary field research request** pending at Chapter 11's end. Velen carries the measured **copy** of a damaged two-position drawing and a field authorization, never the fragile original. After a multi-day road journey from Aetherion, the party moves toward **Evergrove by guided caravan and mapped oasis stations**. Brunti's convergence deadline remains active and should be checked against the complete itinerary; Sira chooses to aid known survivors, and Velen accompanies without claiming a right to their stories. **Project status: 12 draft chapters, 87 IDs drafted, 116 planned, no independent editorial approval or audio.**

## Chapter 13 — Evergrove rebuilding and separated testimony (17 November 2026)

[Chapter 13](../manuscript/chapters/13-after-the-raid.md) physically stages **20125 Raided Verdani Village** and **20053 Exhausted Verdani** in a single **engineered oasis-garden settlement within Evergrove's desert**. Ogrus and Gobbls are the **source-confirmed attackers**, but no specific Ravage outbreak date, organized leader, or link to the Chapter 10 sleeping Ogru is asserted. **Alen** directs the waterwork; **Renn** rests beneath an oasis tree; Brunti's repairs get water into **three of four feeder channels**, not a completed village recovery. Sira's grief is an independent relationship event, not a research task.

The **five additional individual wounds** 20013 (male Cauterized Rokur), 20014 (male Downed Aevis), 20016 (female Ailing Verdani), 20017 (female Flameveil Emberheart in her own burned village), 20054 (female Drained Aevis) are **separate testimony from identified types of sources** (spoken firsthand witnesses or a written messenger report) and not people secretly present at this raid. 20126 Disheartened Rokur and **20127 Eternal Twilight Grove** are **two more separate testimonies**, with the haunted forest *not located in Evergrove*. 20058 Aevis Lady is the **third directly lived source scene**, an older Aevis humming in a **cultivated local glade**. [Individual details and limitations](CHAPTER_13_REVIEW.md).

**Critical handoff to Chapter 14:** The group temporarily separates at Chapter 13's close: **Sira stays** helping survivors in Evergrove; **Brunti and Velen** take a nearby supply wagon to fetch appropriate replacement pipe and regional material accounts. Reunite them through ordinary travel **before any planned three-person Ohgar scene**. An earlier displaced caravan included a child with a **carved walking stick**, but the only present fact is that the caravan split at a station; there is **no confirmed missing child and no established location in Keldor**. Alen's nephew Tavi and this traveler are **not confirmed to be the same person**. The Skyland convergence deadline remains unresolved within the multi-region travel chronology.

**Draft status:** 13 chapters / 53,019 words including headings / 97 integrated encounter IDs / 106 planned / 0 independently editorial-verified. No changes to source game or world lore.

## Chapter 14 — reunification, Ohgar and an unfilled inscription (17 November 2026)

[Chapter 14 — Words in the Sand](../manuscript/chapters/14-words-in-the-sand.md) physically stages **20101 Rocks of Ohgar**, **20035 Ohgar Skorpo**, **20066 Thirsty Grimnir**, and **20063 Ancient Inscription** as four **Lived** scenes. All four descriptions were read at game `e826fa46d3ff`; the [Chapter 14 source review](CHAPTER_14_REVIEW.md) tracks each distinct sensory detail.

**Chapter 13 handoff resolved:** **Brunti and Velen return to the Evergrove village, reunite with Sira on-page and help Alen/Renn test a new fourth feeder fitting**. Water returns to the orchard under monitored flow; the still-damaged houses are **not** instantly restored. They later leave **together** via actual oasis stations, salt flats, mapped wells and guided carts into Ohgar. The trip to Karrhu is a **subsequent caravan/bridge route**, never a direct teleportation from desert into swamp; no exact travel distances are invented.

**Independent Ohgar sources:** Granite monoliths groan and sand enters a dark cleft; treasure remains a rumor and Brunti does not explore unsupported rock. The Skorpo's brown armor, clicking pincers and venomous tail are an on-road obstacle, not a killed monster. Young female Grimnir **Nera**, exhausted in the dunes with **dry cracked living mineral body** and disappearing tracks, receives **shade, gradual mineral water, quiet resonance contact and sheltered station care**; neither her recovery nor her onward fate is guaranteed. The temple disc's repeated and weather-worn runes include **two matching surviving symbols around an erased area**. Velen's drawing leaves the gap blank. No decoded Vale letter, memorial provenance, divine revelation or inscribed prophecy is established by Ohgar.

**The finite Skyland question:** Brunti sends a **sealed courier letter** toward Darrik describing only the uncertain Aetherion two-bed evidence. She asks him to preserve safe handling and keep records if the memorial is transferred; **delivery is not confirmed**, and the established convergence deadline is not suspended. The child with the carved walking stick remains of uncertain location elsewhere; Sira's messages continue through their own relay routes.

**Parallel source change:** Game `e826fa46d3ff` changed **only the prose** of **20086–20093**. [Chapter 4](../manuscript/chapters/04-letters-without-a-word.md) now reflects detailed O/M/A landscaping and letterless intervening glades; [Chapter 5](../manuscript/chapters/05-the-lives-of-the-vale.md) includes three newly detailed Nagar accounts. **A H K J O M A** remains unchanged. Neither earlier passage invents a new global lore rule. [Full diff](SOURCE_RECONCILIATION.md).

**Tracked state:** 14 literary first-draft chapters, 58,041 words including headings, 101 game IDs actually adapted, 102 planned, **none independently editorial-verified**. World and game sources remain untouched.

## Chapter 15 — Karrhu, the child and an uncertain reflection (17 November 2026)

[Chapter 15](../manuscript/chapters/15-beneath-the-reeds.md) stages **five direct Karrhu encounters** 20038, 20116, 20057, 20037, 20077 plus **20082 Alluring Fens as a reported central-land episode**. [Source details and verified boundary](CHAPTER_15_REVIEW.md). Four sources are direct creature/place discoveries and one directly experienced child rescue; none of the six records had a follow link. The **Alluring Fens** lie among Vale landmarks with precise boundaries not established; the traveling herb gatherer recounts hearing their night song elsewhere, at a **Karrhu ferry house**, not falsely placing the Fens inside Karrhu.

**Geographic continuity:** The trio takes linked roads, ferries and raised walkways after leaving Ohgar, over unmeasured but explicitly ordinary travel days. **Calen** is the local ferryman, **Olri** the reed station keeper, **Hessa** the eastward guide—original novel identities, not world canon. The Inferno Duck's steaming beak and short fire burst scorch Brunti's scarf; Aradia's silver wings and venom bead are watched from behind a warning post; both are avoided without combat. A huge red-eyed fly uncurls its proboscis within Karrhu's Flytrap Grotto, but the company retreats and posts **locally approved** danger markers rather than declaring the creature slain or the curse proven.

**Child:** Young Verdani girl **Leta** makes crumbling mud cakes near flooded roots and asks for food. She receives bread and water and is **returned on page to her worried aunt at the reed station** after a tested, supported stone crossing. She is **not the separately reported earlier displaced traveler with a carved walking stick** from Evergrove. The latter's whereabouts remain unverified.

**Quicksilver:** A circular silver pool reflects unfamiliar stars and suggestive shapes by moonlight. Brunti's half-seen image of **two forms** is **her interpretive desire**, not a recovered historical record, promised special power or fixed future. An unstable mud bank forces a retreat; no relic or artifact is taken and no objective connection to the Skyland memorial is claimed.

**Next handoff:** At the ferry house a courier brings **Velen's archive accounts of altered beings** (to be evaluated separately in Chapter 16) and Sira hears **incomplete southern/western relay confirmations** for displaced families. All **three remain together in Karrhu at Chapter 15's end**; Sira has **not yet left** for her separate contact journey. Brunti's letter to Darrik from Ohgar still has **no confirmed delivery**. Time to the convergence remains open.

**Source maintenance:** Game `92b97aef8706` refreshes **only 20094–20098**, reconciled in Chapters 5 and 7 as creature testimony/direct Yowler and unopened Common Chest. [Eighth source diff](SOURCE_RECONCILIATION.md). **Current status:** 15 literary first drafts / 63,149 words including headings / 107 source IDs adapted / 96 planned / 0 independently editorial-verified.

## Chapter 16 — four corruption lineages, twelve separate folios and Sira's western road (17 November 2026)

[Chapter 16](../manuscript/chapters/16-witnesses-of-corruption.md) integrates **all twelve game IDs 20019–20030 as Archive** delivery. Three Ashen Revenants, three Blightwraiths, three Crumblegheists and three Tempestwailers appear through **distinct copied witness records with uncertain dates, missing continuations and later labels**, read at a Karrhu ferry house. They are **not** twelve physically witnessed encounters by Brunti and not one Ravage invasion. Established canon recognizes **corrupted forms of the four created peoples**, but leaves the magic's precise origin unresolved and distinguishes the Urcogor Ravage's older peoples from that taxonomy. [Chapter 16 source table](CHAPTER_16_REVIEW.md).

**Key witness limits:** Witch green poison and Warlock transient sigils must not be decoded. Seer's unintelligible whisper does not certify prophecy. Rootrot being nonverbal does not prove it mindless; Occultist visibly drains a sapling, distinct from Huntress's destructive passing. Crumblegheist **20025** is titled **Roughian** in game JSON, whereas world corrupted-creatures lore uses **Berserk** for a closely described figure; the novel preserves the source name and leaves identity unresolved. Wildheart's supposedly righteous certainty is a witness interpretation; Stormcaller's woodland lightning and Seductress's disorienting scent are separate sightings, not one storm command. Brunti compares them against the two-position memorial sketch but **rejects any causal proof**.

**Travel and cast boundary:** Source-bound Western mail-relay **Rava**, a novel-only courier, tells Sira where to find actual arrival registers of families displaced from Evergrove. The **walking-stick child's whereabouts remain unconfirmed** and no proof of disappearance, identity or Keldor position is established. The trio remains together for **three further days after the ferry house**, traveling through Karrhu's exit routes and forested inland roads, before parting **at a mapped road junction**. **Sira travels west with an ordinary mail caravan; Brunti and Velen alone head north toward Sarga and later Frostwind/Everwinter.** They exchange possible forwarding contacts, **not** verified letter deliveries. Sira must not be inserted into Chapter 17–20 direct scenes by mistake.

**Game-source follow-up:** Latest game `525d26bc8b4d` changed only the encounter prose for **20099–20103**. **20101**'s revised inward falling sand beneath the immense Ohgar monolith is already in Chapter 14 (4,853 words), **20099/20100/20102/20103 await the future Chapter 17**. All twelve Chapter 16 records were unchanged and fully read. [Source log](SOURCE_RECONCILIATION.md).

**Working status:** 16 manuscript first drafts / 68,125 words including headings / 119 IDs adapted / 84 planned / 0 independently editorial-verified. No game/world canon edit.

## Chapter 17 manuscript continuity — 17 November 2026

The [Chapter 17 first draft](../manuscript/chapters/17-the-mountain-has-a-voice.md) follows Sira's actual western departure in Chapter 16: Brunti and Velen are physically together in the Sarga and Frostwind scenes, with Sira mentioned only through memory and undelivered correspondence. The story inserts unmeasured travel intervals and a later northern journey between Sarga and Frostwind; the precise map relation remains **unresolved canon**, not a claimed adjacent location. No travel by instantaneous transfer occurs.

All **eleven** assigned source encounters are adapted as direct experiences. The Giant and Frost Strider remain motionless formations; Embersnout is left alive; the Bronze Vault is left locked; the strange boulder, mountain fissures and a junkyard fragment retain uncertain meaning. The junkyard fragment's apparent fit to Brunti's memorial sketch is **unproven original narrative juxtaposition**, not new evidence of its maker. Cold stress is handled through Grimnir mineral physiology, and the final descent approaches Everwinter's southern trading post without yet incorporating **20104 Sudden Rockslide**, which is assigned to Chapter 18.

The game source comparison at `92cd8dc140c5` found four prose-only changes since the prior baseline. Revisions to **20105** and **20106** are integrated; **20104** and **20107** remain planned and must be reread during their respective chapters. See [source reconciliation](SOURCE_RECONCILIATION.md) and the [Chapter 17 source/continuity review](CHAPTER_17_REVIEW.md). The complete manuscript now has **17 first drafts, 130 adapted encounter IDs and 73 planned**. Final route measurement, seasonal timeline, independent line edit and narrator read-aloud approval are outstanding.
