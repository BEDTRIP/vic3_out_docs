---
type: reference
description: "Что мод PSC меняет в ванили 1.15 (снимок мода — 1.13): записи common/ по папкам, defines, файлы поверх ваниль, события, локализация"
project: vic3
audience: agent
source: psc
tags: [PSC, что-меняет]
generated: "v3 graph mods"
paths: [PSC/**]
---
# Что меняет в ванили — PSC

Снимок `PSC` (снимок мода — 1.13), сравнение с ваниль 1.15. Генерат `v3 graph mods`: руками не править. Правила слияния — навык `vic3-modding`, «load-and-override»: запись, которой нет у ваниль, мод **добавляет**; голое тело или `REPLACE:` ключа ваниль **заменяет** запись целиком; `INJECT:` **дополняет**; файл с путём файла ваниль — файл ваниль не читается, его записи, которых мод не повторил, **удалены**. Сравнение только с ваниль: запись другого мода (мод — аддон или патч) здесь — «нет у ваниль».

## Записи common/

| папка | добавляет | заменяет | дополняет | складывает | вставка в чужое | удаляет файлом | не действует |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `alert_types` | 0 | 1 | 0 | 0 | 0 | 0 | 0 |
| `building_groups` | 1 | 1 | 0 | 0 | 0 | 0 | 0 |
| `buildings` | 1 | 1 | 0 | 0 | 0 | 0 | 0 |
| `game_concepts` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `goods` | 4 | 0 | 0 | 0 | 0 | 0 | 0 |
| `modifier_type_definitions` | 9 | 0 | 0 | 0 | 0 | 0 | 0 |
| `on_actions` | 7 | 0 | 0 | 4 | 0 | 0 | 0 |
| `production_method_groups` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `production_methods` | 4 | 4 | 0 | 0 | 0 | 0 | 0 |
| `script_values` | 46 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_effects` | 11 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_guis` | 9 | 0 | 0 | 0 | 0 | 0 | 0 |
| `static_modifiers` | 3 | 0 | 0 | 0 | 0 | 0 | 0 |

### alert_types

- **заменяет** (1): `insufficient_construction_for_investment`

### building_groups

- **добавляет** (1): [[psc/Группы зданий/Construction Regulators|Construction Regulators]]
- **заменяет** (1): [[psc/Группы зданий/Строительство (группа зданий)|Строительство (группа зданий)]]

### buildings

- **добавляет** (1): [[psc/Здания/Construction Regulator|Construction Regulator]]
- **заменяет** (1): [[psc/Здания/Строительные сектора|Строительные сектора]]

### game_concepts

- **добавляет** (1): `concept_construction_spending`

### goods

- **добавляет** (4): [[psc/Товары/Arc-Welded Construction|Arc-Welded Construction]], [[psc/Товары/Iron Construction|Iron Construction]], [[psc/Товары/Steel Construction|Steel Construction]], [[psc/Товары/Wood Construction|Wood Construction]]

### modifier_type_definitions

- **добавляет** (9): `building_construction_regulator_throughput_add`, `goods_input_arc_welded_construction_add`, `goods_input_iron_construction_add`, `goods_input_steel_construction_add`, `goods_input_wood_construction_add`, `goods_output_arc_welded_construction_add`, `goods_output_iron_construction_add`, `goods_output_steel_construction_add`, `goods_output_wood_construction_add`

### on_actions

- **добавляет** (7): `on_acquired_construction_tech`, `on_construction_sector_built`, `on_construction_sector_method_changed`, `set_construction_country`, `set_construction_start`, `set_construction_weekly_on_action`, `set_spending_value`
- **ключ ваниль в папке, которая складывается (`on_actions` складываются, `effect` — последний загруженный)** (4): `on_acquired_technology`, `on_building_built`, `on_monthly_pulse`, `on_production_method_changed`

### production_method_groups

- **добавляет** (1): [[psc/Группы методов/Основа|Основа]]

### production_methods

- **добавляет** (4): [[psc/Методы производства/Basic Oversight (pm_arc_welded_point_conversion)|Basic Oversight (pm_arc_welded_point_conversion)]], [[psc/Методы производства/Basic Oversight (pm_iron_point_conversion)|Basic Oversight (pm_iron_point_conversion)]], [[psc/Методы производства/Basic Oversight (pm_steel_point_conversion)|Basic Oversight (pm_steel_point_conversion)]], [[psc/Методы производства/Basic Oversight (pm_wood_point_conversion)|Basic Oversight (pm_wood_point_conversion)]]
- **заменяет** (4): [[psc/Методы производства/Сварные сооружения|Сварные сооружения]], [[psc/Методы производства/Сооружения с чугунными рамами|Сооружения с чугунными рамами]], [[psc/Методы производства/Сооружения со стальными рамами|Сооружения со стальными рамами]], [[psc/Методы производства/Деревянные сооружения|Деревянные сооружения]]

### script_values

- **добавляет** (46): `ai_construction_demand`, `arc_welded_construction_good_base_price`, `calculate_added_days`, `calculate_construction_sector_max_level`, `calculate_corrected_private_allocation`, `calculate_government_construction_spending`, `calculate_limited_government_construction_spending`, `calculate_max_government_construction_spending`, `calculate_month_length`, `calculate_sqrt`, `calculate_state_construction_base_price`, `calculate_state_construction_efficiency`, `calculate_total_construction_spending`, `command_economy_spending_mult`, `construction_demand_ratio`, `construction_goods_per_point`, `construction_min_demand`, `construction_ordering`, `construction_price_weeks`, `construction_regulator_level`, `construction_sector_efficiency_multiplier`, `day_of_the_week`, `error_accuracy_denominator`, `goods_efficiency_per_level`, `integer_max_safety_limit`, `iron_construction_good_base_price`, `oversupply_limit`, `private_construction_increase`, `privatisation_percent_weeks`, `privatisation_spending_percent`, `privatisation_spending_percent_weekly`, `recurse_a`, `recurse_a2`, `recurse_n`, `recurse_n2`, `recurse_sqrt1`, `recurse_sqrt2`, `sqrt_scale`, `sqrt_scale_sq`, `state_construction_allocation`, `state_construction_spending_allocation`, `state_oversupply_limit`, `steel_construction_good_base_price`, `sum_construction_types_production`, `weekly_income_multiplier_base`, `wood_construction_good_base_price`

### scripted_effects

- **добавляет** (11): `check_construction_spending_level`, `delay_event_switch`, `my_trigger_event`, `production_method_building_switch`, `set_construction_point_demand`, `set_construction_regulator_level`, `set_government_construction_spending`, `set_new_point_conversion_method`, `set_new_regulator_point_conversion_method`, `set_point_conversion_method_from_tech`, `set_state_construction_efficiency`

### scripted_guis

- **добавляет** (9): `com_add_local_good`, `psc_button_decrease_ctrl_sgui`, `psc_button_decrease_sgui`, `psc_button_decrease_shift_sgui`, `psc_button_increase_ctrl_sgui`, `psc_button_increase_sgui`, `psc_button_increase_shift_sgui`, `psc_save_real_construction_cost`, `psc_test_show`

### static_modifiers

- **добавляет** (3): `construction_throughput_mult`, `country_private_construction_allocation_add`, `state_construction_efficiency_increase`

## defines

Сливаются по одному define, не блоком.

| define | ваниль | мод |
| --- | --- | --- |
| `NCountry.CONSTRUCTION_CAMP_BUILDING` | `"building_construction_sector"` | `"building_construction_regulator"` |

## Вне common/

| папка | файлов | поверх файла ваниль |
| --- | --- | --- |
| `gui/` | 6 | 0 |
| `gfx/` | 7 | 0 |
| `localization/` | 60 | 0 |


**События**: 0 id; с id ваниль — 0.

**Локализация** (английская и русская): ключей 106; в `replace/` — 0; есть у ваниль вне `replace/` — 4 (не действуют: побеждает первый файл).
