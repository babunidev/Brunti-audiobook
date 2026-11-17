# Development journal

## 17 November 2026 — laying the first stones

For this book, my aim is to turn Morkahja's many isolated encounters into a journey capable of carrying other people's lives and memories beside the protagonist's own. A young warrior of the Grimnir makes it possible to begin in a civilization of crafted, moving stone rather than in the familiar shape of a human adventurer.

ChatGPT (**GPT-6**) reviewed GitHub sources, drafted the initial planning and documentation files, proposed a provisional plot direction and generated an encounter index directly from the game JSON. Source checking distinguished **Brunti the warrior (portrait 104)** from a same-name rogue (portrait 78), verified frame 75 and the corresponding image paths, and counted **203 unique encounters**: 130 base, 48 Keldor, 20 Everwinter and five Aetherion. Ten nonzero encounter follow-links were observed.

The audiobook repository was empty before this initialization. The files created here are a source-backed **foundation**, not proof of completed close prose reading, a plot approval, a written chapter, edited audio or publication. No source game or world lore was changed.

**Pinned sources:** Morkahja `58576f063627752f77cdf99514baad875d509114`, MorkahjaWorld `f56a7c3d2034652e1c5961f0ece9c3ef52b52b48`. The game and lore were inspected through the connected GitHub service; no audio or manuscript quality tests were performed.

## 17 November 2026 — from inventory to story architecture

My direction for the book remains one connected adventure that gives all the game encounters a literary place, even when the protagonist hears of a distant event through other lives. The survey revealed why a battle-by-battle transcription would weaken the source: the work contains everyday kindness, curious animals, regional culture, silent landscapes, dangerous thresholds and linked mythic passages.

ChatGPT (**GPT-6**) reviewed the source scenes at a first literary-survey level and consulted the relevant MorkahjaWorld entries. The AI drafted a provisional [30-chapter outline](../story/OUTLINE_V1.md), [203-entry placement matrix](../story/PLACEMENT_MATRIX.md), and [survey](../story/LITERARY_SURVEY.md). Its programmatic check compared every proposed ID against the exact pinned game JSON, initially caught a duplicated use of one source encounter, and verified the corrected mapping has **203 unique IDs, zero missing and zero extra**. The explicit Blackwood sequence and the three smaller follow pairs are preserved in order.

This is **planning**, not human approval, completed close prose editing, manuscript drafting, audiobook generation or a canon update. All invented premises and outcomes remain reviewable proposals. No production or game source changes are claimed.

### Later game-source reconciliation, same day

The game `main` had advanced beyond the content revision originally pinned for the atlas. ChatGPT (**GPT-6**) compared both full encounter JSON objects by encounter ID and per-field values: **203 IDs remained; 19 descriptions had changed; no other fields changed**. The changed Enigmatic Prairies prose specifically moved away from a vague prairie treasure rumor to a musical stone image, so the novel's proposed hook was corrected. The [source comparison record](SOURCE_RECONCILIATION.md) names the commits, blob IDs and affected records. This is source-review verification, not an editorial acceptance test of final book prose.

## 17 November 2026 — choosing the novel's Story Spine

After the 203-encounter placement work, the next challenge in my audiobook project was to give the journey a credible source of pressure and a personal ending. Creative drafting choices were explicitly delegated to ChatGPT at this stage, without changing who owns the underlying world and its established lore.

