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
    - [[vanilla/движок/Модификаторы G#^m-goods-input-radios-add|goods_input_radios_add]] = `10` → [[vanilla/Товары/Радио|Радио]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-telephones-add|goods_input_telephones_add]] = `10` → [[vanilla/Товары/Телефоны|Телефоны]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `10` → [[grey_usu/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `10` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-aeroplanes-add|goods_input_aeroplanes_add]] = `20` → [[vanilla/Товары/Аэропланы|Аэропланы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `25` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_air_travel_add` = `58`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `750` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `900` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `100` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-add|state_migration_pull_add]] = `0.05`
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `-8`
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `25`
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-add|state_migration_pull_add]] = `2`
