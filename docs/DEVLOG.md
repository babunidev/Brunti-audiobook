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
