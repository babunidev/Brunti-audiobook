# Primary source ledger

| Authority | Repository | Pinned source |
| --- | --- | --- |
| Established world lore | [MorkahjaWorld](https://github.com/babunidev/MorkahjaWorld) | [f56a7c3d2034](https://github.com/babunidev/MorkahjaWorld/tree/f56a7c3d2034652e1c5961f0ece9c3ef52b52b48) |
| Game encounter prose (current reviewed revision) | [Morkahja](https://github.com/babunidev/Morkahja) | [5b0d73e550ca](https://github.com/babunidev/Morkahja/tree/5b0d73e550ca123adcb095b45febeba4330a9fdf) |
| Original encounter atlas / avatar and expansion source snapshot | [Morkahja](https://github.com/babunidev/Morkahja) | [58576f063627](https://github.com/babunidev/Morkahja/tree/58576f063627752f77cdf99514baad875d509114) |

## Game records

The [encounter JSON](https://github.com/babunidev/Morkahja/blob/58576f063627752f77cdf99514baad875d509114/server/game/encountersdata.json) was parsed into the [complete source atlas](../story/ENCOUNTER_ATLAS.md). Its 203 records contain encounter IDs, names, descriptions, types, expansion associations and follow links. The full encounter prose is **not** copied into the atlas. A newer game snapshot changes the descriptions of 19 IDs, but no record IDs, titles or gameplay metadata; see [source reconciliation](SOURCE_RECONCILIATION.md). The placement matrix uses the newer reviewed prose baseline.

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
