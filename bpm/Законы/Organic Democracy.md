---
type: concept
description: "Закон «Organic Democracy» — BPM 1.13, `law_organic_democracy`"
project: vic3
source: bpm
aliases: ["Organic Democracy", "law_organic_democracy"]
tags: [BPM, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_organic_democracy
paths: [BPM/common/laws/BPM_distribution_of_power.txt]
---
# Organic Democracy

Закон · `law_organic_democracy` · `common/laws/BPM_distribution_of_power.txt:1205`

## Поля

- **group**: [[bpm/Группы законов/Распределение власти|Распределение власти]]
- **icon**: `gfx/interface/icons/law_icons/corporate_state.dds`
- **progressiveness**: `200`
- **unlocking_technologies**: [[bpm/Технологии/Корпоративизм|Корпоративизм]]
- **can_enact**: скрипт, строки 1216–1225
- **unlocking_laws**: [[bpm/Законы/Всеобщее избирательное право|Всеобщее избирательное право]], [[bpm/Законы/Военная хунта|Военная хунта]]
- **disallowing_laws**: [[bpm/Законы/Советская республика|Советская республика]]
- **modifier**:
  - `country_rigidity_baseline_add` = `10`
  - `country_legitimacy_ideological_incoherence_mult` = `-0.25`
  - `country_legitimacy_govt_total_clout_add` = `150`
  - `country_legitimacy_govt_size_add` = `1`
  - `country_voting_power_wealth_threshold_add` = `30`
  - `interest_group_ig_landowners_pol_str_mult` = `0.4`
  - `interest_group_ig_industrialists_pol_str_mult` = `0.4`
  - `interest_group_ig_petty_bourgeoisie_pol_str_mult` = `0.4`
  - `country_voting_power_base_add` = `15`
  - `country_institution_suffrage_max_investment_add` = `1`
  - `country_institution_cost_institution_suffrage_mult` = `-0.85`
- **institution**: `institution_suffrage`
- **institution_modifier**:
  - `country_rigidity_baseline_add` = `5`
  - `country_legitimacy_ideological_incoherence_mult` = `-0.05`
  - `state_radicals_from_political_movements_mult` = `-0.05`
  - `country_bpm_labor_consciousness_target_mult` = `-0.1`
  - `country_legitimacy_govt_total_votes_add` = `25`
  - `country_legitimacy_govt_total_clout_add` = `-25`
  - `country_voting_power_wealth_threshold_add` = `-6`
  - `country_voting_power_base_add` = `4`
  - `interest_group_ig_rural_folk_pol_str_mult` = `0.05`
  - `interest_group_ig_trade_unions_pol_str_mult` = `0.05`
  - `interest_group_ig_intelligentsia_pol_str_mult` = `0.05`
  - `interest_group_ig_landowners_pol_str_mult` = `-0.1`
  - `interest_group_ig_industrialists_pol_str_mult` = `-0.1`
  - `interest_group_ig_petty_bourgeoisie_pol_str_mult` = `-0.1`
- **on_activate**: скрипт, строки 1281–1298
- **ai_will_do**: скрипт, строки 1300–1313
- **can_impose**: скрипт, строки 1315–1329
- **ai_enact_weight_modifier**: скрипт, строки 1351–1358
- **ai_impose_chance**: скрипт, строки 1360–1374

## Ссылаются

- **Идеологии** (lawgroup_distribution_of_power: approve): [[bpm/Идеологии/Conservative Democrat|Conservative Democrat]], [[bpm/Идеологии/Партийный государственник|Партийный государственник]]
- **Идеологии** (lawgroup_distribution_of_power: disapprove): [[bpm/Идеологии/Divine Democrat|Divine Democrat]], [[bpm/Идеологии/Авторитарный демократ|Авторитарный демократ]], [[bpm/Идеологии/Лоялист метрополии|Лоялист метрополии]]
- **Идеологии** (lawgroup_distribution_of_power: neutral): [[bpm/Идеологии/Christian Democrat|Christian Democrat]]
- **Идеологии** (lawgroup_distribution_of_power: strongly_approve): [[bpm/Идеологии/Organic Democrat|Organic Democrat]], [[bpm/Идеологии/Интегралистский самодержец|Интегралистский самодержец]]
- **Идеологии** (lawgroup_distribution_of_power: strongly_disapprove): [[bpm/Идеологии/Анархист|Анархист]], [[bpm/Идеологии/Анархо-синдикалист (ideology_dop_anarcho_syndicalist)|Анархо-синдикалист (ideology_dop_anarcho_syndicalist)]], [[bpm/Идеологии/Институциональный синдикалист|Институциональный синдикалист]], [[bpm/Идеологии/Меритократический самодержец|Меритократический самодержец]], [[bpm/Идеологии/Олигарх|Олигарх]], [[bpm/Идеологии/Партийный социалист|Партийный социалист]], [[bpm/Идеологии/Радикальный демократ|Радикальный демократ]], [[bpm/Идеологии/Самодержец|Самодержец]], [[bpm/Идеологии/Синдикалист (ideology_dop_syndicalist)|Синдикалист (ideology_dop_syndicalist)]], [[bpm/Идеологии/Технократ (ideology_dop_technocrat)|Технократ (ideology_dop_technocrat)]], [[bpm/Идеологии/Традиционная власть|Традиционная власть]], [[bpm/Идеологии/Умеренный демократ|Умеренный демократ]]
