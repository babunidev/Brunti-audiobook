# Audiobook production — future stage

**Confirmed model choice by Babuni: ElevenLabs v3 and v4 only.** See the [v3/v4 narration cues, scene pauses and chapter-join guide](ELEVENLABS_V3_V4.md). The guide is a documented production convention, not evidence of generated or approved audio.

**No narrated audio exists in this repository.** The book manuscript must be drafted and reviewed before production.

## Proposed sequence

1. Fix the editorial manuscript, chapter boundaries and pronunciations.
2. Produce **narration-only scripts** stripped of chapter-brief tables and internal comments; preserve spoken scene breaks. Add **v3/v4 square-bracket audio tags** only in derived scripts/Studio, never in the canonical chapters.
3. Agree on narrator/voice design, character differentiation, rhythm and delivery. Avoid needless voice or sound changes that distract from the prose.
4. Confirm rights and provenance of artwork, every voice workflow, music and effects. Commissioned Morkahja compositions have separate rights and should not be copied automatically.
5. Produce chapter audio as reviewable units. **Make an actual inter-chapter silence (initial target 3 seconds) in the Studio timeline or audio assembly**, and listen to adjoining chapter files together. Check proper nouns, repeated lines, clipped silences, pacing problems and continuity.
6. Master exported audio consistently and record edition metadata, credits, chapter order and publication status only after actual production.

## Folder intentions

When production begins, create `production/scripts/` for clean spoken text, `production/notes/` for pronunciation/voice direction and `production/manifests/` for per-chapter deliverables. Keep large intermediate audio files outside Git until the storage and licensing strategy is chosen; **do not** commit secrets or unauthorized third-party media.

The user's existing book poster has not been added here.