ChatGPT (**GPT-6**) reviewed the Grimnir source culture, Skyland architecture, memory stones, Evergrove, Keldor, Blackwood, the Ravage and Divine Laws, along with the first 30-chapter structure. The AI authored [Story Spine](../story/STORY_SPINE.md), [Character Arcs](../story/CHARACTER_ARCS.md) and [Causal Chain](../story/CAUSAL_CHAIN.md). The selected novel premise gives the opening resonance anomaly an accountable **local** craft explanation (two deceased people's memorial stones under an old shared casing) and separate, legitimate safety and preservation duties. Sira extends the source Bloomwalker as a fictional recurring character; Darrik and Velen are original.

The resulting ending keeps the identities of two separate memorials without compromising the safety of living Grimnir. The Blackwood descent remains a grave, unreliable encounter, not a universal explanation for Morkahja's mysteries. These files are **documented creative drafting**, not reviewed manuscript prose, game lore changes, source-edit verification or audiobook output. Additional per-scene and travel-continuity checks remain outstanding.

## 17 November 2026 — from chapter intention to scene action

With the working Story Spine in place, the next drafting problem was to make each encounter useful without allowing the audiobook to collapse into a sequence of game choices. A hundred small moments need different weights: some are direct experiences, others are remembered, reported, read from archives or given as the surrounding world's texture. My creative direction to include the complete encounter collection remains intact.

ChatGPT (**GPT-6**) authored five movement-level scene brief documents under [story/scenes](../story/scenes/README.md). Each scene records what happens, how it changes the characters or circumstances, and which source encounters contribute distinctive details. The five documents contain **109 scenes across 30 chapters**. A programmatic comparison of their source-ID annotations against the original placement matrix confirmed **203 distinct assignments, 0 missing, 0 duplicates, 0 extra and 0 wrong chapter matches**. The three short follow sequences, Blackwood's eight-part sequence and the seven letter inscriptions retained their intended order.

The AI also compared the newer game JSON against the previous reviewed revision and recorded **five additional text-only edits** without changes to IDs or follow links. A [continuity register](SCENE_CONTINUITY.md) now records specific source-confirmed constraints and unresolved routes, including the Cliffs of Sarga, the displaced child's invented history, Sira's time apart from the party and the Blackwood Portal's unverified mechanism. This is an **editorial planning and structural-verification result**, not a complete paragraph-by-paragraph literary audit or the first manuscript chapter.

## 17 November 2026 — the first two chapters become prose

For this novel, the sound of a Skyland should be lived rather than described from outside, and the first injury should follow Brunti's own decision rather than a chosen enemy's attack. My source world already gives the Grimnir memorial stones, moving cities, communal care and the duty of reliable craft; the story's specific failure and relationships are new fiction.

ChatGPT (**GPT-6**) authored [Chapter 1, Skyland Morning](../manuscript/chapters/01-skyland-morning.md), **3,249 words**, and [Chapter 2, The Weight of Other Stones](../manuscript/chapters/02-the-weight-of-other-stones.md), **3,313 words**, as readable first-draft prose. Chapter 1 carries the household craft scene, resonance accident, Darrik's protective work and conditional council permission. Chapter 2 gives five distinct game encounters a credible form as witnessed or transmitted accounts, then places the earliest transport-ledger clue in Brunti's hands. Both chapters preserve the selected character arc and the safety concerns of the living.

The AI reread five complete game encounter descriptions and checked selected Grimnir world-lore entries. A [manuscript review record](MANUSCRIPT_REVIEW.md) names the source conflicts where encounter text uses human anatomical details despite canonical Grimnir physiology; it also records Stonefist Ironwill's mismatched gender pronouns between game and world archive. Structural totals are **2 prose chapters**, **6,562 draft words**, **5 encounter integrations drafted**, **198 planned**, and **0 independently editorial-verified**. A later game-source refresh changed only encounter 20081 (no Chapter 2 source), and was separately reconciled. No audio was generated and no canonical Morkahja data was edited.

## 17 November 2026 — the road begins; letters remain letters

The opening chapters now have to move beyond the Skyland without losing Brunti's personal reasons for traveling. My aim remains a living journey: meadows and ordinary creatures deserve as much attention as the astonishing relics, and a scene only counts when it shapes the reader's experience rather than being checked off as source inventory.

ChatGPT (**GPT-6**) wrote two more first-draft prose chapters: [A Road Made of Grass](../manuscript/chapters/03-a-road-made-of-grass.md) (**3,225 words**) and [Letters Without a Word](../manuscript/chapters/04-letters-without-a-word.md) (**3,681 words**). The AI checked all **22 full game texts** assigned to these chapters against the current pinned source and read relevant Ethera's Vale, Vale landmarks, Grimnir Skylands and traveler records. It adapted the Earthsinger's lived challenge, the separate meadows and pillars, the seven engraved **A H K J O M A** letters, a second-hand cube account, and the Bloomwalker's invitation that brings Sira into the story.

A seasonal continuity conflict in the plan was resolved explicitly: the **autumn fox** of encounter 20072 is **Eda's reported memory**, not something Brunti witnesses during her summer Vale journey. A [new review record](CHAPTERS_03_04_REVIEW.md) documents source-specific integrations, original-fiction additions and remaining geographic unknowns. The draft-status ledger now records **four prose chapters**, **13,468 words including headings**, **27 drafted source integrations**, **176 planned**, and **0 independently editorial-verified**. No canonical-world, game or audio files were changed.

## 17 November 2026 — animal passages and the light beneath Eldertree

The next movement of my novel needs to give wild creatures and forgotten craft their own space; not everything seen beside the road should become an opponent or a treasure awarded to Brunti. The growing friendship with Sira also needs to change both travelers' immediate choices, rather than simply decorate the journey.

ChatGPT (**GPT-6**) wrote [The Lives of the Vale](../manuscript/chapters/05-the-lives-of-the-vale.md) (**3,825 words**) and [Under Eldertree](../manuscript/chapters/06-under-eldertree.md) (**3,871 words**) as uninterrupted first-draft novel prose. The AI compared all **24 assigned complete game descriptions** with the text and read relevant world records for Nagar, wolves, Eldertree and Aevis. A tracker named Mara carries the varied animal reports. Brunti's deliberate departure from the wolves' den gives a concrete consequence to her growing restraint; Sira hears Brunti's own account of the Skyland's damaged memorial, and the forest's small, protected sanctuary offers a genuine interval of rest.

Two source differences are recorded in the [review](CHAPTERS_05_06_REVIEW.md): encounter 20007's “Aevis royal house” crest has no confirmed monarchy in the council-governed world archive, and the old “dworv” description in 20040 cannot by itself establish another race. Both remain attributed uncertain details instead of new game canon. While drafting, the live game source changed the prose of 20082 and 20083; [reconciliation](SOURCE_RECONCILIATION.md) was recorded, and Chapter 4 was edited to preserve the new Enchanted Gardens note. The book now has **six draft chapters, 21,197 words including headings, 51 adapted encounters, 152 planned, none editorially verified**. No audio was made and no source game or world files were modified.

## 17 November 2026 — what may be kept, and where a road should stop

My encounter-world contains many objects and hidden places, but the audiobook needs their particular lives and distinct ownership rather than a repeating sequence of locks to break. Brunti's changing craft ethic can be heard in the moments she leaves a casket intact, listens to someone else's account and admits a living forest has its own limits.

ChatGPT (**GPT-6**) wrote first-draft [Things That Are Kept](../manuscript/chapters/07-things-that-are-kept.md) (**3,504 words**) and [At the Green Boundary](../manuscript/chapters/08-at-the-green-boundary.md) (**3,131 words**). It read the **16 assigned game scene texts** and relevant world forest/Liani accounts. The AI corrected the early chapter plan's error of bringing the northern Grimnir Trunk (20008) and Vault (20009) physically into Eldertree; **Teren's attributed drawings** preserve their actual Frostwind/Deepstone setting. Both delivery modes and scene notes were updated. The Liani Shadowwolf, Guardian, reported Predator and Thunderfly Matriarch remain distinct; Brunti turns back without discovering any fixed portal or compulsory reward.

The [Chapter 7–8 review](CHAPTERS_07_08_REVIEW.md) documents the corrections and still-unverified travel details. Current verifiable structure: **8 manuscript draft chapters, 27,832 words including headings, 67 encounter IDs in prose, 136 not yet drafted, zero independent editorial approvals**. No new audio, game files or world lore were committed.
