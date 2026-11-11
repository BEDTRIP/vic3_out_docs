---
type: reference
description: "Что мод KAI меняет в ванили 1.15: записи common/ по папкам, defines, файлы поверх ваниль, события, локализация"
project: vic3
audience: agent
source: kai
tags: [KAI, что-меняет]
generated: "v3 graph mods"
paths: [TechRes+Kuromi/kai/**]
---
# Что меняет в ванили — KAI

Снимок `TechRes+Kuromi/kai`, сравнение с ваниль 1.15. Генерат `v3 graph mods`: руками не править. Правила слияния — навык `vic3-modding`, «load-and-override»: запись, которой нет у ваниль, мод **добавляет**; голое тело или `REPLACE:` ключа ваниль **заменяет** запись целиком; `INJECT:` **дополняет**; файл с путём файла ваниль — файл ваниль не читается, его записи, которых мод не повторил, **удалены**. Сравнение только с ваниль: запись другого мода (мод — аддон или патч) здесь — «нет у ваниль».

## Записи common/

| папка | добавляет | заменяет | дополняет | складывает | вставка в чужое | удаляет файлом | не действует |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `ai_strategies` | 0 | 8 | 15 | 0 | 0 | 0 | 0 |
| `buildings` | 0 | 0 | 4 | 0 | 0 | 0 | 0 |
| `diplomatic_actions` | 0 | 2 | 0 | 0 | 0 | 0 | 0 |
| `laws` | 0 | 0 | 34 | 0 | 0 | 0 | 0 |
| `mobilization_options` | 0 | 0 | 1 | 0 | 0 | 0 | 0 |
| `modifier_type_definitions` | 0 | 0 | 9 | 0 | 0 | 0 | 0 |
| `script_values` | 5 | 2 | 0 | 0 | 0 | 0 | 0 |
| `scripted_buttons` | 0 | 0 | 2 | 0 | 0 | 0 | 0 |
| `scripted_triggers` | 2 | 0 | 0 | 0 | 0 | 0 | 0 |
| `technology/technologies` | 0 | 0 | 5 | 0 | 0 | 0 | 0 |
| `treaty_articles` | 0 | 0 | 2 | 0 | 0 | 0 | 0 |

### ai_strategies

Файлы поверх ваниль: `common/ai_strategies/00_default_strategy.txt`.

- **заменяет** (8): `ai_strategy_agricultural_expansion`, `ai_strategy_colonial_extraction`, `ai_strategy_default`, `ai_strategy_industrial_expansion`, `ai_strategy_meiji_restoration`, `ai_strategy_placate_population`, `ai_strategy_plantation_economy`, `ai_strategy_resource_expansion`
- **дополняет** (15): `ai_strategy_anti_imperialism`, `ai_strategy_armed_isolationism`, `ai_strategy_colonial_expansion`, `ai_strategy_conservative_agenda`, `ai_strategy_economic_imperialism`, `ai_strategy_egalitarian_agenda`, `ai_strategy_great_reforms`, `ai_strategy_maintain_power_balance`, `ai_strategy_nationalist_agenda`, `ai_strategy_progressive_agenda`, `ai_strategy_reactionary_agenda`, `ai_strategy_restore_natural_borders`, `ai_strategy_socialism_in_one_country`, `ai_strategy_tanzimat_reforms`, `ai_strategy_territorial_expansion`

### buildings

- **дополняет** (4): [[kai/Здания/Строительные сектора|Строительные сектора]], [[kai/Здания/Правительственные ведомства|Правительственные ведомства]], [[kai/Здания/Статуи блока государств|Статуи блока государств]], [[kai/Здания/Университеты|Университеты]]

### diplomatic_actions

Файлы поверх ваниль: `common/diplomatic_actions/40_subjects_knowledge_sharing.txt`.

- **заменяет** (2): `da_knowledge_sharing`, `da_request_knowledge_sharing`

### laws

- **дополняет** (34): [[kai/Законы/Аграрность|Аграрность]], [[kai/Законы/Бакуфу|Бакуфу]], [[kai/Законы/Благотворительные лечебницы|Благотворительные лечебницы]], [[kai/Законы/Колониальная эксплуатация|Колониальная эксплуатация]], [[kai/Законы/Переселение в колонии|Переселение в колонии]], [[kai/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]], [[kai/Законы/Корпоративное государство|Корпоративное государство]], [[kai/Законы/Советская республика|Советская республика]], [[kai/Законы/Профессиональная полиция|Профессиональная полиция]], [[kai/Законы/Чрезвычайная комиссия|Чрезвычайная комиссия]], [[kai/Законы/Колонизация границ|Колонизация границ]], [[kai/Законы/Гарантия свобод|Гарантия свобод]], [[kai/Законы/Внутренняя колонизация|Внутренняя колонизация]], [[kai/Законы/Местная полиция|Местная полиция]], [[kai/Законы/Военизированная полиция|Военизированная полиция]], [[kai/Законы/Национальная гвардия|Национальная гвардия]], [[kai/Законы/Охранное отделение|Охранное отделение]], [[kai/Законы/Пенсия по старости|Пенсия по старости]], [[kai/Законы/Парламентская республика|Парламентская республика]], [[kai/Законы/Крестьянское землевладение|Крестьянское землевладение]], [[kai/Законы/Налог на душу населения|Налог на душу населения]], [[kai/Законы/Законы о бедняках|Законы о бедняках]], [[kai/Законы/Президентская республика|Президентская республика]], [[kai/Законы/Индивидуальное медицинское страхование|Индивидуальное медицинское страхование]], [[kai/Законы/Частные школы|Частные школы]], [[kai/Законы/Пропорциональный налог|Пропорциональный налог]], [[kai/Законы/Государственное медицинское страхование|Государственное медицинское страхование]], [[kai/Законы/Государственные школы|Государственные школы]], [[kai/Законы/Регулирующие органы|Регулирующие органы]], [[kai/Законы/Религиозные школы|Религиозные школы]], [[kai/Законы/Тайная полиция|Тайная полиция]], [[kai/Законы/Третье отделение|Третье отделение]], [[kai/Законы/Субсидирование зарплат|Субсидирование зарплат]], [[kai/Законы/Защита прав рабочих|Защита прав рабочих]]

### mobilization_options

- **дополняет** (1): `mobilization_option_first_aid`

### modifier_type_definitions

- **дополняет** (9): `building_shopkeepers_shares_add`, `military_formation_army_movement_speed_mult`, `state_fortification_naval_invasion_add`, `unit_defense_add`, `unit_kill_rate_add`, `unit_morale_recovery_mult`, `unit_occupation_mult`, `unit_offense_add`, `unit_recovery_rate_add`

### script_values

- **добавляет** (5): `kai_country_income_normalized`, `kai_estimated_bureaucracy_cost`, `kai_gdp_per_capita`, `kai_income_efficiency`, `kai_interest_rate`
- **заменяет** (2): `wanted_army_size_script_value`, `wanted_navy_size_script_value`

### scripted_buttons

- **дополняет** (2): `je_meiji_restoration_decide_shogunate_strategy`, `je_meiji_restoration_proclaim_imperial_restoration`

### scripted_triggers

- **добавляет** (2): `kai_can_afford_institution`, `kai_has_high_supply`

### technology/technologies

- **дополняет** (5): [[kai/Технологии/Пароатмосферный двигатель|Пароатмосферный двигатель]], [[kai/Технологии/Механические инструменты|Механические инструменты]], [[kai/Технологии/Радио|Радио]], [[kai/Технологии/Паровая турбина|Паровая турбина]], [[kai/Технологии/Телефон|Телефон]]

### treaty_articles

- **дополняет** (2): `foreign_investment_rights`, `trade_privilege`

## defines

Сливаются по одному define, не блоком.

| define | ваниль | мод |
| --- | --- | --- |
| `NAI.CONSUMPTION_TAX_INCOME_VALUE` | `10` | `150` |
| `NAI.GOVERNMENT_BUILDING_STATE_MISSING_QUALIFICATIONS_MULT` | `0.10` | `0.6` |
| `NAI.GOVERNMENT_BUILDING_STATE_POP_CONSTRUCTION_SECTOR_IMPORTANCE_MULT` | `1.5` | `1.0` |
| `NAI.INSTITUTION_SPENDING_DECREASE_SPENDING_RATIO` | `2.0` | `1.2` |
| `NAI.MAX_INSTITUTION_SPENDING_BASE` | `0.015` | `0.001` |
| `NAI.MAX_INSTITUTION_SPENDING_PER_INSTITUTION` | `0.005` | `0.004` |
| `NAI.MONEY_SPENDING_INNOVATION_DESIRED_THRESHOLD` | `1.0` | `2.0` |
| `NAI.MONEY_SPENDING_INNOVATION_EXCESSIVE_THRESHOLD` | `1.25` | `2.5` |
| `NAI.MONEY_SPENDING_MIN_RATIO_TO_ADD_SHOULD_HAVE` | `1.2` | `1.3` |
| `NAI.MONEY_SPENDING_MIN_RATIO_TO_ADD_WANTS_TO_HAVE` | `1.3` | `1.35` |
| `NAI.MONEY_SPENDING_MIN_SURPLUS_TO_IGNORE_RATIO_FOR_NICE_TO_HAVE` | `50000` | `200000` |
| `NAI.MONEY_SPENDING_MIN_SURPLUS_TO_IGNORE_RATIO_FOR_SHOULD_HAVE` | `15000` | `100000` |
| `NAI.MONEY_SPENDING_MIN_SURPLUS_TO_IGNORE_RATIO_FOR_WANTS_TO_HAVE` | `30000` | `150000` |
| `NAI.PRODUCTION_BUILDING_FAVORED_GOODS_FACTOR` | `0.5` | `0.25` |
| `NAI.PRODUCTION_BUILDING_OUTPUT_HIGH_PRICE_WANTS_HIGH_SUPPLY_FACTOR` | `0.75` | `2.0` |
| `NAI.PRODUCTION_METHOD_BASE_VALUE` | `1000` | `300` |
| `NAI.PRODUCTION_METHOD_EMPLOYMENT_CHANGE_FACTOR` | `2.0` | `0.75` |
| `NAI.PRODUCTION_METHOD_FAVORED_GOODS_FACTOR` | `0.25` | `0.05` |
| `NAI.PRODUCTION_METHOD_FAVORED_MILITARY_GOODS_FACTOR` | `0.5` | `1.5` |
| `NAI.PRODUCTION_METHOD_INCREASE_OUTPUT_PENALTY_FACTOR` | `0.01` | `0.95` |
| `NAI.PRODUCTION_METHOD_REDUCE_OUTPUT_PENALTY_FACTOR` | `10` | `5` |
| `NAI.PRODUCTION_METHOD_STICKINESS_DOWNGRADE` | `0.75` | `0.95` |
| `NAI.PRODUCTION_METHOD_STICKINESS_UPGRADE` | `0.95` | `1.0` |
| `NAI.PRODUCTION_METHOD_UNDESIRABLE_GOODS_PRICE_FACTOR_UNTRADEABLE` | `-0.25` | `-0.75` |
| `NAI.REFORM_GOVERNMENT_PRO_IG_CLOUT_FACTOR` | `1.0` | `2.5` |
| `NAI.REFORM_GOVERNMENT_STICKINESS` | `1.25` | `1.0` |
| `NAI.SHIP_DESIGN_UTILITY_MOD_MIN_SCORE` | `2.0` | `1.125` |
| `NAI.SUPPLY_SHIP_STRAIN_MAX_RATIO` | `2.0` | `1.1` |

## Вне common/

| папка | файлов | поверх файла ваниль |
| --- | --- | --- |
| `events/` | 1 | 1 |

- **events/ поверх ваниль**: `events/iberia_events/ip4_election_rigging.txt`

**События**: 2 id; с id ваниль — 2 (`caciquismo.1`, `caciquismo.2`) — игра оставляет одно, не по порядку модов.

**Локализация** (английская и русская): ключей 0; в `replace/` — 0; есть у ваниль вне `replace/` — 0 (не действуют: побеждает первый файл).
