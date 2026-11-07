---
type: concept
description: "Метод производства «Пассажи (usu_pm_hv_arcades)» — grey USU 1.13, `usu_pm_hv_arcades`"
project: vic3
source: grey_usu
aliases: ["Пассажи (usu_pm_hv_arcades)", "Arcades", "usu_pm_hv_arcades"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: usu_pm_hv_arcades
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_urban_base_pms.txt]
---
# Пассажи (usu_pm_hv_arcades)

Метод производства · `usu_pm_hv_arcades` · `common/production_methods/yMoG_USU_urban_base_pms.txt:227`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/arcades.dds`
- **is_hidden_when_unavailable**: `yes`
- **ai_value**: `50000`
- **unlocking_production_methods**: [[grey_usu/Методы производства/Лампы накаливания|Лампы накаливания]]
- **unlocking_technologies**: [[vanilla/Технологии/Лифты|Лифты]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-construction-add|country_construction_add]] = `1`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-glass-add|goods_input_glass_add]] = `2` → [[vanilla/Товары/Стекло|Стекло]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `2` → [[vanilla/Товары/Сталь|Сталь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `1.5` → [[grey_usu/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `2` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-hardwood-add|goods_input_hardwood_add]] = `1` → [[vanilla/Товары/Твёрдая древесина|Твёрдая древесина]]
    - `goods_input_ppp_hv_power_add` = `0.3` → [[grey_usu/Товары/Высоковольтная мощность|Высоковольтная мощность]]
    - `goods_input_usu_logistics_add` = `10` → [[grey_usu/Товары/Логистические услуги|Логистические услуги]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-services-add|goods_output_services_add]] = `60` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `600` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `1900` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `1000` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `200` → [[vanilla/Население/Типы/Механики|Механики]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-shopkeepers-shares-add|building_shopkeepers_shares_add]] = `10`
- **state_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-construction-mult|state_construction_mult]] = `0.002`
    - `state_usu_building_public_green_max_level_add` = `0.1`
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-add|state_migration_pull_add]] = `0.1`
  - **unscaled**:
    - `state_usu_building_public_green_max_level_add` = `2`
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-add|state_migration_pull_add]] = `20`
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-construction-mult|state_construction_mult]] = `-0.0011`
    - [[vanilla/движок/Модификаторы B#^m-building-food-industry-throughput-add|building_food_industry_throughput_add]] = `0.005` → [[vanilla/Здания/Пищевые производства|Пищевые производства]]
    - [[vanilla/движок/Модификаторы B#^m-building-textile-mill-throughput-add|building_textile_mill_throughput_add]] = `0.005` → [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
    - [[vanilla/движок/Модификаторы B#^m-building-furniture-manufactory-throughput-add|building_furniture_manufactory_throughput_add]] = `0.005` → [[vanilla/Здания/Мебельные фабрики|Мебельные фабрики]]
    - `ppp_building_power_grid_throughput_add` = `0.01`
    - `usu_building_public_green_throughput_add` = `0.02`
- **required_input_goods**: [[grey_usu/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Блага|Блага]]
- **Методы производства** (replacement_if_valid): [[grey_usu/Методы производства/Пассажи (pm_arcades)|Пассажи (pm_arcades)]]
