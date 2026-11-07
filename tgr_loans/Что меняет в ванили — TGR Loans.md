---
type: reference
description: "Что мод TGR Loans меняет в ванили 1.13: записи common/ по папкам, defines, файлы поверх ваниль, события, локализация"
project: vic3
audience: agent
source: tgr_loans
tags: [tgr_loans, что-меняет]
generated: "v3 graph mods"
paths: [TGR_Loans/**]
---
# Что меняет в ванили — TGR Loans

Снимок `TGR_Loans`, сравнение с ваниль 1.13. Генерат `v3 graph mods`: руками не править. Правила слияния — навык `vic3-modding`, «load-and-override»: запись, которой нет у ваниль, мод **добавляет**; голое тело или `REPLACE:` ключа ваниль **заменяет** запись целиком; `INJECT:` **дополняет**; файл с путём файла ваниль — файл ваниль не читается, его записи, которых мод не повторил, **удалены**. Сравнение только с ваниль: запись другого мода (мод — аддон или патч) здесь — «нет у ваниль».

## Записи common/

| папка | добавляет | заменяет | дополняет | складывает | вставка в чужое | удаляет файлом | не действует |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `country_ranks` | 0 | 8 | 0 | 0 | 0 | 0 | 0 |
| `customizable_localization` | 15 | 0 | 0 | 0 | 0 | 0 | 0 |
| `journal_entries` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `legitimacy_levels` | 0 | 5 | 0 | 0 | 0 | 0 | 0 |
| `modifier_type_definitions` | 0 | 13 | 0 | 0 | 0 | 0 | 0 |
| `script_values` | 5 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_buttons` | 8 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_progress_bars` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `static_modifiers` | 11 | 0 | 1 | 0 | 0 | 0 | 0 |
| `technology/technologies` | 0 | 5 | 0 | 0 | 0 | 0 | 0 |

### country_ranks

- **заменяет** (8): `decentralized_power`, `great_power`, `insignificant_power`, `major_power`, `minor_power`, `unrecognized_major_power`, `unrecognized_power`, `unrecognized_regional_power`

### customizable_localization

- **добавляет** (15): `great_gdp_ranking_checkbox`, `great_political_movement_radicalism_checkbox`, `great_revision_communist_countries_checkbox`, `great_revision_country_radicals_checkbox`, `great_revision_debt_checkbox`, `great_revision_economic_system_checkbox`, `great_revision_infamy_checkbox`, `great_revision_is_at_war_checkbox`, `great_revision_legittimacy_checkbox`, `great_revision_no_autocratic_countries_checkbox`, `great_revision_no_slavery_countries_checkbox`, `great_revision_positive_cash_reserve_checkbox`, `great_revision_positive_cashflow_checkbox`, `great_revision_positive_investment_pool_cashflow_checkbox`, `great_revision_trade_policy_checkbox`

### journal_entries

- **добавляет** (1): `je_international_loans`

### legitimacy_levels

- **заменяет** (5): `legitimacy_level_contested`, `legitimacy_level_illegitimate`, `legitimacy_level_legitimate`, `legitimacy_level_righteous`, `legitimacy_level_unacceptable`

### modifier_type_definitions

- **заменяет** (13): `state_academics_investment_pool_contribution_add`, `state_aristocrats_investment_pool_contribution_add`, `state_bureaucrats_investment_pool_contribution_add`, `state_capitalists_investment_pool_contribution_add`, `state_clergymen_investment_pool_contribution_add`, `state_clerks_investment_pool_contribution_add`, `state_engineers_investment_pool_contribution_add`, `state_farmers_investment_pool_contribution_add`, `state_laborers_investment_pool_contribution_add`, `state_machinists_investment_pool_contribution_add`, `state_officers_investment_pool_contribution_add`, `state_shopkeepers_investment_pool_contribution_add`, `state_soldiers_investment_pool_contribution_add`

### script_values

- **добавляет** (5): `great_revision_international_loans_credit_script_value`, `great_revision_international_loans_tgr_loans_button_2_interest_value`, `great_revision_international_loans_tgr_loans_button_2_value`, `great_revision_international_loans_tgr_loans_button_6_interest_value`, `great_revision_international_loans_tgr_loans_button_6_value`

### scripted_buttons

- **добавляет** (8): `tgr_loans_button_1`, `tgr_loans_button_2`, `tgr_loans_button_3`, `tgr_loans_button_4`, `tgr_loans_button_5`, `tgr_loans_button_6`, `tgr_loans_button_7`, `tgr_loans_button_8`

### scripted_progress_bars

- **добавляет** (1): `je_international_loans_progress_bar`

### static_modifiers

- **добавляет** (11): `great_revision_international_loans_credit_rating_modifier`, `tgr_loans_button_1_modifier`, `tgr_loans_button_2_interest_modifier`, `tgr_loans_button_2_modifier`, `tgr_loans_button_3_modifier_trigger`, `tgr_loans_button_4_modifier`, `tgr_loans_button_5_modifier_trigger`, `tgr_loans_button_6_interest_modifier`, `tgr_loans_button_6_modifier`, `tgr_loans_button_7_modifier`, `tgr_loans_button_8_modifier`
- **дополняет** (1): `base_values`

### technology/technologies

- **заменяет** (5): [[tgr_loans/Технологии/Банковская система|Банковская система]], [[tgr_loans/Технологии/Центральный банк (технология)|Центральный банк (технология)]], [[tgr_loans/Технологии/Стандарты международного обмена|Стандарты международного обмена]], [[tgr_loans/Технологии/Современные финансовые инструменты|Современные финансовые инструменты]], [[tgr_loans/Технологии/Паевые инвестиционные фонды|Паевые инвестиционные фонды]]

## Вне common/

| папка | файлов | поверх файла ваниль |
| --- | --- | --- |
| `gfx/` | 2 | 0 |
| `localization/` | 1 | 0 |


**События**: 0 id; с id ваниль — 0.

**Локализация** (английская и русская): ключей 107; в `replace/` — 0; есть у ваниль вне `replace/` — 0 (не действуют: побеждает первый файл).
