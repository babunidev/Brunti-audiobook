# Audiobook production — scripts prepared, audio production pending

**Confirmed model choice by Babuni: ElevenLabs v3 and v4 only.** See the [v3/v4 narration cues, scene pauses and chapter-join guide](ELEVENLABS_V3_V4.md). The guide is a documented production convention, not evidence of generated or approved audio.

**30/30 narration scripts are now drafted and available** in [the v3/v4 script index](scripts/eleven-v3-v4/README.md), generated from the 146,816-word working novel. They include **271 scene pauses, 30 chapter-ending pauses, and 53 selectively placed voice-delivery cues**; all spoken content was cross-checked against its source. **No narrated audio is stored in this repository.** Babuni published Chapter 1 as an audio episode on [Indikin.online](https://indikin.online/share/storymaker/babuni?v=5.0) on 20 November 2026; the audio files themselves stay outside Git. Final literary review, Studio import, voice decisions, audio generation and timing tests remain outstanding.

## Proposed sequence

1. Fix the editorial manuscript, chapter boundaries and pronunciations.
2. **Done for draft production:** 30 plain-text scripts retain all original prose and chapter titles, turn the established scene breaks into 271 `[pause]` cues, and append 30 final `[long pause]` cues. They remain separate from the literary originals; [index and import notes](scripts/eleven-v3-v4/README.md). Refresh them after any future literary revision.
3. Agree on narrator/voice design, character differentiation, rhythm and delivery. Avoid needless voice or sound changes that distract from the prose.
4. Confirm rights and provenance of artwork, every voice workflow, music and effects. Commissioned Morkahja compositions have separate rights and should not be copied automatically.
5. Produce chapter audio as reviewable units. **Make an actual inter-chapter silence (initial target 3 seconds) in the Studio timeline or audio assembly**, and listen to adjoining chapter files together. Check proper nouns, repeated lines, clipped silences, pacing problems and continuity.
6. Master exported audio consistently and record edition metadata, credits, chapter order and publication status only after actual production.

## Folder intentions

The separate `production/scripts/eleven-v3-v4/` narration-script area now exists. During further production, create `production/notes/` for pronunciation/voice direction and `production/manifests/` for per-chapter rendered deliverables. Keep large intermediate audio files outside Git until the storage and licensing strategy is chosen; **do not** commit secrets or unauthorized third-party media.

The user's existing book poster has not been added here.
