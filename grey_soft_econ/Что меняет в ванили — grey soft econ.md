---
type: reference
description: "Что мод grey soft econ меняет в ванили 1.13: записи common/ по папкам, defines, файлы поверх ваниль, события, локализация"
project: vic3
source: grey_soft_econ
tags: [grey_soft_econ, что-меняет]
generated: "v3 graph mods"
paths: [grey_add_alot_of_things/_grey_soft_econ/**]
---
# Что меняет в ванили — grey soft econ

Снимок `grey_add_alot_of_things/_grey_soft_econ`, сравнение с ваниль 1.13. Генерат `v3 graph mods`: руками не править. Правила слияния — навык `vic3-modding`, «load-and-override»: запись, которой нет у ваниль, мод **добавляет**; голое тело или `REPLACE:` ключа ваниль **заменяет** запись целиком; `INJECT:` **дополняет**; файл с путём файла ваниль — файл ваниль не читается, его записи, которых мод не повторил, **удалены**. Сравнение только с ваниль: запись другого мода (мод — аддон или патч) здесь — «нет у ваниль».

## Записи common/

| папка | добавляет | заменяет | дополняет | складывает | вставка в чужое | удаляет файлом | не действует |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `company_charter_types` | 0 | 1 | 0 | 0 | 0 | 0 | 0 |
| `on_actions` | 2 | 0 | 0 | 2 | 0 | 0 | 0 |
| `pop_types` | 0 | 1 | 0 | 0 | 0 | 0 | 0 |
| `production_methods` | 0 | 2 | 0 | 0 | 0 | 0 | 0 |
| `scripted_triggers` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `static_modifiers` | 1 | 3 | 0 | 0 | 0 | 0 | 0 |

### company_charter_types

- **заменяет** (1): `monopoly_charter`

### on_actions

- **добавляет** (2): `state_market_access_from_literacy_setup_action`, `state_market_access_from_literacy_update_action`
- **ключ ваниль в папке, которая складывается (`on_actions` складываются, `effect` — последний загруженный)** (2): `on_game_started`, `on_monthly_pulse_state`

### pop_types

- **заменяет** (1): [[grey_soft_econ/Население/Типы/Крестьяне|Крестьяне]]

### production_methods

- **заменяет** (2): [[grey_soft_econ/Методы производства/Международная торговля|Международная торговля]], [[grey_soft_econ/Методы производства/Влиятельный торговый центр|Влиятельный торговый центр]]

### scripted_triggers

- **добавляет** (1): `Grey_SEA_is_active`

### static_modifiers

- **добавляет** (1): `mog_market_access_from_literacy`
- **заменяет** (3): `administrative_overburden`, `government_owned_debt`, `state_region_devastation`

## defines

Сливаются по одному define, не блоком.

| define | ваниль | мод |
| --- | --- | --- |
| `NAI.TRADE_CENTER_MINIMUM_GDP_UNRECOGNIZED_MULT` | `2.0` | `1` |
| `NEconomy.AUTO_DOWNSIZE_BUILDING_MONTHS_TO_WAIT` | `6` | `2` |
| `NEconomy.BUILDING_CASH_RESERVES_MAX_DEPOSIT_PERCENT` | `0.50` | `0.90` |
| `NEconomy.BUILDING_FOREIGN_OWNERSHIP_WAGE_FACTOR` | `-0.25` | `-0.35` |
| `NEconomy.BUILDING_INITIAL_WAGE_WEEKS` | `2` | `1` |
| `NEconomy.BUILDING_LAYOFF_HIRING_COOLDOWN_WEEKS` | `4` | `2` |
| `NEconomy.BUILDING_LOWER_WAGES_TARGET_WEALTH_MULT` | `1.2` | `1.33` |
| `NEconomy.BUILDING_MAX_EMPLOYMENT_FRACTION_TO_CONSIDER_CASH_RESERVES` | `0.5` | `0.8` |
| `NEconomy.BUILDING_MAX_EMPLOYMENT_FRACTION_TO_RAISE_WAGES` | `0.5` | `0.85` |
| `NEconomy.BUILDING_MIN_EMPLOYMENT_FRACTION_TO_PAUSE_HIRES` | `0.1` | `0.2` |
| `NEconomy.BUILDING_PAUSE_HIRES_CASH_RESERVES_THRESHOLD` | `0.75` | `0.25` |
| `NEconomy.BUILDING_PREFER_LAYOFFS_TARGET_WEALTH_MULT` | `0.66` | `0.7` |
| `NEconomy.BUILDING_PROFIT_TARGET_TO_HIRE_EMPLOYEES` | `0.25` | `0.2` |
| `NEconomy.BUILDING_PROFIT_TARGET_TO_LOWER_WAGES` | `0.15` | `0.1999` |
| `NEconomy.BUILDING_PROFIT_TARGET_TO_RAISE_WAGES` | `0.25` | `0.2111` |
| `NEconomy.BUILDING_PROFIT_TARGET_TO_WITHDRAW_CASH` | `0.15` | `0.2` |
| `NEconomy.BUILDING_WAGES_MIN_RELEVANT_POP_SIZE` | `50` | `25` |
| `NEconomy.BUILDING_WEEKS_BETWEEN_PAY_CHANGES` | `0` | `6` |
| `NEconomy.BUILDING_WEEKS_BETWEEN_PAY_CHANGES_WHEN_UNPROFITABLE` | `0` | `4` |
| `NEconomy.BUY_SELL_DIFF_AT_MAX_FACTOR` | `2` | `3` |
| `NEconomy.COMPANY_ON_DISBAND_COOLDOWN_MONTHS` | `48` | `36` |
| `NEconomy.COMPANY_ON_ESTABLISH_COOLDOWN_MONTHS` | `60` | `48` |
| `NEconomy.COMPANY_PRODUCTIVITY_ABSOLUTE_HIGH_THRESHOLD` | `25` | `20` |
| `NEconomy.COMPANY_PRODUCTIVITY_RATIO_HIGH_THRESHOLD` | `1.25` | `1.1` |
| `NEconomy.COMPANY_PRODUCTIVITY_RATIO_LOW_THRESHOLD` | `0.75` | `0.66` |
| `NEconomy.COUNTRY_MIN_CREDIT_BASE` | `100000` | `10000` |
| `NEconomy.COUNTRY_MIN_CREDIT_SCALED` | `0.5` | `0.01` |
| `NEconomy.DEFAULT_MAX_HIRING_RATE` | `0.1` | `0.2` |
| `NEconomy.DEFAULT_MIN_HIRING_RATE` | `0.01` | `0.05` |
| `NEconomy.GOODS_SHORTAGE_PENALTY_MAX` | `0.5` | `0.7` |
| `NEconomy.GOODS_SHORTAGE_PENALTY_THRESHOLD` | `0.5` | `0.4` |
| `NEconomy.MAX_WAGE_STEP_CHANGE` | `0.1` | `0.05` |
| `NEconomy.MINIMUM_WAGE_RATE` | `10.0` | `2.0` |
| `NEconomy.MIN_CONSTRUCTION_EFFICIENCY` | `0.05` | `0.15` |
| `NEconomy.OWNERSHIP_BUILDING_CASH_RESERVES_MAX_DEPOSIT_PERCENT` | `0.25` | `0.45` |
| `NEconomy.OWNERSHIP_BUILDING_PROFIT_TARGET_TO_HIRE_EMPLOYEES` | `0.5` | `0.3` |
| `NEconomy.OWNERSHIP_BUILDING_PROFIT_TARGET_TO_LOWER_WAGES` | `0.3` | `0.2999` |
| `NEconomy.OWNERSHIP_BUILDING_PROFIT_TARGET_TO_WITHDRAW_CASH` | `0.3` | `0.2` |
| `NEconomy.PRICE_RANGE` | `0.75` | `0.9` |
| `NEconomy.SUBSISTENCE_BUILDING_PROFIT_TARGET_TO_WITHDRAW_CASH` | `0.5` | `0.3` |
| `NWar.DEVASTATION_INCREASE_RATE` | `0.1` | `0.05` |

## Вне common/

| папка | файлов | поверх файла ваниль |
| --- | --- | --- |
| `events/` | 1 | 0 |
| `localization/` | 1 | 0 |


**События**: 1 id; с id ваниль — 0.

**Локализация** (английская и русская): ключей 1; в `replace/` — 0; есть у ваниль вне `replace/` — 0 (не действуют: побеждает первый файл).
