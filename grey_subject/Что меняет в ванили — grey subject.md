---
type: reference
description: "Что мод grey subject меняет в ванили 1.13: записи common/ по папкам, defines, файлы поверх ваниль, события, локализация"
project: vic3
audience: agent
source: grey_subject
tags: [grey_subject, что-меняет]
generated: "v3 graph mods"
paths: [grey_add_alot_of_things/grey_subject/**]
---
# Что меняет в ванили — grey subject

Снимок `grey_add_alot_of_things/grey_subject`, сравнение с ваниль 1.13. Генерат `v3 graph mods`: руками не править. Правила слияния — навык `vic3-modding`, «load-and-override»: запись, которой нет у ваниль, мод **добавляет**; голое тело или `REPLACE:` ключа ваниль **заменяет** запись целиком; `INJECT:` **дополняет**; файл с путём файла ваниль — файл ваниль не читается, его записи, которых мод не повторил, **удалены**. Сравнение только с ваниль: запись другого мода (мод — аддон или патч) здесь — «нет у ваниль».

## Записи common/

| папка | добавляет | заменяет | дополняет | складывает | вставка в чужое | удаляет файлом | не действует |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `ai_strategies` | 0 | 1 | 0 | 0 | 0 | 0 | 0 |
| `alert_groups` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `alert_types` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `customizable_localization` | 3 | 0 | 0 | 0 | 0 | 0 | 0 |
| `diplomatic_actions` | 21 | 11 | 0 | 0 | 0 | 0 | 0 |
| `diplomatic_catalysts` | 1 | 1 | 0 | 0 | 0 | 0 | 0 |
| `game_rules` | 6 | 0 | 0 | 0 | 0 | 0 | 0 |
| `journal_entries` | 0 | 1 | 0 | 0 | 0 | 0 | 0 |
| `messages` | 5 | 0 | 0 | 0 | 0 | 0 | 0 |
| `on_actions` | 9 | 0 | 0 | 14 | 0 | 0 | 0 |
| `political_lobbies` | 0 | 2 | 0 | 0 | 0 | 0 | 0 |
| `political_lobby_appeasement` | 3 | 0 | 0 | 0 | 0 | 0 | 0 |
| `script_values` | 18 | 4 | 0 | 0 | 0 | 0 | 1 |
| `scripted_buttons` | 0 | 2 | 0 | 0 | 0 | 0 | 0 |
| `scripted_effects` | 6 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_guis` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_triggers` | 11 | 0 | 0 | 0 | 0 | 0 | 0 |
| `static_modifiers` | 5 | 0 | 0 | 0 | 0 | 0 | 0 |
| `treaty_articles` | 0 | 1 | 0 | 0 | 0 | 0 | 0 |

### ai_strategies

- **заменяет** (1): `ai_strategy_territorial_expansion`

### alert_groups

- **добавляет** (1): `can_consolidate_subject`

### alert_types

- **добавляет** (1): `overlord_can_consolidate_subject`

### customizable_localization

- **добавляет** (3): `change_religion_dynamic_name`, `mog_topbar_coloured_all_subject_pp`, `occ_offer_convoys_decision_dynamic_name`

### diplomatic_actions

- **добавляет** (21): `ask_subject_to_fight`, `bankroll`, `change_primary_culture`, `change_state_religion`, `consolidate_subject`, `forced_border_closing`, `forced_border_opening`, `forced_industry_ban`, `forced_slave_trade`, `forced_slavery_ban`, `get_recognized`, `include_primary_culture`, `laws_synergize_bureaucracy`, `laws_synergize_economy`, `laws_synergize_land`, `laws_synergize_trade`, `merge_subject`, `military_support`, `open_border`, `recognize`, `sis_forced_extraction`
- **заменяет** (11): `add_power_bloc_culture`, `da_appoint_colonial_governor`, `da_evangelize`, `da_request_support_regime`, `da_support_regime`, `decrease_payments`, `demand_state`, `force_become_subject`, `fund_lobbies`, `raise_payments`, `trade_states`

### diplomatic_catalysts

- **добавляет** (1): `catalyst_force_laws`
- **заменяет** (1): `catalyst_became_subject`

### game_rules

- **добавляет** (6): `ai_merge_subject`, `consolidate_subject_action`, `merge_subject_cheat`, `sis_cultural_religion_actions`, `sis_force_law_actions`, `sis_synergize_actions`

### journal_entries

- **заменяет** (1): `je_law_imposition`

### messages

- **добавляет** (5): `MoG_SIS_border_opened`, `MoG_SIS_culture_changed`, `MoG_SIS_culture_included`, `MoG_SIS_religion_changed`, `MoG_SIS_synergy_complete`

### on_actions

- **добавляет** (9): `impose_je_reset_on_actions`, `incorporate_state_actions`, `law_progress_check_presets_country_on_action`, `law_progress_check_presets_target_on_action`, `mog_sis_subject_expansion_support`, `mog_sis_synergize_cleanup_check`, `mog_sis_topbar_activate`, `mog_sis_topbar_calculations`, `mog_sis_topbar_save_game_compatibility`
- **ключ ваниль в папке, которая складывается (`on_actions` складываются, `effect` — последний загруженный)** (14): `on_capitulation`, `on_country_released_as_independent`, `on_country_released_as_overlord_subject`, `on_country_released_as_own_subject`, `on_diplomatic_play_started`, `on_game_started_after_lobby`, `on_law_enactment_fail`, `on_monthly_pulse`, `on_monthly_pulse_country`, `on_peace_agreement_signed_war_leader`, `on_peace_agreement_signed_war_participant`, `on_revolution_start`, `on_secession_start`, `on_yearly_pulse_country`

### political_lobbies

- **заменяет** (2): `lobby_anti_overlord`, `lobby_pro_overlord`

### political_lobby_appeasement

- **добавляет** (3): `appeasement_industry_banned`, `appeasement_support_expansion_agreement_broken`, `appeasement_support_expansion_agreement_formed`

### script_values

- **добавляет** (18): `compatible_mod_value_1`, `compatible_mod_value_2`, `compatible_mod_value_3`, `compatible_mod_value_4`, `compatible_mod_value_5`, `liberty_desire_weekly_change_combined_subjects`, `liberty_desire_weekly_change_legal_friction`, `liberty_desire_weekly_change_own_combined_subjects`, `liberty_desire_weekly_change_relative_prestige`, `overlord_synergize_cost_bureau`, `overlord_synergize_cost_standard`, `subject_fight_annex_war_lib_hit`, `subject_fight_annex_war_overlord_infamy`, `subject_fight_target_country_baseline`, `subject_fight_targeted_state_baseline`, `subject_fight_targeted_state_lib_hit`, `subject_fight_targeted_state_overlord_infamy`, `total_bureaucracy_need`
- **заменяет** (4): `anti_overlord_lobby_starting_appeasement`, `liberty_desire_weekly_change`, `num_primary_cultures`, `pro_overlord_lobby_starting_appeasement`
- **повтор без `REPLACE_OR_CREATE:` — не действует (первое определение остаётся)** (1): `leverage_threshold_to_invite`

### scripted_buttons

- **заменяет** (2): `button_implement_law_imposition`, `button_refuse_law_imposition`

### scripted_effects

- **добавляет** (6): `add_com_topbar_element`, `fix_variable_error`, `mog_sis_add_topbar_elements`, `mog_sis_suppress_topbar_errors`, `mog_sis_synergy_complete_effect`, `mog_sis_topbar_calculate_all_subject_pp`

### scripted_guis

- **добавляет** (1): `mog_topbar_element_all_subject_pp`

### scripted_triggers

- **добавляет** (11): `Grey_SIS_is_active`, `active_synergize_bureaucracy`, `active_synergize_economy`, `active_synergize_land`, `active_synergize_trade`, `ai_can_merge_subject_trigger`, `can_be_consolidation_recipient`, `can_consolidate_subject`, `is_giftable_treaty_article`, `merge_subject_cheat_trigger`, `subject_can_be_consolidation_target`

### static_modifiers

- **добавляет** (5): `IB_success`, `overlord_syn_cost_bureau`, `overlord_syn_cost_economy`, `overlord_syn_cost_land`, `overlord_syn_cost_trade`

### treaty_articles

- **заменяет** (1): `support_independence`

## defines

Сливаются по одному define, не блоком.

| define | ваниль | мод |
| --- | --- | --- |
| `NPolitics.MAX_NUM_POLITICAL_LOBBIES_OF_SAME_CATEGORY_PER_IG` | `1` | `2` |

## Вне common/

| папка | файлов | поверх файла ваниль |
| --- | --- | --- |
| `events/` | 4 | 0 |
| `gui/` | 1 | 0 |
| `gfx/` | 24 | 2 |
| `localization/` | 220 | 0 |

- **gfx/ поверх ваниль**: `gfx/interface/icons/lens_toolbar_icons/bankroll.dds`, `gfx/interface/icons/lens_toolbar_icons/bankroll_break.dds`

**События**: 11 id; с id ваниль — 3 (`law_imposition_events.1`, `law_imposition_events.2`, `law_imposition_events.3`) — игра оставляет одно, не по порядку модов.

**Локализация** (английская и русская): ключей 988; в `replace/` — 0; есть у ваниль вне `replace/` — 6 (не действуют: побеждает первый файл).
