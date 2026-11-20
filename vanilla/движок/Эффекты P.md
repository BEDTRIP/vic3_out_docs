---
type: reference
description: "Справочник движка Victoria 3 1.15.2: Эффекты P — 6, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Эффекты P

Из дампа `effects.log` (2026-11-20; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **place_character_in_void** — Banishes a character to the void, duration is how long character is kept before being deleted · `place_character_in_void = months` · supported scopes: character ^e-place-character-in-void
- **play_as** — Change which country scoped country's player will play as · `play_as = <scope>` · supported scopes: country · supported targets: country ^e-play-as
- **play_music_cue** — Plays the specified music track for the player, interrupting the current one · supported scopes: country ^e-play-music-cue
- **post_audio_event** — Runs an audio even on a "persistent" audio object } · `post_audio_event = { persistent_object = [object_name] # For example music_manager event = [audio_event] # For example start_debug_music` · supported scopes: none ^e-post-audio-event
- **post_notification** — Posts notification · value type: common/messages · supported scopes: none ^e-post-notification
- **post_proposal** — Posts proposal · value type: common/proposal_types · supported scopes: none ^e-post-proposal
