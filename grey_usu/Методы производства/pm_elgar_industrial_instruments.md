---
type: concept
description: "Метод производства «pm_elgar_industrial_instruments» — grey USU 1.13, `pm_elgar_industrial_instruments`"
project: vic3
source: grey_usu
aliases: ["pm_elgar_industrial_instruments"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_elgar_industrial_instruments
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/mMoG_USU_MR_elgar_pms.txt]
---
# pm_elgar_industrial_instruments

Метод производства · `pm_elgar_industrial_instruments` · `common/production_methods/mMoG_USU_MR_elgar_pms.txt:110`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/elgar_industrial_instruments_pm.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Механические инструменты|Механические инструменты]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_wood_add` = `10` → [[grey_usu/Товары/Древесина|Древесина]]
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_elgar_instruments_add` = `35`
  - **level_scaled**:
    - `building_employment_laborers_add` = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `3`
