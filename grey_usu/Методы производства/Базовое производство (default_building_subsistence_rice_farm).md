---
type: concept
description: "Метод производства «Базовое производство (default_building_subsistence_rice_farm)» — grey USU 1.13, `default_building_subsistence_rice_farm`"
project: vic3
source: grey_usu
aliases: ["Базовое производство (default_building_subsistence_rice_farm)", "Базовое производство", "default_building_subsistence_rice_farm"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: default_building_subsistence_rice_farm
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_road_carts_subsistence.txt]
replaces: "[[vanilla/Методы производства/Базовое производство (default_building_subsistence_rice_farm)]]"
---
# Базовое производство (default_building_subsistence_rice_farm)

Метод производства · `default_building_subsistence_rice_farm` · `common/production_methods/yMoG_USU_road_carts_subsistence.txt:152`

## Отличия от ваниль

- **building_modifiers**: изменено
- **state_modifiers**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/subsistence_farming.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_grain_add` = `2` → [[vanilla/Товары/Зерно|Зерно]]
    - `goods_output_fabric_add` = `0.75` → [[grey_usu/Товары/Ткань|Ткань]]
    - `goods_output_wood_add` = `0.75` → [[grey_usu/Товары/Древесина|Древесина]]
    - `goods_output_services_add` = `0.4` → [[vanilla/Товары/Услуги|Услуги]]
    - `goods_output_transportation_add` = `0.5` → [[grey_usu/Товары/Перевозка|Перевозка]]
    - `goods_output_usu_logistics_add` = `0.1` → [[grey_usu/Товары/Логистические услуги|Логистические услуги]]
  - **level_scaled**:
    - `building_employment_peasants_add` = `10000` → [[vanilla/Население/Типы/Крестьяне|Крестьяне]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_from_population_max_add` = `-1`
  - **level_scaled**:
    - `state_infrastructure_from_population_max_add` = `1`
  - **unscaled**:
    - `state_birth_rate_mult` = `0.5`
