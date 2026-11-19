# ElevenLabs v3/v4 audiobook narration and pause guide

**19 November 2026 | Production working guideline, requested by Babuni; drafted by ChatGPT (GPT-6).**

**Model selection is an explicit human decision:** use **Eleven v3** and **Eleven v4** for the Brunti audiobook. No other narration model is in scope. Babuni reports that an externally generated Chapter 2 runs directly into Chapter 3 without an audible separation. This guide addresses **chapter joins, scene pacing and subtle performance**, while keeping the novel's source prose unchanged. There is **no audio file or validated Studio project in this repository**.

## Two different kinds of pauses

1. **Interpretive narration pause:** In the generated speech, insert an audio tag such as `[pause]`, `[short pause]` or `[long pause]` at a meaningful point *within the text*. Eleven v3/v4 can use these square-bracket cues to influence delivery. **Their durations are not exact**, and results depend on the selected voice and generation.
2. **Actual timed chapter break:** When one recorded chapter ends and the next begins, establish an **audible measured interval in the ElevenLabs Studio timeline or audio assembly**, provisionally **3 seconds of silence between the last spoken sound of one chapter and the next chapter title/first word**. Studio offers an **Insert break** control (default 1 second, adjustable up to 3 seconds), but for precise timing its timeline controls are more reliable. An inserted pause or audio tag may be shortened or ignored by some models. A pause tag placed **after the final line of a separately generated chapter** is not sufficient evidence that the assembled audiobook has a real gap.

**There is no need to insert technical text into the literary manuscript.** [Chapters 1–30](../manuscript/chapters/README.md) remain clean novel prose. Narration direction belongs in a **separate, derived script** or in Studio's editing/timeline layer. The same script direction convention applies to both v3 and v4.

## Working editorial pause convention

| Location | Starting choice | Verify during listening |
| --- | --- | --- |
| Ordinary sentence or paragraph | No explicit tag; use existing punctuation and paragraph structure | Natural, unforced flow |
| Significant hesitation or revelation | `[short pause]` or `[pause]`, used sparingly | Meaningful pause without exaggerated drama |
| Distinct scene transition (the manuscript uses `***`) | A restrained `[long pause]` where needed, or an adjusted clip gap in Studio | Start around **1–2 seconds**; not every scene deserves the same gap |
| **Chapter → next chapter** | **Studio/audio timeline: 3 seconds of real silence** as a working default | Listen to the *joined chapters*, not only to each isolated generation |
| Closing chapter or audiobook ending | Deliberate natural tail and final mastering silence | No automatic spoken instruction or artificial dramatic gasp |

The approximate durations above are **our production targets**, not v3/v4 promises. Both models use audio tags; **neither supports SSML `<break>` controls**. Avoid misleading markup that will be spoken aloud, and do not insert a pause after each line or every piece of dialogue.

## The exact Chapter 2 → Chapter 3 case

The current [Chapter 2](../manuscript/chapters/02-the-weight-of-other-stones.md) ends:

> Behind her, somewhere beyond the closed passage, the memorial kept its two quiet rhythms.
>
> Brunti did not try to make them one.

[Chapter 3](../manuscript/chapters/03-a-road-made-of-grass.md) opens:

> The ground was still moving when Brunti stepped off the descent platform.

**Recommended production workflow:**

1. Keep Chapter 2 and Chapter 3 as **different chapters** in the Studio project, with their actual headings. Correct chapter structuring prevents an unbroken paragraph-only import and supports navigation. ElevenLabs Studio can recognize imported chapter structure in well-formed documents; confirm it after import.
2. Generate the final lines of Chapter 2 and first lines of Chapter 3 with the chosen v3/v4 voice. If a title is narrated, it belongs **after the chapter break**, before the first prose sentence.
3. In the **Studio timeline**, leave or insert a **three-second gap after the last audible syllable of Chapter 2** before the first audible syllable/title of Chapter 3.
4. Play the **combined join** and check both the silence and the return to a neutral narrative cadence.
5. If exporting separate chapter audio files for the website/game audiobook player, make sure the **player's sequential playback** also preserves the gap, whether by a deliberate tail or by the mastering/assembly step.

