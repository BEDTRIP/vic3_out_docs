---
type: concept
description: "Метод производства «pm_regional_routes» — grey USU 1.13, `pm_regional_routes`"
project: vic3
source: grey_usu
aliases: ["pm_regional_routes"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_regional_routes
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/mMoG_USU_MR_civil_aviation_pms.txt]
---
# pm_regional_routes

Метод производства · `pm_regional_routes` · `common/production_methods/mMoG_USU_MR_civil_aviation_pms.txt:36`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/air_travel_2.dds`
- **ai_value**: `50`
- **unlocking_technologies**: [[vanilla/Технологии/Телефон|Телефон]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_telephones_add` = `5` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_electricity_add` = `2` → [[grey_usu/Товары/Электричество|Электричество]]
    - `goods_input_aeroplanes_add` = `5` → [[vanilla/Товары/Аэропланы|Аэропланы]]
    - `goods_input_oil_add` = `5` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_air_travel_add` = `18`
  - **level_scaled**:
    - `building_employment_laborers_add` = `750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `750` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_clerks_add` = `500` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `-2`
    - `state_pollution_generation_add` = `25`
  - **unscaled**:
    - `state_migration_pull_add` = `2`
