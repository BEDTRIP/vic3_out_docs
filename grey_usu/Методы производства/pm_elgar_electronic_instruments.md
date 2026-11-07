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
    - `goods_input_wood_add` = `10` → [[grey_usu/Товары/Древесина|Древесина]]
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_lead_add` = `2` → [[vanilla/Товары/Свинец|Свинец]]
    - `goods_input_electricity_add` = `4` → [[grey_usu/Товары/Электричество|Электричество]]
    - `goods_output_elgar_instruments_add` = `55`
  - **level_scaled**:
    - `building_employment_laborers_add` = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1450` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `50` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `3`
