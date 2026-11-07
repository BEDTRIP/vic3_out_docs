---
type: concept
description: "Метод производства «Пассажи (pm_arcades)» — grey USU 1.13, `pm_arcades`"
project: vic3
source: grey_usu
aliases: ["Пассажи (pm_arcades)", "Arcades", "pm_arcades"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_arcades
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_urban_base_pms.txt]
replaces: "[[vanilla/Методы производства/Пассажи]]"
---
# Пассажи (pm_arcades)

Метод производства · `pm_arcades` · `common/production_methods/yMoG_USU_urban_base_pms.txt:166`

## Отличия от ваниль

- **replacement_if_valid**: добавлено
- **ai_value**: добавлено
- **country_modifiers**: добавлено
- **building_modifiers**: изменено
- **state_modifiers**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/arcades.dds`
- **replacement_if_valid**: [[grey_usu/Методы производства/Пассажи (usu_pm_hv_arcades)|Пассажи (usu_pm_hv_arcades)]]
- **ai_value**: `2000`
- **unlocking_technologies**: [[vanilla/Технологии/Лифты|Лифты]]
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_construction_add` = `1`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_glass_add` = `2` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_steel_add` = `2` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_fabric_add` = `1.5` → [[grey_usu/Товары/Ткань|Ткань]]
    - `goods_input_tools_add` = `2` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_hardwood_add` = `1` → [[vanilla/Товары/Твёрдая древесина|Твёрдая древесина]]
    - `goods_input_electricity_add` = `1` → [[grey_usu/Товары/Электричество|Электричество]]
    - `goods_input_usu_logistics_add` = `10` → [[grey_usu/Товары/Логистические услуги|Логистические услуги]]
    - `goods_output_services_add` = `60` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_clerks_add` = `1900` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_shopkeepers_add` = `1000` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_machinists_add` = `300` → [[vanilla/Население/Типы/Механики|Механики]]
  - **unscaled**:
    - `building_shopkeepers_shares_add` = `10`
- **state_modifiers**:
  - **level_scaled**:
    - `state_construction_mult` = `0.002`
    - `state_usu_building_public_green_max_level_add` = `0.1`
    - `state_migration_pull_add` = `0.1`
  - **unscaled**:
    - `state_usu_building_public_green_max_level_add` = `2`
    - `state_migration_pull_add` = `20`
  - **workforce_scaled**:
    - `state_construction_mult` = `-0.0011`
    - `building_food_industry_throughput_add` = `0.005` → [[vanilla/Здания/Пищевые производства|Пищевые производства]]
    - `building_textile_mill_throughput_add` = `0.005` → [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
    - `building_furniture_manufactory_throughput_add` = `0.005` → [[vanilla/Здания/Мебельные фабрики|Мебельные фабрики]]
    - `ppp_building_power_grid_throughput_add` = `0.01`
    - `usu_building_public_green_throughput_add` = `0.019`
- **required_input_goods**: [[grey_usu/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Блага|Блага]]
