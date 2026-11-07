---
type: concept
description: "Метод производства «pm_international_routes» — grey USU 1.13, `pm_international_routes`"
project: vic3
source: grey_usu
aliases: ["pm_international_routes"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_international_routes
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/mMoG_USU_MR_civil_aviation_pms.txt]
---
# pm_international_routes

Метод производства · `pm_international_routes` · `common/production_methods/mMoG_USU_MR_civil_aviation_pms.txt:109`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/air_travel_4.dds`
- **ai_value**: `100`
- **unlocking_technologies**: `elgar_mass_culture_tech`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_radios_add` = `10` → [[vanilla/Товары/Радио|Радио]]
    - `goods_input_telephones_add` = `10` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_electricity_add` = `10` → [[grey_usu/Товары/Электричество|Электричество]]
    - `goods_input_tools_add` = `10` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_aeroplanes_add` = `20` → [[vanilla/Товары/Аэропланы|Аэропланы]]
    - `goods_input_oil_add` = `25` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_air_travel_add` = `58`
  - **level_scaled**:
    - `building_employment_laborers_add` = `750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `750` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_clerks_add` = `900` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_engineers_add` = `100` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_migration_pull_add` = `0.05`
    - `state_infrastructure_add` = `-8`
    - `state_pollution_generation_add` = `25`
  - **unscaled**:
    - `state_migration_pull_add` = `2`
