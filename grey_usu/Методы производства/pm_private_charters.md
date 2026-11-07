---
type: concept
description: "Метод производства «pm_private_charters» — grey USU 1.13, `pm_private_charters`"
project: vic3
source: grey_usu
aliases: ["pm_private_charters"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_private_charters
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/mMoG_USU_MR_civil_aviation_pms.txt]
---
# pm_private_charters

Метод производства · `pm_private_charters` · `common/production_methods/mMoG_USU_MR_civil_aviation_pms.txt:5`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/air_travel_1.dds`
- **ai_value**: `50`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `2` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `2` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-aeroplanes-add|goods_input_aeroplanes_add]] = `2` → [[vanilla/Товары/Аэропланы|Аэропланы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `2` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_air_travel_add` = `8`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `250` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `-1`
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-add|state_migration_pull_add]] = `2`
