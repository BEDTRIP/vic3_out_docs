---
type: reference
description: "Что мод LLWA меняет в ванили 1.13: записи common/ по папкам, defines, файлы поверх ваниль, события, локализация"
project: vic3
audience: agent
source: llwa
tags: [LLWA, что-меняет]
generated: "v3 graph mods"
paths: [llwa/**]
---
# Что меняет в ванили — LLWA

Снимок `llwa`, сравнение с ваниль 1.13. Генерат `v3 graph mods`: руками не править. Правила слияния — навык `vic3-modding`, «load-and-override»: запись, которой нет у ваниль, мод **добавляет**; голое тело или `REPLACE:` ключа ваниль **заменяет** запись целиком; `INJECT:` **дополняет**; файл с путём файла ваниль — файл ваниль не читается, его записи, которых мод не повторил, **удалены**. Сравнение только с ваниль: запись другого мода (мод — аддон или патч) здесь — «нет у ваниль».

## Записи common/

| папка | добавляет | заменяет | дополняет | складывает | вставка в чужое | удаляет файлом | не действует |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `ai_strategies` | 0 | 9 | 1 | 0 | 0 | 0 | 0 |
| `building_groups` | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
| `buildings` | 7 | 0 | 1 | 0 | 0 | 0 | 0 |
| `company_types` | 4 | 0 | 0 | 0 | 0 | 0 | 0 |
| `game_rules` | 2 | 0 | 0 | 0 | 0 | 0 | 0 |
| `goods` | 2 | 0 | 0 | 0 | 0 | 0 | 0 |
| `modifier_type_definitions` | 11 | 1 | 0 | 0 | 0 | 0 | 0 |
| `on_actions` | 9 | 0 | 0 | 10 | 0 | 0 | 0 |
| `production_method_groups` | 11 | 0 | 0 | 0 | 0 | 0 | 0 |
| `production_methods` | 38 | 10 | 0 | 0 | 0 | 0 | 0 |
| `script_values` | 3 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_effects` | 15 | 0 | 0 | 0 | 0 | 0 | 0 |
| `scripted_triggers` | 11 | 0 | 0 | 0 | 0 | 0 | 0 |
| `static_modifiers` | 6 | 0 | 0 | 0 | 0 | 0 | 0 |

### ai_strategies

Файлы поверх ваниль: `common/ai_strategies/03_political_strategies.txt`.

- **заменяет** (9): `ai_strategy_conservative_agenda`, `ai_strategy_egalitarian_agenda`, `ai_strategy_great_reforms`, `ai_strategy_maintain_mandate_of_heaven`, `ai_strategy_meiji_restoration`, `ai_strategy_nationalist_agenda`, `ai_strategy_progressive_agenda`, `ai_strategy_reactionary_agenda`, `ai_strategy_tanzimat_reforms`
- **дополняет** (1): `ai_strategy_default`

### building_groups

- **добавляет** (1): [[llwa/Группы зданий/Logistics Hub|Logistics Hub]]

### buildings

- **добавляет** (7): [[llwa/Здания/Aerodrome|Aerodrome]], [[llwa/Здания/Logistics Hub|Logistics Hub]], [[llwa/Здания/Natural Waterway|Natural Waterway]], [[llwa/Здания/Roadway|Roadway]], [[llwa/Здания/Canal Waterway|Canal Waterway]], [[llwa/Здания/Financial Exchanges|Financial Exchanges]], [[llwa/Здания/Shipping Lines|Shipping Lines]]
- **дополняет** (1): [[llwa/Здания/Железные дороги|Железные дороги]]

### company_types

- **добавляет** (4): [[llwa/Виды компаний/Trans Oceanic Air Lines|Trans Oceanic Air Lines]], [[llwa/Виды компаний/Central Railway Corporation|Central Railway Corporation]], [[llwa/Виды компаний/Global Shipping Lines, Inc|Global Shipping Lines, Inc]], [[llwa/Виды компаний/Overland Transport Trust|Overland Transport Trust]]

### game_rules

- **добавляет** (2): `LLWA_gr_infra_mode`, `LLWA_gr_mapi_mode`

### goods

- **добавляет** (2): [[llwa/Товары/Local Connectivity|Local Connectivity]], [[llwa/Товары/Market Connectivity|Market Connectivity]]

### modifier_type_definitions

- **добавляет** (11): `goods_input_luxury_furniture_add`, `goods_input_services_add`, `goods_input_transportation_mult`, `goods_output_llwa_logi_conn_add`, `goods_output_llwa_logi_conn_mult`, `goods_output_llwa_market_conn_add`, `llwa_building_exchange_throughput_add`, `llwa_building_freight_depot_throughput_add`, `state_llwa_building_exchange_max_level_add`, `state_llwa_building_freight_depot_max_level_add`, `state_llwa_mt_dist_from_water_add`
- **заменяет** (1): `state_market_access_price_impact`

### on_actions

- **добавляет** (9): `LLWA_oa_MAPI_law_activated`, `LLWA_oa_MAPI_tech_researched`, `LLWA_oa_airway_pm_handler`, `LLWA_oa_building_handler`, `LLWA_oa_logihub_monthly`, `LLWA_oa_logihub_semi_yearly`, `LLWA_oa_monthly_country_pulse`, `LLWA_oa_state_logihub_handler`, `LLWA_oa_weekly_country_pulse`
- **ключ ваниль в папке, которая складывается (`on_actions` складываются, `effect` — последний загруженный)** (10): `on_acquired_technology`, `on_building_built`, `on_building_expanded`, `on_investment_decreased`, `on_investment_increased`, `on_law_activated`, `on_monthly_pulse`, `on_production_method_changed`, `on_start_expanding_building`, `on_yearly_pulse`

### production_method_groups

- **добавляет** (11): [[llwa/Группы методов/Основа (LLWA_pmg_air_base)|Основа (LLWA_pmg_air_base)]], [[llwa/Группы методов/Airline Focus|Airline Focus]], [[llwa/Группы методов/Основа (LLWA_pmg_exchange_base)|Основа (LLWA_pmg_exchange_base)]], [[llwa/Группы методов/Основа (LLWA_pmg_logihub_base)|Основа (LLWA_pmg_logihub_base)]], [[llwa/Группы методов/Information Distribution|Information Distribution]], [[llwa/Группы методов/Private Expansion|Private Expansion]], [[llwa/Группы методов/Основа (LLWA_pmg_road_base)|Основа (LLWA_pmg_road_base)]], [[llwa/Группы методов/Passenger Buses|Passenger Buses]], [[llwa/Группы методов/Основа (LLWA_pmg_shipping_base)|Основа (LLWA_pmg_shipping_base)]], [[llwa/Группы методов/Основа (LLWA_pmg_water_base)|Основа (LLWA_pmg_water_base)]], [[llwa/Группы методов/Passenger Vessels|Passenger Vessels]]

### production_methods

- **добавляет** (38): [[llwa/Методы производства/Air Mail|Air Mail]], [[llwa/Методы производства/Passenger Flights|Passenger Flights]], [[llwa/Методы производства/Аэропланы|Аэропланы]], [[llwa/Методы производства/Дирижабли|Дирижабли]], [[llwa/Методы производства/Clearing Houses|Clearing Houses]], [[llwa/Методы производства/Commodities Listings|Commodities Listings]], [[llwa/Методы производства/Economic Journals|Economic Journals]], [[llwa/Методы производства/Electric Buses|Electric Buses]], [[llwa/Методы производства/Electric Trucks|Electric Trucks]], [[llwa/Методы производства/Hand Carts|Hand Carts]], [[llwa/Методы производства/Wagons|Wagons]], [[llwa/Методы производства/Logistics Hub|Logistics Hub]], [[llwa/Методы производства/Logistics Corporations|Logistics Corporations]], [[llwa/Методы производства/Motorbuses|Motorbuses]], [[llwa/Методы производства/Diesel Ferries|Diesel Ferries]], [[llwa/Методы производства/Motor Vessels|Motor Vessels]], [[llwa/Методы производства/Приоритет на грузы (LLWA_pm_no_air_travel)|Приоритет на грузы (LLWA_pm_no_air_travel)]], [[llwa/Методы производства/Приоритет на грузы (LLWA_pm_no_buses)|Приоритет на грузы (LLWA_pm_no_buses)]], [[llwa/Методы производства/No Information Distribution|No Information Distribution]], [[llwa/Методы производства/Приоритет на грузы (LLWA_pm_no_ferries)|Приоритет на грузы (LLWA_pm_no_ferries)]], [[llwa/Методы производства/Government Expansion Only|Government Expansion Only]], [[llwa/Методы производства/Packet Boats|Packet Boats]], [[llwa/Методы производства/Petrol Trucks|Petrol Trucks]], [[llwa/Методы производства/Rickshaws|Rickshaws]], [[llwa/Методы производства/Riverboats|Riverboats]], [[llwa/Методы производства/Sail-steamships|Sail-steamships]], [[llwa/Методы производства/Sailing Barges|Sailing Barges]], [[llwa/Методы производства/Securities Trading|Securities Trading]], [[llwa/Методы производства/Spot Shipping|Spot Shipping]], [[llwa/Методы производства/Stagecoaches|Stagecoaches]], [[llwa/Методы производства/Steam Buses|Steam Buses]], [[llwa/Методы производства/Steamboats|Steamboats]], [[llwa/Методы производства/Steam Trucks|Steam Trucks]], [[llwa/Методы производства/Steamships|Steamships]], [[llwa/Методы производства/Telegraph Lines|Telegraph Lines]], [[llwa/Методы производства/Telephone Lines|Telephone Lines]], [[llwa/Методы производства/Transport Lines|Transport Lines]], [[llwa/Методы производства/Private Expansion Allowed|Private Expansion Allowed]]
- **заменяет** (10): [[llwa/Методы производства/Тепловозы|Тепловозы]], [[llwa/Методы производства/Состыкованные тепловозы|Состыкованные тепловозы]], [[llwa/Методы производства/Экспериментальные поезда|Экспериментальные поезда]], [[llwa/Методы производства/Электровозы|Электровозы]], [[llwa/Методы производства/Состыкованные электровозы|Состыкованные электровозы]], [[llwa/Методы производства/Приоритет на грузы (pm_no_passenger_trains)|Приоритет на грузы (pm_no_passenger_trains)]], [[llwa/Методы производства/Паровозы|Паровозы]], [[llwa/Методы производства/Состыкованные паровозы|Состыкованные паровозы]], [[llwa/Методы производства/Стальные пассажирские вагоны|Стальные пассажирские вагоны]], [[llwa/Методы производства/Деревянные пассажирские вагоны|Деревянные пассажирские вагоны]]

### script_values

- **добавляет** (3): `LLWA_BASE_MAPI`, `LLWA_INFRA_TRANSPORTATION_RATIO`, `LLWA_MAX_DIST_FROM_WATER_SOURCE`

### scripted_effects

- **добавляет** (15): `@LOGIHUB_CONN_COST`, `@LOGIHUB_CONN_OUTPUT_PER_TRANSPORTATION`, `@LOGIHUB_MINIMUM_WAGE`, `@LOGIHUB_MKT_CONN_WAGES_OUT_MAX`, `@LOGIHUB_MKT_CONN_WAGES_OUT_MIN`, `@LOGIHUB_PROFITABILITY_TARGET`, `@LOGIHUB_WORKFORCE_SIZE`, `@TRANSPORTATION_COST`, `LLWA_se_country_refresh_logihubs`, `LLWA_se_enqueue_infra_building_for_transportation`, `LLWA_se_manage_ai_country`, `LLWA_se_manage_private_expansion`, `LLWA_se_reset_blocked_private_expansions`, `LLWA_se_start_priv_construction`, `LLWA_se_state_refresh_logihubs`

### scripted_triggers

- **добавляет** (11): `LLWA_is_active_trigger`, `LLWA_st_MAPI_building_allowed`, `LLWA_st_air_private_expansion_is_standard`, `LLWA_st_can_have_canal`, `LLWA_st_has_water_access`, `LLWA_st_in_mountains`, `LLWA_st_is_private_expansion_standard`, `LLWA_st_on_river`, `LLWA_st_rail_private_expansion_is_standard`, `LLWA_st_road_private_expansion_is_standard`, `LLWA_st_water_private_expansion_is_standard`

### static_modifiers

- **добавляет** (6): `LLWA_declared_bankruptcy`, `LLWA_md_dist_from_water`, `LLWA_md_logihub_in_mult`, `LLWA_md_logihub_out_mult`, `LLWA_md_mapi_building_lvl`, `LLWA_md_mapi_mapi_lvl`

## Вне common/

| папка | файлов | поверх файла ваниль |
| --- | --- | --- |
| `events/` | 1 | 0 |
| `gui/` | 1 | 0 |
| `gfx/` | 57 | 1 |
| `localization/` | 11 | 0 |

- **gfx/ поверх ваниль**: `gfx/interface/icons/production_method_icons/experimental_trains.dds`

**События**: 4 id; с id ваниль — 0.

**Локализация** (английская и русская): ключей 235; в `replace/` — 0; есть у ваниль вне `replace/` — 0 (не действуют: побеждает первый файл).
