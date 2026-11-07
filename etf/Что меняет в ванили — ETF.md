---
type: reference
description: "Что мод ETF меняет в ванили 1.13: записи common/ по папкам, defines, файлы поверх ваниль, события, локализация"
project: vic3
audience: agent
source: etf
tags: [ETF, что-меняет]
generated: "v3 graph mods"
paths: [_etf/**]
---
# Что меняет в ванили — ETF

Снимок `_etf`, сравнение с ваниль 1.13. Генерат `v3 graph mods`: руками не править. Правила слияния — навык `vic3-modding`, «load-and-override»: запись, которой нет у ваниль, мод **добавляет**; голое тело или `REPLACE:` ключа ваниль **заменяет** запись целиком; `INJECT:` **дополняет**; файл с путём файла ваниль — файл ваниль не читается, его записи, которых мод не повторил, **удалены**. Сравнение только с ваниль: запись другого мода (мод — аддон или патч) здесь — «нет у ваниль».

## Записи common/

| папка | добавляет | заменяет | дополняет | складывает | вставка в чужое | удаляет файлом | не действует |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `on_actions` | 3 | 0 | 0 | 7 | 0 | 0 | 0 |
| `scripted_effects` | 4 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_guis` | 23 | 0 | 0 | 0 | 0 | 0 | 0 |

### on_actions

- **добавляет** (3): `com_topbar_setup`, `on_com_released_country_topbar`, `on_com_revolution_copy_topbar`
- **ключ ваниль в папке, которая складывается (`on_actions` складываются, `effect` — последний загруженный)** (7): `on_country_released_as_company_subject`, `on_country_released_as_independent`, `on_country_released_as_overlord_subject`, `on_country_released_as_own_subject`, `on_game_started_after_lobby`, `on_monthly_pulse`, `on_revolution_start`

### scripted_effects

- **добавляет** (4): `add_com_topbar_element`, `com_topbar_calculate_subsistence_pops`, `com_topbar_new_country`, `fix_variable_error`

### scripted_guis

- **добавляет** (23): `com_topbar_clear_first_line`, `com_topbar_clear_second_line`, `com_topbar_element_agitators`, `com_topbar_element_army_size`, `com_topbar_element_bloc_cohesion`, `com_topbar_element_bloc_prestige`, `com_topbar_element_bloc_size`, `com_topbar_element_charters`, `com_topbar_element_companies`, `com_topbar_element_innovation`, `com_topbar_element_interests`, `com_topbar_element_legitimacy`, `com_topbar_element_market_balance`, `com_topbar_element_market_gdp`, `com_topbar_element_navy_size`, `com_topbar_element_prestige`, `com_topbar_element_subsistence_pops`, `com_topbar_element_trade_capacity`, `com_topbar_element_unemployed_pops`, `com_topbar_element_unrealized_taxes`, `com_topbar_toggle_always_show`, `com_topbar_toggle_element_first_line`, `com_topbar_toggle_element_second_line`

## Вне common/

| папка | файлов | поверх файла ваниль |
| --- | --- | --- |
| `events/` | 1 | 0 |
| `gui/` | 5 | 0 |
| `gfx/` | 1 | 0 |
| `localization/` | 33 | 0 |


**События**: 1 id; с id ваниль — 0.

**Локализация** (английская и русская): ключей 334; в `replace/` — 0; есть у ваниль вне `replace/` — 0 (не действуют: побеждает первый файл).