For a **single combined v3/v4 text-generation experiment**, a soft cue can be tested in the text instead. It is not a precise replacement for the timeline edit:

```text
Brunti did not try to make them one.

[long pause]

Chapter Three — A Road Made of Grass

The ground was still moving when Brunti stepped off the descent platform.
```

The title line above is **spoken only if this audiobook edition includes narrated chapter titles**. The square-bracket tag is a delivery cue, not part of Brunti's story. Do **not** paste the sample onto the end of the canonical Chapter 2 file.

## Other v3/v4 audio tags: restraint over theatrics

ElevenLabs documents tags including `[laughs]`, `[chuckles]`, `[sighs]`, `[clears throat]`, `[whispers]`, `[crying]`, and delivery directions such as `[curious]` or `[mischievously]`. These markers change the narrator's performance, and are available in both models. They **should not automatically be inserted** wherever the prose says that another person laughed, whispered, cried or sighed.

Use a performance tag **only if it matches an already-written action or a deliberate speaking style**, and only when the resulting audio improves the scene. Do not fabricate sounds, additional dialogue, emotion, creature vocalizations or music by adding tags. Sound design—when intentionally chosen—should remain separate from the spoken literary text.

A practical v3/v4 dialog test (not from the manuscript):

```text
[whispers] I can hear someone beyond the door.

[short pause]

[sighs] Then we should wait.
```

**Keep the audiobook's default voice calm, intimate and precise.** Unusual vocal styles should be exceptional. Test any tag with the actual chosen voice: tags are generative guidance and may perform differently, or occasionally be spoken as words.

## Import and export discipline

- Maintain **one narrative chapter per Studio chapter** and preserve chapter headings/numbering. A correctly structured document or EPUB is preferable to pasting thirty chapters as one continuous paragraph. Confirm the chapter list in Studio after import.
- Preserve scene breaks from the manuscript's `***` markers as **nonspoken structure**, translating them to actual paragraph/clip divisions where useful. Never synthesize the literal asterisks.
- Keep narration-only scripts in a **future `production/scripts/`** area, not in `manuscript/chapters/`. Choose whether titles are narrated; use the same convention for all 30 chapters.
- For each generated chapter, log model (v3 or v4), voice, revision of manuscript, cue decisions, verified silence between chapters, quality issues and resulting file/version. Do not claim a clip is finalized until its **rendered audio is listened to**.
- A generated Chapter 2 alone is not sufficient to validate a Chapter 2→3 boundary. Check the actual **joined output**, including any website/game player's transition.
- Any final pause timings, added vocal reactions or edition-specific script modifications must remain separate from the **146,816-word novel draft count**, which does not include TTS cues.

## Source references

- [ElevenLabs: How can I add pauses?](https://elevenlabs.io/docs/help-center/product/core-capabilities/text-to-speech/how-can-i-add-pauses)
- [ElevenLabs: audio tags for Eleven v3/v4](https://elevenlabs.io/docs/help-center/product/core-capabilities/text-to-speech/how-do-audio-tags-work-with-eleven-v3-and-v4)
- [ElevenLabs: TTS best practices](https://elevenlabs.io/docs/overview/capabilities/text-to-speech/best-practices)
- [ElevenLabs: ElevenCreative Studio](https://elevenlabs.io/docs/eleven-creative/products/studio)
- [ElevenLabs: structured chapter import](https://elevenlabs.io/docs/help-center/product/studio/studio/how-do-i-add-chapters-to-a-studio-project)

**Implementation status:** production workflow documented for Eleven v3/v4 only; **no narration-only chapter exports, Studio editing actions, audio generation, quality tests or final production approval performed in this repository**. The Chapter 2→3 pause is an explicit **production target**, not a verified audible result.
