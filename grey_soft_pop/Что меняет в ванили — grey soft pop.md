---
type: reference
description: "Что мод grey soft pop меняет в ванили 1.13: записи common/ по папкам, defines, файлы поверх ваниль, события, локализация"
project: vic3
audience: agent
source: grey_soft_pop
tags: [grey_soft_pop, что-меняет]
generated: "v3 graph mods"
paths: [grey_add_alot_of_things/_grey_soft_pop/**]
---
# Что меняет в ванили — grey soft pop

Снимок `grey_add_alot_of_things/_grey_soft_pop`, сравнение с ваниль 1.13. Генерат `v3 graph mods`: руками не править. Правила слияния — навык `vic3-modding`, «load-and-override»: запись, которой нет у ваниль, мод **добавляет**; голое тело или `REPLACE:` ключа ваниль **заменяет** запись целиком; `INJECT:` **дополняет**; файл с путём файла ваниль — файл ваниль не читается, его записи, которых мод не повторил, **удалены**. Сравнение только с ваниль: запись другого мода (мод — аддон или патч) здесь — «нет у ваниль».

## Записи common/

| папка | добавляет | заменяет | дополняет | складывает | вставка в чужое | удаляет файлом | не действует |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `acceptance_statuses` | 0 | 5 | 0 | 0 | 0 | 0 | 0 |
| `country_ranks` | 0 | 8 | 0 | 0 | 0 | 0 | 0 |
| `decrees` | 0 | 2 | 0 | 0 | 0 | 0 | 0 |
| `game_rules` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `laws` | 0 | 6 | 0 | 0 | 0 | 0 | 0 |
| `modifier_type_definitions` | 1 | 1 | 0 | 0 | 0 | 0 | 0 |
| `on_actions` | 16 | 0 | 0 | 14 | 0 | 0 | 0 |
| `pop_types` | 2 | 15 | 0 | 0 | 0 | 0 | 0 |
| `production_methods` | 119 | 3 | 0 | 0 | 0 | 0 | 0 |
| `script_values` | 0 | 1 | 0 | 0 | 0 | 0 | 5 |
| `scripted_effects` | 7 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_triggers` | 20 | 0 | 0 | 0 | 0 | 0 | 0 |
| `static_modifiers` | 27 | 3 | 0 | 0 | 0 | 0 | 0 |

### acceptance_statuses

- **заменяет** (5): `cultural_erasure`, `full_acceptance`, `open_prejudice`, `second_rate_citizen`, `violent_hostility`

### country_ranks

- **заменяет** (8): `decentralized_power`, `great_power`, `insignificant_power`, `major_power`, `minor_power`, `unrecognized_major_power`, `unrecognized_power`, `unrecognized_regional_power`

### decrees

- **заменяет** (2): `decree_greener_grass_campaign`, `decree_promote_national_values`

### game_rules

- **добавляет** (1): `mog_spa_sol_modification`

### laws

- **заменяет** (6): [[grey_soft_pop/Законы/Культурное отчуждение|Культурное отчуждение]], [[grey_soft_pop/Законы/Этническое государство|Этническое государство]], [[grey_soft_pop/Законы/Мультикультурализм|Мультикультурализм]], [[grey_soft_pop/Законы/Национальное превосходство|Национальное превосходство]], [[grey_soft_pop/Законы/Расовая сегрегация|Расовая сегрегация]], [[grey_soft_pop/Законы/Подданство|Подданство]]

### modifier_type_definitions

- **добавляет** (1): `state_slaves_education_access_add`
- **заменяет** (1): `state_education_access_wealth_add`

### on_actions

- **добавляет** (16): `MoG_SPA_colonial_company_migration_penalty_check`, `MoG_SPA_indigenous_subsistance_monthly_pulse`, `MoG_SPA_indigenous_subsistance_setup_action`, `MoG_SPA_literacy_investment_change`, `MoG_SPA_literacy_law_enact`, `MoG_SPA_literacy_no_longer_default`, `MoG_SPA_literacy_on_country_released`, `MoG_SPA_literacy_setup_action`, `MoG_SPA_sol_base_modifier_action`, `MoG_SPA_sol_game_started_base_action`, `MoG_SPA_sol_monthly_pulse_state`, `MoG_SPA_sol_setup_action`, `clear_colonial_company_migration_penalty_on_actions`, `mog_spa_hail_c_fixes_action`, `state_education_access_setup_action`, `state_education_access_update_action`
- **ключ ваниль в папке, которая складывается (`on_actions` складываются, `effect` — последний загруженный)** (14): `on_country_formed`, `on_country_no_longer_default`, `on_country_released_as_independent`, `on_country_released_as_overlord_subject`, `on_country_released_as_own_subject`, `on_game_started`, `on_investment_decreased`, `on_investment_increased`, `on_law_activated`, `on_monthly_pulse_country`, `on_monthly_pulse_state`, `on_revolution_start`, `on_secession_start`, `on_yearly_pulse_country`

### pop_types

- **добавляет** (2): [[grey_soft_pop/Население/Типы/druids|druids]], [[grey_soft_pop/Население/Типы/mages|mages]]
- **заменяет** (15): [[grey_soft_pop/Население/Типы/Учёные|Учёные]], [[grey_soft_pop/Население/Типы/Аристократы|Аристократы]], [[grey_soft_pop/Население/Типы/Чиновники|Чиновники]], [[grey_soft_pop/Население/Типы/Капиталисты|Капиталисты]], [[grey_soft_pop/Население/Типы/Священнослужители|Священнослужители]], [[grey_soft_pop/Население/Типы/Служащие|Служащие]], [[grey_soft_pop/Население/Типы/Инженеры|Инженеры]], [[grey_soft_pop/Население/Типы/Фермеры|Фермеры]], [[grey_soft_pop/Население/Типы/Рабочие|Рабочие]], [[grey_soft_pop/Население/Типы/Механики|Механики]], [[grey_soft_pop/Население/Типы/Офицеры|Офицеры]], [[grey_soft_pop/Население/Типы/Крестьяне|Крестьяне]], [[grey_soft_pop/Население/Типы/Лавочники|Лавочники]], [[grey_soft_pop/Население/Типы/Рабы|Рабы]], [[grey_soft_pop/Население/Типы/Военнослужащие|Военнослужащие]]

### production_methods

- **добавляет** (119): [[grey_soft_pop/Методы производства/pm_default_building_Broadway|pm_default_building_Broadway]], [[grey_soft_pop/Методы производства/pm_default_building_aarhus_university|pm_default_building_aarhus_university]], [[grey_soft_pop/Методы производства/pm_default_building_abisko_national_park|pm_default_building_abisko_national_park]], [[grey_soft_pop/Методы производства/pm_default_building_amsterdam_central_station|pm_default_building_amsterdam_central_station]], [[grey_soft_pop/Методы производства/pm_default_building_arab_bank|pm_default_building_arab_bank]], [[grey_soft_pop/Методы производства/pm_default_building_banca_nationala_romaniei|pm_default_building_banca_nationala_romaniei]], [[grey_soft_pop/Методы производства/pm_default_building_banco_comercial_costa_rica|pm_default_building_banco_comercial_costa_rica]], [[grey_soft_pop/Методы производства/pm_default_building_banco_comercial_sao_paulo|pm_default_building_banco_comercial_sao_paulo]], [[grey_soft_pop/Методы производства/pm_default_building_banco_de_chile|pm_default_building_banco_de_chile]], [[grey_soft_pop/Методы производства/pm_default_building_banco_inversiones_panama|pm_default_building_banco_inversiones_panama]], [[grey_soft_pop/Методы производства/pm_default_building_banco_nacion_argentina|pm_default_building_banco_nacion_argentina]], [[grey_soft_pop/Методы производства/pm_default_building_banco_nacional_portugal|pm_default_building_banco_nacional_portugal]], [[grey_soft_pop/Методы производства/pm_default_building_banco_republica_uruguay|pm_default_building_banco_republica_uruguay]], [[grey_soft_pop/Методы производства/pm_default_building_bank_melli_iran|pm_default_building_bank_melli_iran]], [[grey_soft_pop/Методы производства/pm_default_building_bank_of_japan|pm_default_building_bank_of_japan]], [[grey_soft_pop/Методы производства/pm_default_building_bank_of_korea|pm_default_building_bank_of_korea]], [[grey_soft_pop/Методы производства/pm_default_building_banque_nationale_belgique|pm_default_building_banque_nationale_belgique]], [[grey_soft_pop/Методы производства/pm_default_building_bayerischer_wald_national_park|pm_default_building_bayerischer_wald_national_park]], [[grey_soft_pop/Методы производства/pm_default_building_bbva|pm_default_building_bbva]], [[grey_soft_pop/Методы производства/pm_default_building_ben_thanh_market|pm_default_building_ben_thanh_market]], [[grey_soft_pop/Методы производства/pm_default_building_bnl|pm_default_building_bnl]], [[grey_soft_pop/Методы производства/pm_default_building_bocconi_university|pm_default_building_bocconi_university]], [[grey_soft_pop/Методы производства/pm_default_building_brooklyn_bridge|pm_default_building_brooklyn_bridge]], [[grey_soft_pop/Методы производства/pm_default_building_cairngorms_national_park|pm_default_building_cairngorms_national_park]], [[grey_soft_pop/Методы производства/pm_default_building_cairo_university|pm_default_building_cairo_university]], [[grey_soft_pop/Методы производства/pm_default_building_carnegie_mellon_university|pm_default_building_carnegie_mellon_university]], [[grey_soft_pop/Методы производства/pm_default_building_church_of_saint_george|pm_default_building_church_of_saint_george]], [[grey_soft_pop/Методы производства/pm_default_building_complutense_university_of_madrid|pm_default_building_complutense_university_of_madrid]], [[grey_soft_pop/Методы производства/pm_default_building_csob|pm_default_building_csob]], [[grey_soft_pop/Методы производства/pm_default_building_danske_bank|pm_default_building_danske_bank]], [[grey_soft_pop/Методы производства/pm_default_building_dartmoor_national_park|pm_default_building_dartmoor_national_park]], [[grey_soft_pop/Методы производства/pm_default_building_deutsche_bank|pm_default_building_deutsche_bank]], [[grey_soft_pop/Методы производства/pm_default_building_dnb_asa|pm_default_building_dnb_asa]], [[grey_soft_pop/Методы производства/pm_default_building_ephe_paris|pm_default_building_ephe_paris]], [[grey_soft_pop/Методы производства/pm_default_building_erasmus_rotterdam_university|pm_default_building_erasmus_rotterdam_university]], [[grey_soft_pop/Методы производства/pm_default_building_eth_zurich|pm_default_building_eth_zurich]], [[grey_soft_pop/Методы производства/pm_default_building_golden_gate_bridge|pm_default_building_golden_gate_bridge]], [[grey_soft_pop/Методы производства/pm_default_building_gran_paradiso_national_park|pm_default_building_gran_paradiso_national_park]], [[grey_soft_pop/Методы производства/pm_default_building_great_wall|pm_default_building_great_wall]], [[grey_soft_pop/Методы производства/pm_default_building_gyeongbokgung_palace|pm_default_building_gyeongbokgung_palace]], [[grey_soft_pop/Методы производства/pm_default_building_ha_long_bay|pm_default_building_ha_long_bay]], [[grey_soft_pop/Методы производства/pm_default_building_helsinki_university_of_technology|pm_default_building_helsinki_university_of_technology]], [[grey_soft_pop/Методы производства/pm_default_building_himeji_castle|pm_default_building_himeji_castle]], [[grey_soft_pop/Методы производства/pm_default_building_hollywood|pm_default_building_hollywood]], [[grey_soft_pop/Методы производства/pm_default_building_hoover_dam|pm_default_building_hoover_dam]], [[grey_soft_pop/Методы производства/pm_default_building_hsbc_building|pm_default_building_hsbc_building]], [[grey_soft_pop/Методы производства/pm_default_building_imperial_ottoman_bank|pm_default_building_imperial_ottoman_bank]], [[grey_soft_pop/Методы производства/pm_default_building_indochina_bank|pm_default_building_indochina_bank]], [[grey_soft_pop/Методы производства/pm_default_building_indochina_university|pm_default_building_indochina_university]], [[grey_soft_pop/Методы производства/pm_default_building_jameh_mosque|pm_default_building_jameh_mosque]], [[grey_soft_pop/Методы производства/pm_default_building_johns_hopkins_university|pm_default_building_johns_hopkins_university]], [[grey_soft_pop/Методы производства/pm_default_building_kyoto_university|pm_default_building_kyoto_university]], [[grey_soft_pop/Методы производства/pm_default_building_leaning_tower_of_pisa|pm_default_building_leaning_tower_of_pisa]], [[grey_soft_pop/Методы производства/pm_default_building_lodi_gardens|pm_default_building_lodi_gardens]], [[grey_soft_pop/Методы производства/pm_default_building_london_provincial_bank|pm_default_building_london_provincial_bank]], [[grey_soft_pop/Методы производства/pm_default_building_london_university|pm_default_building_london_university]], [[grey_soft_pop/Методы производства/pm_default_building_long_bien_bridge|pm_default_building_long_bien_bridge]], [[grey_soft_pop/Методы производства/pm_default_building_magyar_nemzeti_bank|pm_default_building_magyar_nemzeti_bank]], [[grey_soft_pop/Методы производства/pm_default_building_masjed_soleyman_oil_field|pm_default_building_masjed_soleyman_oil_field]], [[grey_soft_pop/Методы производства/pm_default_building_moscow_institute_of_technology|pm_default_building_moscow_institute_of_technology]], [[grey_soft_pop/Методы производства/pm_default_building_mysore_palace|pm_default_building_mysore_palace]], [[grey_soft_pop/Методы производства/pm_default_building_nanjing_university|pm_default_building_nanjing_university]], [[grey_soft_pop/Методы производства/pm_default_building_narodowy_bank_polski|pm_default_building_narodowy_bank_polski]], [[grey_soft_pop/Методы производства/pm_default_building_national_bank_egypt|pm_default_building_national_bank_egypt]], [[grey_soft_pop/Методы производства/pm_default_building_national_bank_greece|pm_default_building_national_bank_greece]], [[grey_soft_pop/Методы производства/pm_default_building_national_bank_guatemala|pm_default_building_national_bank_guatemala]], [[grey_soft_pop/Методы производства/pm_default_building_national_bank_mexico|pm_default_building_national_bank_mexico]], [[grey_soft_pop/Методы производства/pm_default_building_national_bank_philadelphia|pm_default_building_national_bank_philadelphia]], [[grey_soft_pop/Методы производства/pm_default_building_north_sea_canal|pm_default_building_north_sea_canal]], [[grey_soft_pop/Методы производства/pm_default_building_norwegian_university_of_technology|pm_default_building_norwegian_university_of_technology]], [[grey_soft_pop/Методы производства/pm_default_building_notre_dame|pm_default_building_notre_dame]], [[grey_soft_pop/Методы производства/pm_default_building_notre_dame_afrique|pm_default_building_notre_dame_afrique]], [[grey_soft_pop/Методы производства/pm_default_building_notre_dame_saigon|pm_default_building_notre_dame_saigon]], [[grey_soft_pop/Методы производства/pm_default_building_oesterreichische_nationalbank|pm_default_building_oesterreichische_nationalbank]], [[grey_soft_pop/Методы производства/pm_default_building_peak_district_national_park|pm_default_building_peak_district_national_park]], [[grey_soft_pop/Методы производства/pm_default_building_peking_university|pm_default_building_peking_university]], [[grey_soft_pop/Методы производства/pm_default_building_phong_nha_ke_bang|pm_default_building_phong_nha_ke_bang]], [[grey_soft_pop/Методы производства/pm_default_building_ponce_de_leon_hotel|pm_default_building_ponce_de_leon_hotel]], [[grey_soft_pop/Методы производства/pm_default_building_queens_university|pm_default_building_queens_university]], [[grey_soft_pop/Методы производства/pm_default_building_russian_empire_bank|pm_default_building_russian_empire_bank]], [[grey_soft_pop/Методы производства/pm_default_building_sacramento_port|pm_default_building_sacramento_port]], [[grey_soft_pop/Методы производства/pm_default_building_saint_joseph_university|pm_default_building_saint_joseph_university]], [[grey_soft_pop/Методы производства/pm_default_building_sarek_national_park|pm_default_building_sarek_national_park]], [[grey_soft_pop/Методы производства/pm_default_building_seoul_national_university_hospital|pm_default_building_seoul_national_university_hospital]], [[grey_soft_pop/Методы производства/pm_default_building_shanghai_bund|pm_default_building_shanghai_bund]], [[grey_soft_pop/Методы производства/pm_default_building_shanghai_jiaotong_university|pm_default_building_shanghai_jiaotong_university]], [[grey_soft_pop/Методы производства/pm_default_building_societe_generale|pm_default_building_societe_generale]], [[grey_soft_pop/Методы производства/pm_default_building_st_petersburg_polytechnic_university|pm_default_building_st_petersburg_polytechnic_university]], [[grey_soft_pop/Методы производства/pm_default_building_stanford_university|pm_default_building_stanford_university]], [[grey_soft_pop/Методы производства/pm_default_building_state_bank_india|pm_default_building_state_bank_india]], [[grey_soft_pop/Методы производства/pm_default_building_stockholm_city_hall|pm_default_building_stockholm_city_hall]], [[grey_soft_pop/Методы производства/pm_default_building_sun_yat_sen_university|pm_default_building_sun_yat_sen_university]], [[grey_soft_pop/Методы производства/pm_default_building_suomen_pankki|pm_default_building_suomen_pankki]], [[grey_soft_pop/Методы производства/pm_default_building_sutter_mill|pm_default_building_sutter_mill]], [[grey_soft_pop/Методы производства/pm_default_building_sveriges_riksbank|pm_default_building_sveriges_riksbank]], [[grey_soft_pop/Методы производства/pm_default_building_swiss_national_bank|pm_default_building_swiss_national_bank]], [[grey_soft_pop/Методы производства/pm_default_building_technical_university_berlin|pm_default_building_technical_university_berlin]], [[grey_soft_pop/Методы производства/pm_default_building_three_gorges_dam|pm_default_building_three_gorges_dam]], [[grey_soft_pop/Методы производства/pm_default_building_tilburg_university|pm_default_building_tilburg_university]], [[grey_soft_pop/Методы производства/pm_default_building_tohoku_university|pm_default_building_tohoku_university]], [[grey_soft_pop/Методы производства/pm_default_building_tokyo_station|pm_default_building_tokyo_station]], [[grey_soft_pop/Методы производства/pm_default_building_tokyo_university|pm_default_building_tokyo_university]], [[grey_soft_pop/Методы производства/pm_default_building_toronto_dominion_bank|pm_default_building_toronto_dominion_bank]], [[grey_soft_pop/Методы производства/pm_default_building_tsinghua_university|pm_default_building_tsinghua_university]], [[grey_soft_pop/Методы производства/pm_default_building_uffizi|pm_default_building_uffizi]], [[grey_soft_pop/Методы производства/pm_default_building_ulb_brussels|pm_default_building_ulb_brussels]], [[grey_soft_pop/Методы производства/pm_default_building_universidade_de_sao_paulo|pm_default_building_universidade_de_sao_paulo]], [[grey_soft_pop/Методы производства/pm_default_building_university_of_british_columbia|pm_default_building_university_of_british_columbia]], [[grey_soft_pop/Методы производства/pm_default_building_university_of_cape_town|pm_default_building_university_of_cape_town]], [[grey_soft_pop/Методы производства/pm_default_building_university_of_gothenburg|pm_default_building_university_of_gothenburg]], [[grey_soft_pop/Методы производства/pm_default_building_university_of_lisbon|pm_default_building_university_of_lisbon]], [[grey_soft_pop/Методы производства/pm_default_building_university_of_ottawa|pm_default_building_university_of_ottawa]], [[grey_soft_pop/Методы производства/pm_default_building_university_of_stockholm|pm_default_building_university_of_stockholm]], [[grey_soft_pop/Методы производства/pm_default_building_vanoise_national_park|pm_default_building_vanoise_national_park]], [[grey_soft_pop/Методы производства/pm_default_building_vienna_university_of_economics_and_business|pm_default_building_vienna_university_of_economics_and_business]], [[grey_soft_pop/Методы производства/pm_default_building_wuhan_university|pm_default_building_wuhan_university]], [[grey_soft_pop/Методы производства/pm_default_building_yonsei_university|pm_default_building_yonsei_university]], [[grey_soft_pop/Методы производства/pm_default_building_yosemite_national_park|pm_default_building_yosemite_national_park]], [[grey_soft_pop/Методы производства/pm_default_building_zhejiang_university|pm_default_building_zhejiang_university]]
- **заменяет** (3): [[grey_soft_pop/Методы производства/Статуя Свободы|Статуя Свободы]], [[grey_soft_pop/Методы производства/Белый дом|Белый дом]], [[grey_soft_pop/Методы производства/Увеличенный обмен|Увеличенный обмен]]

### script_values

- **заменяет** (1): `cultural_community_creation_weight`
- **повтор без `REPLACE_OR_CREATE:` — не действует (первое определение остаётся)** (5): `acceptance_status_1`, `acceptance_status_2`, `acceptance_status_3`, `acceptance_status_4`, `acceptance_status_5`

### scripted_effects

- **добавляет** (7): `add_modifier_hack`, `mog_spa_new_refresh_expected_sol_modifier`, `refresh_indigenous_subsistance_modifier`, `refresh_institution_schools_modifier`, `refresh_institution_schools_modifier_universal_cleanup`, `refresh_institution_schools_plp_modifier`, `refresh_institution_schools_uhre_modifier`

### scripted_triggers

- **добавляет** (20): `Grey_PLP_is_active`, `Grey_SPA_is_active`, `Ultra_RE_is_active_trigger`, `com_law_cultural_exclusion_alternative_trigger`, `com_law_cultural_exclusion_trigger`, `com_law_ethnostate_alternative_trigger`, `com_law_ethnostate_trigger`, `com_law_multicultural_alternative_trigger`, `com_law_multicultural_trigger`, `com_law_national_supremacy_alternative_trigger`, `com_law_national_supremacy_trigger`, `com_law_racial_segregation_alternative_trigger`, `com_law_racial_segregation_trigger`, `com_law_subjecthood_alternative_trigger`, `com_law_subjecthood_trigger`, `is_usfp_active`, `mog_plp_cul_exc_culture_minority_trigger`, `mog_plp_nat_sup_culture_minority_trigger`, `mog_plp_rac_seg_culture_minority_trigger`, `spa_sol_modification_trigger`

### static_modifiers

- **добавляет** (27): `mog_company_migration_penalty`, `mog_dei_citizenship_adjustment`, `mog_education_access_from_urbanization`, `mog_legacy_migration_penalty`, `mog_lower_strata_expected_sol_from_average`, `mog_middle_strata_expected_sol_from_average`, `mog_spa_base_sol_from_literacy`, `mog_spa_child_labor_allowed_literacy`, `mog_spa_compulsory_primary_school_literacy`, `mog_spa_diff_compulsory_school_literacy`, `mog_spa_diff_private_schools_literacy`, `mog_spa_diff_public_schools_literacy`, `mog_spa_diff_religious_schools_literacy`, `mog_spa_indigenous_subsistance`, `mog_spa_plp_diff_private_schools_literacy`, `mog_spa_plp_diff_public_schools_literacy`, `mog_spa_plp_diff_religious_schools_literacy`, `mog_spa_plp_uhre_diff_private_schools_literacy`, `mog_spa_plp_uhre_diff_public_schools_literacy`, `mog_spa_plp_uhre_diff_religious_schools_literacy`, `mog_spa_restricted_child_labor_literacy`, `mog_spa_uhre_diff_compulsory_school_literacy`, `mog_spa_uhre_diff_private_schools_literacy`, `mog_spa_uhre_diff_public_schools_literacy`, `mog_spa_uhre_diff_religious_schools_literacy`, `mog_spa_uhre_diff_restricted_child_labor_literacy`, `mog_upper_strata_expected_sol_from_average`
- **заменяет** (3): `state_turmoil`, `state_turmoil_extreme`, `state_turmoil_high`

## defines

Сливаются по одному define, не блоком.

| define | ваниль | мод |
| --- | --- | --- |
| `NPops.ACCEPTANCE_FROM_HOMELAND_COMMUNITY` | `0` | `15` |
| `NPops.ALLOW_ASSIMILATION_REQUIRE_HERITAGE_GROUP` | `no` | `yes` |
| `NPops.ASSIMILATION_IN_HOMELAND_MULT` | `0.75` | `0.2` |
| `NPops.ASSIMILATION_RATE` | `0.002` | `0.005` |
| `NPops.CONVERSION_RATE` | `0.002` | `0.003` |
| `NPops.CONVERSION_UNINCORPORATED_MULT` | `0.1` | `0.2` |
| `NPops.CULTURAL_COMMUNITY_LINGER_TIME_WEEKS` | `3` | `5` |
| `NPops.CULTURAL_COMMUNITY_MAX_PER_MONTH_CHANCE` | `0.04` | `1.0` |
| `NPops.CULTURAL_FERVOR_ASSIMILATIOM_EFFECT` | `0.01` | `0.008` |
| `NPops.EXPECTED_SOL_FROM_LITERACY_SUBSISTENCE_MULT` | `0.25` | `0.5` |
| `NPops.JOB_SATISFACTION_BASE` | `-130` | `-120` |
| `NPops.JOB_SATISFACTION_DIVIDENDS_BASE` | `50` | `10` |
| `NPops.JOB_SATISFACTION_FROM_CANNOT_AFFORD_EXPENSES` | `-100` | `-500` |
| `NPops.JOB_SATISFACTION_FROM_CAN_AFFORD_EXPENSES` | `1000` | `500` |
| `NPops.JOB_SATISFACTION_FROM_JOB_ATTRACTIVENESS` | `100` | `70` |
| `NPops.JOB_SATISFACTION_GOVERNMENT` | `50` | `100` |
| `NPops.JOB_SATISFACTION_LOSSES_MIN_MULT` | `-5` | `-10` |
| `NPops.JOB_SATISFACTION_PER_PERCENT_HIGHER_SOL_QUALIFICATION` | `-1` | `-0.8` |
| `NPops.JOB_SATISFACTION_PER_PERCENT_WAGE_RATE_ABOVE_NORMAL` | `1` | `0.5` |
| `NPops.JOB_SATISFACTION_PER_SOL_ABOVE_COUNTRY_STRATA_SOL` | `1` | `0.5` |
| `NPops.JOB_SATISFACTION_PER_SOL_ABOVE_EXPECTED_SOL` | `3` | `8` |
| `NPops.JOB_SATISFACTION_PER_SOL_ABOVE_STATE_STRATA_SOL` | `2` | `8` |
| `NPops.MARKET_MIGRATION_MIN_DIFFERENCE_IN_MIGRATION_ATTRACTION_TO_MOVE` | `5` | `3` |
| `NPops.MARKET_MIGRATION_MIN_POP_FRACTION_TO_MOVE` | `0.05` | `0.00001` |
| `NPops.MARKET_MIGRATION_PER_WEEK_FACTOR` | `5` | `2` |
| `NPops.MARKET_MIGRATION_PER_WEEK_PER_TOTAL_POPULATION` | `100000` | `160000` |
| `NPops.MARKET_MIGRATION_STATE_ATTRACTION_FRACTION` | `0.75` | `0.25` |
| `NPops.MASS_MIGRATION_COOLDOWN_MONTHS` | `48` | `60` |
| `NPops.MASS_MIGRATION_FEW_TARGET_STATES_PENALTY` | `0.2` | `0.3` |
| `NPops.MASS_MIGRATION_MIN_DIFFERENCE_IN_MIGRATION_ATTRACTION_TO_MOVE` | `10` | `6` |
| `NPops.MASS_MIGRATION_NUM_TARGET_STATES_FOR_NO_PENALTY` | `4` | `3` |
| `NPops.MASS_MIGRATION_ORIGIN_MIN_EMIGRANTS` | `100000` | `150000` |
| `NPops.MASS_MIGRATION_ORIGIN_MIN_TURMOIL` | `0.15` | `0.20` |
| `NPops.MASS_MIGRATION_PER_WEEK_FACTOR` | `10` | `8` |
| `NPops.MASS_MIGRATION_SPAWN_CHANCE` | `2` | `3` |
| `NPops.MASS_MIGRATION_SPAWN_CHANCE_STARVING_FACTOR` | `1` | `1.5` |
| `NPops.MASS_MIGRATION_SPAWN_CHANCE_STRUGGLING_FACTOR` | `0.2` | `0.3` |
| `NPops.MASS_MIGRATION_STATE_MIN_MARKET_ACCESS` | `0.7` | `0.8` |
| `NPops.MIGRATION_DESIRE_FROM_JOB_SATISFACTION_FACTOR` | `-1.0` | `-0.5` |
| `NPops.MIGRATION_MAX_PER_STATE_BASE` | `500` | `2000` |
| `NPops.MIGRATION_MAX_PER_STATE_INFRASTRUCTURE` | `5` | `10` |
| `NPops.MIGRATION_MAX_PER_STATE_MASS_IMMIGRATION_MULT` | `5.0` | `7.0` |
| `NPops.MIGRATION_MAX_PER_STATE_UNEMPLOYMENT_ORIGIN_FRACTION` | `0.05` | `0.1` |
| `NPops.MIGRATION_MAX_PER_STATE_UNEMPLOYMENT_TARGET_FRACTION` | `0.05` | `0.1` |
| `NPops.MIGRATION_MIN_STATE_POPS` | `20000` | `50000` |
| `NPops.MIGRATION_PULL_FROM_AVAILABLE_EMPLOYMENT` | `30` | `40` |
| `NPops.MIGRATION_PULL_FROM_AVAILABLE_EMPLOYMENT_MAX` | `30` | `20` |
| `NPops.MIGRATION_PULL_FROM_LIVING_STANDARD` | `2` | `1.6` |
| `NPops.MIGRATION_PULL_HIGH_THRESHOLD` | `1.25` | `0.75` |
| `NPops.MIGRATION_PULL_MULT_FROM_HOMELANDS` | `0.2` | `0.4` |
| `NPops.MIGRATION_PULL_MULT_FROM_MASS_MIGRATION_TARGET` | `1.5` | `1.8` |
| `NPops.MIGRATION_PULL_MULT_FROM_MASS_MIGRATION_TARGET_ADJACENCY` | `1.1` | `1.2` |
| `NPops.MIGRATION_PULL_MULT_FROM_NO_DISCRIMINATION` | `0.5` | `0.8` |
| `NPops.MIGRATION_PULL_REDUCTION_FROM_UNEMPLOYMENT` | `50` | `100` |
| `NPops.MIGRATION_PULL_REDUCTION_FROM_UNEMPLOYMENT_MAX` | `50` | `200` |
| `NPops.MIGRATION_STATE_POPULATION_THRESHOLD` | `100000` | `200000` |
| `NPops.MIN_ASSIMILATION` | `1` | `10` |
| `NPops.MIN_CONVERSION` | `1` | `10` |
| `NPops.MIN_POPS_FOR_NEW_OBSESSION` | `50000` | `500000` |
| `NPops.MIN_REQUIRED_ACCEPTANCE_FOR_MIGRATION` | `30` | `35` |
| `NPops.MIN_SUPPLY_LEVEL_FOR_NEW_OBSESSION` | `0.5` | `0.3` |
| `NPops.OBSESSION_SPAWN_CHANCE` | `0.5` | `4` |
| `NPops.OBSESSION_SPAWN_CHANCE_MAX_SUPPLY_MULT` | `3.0` | `2.0` |
| `NPops.POP_MERGE_MAX_WORKFORCE_AGGRESSIVE_CONSOLIDATION` | `50` | `100` |
| `NPops.POP_MERGE_MAX_WORKFORCE_MAX_CONSOLIDATION` | `100` | `200` |
| `NPops.POP_MERGE_MAX_WORKFORCE_MINOR_CONSOLIDATION` | `10` | `20` |
| `NPops.POP_MERGE_MAX_WORKFORCE_MODERATE_CONSOLIDATION` | `30` | `60` |
| `NPops.QUALIFICATIONS_NUM_MONTHS_AT_START` | `60` | `120` |
| `NPops.RADICALS_MAX_FROM_DISCRIMINATION` | `0.5` | `0.7` |
| `NPops.RADICALS_MAX_FROM_LOW_SOL` | `0.15` | `0.25` |
| `NPops.RADICALS_MONTHLY_FROM_LOW_SOL` | `0.003` | `0.004` |
| `NPops.RADICALS_MONTHLY_FROM_STARVATION_BASE` | `0.002` | `0.006` |
| `NPops.RADICALS_MONTHLY_FROM_STARVATION_MILD` | `0.008` | `0.012` |
| `NPops.WORKING_ADULT_RATIO_SKEW_MAXIMUM` | `2.0` | `4.0` |

## Вне common/

| папка | файлов | поверх файла ваниль |
| --- | --- | --- |
| `events/` | 3 | 0 |
| `localization/` | 22 | 0 |


**События**: 3 id; с id ваниль — 0.

**Локализация** (английская и русская): ключей 68; в `replace/` — 0; есть у ваниль вне `replace/` — 0 (не действуют: побеждает первый файл).
