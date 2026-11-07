---
type: reference
description: "Что мод PBE меняет в ванили 1.13: записи common/ по папкам, defines, файлы поверх ваниль, события, локализация"
project: vic3
audience: agent
source: pbe
tags: [PBE, что-меняет]
generated: "v3 graph mods"
paths: [PowerBlocksExpanded/**]
---
# Что меняет в ванили — PBE

Снимок `PowerBlocksExpanded`, сравнение с ваниль 1.13. Генерат `v3 graph mods`: руками не править. Правила слияния — навык `vic3-modding`, «load-and-override»: запись, которой нет у ваниль, мод **добавляет**; голое тело или `REPLACE:` ключа ваниль **заменяет** запись целиком; `INJECT:` **дополняет**; файл с путём файла ваниль — файл ваниль не читается, его записи, которых мод не повторил, **удалены**. Сравнение только с ваниль: запись другого мода (мод — аддон или патч) здесь — «нет у ваниль».

## Записи common/

| папка | добавляет | заменяет | дополняет | складывает | вставка в чужое | удаляет файлом | не действует |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `cohesion_levels` | 0 | 5 | 0 | 0 | 0 | 0 | 0 |
| `diplomatic_actions` | 3 | 3 | 0 | 0 | 0 | 0 | 0 |
| `diplomatic_plays` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `game_concepts` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `game_rules` | 14 | 0 | 0 | 0 | 0 | 0 | 0 |
| `messages` | 2 | 0 | 0 | 0 | 0 | 0 | 0 |
| `modifier_type_definitions` | 30 | 7 | 0 | 0 | 0 | 0 | 0 |
| `on_actions` | 4 | 0 | 0 | 4 | 0 | 0 | 0 |
| `power_bloc_identities` | 0 | 5 | 0 | 0 | 0 | 0 | 0 |
| `power_bloc_principle_groups` | 36 | 1 | 0 | 0 | 0 | 0 | 0 |
| `power_bloc_principles` | 108 | 9 | 0 | 0 | 0 | 0 | 0 |
| `production_method_groups` | 2 | 0 | 0 | 0 | 0 | 0 | 0 |
| `production_methods` | 4 | 0 | 0 | 0 | 0 | 0 | 0 |
| `script_values` | 38 | 0 | 0 | 0 | 0 | 0 | 1 |
| `scripted_effects` | 11 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_guis` | 4 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_rules` | 8 | 4 | 0 | 0 | 0 | 0 | 0 |
| `scripted_triggers` | 5 | 0 | 0 | 0 | 0 | 0 | 0 |
| `static_modifiers` | 20 | 0 | 0 | 0 | 0 | 0 | 0 |

### cohesion_levels

- **заменяет** (5): `cohesion_level_high`, `cohesion_level_low`, `cohesion_level_moderate`, `cohesion_level_very_high`, `cohesion_level_very_low`

### diplomatic_actions

- **добавляет** (3): `force_privatization`, `holy_war_action`, `vokaes_foreign_investment_agreement`
- **заменяет** (3): `force_become_subject`, `force_regime_change`, `force_state_religion`

### diplomatic_plays

- **добавляет** (1): `dp_holy_war`

### game_concepts

- **добавляет** (1): `concept_power_blocs_expanded`

### game_rules

- **добавляет** (14): `vokaes_power_bloc_rule_diplo_action_changes`, `vokaes_power_bloc_rule_enable_identity_switch`, `vokaes_power_bloc_rule_enable_mandate_progress`, `vokaes_power_bloc_rule_enable_new_cohesion`, `vokaes_power_bloc_rule_enable_new_principles`, `vokaes_power_bloc_rule_free_founding_mandates`, `vokaes_power_bloc_rule_holy_wars_gp`, `vokaes_power_bloc_rule_late_founding_mandates`, `vokaes_power_bloc_rule_low_member_penalty`, `vokaes_power_bloc_rule_mandate_cost_growth`, `vokaes_power_bloc_rule_mandate_progress_speed`, `vokaes_power_bloc_rule_max_saved_mandates`, `vokaes_power_bloc_rule_principle_restrictions`, `vokaes_power_bloc_rule_principle_slots`

### messages

- **добавляет** (2): `power_bloc_identity_change`, `power_bloc_identity_change_third_party`

### modifier_type_definitions

- **добавляет** (30): `building_training_rate_per_subject_mult`, `country_authority_per_manor_house_max`, `country_bureaucracy_from_bloc_members_mult`, `country_can_declare_holy_wars_bool`, `country_can_impose_same_lawgroup_economy_in_power_bloc_bool`, `country_can_impose_same_lawgroup_home_affairs_in_power_bloc_bool`, `country_can_impose_same_lawgroup_welfare_in_power_bloc_bool`, `country_convoys_per_leader_subject_mult`, `country_convoys_per_leader_subject_mult_max`, `country_influence_from_bloc_members_add`, `country_influence_per_subject_add`, `country_institution_size_change_speed_institution_home_affairs_mult`, `country_institution_size_change_speed_institution_social_security_mult`, `country_interest_from_gold_reserves_bool`, `country_interest_rate_from_bloc_members_mult`, `country_interest_rate_from_bloc_members_mult_max`, `country_legitimacy_per_power_bloc_member_add`, `country_mapi_per_leader_subject_mult`, `country_mapi_per_leader_subject_mult_max`, `country_minting_from_bloc_members_mult`, `country_minting_from_bloc_members_mult_max`, `country_trade_from_bloc_members_mult`, `country_trade_from_bloc_members_mult_max`, `forced_privatization_subject_action_bool`, `mandate_progress_from_cohesion_mult`, `mandate_progress_from_members_mult`, `power_bloc_allow_foreign_investment_all_rank_bool`, `power_bloc_free_mandates_from_reform`, `power_bloc_members_auto_help_against_revolutions_bool`, `vokaes_country_authority_add`
- **заменяет** (7): `country_force_privatization_bool`, `country_influence_add`, `country_institution_cost_institution_home_affairs_mult`, `country_institution_cost_institution_social_security_mult`, `power_bloc_cohesion_per_member_add`, `state_bureaucrats_investment_pool_contribution_add`, `state_bureaucrats_investment_pool_efficiency_mult`

### on_actions

- **добавляет** (4): `vokaes_dynamic_modifier_on_action`, `vokaes_power_bloc_holy_war_enforced_on_action`, `vokaes_power_bloc_revolution_on_action`, `vokaes_weekly_global_on_action`
- **ключ ваниль в папке, которая складывается (`on_actions` складываются, `effect` — последний загруженный)** (4): `on_diplomatic_play_started`, `on_monthly_pulse`, `on_monthly_pulse_country`, `on_wargoal_enforced`

### power_bloc_identities

- **заменяет** (5): `identity_ideological_union`, `identity_military_treaty_organization`, `identity_religious`, `identity_sovereign_empire`, `identity_trade_league`

### power_bloc_principle_groups

- **добавляет** (36): `principle_group_alms_for_the_poor`, `principle_group_antitrust_commission`, `principle_group_champion_the_true_faith`, `principle_group_chivalrous_pursuit`, `principle_group_collective_bargaining_power`, `principle_group_colonial_manpower`, `principle_group_conventions_of_war`, `principle_group_currency_union`, `principle_group_deregulation`, `principle_group_development_fund`, `principle_group_direct_oversight`, `principle_group_economic_consensus`, `principle_group_economic_imperialism`, `principle_group_entrenched_elite`, `principle_group_henotheism`, `principle_group_holy_wars`, `principle_group_imperial_prerogative`, `principle_group_international_criminal_court`, `principle_group_joint_training_exercises`, `principle_group_leviathan`, `principle_group_logistics_network`, `principle_group_member_council`, `principle_group_organised_religion`, `principle_group_pax_imperia`, `principle_group_people_of_faith`, `principle_group_preferential_colonial_trade`, `principle_group_private_tax_collectors`, `principle_group_propaganda`, `principle_group_righteous_cause`, `principle_group_settlement_drive`, `principle_group_sovereign_wealth_fund`, `principle_group_status_quo`, `principle_group_unified_bond_market`, `principle_group_unity`, `principle_group_wonder_weapons`, `principle_group_your_country_needs_you`
- **заменяет** (1): `principle_group_creative_legislature`

### power_bloc_principles

- **добавляет** (108): `principle_alms_for_the_poor_1`, `principle_alms_for_the_poor_2`, `principle_alms_for_the_poor_3`, `principle_antitrust_commission_1`, `principle_antitrust_commission_2`, `principle_antitrust_commission_3`, `principle_champion_the_true_faith_1`, `principle_champion_the_true_faith_2`, `principle_champion_the_true_faith_3`, `principle_chivalrous_pursuit_1`, `principle_chivalrous_pursuit_2`, `principle_chivalrous_pursuit_3`, `principle_collective_bargaining_power_1`, `principle_collective_bargaining_power_2`, `principle_collective_bargaining_power_3`, `principle_colonial_manpower_1`, `principle_colonial_manpower_2`, `principle_colonial_manpower_3`, `principle_conventions_of_war_1`, `principle_conventions_of_war_2`, `principle_conventions_of_war_3`, `principle_currency_union_1`, `principle_currency_union_2`, `principle_currency_union_3`, `principle_deregulation_1`, `principle_deregulation_2`, `principle_deregulation_3`, `principle_development_fund_1`, `principle_development_fund_2`, `principle_development_fund_3`, `principle_direct_oversight_1`, `principle_direct_oversight_2`, `principle_direct_oversight_3`, `principle_economic_consensus_1`, `principle_economic_consensus_2`, `principle_economic_consensus_3`, `principle_economic_imperialism_1`, `principle_economic_imperialism_2`, `principle_economic_imperialism_3`, `principle_entrenched_elite_1`, `principle_entrenched_elite_2`, `principle_entrenched_elite_3`, `principle_henotheism_1`, `principle_henotheism_2`, `principle_henotheism_3`, `principle_holy_wars_1`, `principle_holy_wars_2`, `principle_holy_wars_3`, `principle_imperial_prerogative_1`, `principle_imperial_prerogative_2`, `principle_imperial_prerogative_3`, `principle_international_criminal_court_1`, `principle_international_criminal_court_2`, `principle_international_criminal_court_3`, `principle_joint_training_exercises_1`, `principle_joint_training_exercises_2`, `principle_joint_training_exercises_3`, `principle_leviathan_1`, `principle_leviathan_2`, `principle_leviathan_3`, `principle_logistics_network_1`, `principle_logistics_network_2`, `principle_logistics_network_3`, `principle_member_council_1`, `principle_member_council_2`, `principle_member_council_3`, `principle_organised_religion_1`, `principle_organised_religion_2`, `principle_organised_religion_3`, `principle_pax_imperia_1`, `principle_pax_imperia_2`, `principle_pax_imperia_3`, `principle_people_of_faith_1`, `principle_people_of_faith_2`, `principle_people_of_faith_3`, `principle_preferential_colonial_trade_1`, `principle_preferential_colonial_trade_2`, `principle_preferential_colonial_trade_3`, `principle_private_tax_collectors_1`, `principle_private_tax_collectors_2`, `principle_private_tax_collectors_3`, `principle_propaganda_1`, `principle_propaganda_2`, `principle_propaganda_3`, `principle_righteous_cause_1`, `principle_righteous_cause_2`, `principle_righteous_cause_3`, `principle_settlement_drive_1`, `principle_settlement_drive_2`, `principle_settlement_drive_3`, `principle_sovereign_wealth_fund_1`, `principle_sovereign_wealth_fund_2`, `principle_sovereign_wealth_fund_3`, `principle_status_quo_1`, `principle_status_quo_2`, `principle_status_quo_3`, `principle_unified_bond_market_1`, `principle_unified_bond_market_2`, `principle_unified_bond_market_3`, `principle_unity_1`, `principle_unity_2`, `principle_unity_3`, `principle_wonder_weapons_1`, `principle_wonder_weapons_2`, `principle_wonder_weapons_3`, `principle_your_country_needs_you_1`, `principle_your_country_needs_you_2`, `principle_your_country_needs_you_3`
- **заменяет** (9): `principle_advanced_research_1`, `principle_advanced_research_2`, `principle_advanced_research_3`, `principle_internal_trade_1`, `principle_internal_trade_2`, `principle_internal_trade_3`, `principle_vassalization_1`, `principle_vassalization_2`, `principle_vassalization_3`

### production_method_groups

- **добавляет** (2): [[pbe/Группы методов/Entrenched Elite|Entrenched Elite]], [[pbe/Группы методов/Sovereign Wealth Fund|Sovereign Wealth Fund]]

### production_methods

- **добавляет** (4): [[pbe/Методы производства/Sovereign Wealth Fund|Sovereign Wealth Fund]], [[pbe/Методы производства/No Effect (pm_company_headquarter_swg_no_effect)|No Effect (pm_company_headquarter_swg_no_effect)]], [[pbe/Методы производства/Entrenched Elite|Entrenched Elite]], [[pbe/Методы производства/No Effect (pm_manor_house_entrenched_no_effect)|No Effect (pm_manor_house_entrenched_no_effect)]]

### script_values

- **добавляет** (38): `power_bloc_adjusted_mandate_cost_vanilla`, `power_bloc_ai_max_principles`, `power_bloc_diminishing_modifier_tooltip`, `power_bloc_diminishing_multiplier`, `power_bloc_diminishing_return_exponent_base`, `power_bloc_diminishing_return_exponent_base_tooltip`, `power_bloc_free_founding_mandates`, `power_bloc_identity_change_mandates`, `power_bloc_identity_change_mandates_tt`, `power_bloc_mandate_progress_countries`, `power_bloc_mandate_progress_rule_value`, `power_bloc_mandates_plus_principle_levels`, `power_bloc_max_mandates_rule_value`, `power_bloc_max_principles_rule_value`, `power_bloc_preserved_principles_switch`, `power_bloc_preserved_principles_switch_tt`, `power_bloc_vanilla_cohesion_mandate_modifier`, `vokaes_authority_per_manor_house_multiplier`, `vokaes_bureaucracy_per_bloc_member_multiplier`, `vokaes_convoys_per_leader_subjects_multiplier`, `vokaes_force_become_subject_infamy`, `vokaes_force_regime_change_infamy`, `vokaes_gold_interest_rate_baseline`, `vokaes_gold_reserves_interest_rate_multiplier`, `vokaes_gold_reserves_interest_rate_multiplier_tt`, `vokaes_influence_per_bloc_member_multiplier`, `vokaes_influence_per_subject_multiplier`, `vokaes_interest_rate_additive_modifier`, `vokaes_interest_rate_mult_modifier`, `vokaes_interest_rate_per_bloc_member_multiplier`, `vokaes_late_founding_mandates`, `vokaes_legitimacy_per_bloc_member_multiplier`, `vokaes_low_member_penalty_rule_value`, `vokaes_mapi_per_leader_subjects_multiplier`, `vokaes_minting_per_bloc_member_multiplier`, `vokaes_prestige_value_3x_target`, `vokaes_trade_per_bloc_member_multiplier`, `vokaes_training_rate_per_subject_multiplier`
- **повтор без `REPLACE_OR_CREATE:` — не действует (первое определение остаётся)** (1): `power_bloc_mandate_progress_by_rank`

### scripted_effects

- **добавляет** (11): `holy_war_start_action`, `power_bloc_reform_action`, `power_bloc_reform_action_2`, `vokaes_dynamic_modifier_handler`, `vokaes_dynamic_modifier_update`, `vokaes_foreign_investment_agreement_pact`, `vokaes_leviathan_modifier`, `vokaes_power_bloc_holy_war_enforced_effect`, `vokaes_power_bloc_revolution_effect`, `vokaes_set_rule_modifier`, `vokaes_weekly_global_handler`

### scripted_guis

- **добавляет** (4): `power_bloc_prereform`, `power_bloc_reform`, `power_bloc_reform_2`, `vokaes_power_bloc_rule_enable_identity_switch_gui`

### scripted_rules

- **добавляет** (8): `unlock_power_bloc_principle_slot_10`, `unlock_power_bloc_principle_slot_11`, `unlock_power_bloc_principle_slot_12`, `unlock_power_bloc_principle_slot_5`, `unlock_power_bloc_principle_slot_6`, `unlock_power_bloc_principle_slot_7`, `unlock_power_bloc_principle_slot_8`, `unlock_power_bloc_principle_slot_9`
- **заменяет** (4): `can_impose_law_default`, `can_lead_power_bloc`, `unlock_power_bloc_principle_slot_3`, `unlock_power_bloc_principle_slot_4`

### scripted_triggers

- **добавляет** (5): `PBE_is_active_trigger`, `vokaes_custom_law_imposition_trigger`, `vokaes_custom_law_imposition_trigger_economy`, `vokaes_custom_law_imposition_trigger_home_affairs`, `vokaes_custom_law_imposition_trigger_welfare`

### static_modifiers

- **добавляет** (20): `ideological_union_vanilla_modifier`, `military_treaty_organization_vanilla_modifier`, `religious_vanilla_modifier`, `sovereign_empire_leviathan_modifier`, `sovereign_empire_vanilla_modifier`, `trade_league_vanilla_modifier`, `vokaes_authority_per_manor_house_modifier`, `vokaes_bureaucracy_per_member_modifier`, `vokaes_convoys_per_leader_subject_modifier`, `vokaes_free_mandates_modifier`, `vokaes_gold_reserve_interest_modifier`, `vokaes_influence_per_bloc_member_modifier`, `vokaes_influence_per_subject_modifier`, `vokaes_interest_rate_power_bloc_member_modifier`, `vokaes_legitimacy_per_bloc_member_modifier`, `vokaes_mapi_per_leader_subject_modifier`, `vokaes_minting_per_bloc_member_modifier`, `vokaes_temp_influence_modifier`, `vokaes_trade_per_bloc_member_modifier`, `vokaes_training_rate_per_subject_modifier`

## defines

Сливаются по одному define, не блоком.

| define | ваниль | мод |
| --- | --- | --- |
| `NPowerBlocs.MAX_MANDATES` | `3` | `100` |
| `NPowerBlocs.MAX_MANDATE_PROGRESS` | `2000` | `750` |
| `NPowerBlocs.MAX_PRINCIPLES` | `4` | `12` |
| `NPowerBlocs.POWER_BLOC_INFLUENCE_COST` | `500` | `0` |

## Вне common/

| папка | файлов | поверх файла ваниль |
| --- | --- | --- |
| `events/` | 1 | 0 |
| `gui/` | 2 | 2 |
| `gfx/` | 40 | 0 |
| `localization/` | 1 | 0 |

- **gui/ поверх ваниль**: `gui/power_bloc_formation_panel.gui`, `gui/power_bloc_panel.gui`

**События**: 3 id; с id ваниль — 0.

**Локализация** (английская и русская): ключей 437; в `replace/` — 0; есть у ваниль вне `replace/` — 4 (не действуют: побеждает первый файл).
