---
type: concept
description: "Метод производства «pm_elgar_electronic_instruments» — grey USU 1.13, `pm_elgar_electronic_instruments`"
project: vic3
source: grey_usu
aliases: ["pm_elgar_electronic_instruments"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_elgar_electronic_instruments
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/mMoG_USU_MR_elgar_pms.txt]
---
# pm_elgar_electronic_instruments

Метод производства · `pm_elgar_electronic_instruments` · `common/production_methods/mMoG_USU_MR_elgar_pms.txt:140`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/elgar_electronic_instruments_pm.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Электрические конденсаторы|Электрические конденсаторы]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `10` → [[grey_usu/Товары/Древесина|Древесина]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-lead-add|goods_input_lead_add]] = `2` → [[vanilla/Товары/Свинец|Свинец]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `4` → [[grey_usu/Товары/Электричество|Электричество]]
    - `goods_output_elgar_instruments_add` = `55`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1450` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `50` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `3`
