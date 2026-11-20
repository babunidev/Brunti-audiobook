# Brunti audiobook — ElevenLabs v3/v4 narration scripts

**19 November 2026 | First derived narration scripts.** Prepared by **ChatGPT (GPT-6)** at Babuni's request. The **30 complete `.txt` files** contain the current manuscript chapter text with intentional speech-pacing markers. The source novel remains separately maintained in [`manuscript/chapters/`](../../../manuscript/chapters/README.md). **The complete chapter list here is a ready-to-import production draft, not generated or approved audio.**

**20 November 2026 update:** Babuni has imported the scripts for Chapters 1–7 unchanged into ElevenLabs Studio and rendered them with a cloned voice; Chapter 1 is published. See the [production status](../../README.md#current-workflow-babuni-20-november-2026).

## How these differ from the literary manuscripts

- One **individual plain-text script per chapter**, with a human-readable chapter title as the first line. If pasted directly into text-to-speech, the title may be spoken. In Studio, avoid accidentally narrating a title twice if it is also supplied as chapter metadata.
- Original manuscript's standalone `***` scene dividers are replaced by **`[pause]`**, with surrounding blank lines. Ordinary paragraphs and dialogue remain in their original sequence; **53 selectively placed performance cues** now precede particular spoken lines. No synthetic laughter, sobbing, extra dialogue, speaker switches or environmental sound effects have been added.
- Every chapter has exactly one final **`[long pause]`** cue after its last actual prose sentence. This applies to **Chapter 30** as an ending tail, too.
- The **first prose line of each following chapter has no automatic introductory pause**; a chapter join should be produced via **real timed silence**, not by trusting the preceding chapter's terminal tag.
- Inline Markdown emphasis markers are removed for plain-text performance. The words and punctuation of the novel are otherwise retained, and the exported text is not a new literary rewrite.
- **Only ElevenLabs v3/v4 square-bracket tags** are used. No SSML break tags, v2 syntax or proprietary TTS commands are included.

## Selected performance cues — editorial pass of all 30 chapters (19 November 2026)

Following Babuni's explicit request for the **entire book** to receive carefully chosen Eleven v3/v4 audio tags, ChatGPT (**GPT-6**) reopened **all 30 full narration scripts** and placed **53 voice-only direction tags** next to actual relevant speech. This is an **editorial production pass**, not an automatic regex applied to every emotional word in the novel.

| Cue | Count | Intended use |
| --- | ---: | --- |
| `[thoughtful]` | 15 | Measured reflections and consequential statements |
| `[softly]` | 14 | Gentle conversation, quiet care or subdued speech |
| `[curious]` | 12 | Genuine questions and moments of discovery |
| `[whispers]` | 9 | Quiet warnings and dialogue already explicitly whispered |
| `[mischievously]` | 2 | Small, context-supported moments of teasing |
| `[shouts]` | 1 | A single call that the prose expressly describes as shouted |
| **Total** | **53** | **One or two cues per chapter; no overacting** |

**Examples:** [Chapter 5](05-the-lives-of-the-vale.txt) marks the already-whispered question about an animal's cub; [Chapter 10](10-the-shelter-beyond-the-veil.txt) marks Brunti's explicitly shouted road warning; [Chapter 23](23-those-who-still-tend-the-forest.txt) marks the child's quiet “You can”; [Chapter 29](29-the-work-of-bringing-back.txt) gives reflective delivery to Brunti's accountable homecoming statement. The eerie [Blackwood sequence](25-the-door-in-the-cliff.txt) intentionally has very few tags, leaving atmosphere to the prose and the existing pauses.

**Verification:** Reopened every amended script **and its corresponding canonical chapter**. Removing only the 53 new performance tags reproduces the prior clean narration output exactly, including **271 existing `[pause]` scene separators**, **30 `[long pause]` chapter endings**, chapter titles, wording and order. No manuscript was changed, so the book still counts **146,816 words**.

**Auditory limitation:** v3/v4 tags are generative directions, not fixed performances. The selected narrator may interpret them differently or occasionally speak an instruction. No ElevenLabs voice output has yet been rendered and listened to. Remove or refine any specific tag that sounds artificial; do not assume every cue will be retained in final mastered audio.

## Import and chapter-break handling

1. Import or paste **each numbered `.txt` file into its own ElevenLabs Studio chapter**, in numerical order. Keep the first-line title only if the audiobook narrates chapter titles; otherwise use Studio's chapter label without voicing it twice.
2. Render at the selected Eleven **v3 or v4** voice setting. `[pause]` at scene changes and `[long pause]` at chapter ends are **instructions, not guarantees**. Listen for any tag accidentally read aloud, overly long/short gaps, and undesired delivery changes.
3. At **every chapter join (1→2 ... 29→30), ensure a real approximately 3-second silent interval** between the **end of the previous chapter's last audible word** and **the following chapter's first audible word/title**. Use Studio's timeline or final assembled audio; a terminal tag in a separately rendered file **may not survive generation/export**.
4. Listen particularly to **Chapter 2→3**: Chapter 2's final words are “Brunti did not try to make them one.” Chapter 3's first spoken line after its chapter title is “The ground was still moving when Brunti stepped off the descent platform.” Confirm that these do **not run together**.
5. For audiobook player playback (website/game), retain the same timed chapter gap when files are queued sequentially. Test the actual player, not only the ElevenLabs generation preview.
6. Review expressive tags **later by ear** in a few carefully chosen passages; avoid mass insertion into every line of dialogue.

## All 30 chapters

| Chapter | Narration script | Original literary source |
| ---: | --- | --- |
| 1 | [skyland morning](01-skyland-morning.txt) | [Novel source](../../../manuscript/chapters/01-skyland-morning.md) |
| 2 | [the weight of other stones](02-the-weight-of-other-stones.txt) | [Novel source](../../../manuscript/chapters/02-the-weight-of-other-stones.md) |
| 3 | [a road made of grass](03-a-road-made-of-grass.txt) | [Novel source](../../../manuscript/chapters/03-a-road-made-of-grass.md) |
| 4 | [letters without a word](04-letters-without-a-word.txt) | [Novel source](../../../manuscript/chapters/04-letters-without-a-word.md) |
| 5 | [the lives of the vale](05-the-lives-of-the-vale.txt) | [Novel source](../../../manuscript/chapters/05-the-lives-of-the-vale.md) |
| 6 | [under eldertree](06-under-eldertree.txt) | [Novel source](../../../manuscript/chapters/06-under-eldertree.md) |
| 7 | [things that are kept](07-things-that-are-kept.txt) | [Novel source](../../../manuscript/chapters/07-things-that-are-kept.md) |
| 8 | [at the green boundary](08-at-the-green-boundary.txt) | [Novel source](../../../manuscript/chapters/08-at-the-green-boundary.md) |
| 9 | [where stories are sold](09-where-stories-are-sold.txt) | [Novel source](../../../manuscript/chapters/09-where-stories-are-sold.md) |
| 10 | [the shelter beyond the veil](10-the-shelter-beyond-the-veil.txt) | [Novel source](../../../manuscript/chapters/10-the-shelter-beyond-the-veil.md) |
| 11 | [the city of listening](11-the-city-of-listening.txt) | [Novel source](../../../manuscript/chapters/11-the-city-of-listening.md) |
| 12 | [where water is guarded](12-where-water-is-guarded.txt) | [Novel source](../../../manuscript/chapters/12-where-water-is-guarded.md) |
| 13 | [after the raid](13-after-the-raid.txt) | [Novel source](../../../manuscript/chapters/13-after-the-raid.md) |
| 14 | [words in the sand](14-words-in-the-sand.txt) | [Novel source](../../../manuscript/chapters/14-words-in-the-sand.md) |
| 15 | [beneath the reeds](15-beneath-the-reeds.txt) | [Novel source](../../../manuscript/chapters/15-beneath-the-reeds.md) |
| 16 | [witnesses of corruption](16-witnesses-of-corruption.txt) | [Novel source](../../../manuscript/chapters/16-witnesses-of-corruption.md) |
| 17 | [the mountain has a voice](17-the-mountain-has-a-voice.txt) | [Novel source](../../../manuscript/chapters/17-the-mountain-has-a-voice.md) |
| 18 | [the last warm bowl](18-the-last-warm-bowl.txt) | [Novel source](../../../manuscript/chapters/18-the-last-warm-bowl.md) |
| 19 | [ice that remembers](19-ice-that-remembers.txt) | [Novel source](../../../manuscript/chapters/19-ice-that-remembers.md) |
| 20 | [the broken frostweaver record](20-the-broken-frostweaver-record.txt) | [Novel source](../../../manuscript/chapters/20-the-broken-frostweaver-record.md) |
| 21 | [before the cursed trees](21-before-the-cursed-trees.txt) | [Novel source](../../../manuscript/chapters/21-before-the-cursed-trees.md) |
| 22 | [the price of warning](22-the-price-of-warning.txt) | [Novel source](../../../manuscript/chapters/22-the-price-of-warning.md) |
| 23 | [those who still tend the forest](23-those-who-still-tend-the-forest.txt) | [Novel source](../../../manuscript/chapters/23-those-who-still-tend-the-forest.md) |
| 24 | [paths among the dead](24-paths-among-the-dead.txt) | [Novel source](../../../manuscript/chapters/24-paths-among-the-dead.md) |
| 25 | [the door in the cliff](25-the-door-in-the-cliff.txt) | [Novel source](../../../manuscript/chapters/25-the-door-in-the-cliff.md) |
| 26 | [the voices beneath](26-the-voices-beneath.txt) | [Novel source](../../../manuscript/chapters/26-the-voices-beneath.md) |
| 27 | [what the throne keeps](27-what-the-throne-keeps.txt) | [Novel source](../../../manuscript/chapters/27-what-the-throne-keeps.md) |
| 28 | [a story about the end](28-a-story-about-the-end.txt) | [Novel source](../../../manuscript/chapters/28-a-story-about-the-end.md) |
| 29 | [the work of bringing back](29-the-work-of-bringing-back.txt) | [Novel source](../../../manuscript/chapters/29-the-work-of-bringing-back.md) |
| 30 | [the note that remains](30-the-note-that-remains.txt) | [Novel source](../../../manuscript/chapters/30-the-note-that-remains.md) |

## Source control and verification

Every script was derived from the corresponding chapter's current `.md` at generation and checked to round-trip to the same source text **after restoring scene dividers, chapter-title Markdown and italics formatting and removing production cues**. Chapter source files were not modified. **Production scripts are snapshots**: if the literary chapters are revised later, the matching narration scripts need to be refreshed and rechecked before recording, rather than being edited as a new literary canon.

See the [ElevenLabs v3/v4 production guide](../../ELEVENLABS_V3_V4.md) for detailed timing and audio-tag behavior. **No Studio account edit, rendered audio, actual inter-chapter silence verification, narrator approval, mastering, or publication is claimed.**
