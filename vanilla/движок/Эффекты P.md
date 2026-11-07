---
type: reference
description: "Справочник движка Victoria 3 1.13: Эффекты P — 5, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Эффекты P

Из дампа `effects.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **place_character_in_void** — Banishes a character to the void, duration is how long character is kept before being deleted · `place_character_in_void = months` · supported scopes: character ^e-place-character-in-void
- **play_as** — Change which country scoped country's player will play as · `play_as = <scope>` · supported scopes: country · supported targets: country ^e-play-as
- **post_audio_event** — Runs an audio even on a "persistent" audio object } · `post_audio_event = { persistent_object = [object_name] # For example music_manager event = [audio_event] # For example start_debug_music` · supported scopes: none ^e-post-audio-event
- **post_notification** — Posts notification · supported scopes: none ^e-post-notification
- **post_proposal** — Posts proposal · supported scopes: none ^e-post-proposal
