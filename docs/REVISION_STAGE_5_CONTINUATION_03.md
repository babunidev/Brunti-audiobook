# Stage 5 — continuation C: Vale wildlife, Eldertree and Liani boundary (Chapters 5–8)

**18 November 2026 | Targeted AI source-to-manuscript audit by ChatGPT (GPT-6) under Babuni's creative direction.** Manuscript remains draft fiction and source-adaptation work, **not** an approved/canonical game story, human editorial approval, read-aloud review, narrator script, or recording.

## Scope and current source pin

- **Current audiobook source:** `main` at the start of this continuation, [`dde7ae06bcc16620453b1ce562a97ab6692f97f3`](https://github.com/babunidev/audiobookGrimnir/tree/dde7ae06bcc16620453b1ce562a97ab6692f97f3).
- **Current game source parsed and checked:** [Morkahja `2ba61f5a6bcde383ed2a931c3d2a06c87404dffd`](https://github.com/babunidev/Morkahja/blob/2ba61f5a6bcde383ed2a931c3d2a06c87404dffd/server/game/encountersdata.json).
- **Literary baseline comparison:** [Morkahja `952437c5c59da26a2f873f1a18590496f88a2354`](https://github.com/babunidev/Morkahja/blob/952437c5c59da26a2f873f1a18590496f88a2354/server/game/encountersdata.json). **All 40 Chapters 5–8 source JSON objects are exactly unchanged** between these two versions, including prose, titles, IDs and follow metadata. The game has other changes elsewhere in the 203-record catalog, already covered in [continuation B](REVISION_STAGE_5_CONTINUATION_02.md).
- **Manuscript passages directly read:** [Chapter 5](../manuscript/chapters/05-the-lives-of-the-vale.md), [Chapter 6](../manuscript/chapters/06-under-eldertree.md), [Chapter 7](../manuscript/chapters/07-things-that-are-kept.md) and [Chapter 8](../manuscript/chapters/08-at-the-green-boundary.md). Their assigned source passages were checked against the full current encounter descriptions and the [placement matrix](../story/PLACEMENT_MATRIX.md), with Chapter 4's closing meeting and Chapter 7's opening/continuity also inspected.
- **Canonical comparison reopened at pinned MorkahjaWorld `f56a7c3d2034`:** [Nagar](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Creatures/Nagar.md), [Wolves and Liani](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Creatures/Wolves_and_Liani.md), [Eldertree Forest](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Eldertree_Forest.md), [Eldertree Landmarks](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Eldertree_Landmarks.md), [Aevis](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Races/Aevis.md), [Emerald Realm](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Emerald_Realm_of_the_Liani.md) and [Unresolved Creature Traditions](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Creatures/Unresolved_Creature_Traditions.md).

**Unique-check accounting:** [Stage 5 first batch](REVISION_STAGE_5_SEMANTIC_REVIEW.md) reviewed 54 IDs; [continuation B](REVISION_STAGE_5_CONTINUATION_02.md) added 20 = 74. This pass checks **40 source IDs** assigned to Chapters 5–8, of which **six were already checked**: `20039`, `20065`, `20093`, `20096`, `20036` and `20115`. Thus **34 new distinct IDs** are added. Running total **108/203 AI-targeted scene-hook/source comparisons**, leaving **95** not individually checked. **None is independently human approved.**

## A. Chapter 5 — sixteen source IDs, thirteen new targeted checks

| ID | Source-specific evidence observed in the current chapter | Status |
| ---: | --- | --- |
| 20032 Rare Treasurechest | Mara describes aged green bronze, flower-covered Seraphic/Sepharic Plains setting, fitted levers and delicate gear lock; ownership not invented | New: Testimony hook |
| 20033 Wild Bloodfang | Mud-scarred dark boar charges with projecting horns and long fangs; Brunti physically moves Sira aside rather than manufacturing a victory | New: Lived hook |
| 20034 Menacing Goldhorn | Mara's earlier report preserves great golden horns, dust and forceful charge | New: Testimony hook |
| 20051 Nagar Charger | Mara cites driver, crimson eyes, enormous curved tusks, rapid sustained charge and displaced stones | New: Testimony hook |
| 20052 Nagar Elder | Mara distinguishes weathered scarred shoulders, worn tusks, long attention and warning scrape before possible charge; no formal animal rank invented | New: Testimony hook |
| 20065 Zeelai Feline | Pale sparks and unstable feline shape with fading grass, partly dissolving foreleg and imminent leap are contained in Mara's separate account | **Rechecked; previously counted** |
| 20067 Ferocious Silvermane | A dark-flanked, silver-shouldered, heavy-clawed predator stands in moonlight, bares teeth and withdraws; no identity conflation with cursed Keldor variants | New: Lived hook |
| 20091 Nagar Berserk | Mara's distinct raging boar description retains violent branch breaks, lowering tusks and hot nostril vapor | New: Testimony hook |
| 20092 Nagar Boar | Brush-camouflaged grey-brown animal, testing nostrils, one hard-set hoof and tensed shoulders | New: Testimony hook |
| 20093 Bonecrusher | Pale scarred boar, red eyes, worn horn edges and broken branch crushed beneath immense hoof | **Rechecked; previously counted** |
| 20094 Nagar Humpback | Distinct raised back, oversized neck/shoulders and tusk snagging branch before shower of leaves | New: Testimony hook |
| 20095 Nagar Razorback | Jagged spine projections, turn around fallen trunk and hind-hoof ground spray | New: Testimony hook |
| 20096 Thunderhoof | Trembling pebbles before approach, enormous horns, suspended hoof and dirt-bank shudder | **Rechecked; previously counted** |
| 20097 Yowler | Separate two-call wolf from outcrop, mismatched ear direction, distant echoes and lowering growl | New: Lived hook |
| 20110 Mother Wolf | Grey-brown mother, whimpering cub, oversized paw, body blocking den opening and warning growl; travelers withdraw | New: Lived hook |
| 20111 Young Redeye | Russet playful pup with crimson eyes, asymmetric ears, butterfly, flower-sneeze and ungainly tumble. **No assumed maternity from 20110** | New: Lived hook |

**Literary finding:** The live Bloodfang incident changes Brunti's behavior before Mara shares her field stories; the Silvermane and wolves test that learning in lived situations. The brief comic Redeye moment returns the story to ordinary animal life. The eight distinct `Charger/Elder/Berserk/Boar/Bonecrusher/Humpback/Razorback/Thunderhoof` descriptions, however, occur in a **single extended campfire account**. Their specific hooks are present, but sequential names and physical traits are a **medium-priority oral comprehension concern**, not an evidence-based omission. Any restructuring must retain their distinct identities, narrative testimony status and the surrounding companion dynamics. **No speculative rewrite applied.**

## B. Chapter 6 — eight source IDs, seven new targeted checks

| ID | Source-specific evidence observed in the current chapter | Status |
| ---: | --- | --- |
| 20006 Aevis Chest | Large fine Aevis feather/wind chest, root shelter and intricate lock; owner and contents unknown | New: Lived hook |
| 20007 Aevis Lockbox | Smaller opalescent metal box, featherwork and gilded crest. The merchant's “royal” attribution is **explicitly unconfirmed** against Aevis council culture | New: Lived hook |
| 20011 Magic Source | Waterlike luminous fount, sparks, momentary star patterns, resonance and a choice **not** to touch unknown magic | New: Lived hook |
| 20039 Eldertree Grove | Immense tree, ancient large carvings associated with first giants, delicate Verdani pattern and watery trunk vibration | **Rechecked; previously counted** |
| 20040 Shadowed Hollow | Narrow root-and-ivy cave, metal/crystal veins, old rough mining-tool cuts and fae-like marks, drip and distant resonance; **no invented dworv people** | New: Lived hook |
| 20041 Sunlit Dell | Warm clearing, broad old stone seats and curved traces of dancing; giant/faun references remain stories, not certified authorship | New: Lived hook |
| 20042 Enchanted Hollow | Keeper retells hidden fae-den glow, old root marks and seeming voices without claiming the travelers found or entered the location | New: Testimony hook |
| 20043 Sylvan Sanctuary | Actual cliff-side moss-lit shelter, roots, ferns, nearby stream and ordinary rest; no formal worship of Sylvanus asserted | New: Lived hook |

**Lore finding:** The canonical Aevis archive establishes resonance councils, not a confirmed royal dynasty; the “royal house” label in the older game encounter is therefore preserved *as an unverified merchant story*, not a world fact. Older “dworv” wording likewise remains an unresolved tradition, and the manuscript names no such miners. The great-tree carvings remain traditions of first giants and Verdani song-making, rather than proof of ancestral authorship. The small Sylvan Sanctuary stays a natural refuge. **No new blocking contradiction established in these four chapters.**

## C. Chapter 7 — twelve new targeted checks

| ID | Source-specific evidence observed in the current chapter | Status |
| ---: | --- | --- |
| 20008 Grimnir Trunk | Frost-covered stone/metal container with runes and hidden plates is **a named northern survey copy from Frostwind near Deepstone**, supplied by Teren | New: Archive hook |
| 20009 Grimnir Vault | Distinct immense vault door in **Deepstone near Everwinter**, icicles, masonry and shaped-keystone opening; second northern drawing | New: Archive hook |
| 20010 Verdani Casket | Dark carved timber, leaves/creatures/stems, fern bed and shaped wooden keyhole; object physically found and left closed | New: Lived hook |
| 20045 Tranquil Glade | Sunlit pine stream, moss, clear water, flower insects and rest; not a magical solution | New: Lived hook |
| 20046 Feral Hollow | Root-arched sheltered lair, moss and pine needles; animal hair/pressed bedding plausibly adds caution, not confirmed tenant identity | New: Lived hook |
| 20047 Moonlit Oasis | **Forest pond**, lights/fog, fireflies and sleeping ducks, explicitly not Evergrove's desert oasis infrastructure | New: Lived hook |
| 20048 Grimnir Steps | Moss-covered stone stair rising under roots and historical underground-route legend kept uncertain; the small clasp is novel-only | New: Lived hook |
| 20049 Firefly Brook | Distinct night stream with fireflies, owl, distant wolf and whisper-like water; forest spirits remain hearsay | New: Lived hook |
| 20068 Fey Greens | Elder traveler's **secondhand** account of great standing rock, carved refuge, deer/stag and treasure rumor; “faun craft” is a reported tradition | New: Testimony hook |
| 20073 Celestial Cairn | Stream platforms, guardian sculpture, rain-softened face, resting platform and quiet current heard directly | New: Lived hook |
| 20098 Common Chest | Acorn knocks on scratched polished wood, old brass lock and delicate spiderweb under large roots; unopened | New: Lived hook |
| 20119 Simple Treasure | Different light-brown meadow chest, tiny carved travelers/buildings, reflective brass lock and shaded keyhole; unopened | New: Lived hook |

**Source-order finding:** The physical Eldertree discovery cluster does **not** move 20008/20009 from northern Frostwind to the forest: the two distinct archival drawings retain source geography and provenance. Three visited woodland chests are kept separate from them, and the two night waters are separate settings. The passage from Ch6's Sylvan Sanctuary into Ch7's morning is continuous, including Brunti's earlier repaired knot.

## D. Chapter 8 — four source IDs, two new targeted checks

| ID | Source-specific evidence observed in the current chapter | Status |
| ---: | --- | --- |
| 20036 Liani Shadowwolf | Dark fur conceals unmoving watcher, with no demanded answer or permission to enter | **Rechecked; previously counted** |
| 20114 Liani Guardian | Separate luminous emerald wolf holds the tree-gap boundary, measured paw placement, jade gaze and attention to falling leaf | New: Lived hook |
| 20115 Liani Predator | Halven's separate report of low, concealed green stalking wolf, eyes, unsnapped twigs, lifted paw and hunting attention | **Rechecked; previously counted** |
| 20117 Thunderfly Matriarch | Huge sapphire/silver winged matriarch with multifaceted eyes, charged blue antennae, wind-scattered leaves and sudden downwash seen directly | New: Lived hook |

**Boundary finding:** The [Emerald Realm](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Emerald_Realm_of_the_Liani.md) lies *inside* Eldertree; the Guardian's presence is not a game-certified verbal gate rule. The Shadowwolf does not become the Guardian, and Halven's Predator sighting is neither of the animals Brunti meets. After the Matriarch Brunti/Sira return to an ordinary wayhouse and hear a market story; Celesterra is described by that speaker as a **city beneath the earth**, not a sudden surface city or Brunti's new destination by teleportation.

## E. Narrative seams and remaining editor/read-aloud work

- **Ch4 → 5:** Sira meets Brunti near the end of Ch4 and walks with her into Ch5. Her messenger duties remain hers; Mara becomes an original field guide in Ch5 rather than a source-canon figure.
- **Ch5 → 6:** The entry under Eldertree branches at the end of Ch5 leads to the forest path's uncertain turns in Ch6; MorkahjaWorld explicitly notes that disorienting paths may appear to rearrange. No new transport shortcut is claimed.
- **Ch6 → 7:** Sylvan Sanctuary, keeper's marker fastening, morning departure and two northern archival records retain continuous custody and source provenance.
- **Ch7 → 8:** The forest record lead remains available when the companions choose the short Liani-boundary detour; they return to public roads rather than entering an invented hidden political realm.
- **Audio watchlist:** Ch5's eight-boar campfire catalogue risks sound-alike names and back-to-back physical traits, while Ch7 has three lived chests plus two archival containers. Both are **distinct and source-present**; neither sequence has undergone a recorded listening test. A selective performance review should determine whether pacing—not source omission—is the actual problem.
- **Voice/canon limit:** All four chapters were read here with their current source descriptions and selected pinned lore entries, but no continuous 30-chapter listening pass, full atlas-scale distance check, professional voice differentiation, human approval, or audio recording was performed.

**Outcome:** **40/40 Chapter 5–8 IDs have a distinct located scene or explicitly documented account, with correct literary delivery forms.** Six were already counted in earlier Stage 5 reviews; **34** are newly counted. **Running total 108/203 targeted source/scene checks; 95 pending.** No manuscript prose file was changed during this package because the checked scenes did not establish a new hard error requiring a speculative alteration. Their status remains **AI-targeted fidelity check, not editorial approval**. Previous [Stage 5 source issue at the Nereval river rune](REVISION_STAGE_5_CONTINUATION_02.md) remains open and outside these chapter targets.

## F. Repository integrity and distinct-ID recount

At audiobook `main` revision [`e04d45ccbc43f0552053a50d67c0e19b8cb74b1f`](https://github.com/babunidev/audiobookGrimnir/tree/e04d45ccbc43f0552053a50d67c0e19b8cb74b1f), the GitHub tree was fetched recursively without truncation. **All nine Markdown documents created/edited in this continuation** were read back and their **382 relative Markdown link destinations** were checked against tracked file paths: **zero missing destinations**. This test does not validate anchor fragments, external websites, render quality or audio.

The three targeted audit ledgers were independently parsed for explicit table-ID entries and the union compared with the **203 current game `mEncounterID` values**: first ledger **57 table appearances / 54 unique**, continuation B **22 table appearances / 22 unique** (including two deliberate rechecks), continuation C **40 appearances / 40 unique**. The **final union is exactly 108 distinct IDs**, all found in game source, with **95** remaining. The six duplicate IDs counted in continuation C are `20039, 20065, 20093, 20096, 20036, 20115`. The game source count includes normalized numeric IDs **1** and **2** corresponding to JSON keys `00001` and `00002`.

No novel chapter files were changed in this package, so the previous full-manuscript count **146,742** remains the last directly measured count rather than a new recount. **Verification is restricted to source-ID traceability and local link-path existence; prose, canon, timing, oral delivery and human acceptance remain open.**
