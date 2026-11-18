# Stage 5 — continuation F: last 26 source hooks (Chapters 2 and 21–25)

**18 November 2026 | ChatGPT (GPT-6) internal targeted source/novel comparison under Babuni's creative direction.** This continuation finishes **203/203 distinct game encounter IDs** at the *targeted individual source-to-manuscript-passage* level. It does **not** finish the full 30-chapter uninterrupted literary review, scene-function assessment, spatial/atlas travel check, narrator listening test or independent human editorial acceptance.

## 1. Current evidence and accounting

- **Audiobook `main` at entry:** [`69629588e56a360db64cb977042d211f58173652`](https://github.com/babunidev/audiobookGrimnir/tree/69629588e56a360db64cb977042d211f58173652). [Placement matrix](../story/PLACEMENT_MATRIX.md) used to identify all remaining 26 rows.
- **Current game:** [Morkahja `2ba61f5a6bcde383ed2a931c3d2a06c87404dffd`](https://github.com/babunidev/Morkahja/blob/2ba61f5a6bcde383ed2a931c3d2a06c87404dffd/server/game/encountersdata.json); all 26 complete current encounter texts read and checked individually against their scenes. Compared their **entire JSON objects** to original literary baseline [`952437c5c59da26a2f873f1a18590496f88a2354`](https://github.com/babunidev/Morkahja/blob/952437c5c59da26a2f873f1a18590496f88a2354/server/game/encountersdata.json). **26/26 identical**; none of the original-versus-latest game's 37 prose-only changes occurred in this remaining set.
- **Established world archive:** [MorkahjaWorld `f56a7c3d2034652e1c5961f0ece9c3ef52b52b48`](https://github.com/babunidev/MorkahjaWorld/tree/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48), with direct reads of [Grimnir](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Races/Grimnir.md), [Grimnir Life and Care](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Traditions/Grimnir_Life_and_Care.md), [the Urcogor Ravage](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/WorldEvents/Urcogor_Ravage.md), [magic corruption](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Magic/Magic_Corruption.md), [Keldor](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Keldor.md), [Keldor Landmarks](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Keldor_Landmarks.md), [Keldor Creatures](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Creatures/Keldor_Creatures.md), [Wolves and Liani](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Creatures/Wolves_and_Liani.md), [Blackwood Abyss](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Blackwood_Abyss.md) and [Guardian](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Creatures/Guardians_and_Spirits.md).
- **Earlier audited distinct-ID counts:** [A](REVISION_STAGE_5_SEMANTIC_REVIEW.md) **54**, [B](REVISION_STAGE_5_CONTINUATION_02.md) **+20**, [C](REVISION_STAGE_5_CONTINUATION_03.md) **+34**, [D](REVISION_STAGE_5_CONTINUATION_04.md) **+21**, [E](REVISION_STAGE_5_CONTINUATION_05.md) **+48** = **177**. The **26 listed below** are absent from all preceding semantic tables, giving **203/203** distinct source-to-prose checks. Full union verification is recorded in the final verification section, not implied by this arithmetic alone.

## 2. Chapter 2 — four separate Grimnir reports, all new targeted checks

[Chapter 2](../manuscript/chapters/02-the-weight-of-other-stones.md) uses a council/Skykeeper gathering. No warrior is falsely portrayed as one of Brunti's personal rescues. Each report carries its own source and degree of knowledge.

| Source ID / delivery | Exact source hook present in novel | Fidelity/canon boundary |
| --- | --- | --- |
| **20015 Weakened Grimnir · Testimony** | **Female** armored warrior kneeling in a cave, damaged shoulder armor, braced by her weapon, visibly fatigued; Orven's scout records an **unconfirmed aftermath** | Game's humanlike sweat, hair and breath do not require redefining a Grimnir's mineral physiology; no invented survival |
| **20055 Wounded Grimnir · Testimony** | **Different female** warrior injured by a **Crumblegheist**, rock gouges, broken slabs, hand pressing split side, narrow daylight and distant dripping cave water; a worker's separate account | Novel represents the game's “dark blood” as a **fractured mineral seam** under the [living-stone Grimnir](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Races/Grimnir.md) source; injury genuinely serious |
| **20056 Venerable Grimnir · Testimony** | **Male elderly** Grimnir in a pillaged underground dwelling, broken shelves and **empty earthen bowl**, hunger after **Urcogor** raid; Kelna describes later meal and interim shelter as original novel aftermath | Ravage peoples are not one uniform villainous ancestry; the old man's recovery is a distinct scene-level extension |
| **20128 Grimnir Rebels · Testimony** | Stoneguard **group** around dying cave fire, gemstone eyes, drop from stalactite, one member adds fuel; an elder shifts stone to an **empty place** without identifying an absent person | Neither rebel cause nor political allegiance is invented; an archive rubbing, not Brunti witnessing the gathering |

**Seam:** These reports feed Brunti's developing respect for limited evidence before the long journey. The separate wounded warrior Stonefist Ironwill is already assigned a different ID (`20018`) and is **not conflated** with `20015` or `20055`. Earlier decisions about Stonefist's pronouns in [Decisions](DECISIONS.md) remain independent of this four-ID audit.

## 3. Chapter 21 — five distinct border, wolf and cursed-forest encounters

[Chapter 21](../manuscript/chapters/21-before-the-cursed-trees.md) physically reconnects Brunti with Sira by ordinary relief roads, before the limited search at the Keldor/Vale border.

| Source ID / delivery | Exact source hook present in novel | Fidelity/canon boundary |
| --- | --- | --- |
| **20107 Silver Wolf · Lived** | **Female** slender silver wolf crosses wooded Vale/Keldor border, leaf lifts from flank, sound drops, low body and graceful **leap over roots** | No identified prey or magical message invented |
| **20108 Shena Alpha · Lived** | **Different** glossy-coated strong wolf on moss hillock, deep pawprints, one ear toward noise, silent response to distant howl, low growl | “Shena” not proven a separate breed or literal royal title |
| **20044 Darkwood Thicket · Lived** | Twisted dense forest, leaf litter, **low wavering call**, indistinct whispers, unusual pale blossoms and bark shapes; route only as far as marker | The **fae banishment** is **unverified old tale**, not confirmed history |
| **20112 Cursed Silvermane · Lived** | **Tall** matted silver wolf with painful spasms, stiff foreleg, sudden head jerk, **spectral light in eyes/fur** and **leaves circling without wind** | Separate from the earlier ordinary Silver Wolf; no forced cure or violent conquest |
| **20113 Cursed Liani · Testimony** | **Different** dark shadowlike wolf, pale **cyan eyes**, silent movement, chill, distant howl turning to broken voice and strange nearness; witnessed by someone other than Brunti | World lore does **not establish identity** with the wise, patient Liani Shadowwolf. Distinction from Cursed Silvermane preserved |

**Geography:** The Vale/Keldor edge is traversed through road stations and return markers, not an invented portal; the border is natural and partly contested. The lost child remains unconfirmed until Chapter 23; wolves' ordinary movements are not used as miraculous tracking clues.

## 4. Chapter 22 — four Keldor warnings, three lived and one attributed

[Chapter 22](../manuscript/chapters/22-the-price-of-warning.md) gives separate roles to the merchant's mischief, a suffering Gobbl, Ivera's dangerous witness and an unusually behaving raven. Other assigned Ch22 source `20118` had previously been individually targeted; all five chapter integrations are now covered.

| Source ID / delivery | Exact source hook present in novel | Fidelity/canon boundary |
| --- | --- | --- |
| **20075 Grumpy Fence · Lived** | Old merchant with sagging **wizard hat**, old grey clothing, moth-eaten stall cloth, skull trinkets, tarnished charms, grumbling **“Very ancient. Very rare”** as the cord tangles | Original-only dialogue and small barter; an old shopkeeper, no mystical gate knowledge certified |
| **20078 Unhinged Gobbl · Lived** | Scarred asymmetrical Gobbl with **green eyes**, hunched form, guttural laughter, one hand **grabs violently jerking other arm**, claws and snarl | His affliction is one being's condition, **not** a claim about all Gobbls; no involuntary “cure” |
| **20079 Fearfeaster Gobbl · Testimony** | **Different** long-limbed leaf/rotting-flesh creature, needle talons, fixed wide grin, eye darting, eerie claw scraping bark; Ivera leaves the hollow | Feeding upon fear remains rumor, not established mechanism; **not** made an attack on companions |
| **20155 Blightwatcher Raven · Lived** | Blue-eyed raven with uneven feathers, **double/broken caw**, head turns before shoulders, talons release, backlight under feathers and uneasy wing movement | The bird's next prey/action remains unconfirmed; no invented pursuit or certainty of motive |

**Confirmed copyedit:** The chapter originally opened **“The first warning cost them a button.”** Yet later the merchant actually **returned the button**, and Sira paid money for the useful information. The opening now reads **“The first warning almost cost them a button.”** This is direct sequence/transaction continuity, not decorative rewriting. **Chapter 22: 4,813 → 4,814 words (+1).**

## 5. Chapter 23 — Luminous Enclave, one new targeted ID

[Chapter 23](../manuscript/chapters/23-those-who-still-tend-the-forest.md) contains twelve assigned game IDs; this was its only remaining individually unreviewed source.

| Source ID / delivery | Exact source hook present in novel | Fidelity/canon boundary |
| --- | --- | --- |
| **20148 Luminous Enclave · Lived** | Warm **moss-bright wooden hut** among Keldor dark, ancient hag's bubbling laughter, crowded **magical curios**, almost-falling trinket caught between two fingers, comically suspicious glance and mischievous welcome | Proprietor remains **unnamed** as in established world archive; her practical directions toward Sageglow are novel-only service, not knowledge of Keldor's secret cause |

**Seam:** Elda's shelter and independent local aid workers preserve lived community. Luminous Enclave is distinct from the sanctuary or a magic solution to the curse. The rescued child's verification and return take place after this visit; no separate character is fused into that child.

## 6. Chapter 24 — nine separate lived objects/creatures/landmarks

[Chapter 24](../manuscript/chapters/24-paths-among-the-dead.md) has **20 assigned IDs**, eleven already targeted in earlier semantic passes and **nine** newly compared here. Brunti has deliberately left the safe return route **alone**; neither Sira nor Velen shares these sightings.

| Source ID / delivery | Source detail present in actual page | Fate, limits and distinctions |
| --- | --- | --- |
| **20146 Eldritch Stronghold · Lived** | Huge **cube** of darksteel and old ironwood sunk into dead-tree roots, overgrown **multiple rusty locks**, metal water-drop knock, pale fungi and tiny insects | Sealed treasure remains unopened |
| **20147 Ironclad Reliquary · Lived** | **Different smaller rectangular** darkwood box bound by corroded iron; engraving continues under bands, **intermittent dull pulse**, leaf glimmer and beetle | No claim that this pulse matches Brunti's memorial or is the same chest |
| **20149 Tempest Fury · Lived** | **Enormous obsidian panther** with **spinal storm tentacles**, blue-white arcs and ozone, roaring/crouching, luminous point gathering between raised tips | Panther not reduced to a small cat, defeated or made a guardian of a door |
| **20150 Timberclaw Wretch · Lived** | Wrong-jointed tree-like creature, **burning knot eyes**, bark cracks, trailing **amber ichor**, one dragging arm and **five jagged claws breaking branch** | Distinct from the afflicted Gobbl encountered earlier |
| **20151 Auraglow Mireling · Lived** | Small **goblin-like** figure at stagnant pond, **gold light drains from pond and climbs into body**, water dims, bent crouching legs | Its resemblance does **not** prove Gobbl species or origin; magic function unknown |
| **20152 Echowraith Skulker · Lived** | Harsh **echo arriving early**, piecewise appearance (eye, claw, shoulder), disjointed smooth/jerking motion, arm frozen mid-raise, spectral claws | No invented prey or certainty whether ghost/material |
| **20153 Lumbering Necrobrute · Lived** | Colossal **Ogru-like decaying body**, hollow eye sockets, broken teeth, branch snapped by careless mass and long delays between footfalls | The former individual's identity not established |
| **20156 Twilight Whisper Grove · Lived** | Wisps make a **face appear then vanish in rotting bark**, shifting stumps, whisper and **hollow tree with root-deep recess** | No recorded dead speaker / memorial signal established |
| **20157 Enigmas End · Lived** | Constant **blue-white light**, two deceptive routes with same apparent direction, **shadow from nothing visible**, fog erases first passage leaving pale stones | Source spelling `Enigmas End` vs novel apostrophe **Enigma's End** is possessive punctuation, not a new place. Light source and exit remain unknown |

**Seam:** Chapter 24's two **separate** sealed chests are distinct from Chapter 23's colorful hag shop and Chapter 25's cliff door. The novel's other eleven Chapter 24 source encounters were checked in earlier Stage 5 semantic passes; a reader must still assess the **high density of twenty lived encounters and Brunti's alone-in-forest pacing** without converting the cluster into an unreviewed audio claim.

## 7. Chapter 25 — full three-ID Blackwood follow chain

[Chapter 25](../manuscript/chapters/25-the-door-in-the-cliff.md) is the hinge into the abyss; source/game and established world lore were read again.

| Game ID / follow | Source encounter feature and its specific lived rendering | Source-vs-novel boundary |
| --- | --- | --- |
| **20050 Blackwood Portal → 19666** | **Wooden runed door high in a cliff**, no visible access path, moving-looking symbols, pulsating dim light, low whispers and unnatural cold. Brunti climbs narrow ledges but **does not narrate opening the door**; subsequent location change is in lost memory | Established Blackwood Abyss lore explicitly records **no confirmed opening mechanism**, and many find the portal without entry |
| **19666 Tangled Depths → 19667** | **Enormous twisted shifting roots**, cold wet passages, soundless black drops, displaced geometry, wrong counts in Brunti's hand sketches, changed location of supplies | Maze and memory unreliability are **experienced**, not explained as a solved system; no stable atlas route invented |
| **19667 Blackwood Guardian → 19668** | **Ancient colossal black tree**, roots closing passage, long branches, indistinct whispers, and **one large root lifted above opening**. Brunti considers the game's old password or significant-object claim but cannot confirm it | The world archive says no **reliable** Guardian passage condition is established. After lamp failure a **missing interval** separates Brunti's last known position from her waking beyond. No narrated password, offering or ritual is asserted to have worked; **this is a deliberate fiction-level epistemic gap**, not a verified live game bypass |

**Follow order preserved exactly:** `20050 → 19666 → 19667 → 19668`. The next source **19668 Hollow Choir** and later linked abyss passages begin in [Chapter 26](../manuscript/chapters/26-the-voices-beneath.md), while Ch25's final view of inverted trees is only a **transition glimpse**, not an uncounted second Choir scene. **The central mechanism remains unproven**, matching [Blackwood Abyss](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Blackwood_Abyss.md) and [Blackwood Guardian](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Creatures/Guardians_and_Spirits.md), despite the game Guardian's categorical password/item wording. **Babuni's approved rule** permits retention of compatible older lore and layered witness accounts; it does not authorize claiming a universally reliable Blackwood unlocking method.

**Confirmed copyedit:** Chapter 25 repeated **“sat with her back against the damp wood”** after already depicting the same seated position, an acoustic/line-edit defect. The two adjacent sentences were merged into one restrained rest beat and wrist pain, preserving the later unexplained sound. **Chapter 25: 5,407 → 5,398 words (−9)**. No new passage resolution or encounter fate.

## 8. Cross-chapter and milestone outcome

- The four opening reports in Chapter 2 remain **different** from the four later wolves, the Keldor witness reports and any loved one identified near the novel's memorial. Grimnir injury is described in mineral terms despite human-body language in original encounter texts. The Ravage is not equated with all Gobbls or all corruption.
- Chapter 21 reunites Brunti with Sira via the relief system; search leads narrow in Chapters 22–23; the rescue is **achieved** and a **safe route home is available** before Brunti deliberately reenters alone in Chapter 24. This makes her costly error a character action, not a mission requirement.
- Chapter 24's twenty-source density and Chapter 25's memory-loss gates preserve supernatural uncertainty; no chosen-one rule, inevitable prophecy, cliff shortcut, new grimnir cure, or comprehensive explanation of Keldor is given. Chronology/atlas and spoken perception still require bookwide checking.
- **Targeted source-fidelity milestone:** **26 newly checked IDs**, without duplicates among the previous 177, hence **203/203** distinct game encounter descriptions compared directly with their own draft narrative passages.
- **Manuscript edits:** Chapter 22 **+1** word for returned-button consistency; Chapter 25 **−9** words for repetition; **net −8**, no source ID reassignment or plot/canon rewrite. All **30 chapters were refetched individually after both edits** in groups of ten. Standard whitespace-separated tokens with at least one Unicode letter or number: **Ch1–10 37,570**, **Ch11–20 52,476**, **Ch21–30 56,687**, **total 146,733** counted words including headings.
- **No independent human editor has approved these 203 integrations.** Targeted source hooks are now exhaustively compared, but **targeted checking is not an uninterrupted, comprehensive line-by-line novel read** or an audio performance test. Remaining Stage 5 acceptance gates: [109 scene briefs](../story/scenes/README.md) and each adapted scene's dramatic function, continuous character/prop/timeline consistency, place/atlas-scale geography, spoken pacing and distinct voices, and explicit separate human editorial acceptance. Known high-density listening risks remain Ch5 Nagar accounts, Ch7 chests, Ch13 distant injuries, Ch16 corruption records, Ch20 frozen sites and Ch24 forest encounter chain.
