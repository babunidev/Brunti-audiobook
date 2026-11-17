# Primary source ledger

| Authority | Repository | Pinned source |
| --- | --- | --- |
| Established world lore | [MorkahjaWorld](https://github.com/babunidev/MorkahjaWorld) | [f56a7c3d2034](https://github.com/babunidev/MorkahjaWorld/tree/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48) |
| Game encounter prose (current reviewed revision) | [Morkahja](https://github.com/babunidev/Morkahja) | [92cd8dc140c5](https://github.com/babunidev/Morkahja/tree/92cd8dc140c5a73fce11f8ad3b5d87a488b3fd7b) |
| Intermediate source revision (five refreshed source descriptions) | [Morkahja](https://github.com/babunidev/Morkahja) | [525d26bc8b4d](https://github.com/babunidev/Morkahja/tree/525d26bc8b4d745ca0e4e7c2b3c86c20d9829df6) |
| Intermediate source revision (five refreshed source descriptions) | [Morkahja](https://github.com/babunidev/Morkahja) | [92b97aef8706](https://github.com/babunidev/Morkahja/tree/92b97aef8706dabfcd8d8d80c0477a70e3336097) |
| Intermediate source revision (five refreshed source descriptions) | [Morkahja](https://github.com/babunidev/Morkahja) | [e826fa46d3ff](https://github.com/babunidev/Morkahja/tree/e826fa46d3ff3f27628eec54ebfd193b597f731a) |
| Intermediate source revision (eight refreshed source descriptions) | [Morkahja](https://github.com/babunidev/Morkahja) | [ad34afb686ef](https://github.com/babunidev/Morkahja/tree/ad34afb686efa017cd43ffeccc554afb43d79b22) |
| Intermediate source revision (one earlier text change) | [Morkahja](https://github.com/babunidev/Morkahja) | [734f439b1699](https://github.com/babunidev/Morkahja/tree/734f439b1699ac144909462d31ca3e045cb4d811) |
| Intermediate source revision (two earlier text changes) | [Morkahja](https://github.com/babunidev/Morkahja) | [096c99bdf5ac](https://github.com/babunidev/Morkahja/tree/096c99bdf5ac8af5174b26a337914f573263ab72) |
| Intermediate source revision (one earlier text change) | [Morkahja](https://github.com/babunidev/Morkahja) | [13a5d134c8e6](https://github.com/babunidev/Morkahja/tree/13a5d134c8e63855894436e4f1b09910c5c50b95) |
| Intermediate source revision (five earlier text changes) | [Morkahja](https://github.com/babunidev/Morkahja) | [e0bc99c51c74](https://github.com/babunidev/Morkahja/tree/e0bc99c51c74bb088f27a8252082b41c61629cf7) |
| Intermediate source revision (initial text refresh) | [Morkahja](https://github.com/babunidev/Morkahja) | [5b0d73e550ca](https://github.com/babunidev/Morkahja/tree/5b0d73e550ca123adcb095b45febeba4330a9fdf) |
| Original encounter atlas / avatar and expansion source snapshot | [Morkahja](https://github.com/babunidev/Morkahja) | [58576f063627](https://github.com/babunidev/Morkahja/tree/58576f063627752f77cdf99514baad875d509114) |

## Game records

The [encounter JSON](https://github.com/babunidev/Morkahja/blob/58576f063627752f77cdf99514baad875d509114/server/game/encountersdata.json) was parsed into the [complete source atlas](../story/ENCOUNTER_ATLAS.md). Its 203 records contain encounter IDs, names, descriptions, types, expansion associations and follow links. The full encounter prose is **not** copied into the atlas. Ten later game snapshots changed **19, then 5, then 1, then 2, then 1, then 1, then 8, then 5, then 5, then 4 additional `mEncounterText` strings**, with all 203 IDs, titles and gameplay metadata retained. See [source reconciliation](SOURCE_RECONCILIATION.md). The scene plan and placement matrix remain structurally complete; all **twelve Chapter 16** records (20019–20030) were read at game baseline `525d26bc8b4d` and integrated **as Archive, not physically lived**; **five** changed texts (20099–20103) were compared with prior game baseline. Of those, **20101** was already in Chapter 14 and was reconciled there; **20099/20100/20102/20103 and the later-revised 20105/20106 are incorporated in Chapter 17**, while newer revisions to **20104 (Chapter 18)** and **20107 (Chapter 21)** await their chapters. Previously, six Chapter 15 source descriptions were reread at `92b97aef8706` and five older descriptions (20094–20098) were reconciled in Chapters 5 and 7. Previously, four Chapter 14 Ohgar encounters were checked at `e826fa46d3ff`, and eight older descriptions (20086–20093) were reconciled in Chapters 4–5; Chapter 12 descriptions and 20192→19001 follow-link were reviewed previously; the Chapter 10 20188→19444 follow-link and Chapter 4's 20083/20084/20085 revisions were already reconciled. See the [draft review index](../manuscript/chapters/README.md) for exact chapter-level evidence. The [continuity audit](SCENE_CONTINUITY.md) identifies remaining detailed source verification needs.

In the [portrait JSON](https://github.com/babunidev/Morkahja/blob/58576f063627752f77cdf99514baad875d509114/server/game/portraits.json), **Brunti** appears twice:

- **ID 104**: race 1 Grimnir, gender 2 female, **role 3 warrior**, portrait type 1. **Selected.**
- ID 78: race 1 Grimnir, gender 2 female, role 2 rogue, portrait type 1. **Not selected.**

Mappings are confirmed in [AvatarCreation.tsx](https://github.com/babunidev/Morkahja/blob/58576f063627752f77cdf99514baad875d509114/client/src/ui/avatar/AvatarCreation.tsx). In the [frame catalog](https://github.com/babunidev/Morkahja/blob/58576f063627752f77cdf99514baad875d509114/server/game/frames.json), frame **75** has frameRace 1, frameRole 0, frameType 1 and is compatible with the Grimnir protagonist.

Game artwork is referenced, not copied:

- [Portrait — avatar_104.webp](https://github.com/babunidev/Morkahja/blob/58576f063627752f77cdf99514baad875d509114/client/public/UI/02_AvatarCreation/Avatare/avatar_104.webp)
- [Frame — frame_75.webp](https://github.com/babunidev/Morkahja/blob/58576f063627752f77cdf99514baad875d509114/client/public/UI/02_AvatarCreation/Frames/frame_75.webp)

## First-stage world references

- [World overview](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Overview/World_Overview.md)
- [Grimnir](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Races/Grimnir.md) and [Skylands](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Grimnir_Skylands.md)
- [Grimnir birth and community](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Traditions/Grimnir_Birth_and_Community.md)
- [Grimnir life and care](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Traditions/Grimnir_Life_and_Care.md)
- [Keldor](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Keldor.md) and [Blackwood Abyss](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Blackwood_Abyss.md)
- [Atranor](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Places/Atranor.md) and [Divine Laws](https://github.com/babunidev/MorkahjaWorld/blob/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48/Pantheon/Divine_Laws.md)

The game [expansion catalog](https://github.com/babunidev/Morkahja/blob/58576f063627752f77cdf99514baad875d509114/server/game/expansiondata.json) names Keldor (1001), Urcogor Ravage (1002), Everwinter Valley (1003) and Aetherion (1004). No source encounters currently use expansion ID 1002; this is not an absence of Ravage lore.

## Rights and change limits

The game's [creative-content licensing note](https://github.com/babunidev/Morkahja/blob/58576f063627752f77cdf99514baad875d509114/CONTENT_LICENSE.md) covers Babuni's material to the extent rights can be granted, with exclusions for commissioned music and third-party media. This repository has not made a new audiobook license declaration. The existing title poster was not supplied to this repository. See [Rights](RIGHTS.md).

## Chapter 17 source check (17 November 2026)

[Morkahja game `92cd8dc140c5`](https://github.com/babunidev/Morkahja/blob/92cd8dc140c5a73fce11f8ad3b5d87a488b3fd7b/server/game/encountersdata.json), blob `ec27f8ef04095906ab811f3a21aa2378dfe48d46`, was checked against `525d26bc8b4d`: **4 text-only revisions**, IDs **20104–20107**. All **11** Chapter 17 source entries were reread from the updated baseline, with **20105** and **20106** changes reflected in the prose. **20104** and **20107** are not drafted. Full evidence: [Chapter 17 review](CHAPTER_17_REVIEW.md) and [tenth source reconciliation](SOURCE_RECONCILIATION.md). Current working coverage: **130 drafted / 73 planned out of 203**, not editorially approved.
