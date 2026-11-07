---
type: concept
description: "Метод производства «pm_air_freight» — grey USU 1.13, `pm_air_freight`"
project: vic3
source: grey_usu
aliases: ["pm_air_freight"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_air_freight
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/mMoG_USU_MR_civil_aviation_pms.txt]
---
# pm_air_freight

Метод производства · `pm_air_freight` · `common/production_methods/mMoG_USU_MR_civil_aviation_pms.txt:186`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/air_freight.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Конвейеры|Конвейеры]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_paper_add` = `4` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_wood_add` = `4` → [[grey_usu/Товары/Древесина|Древесина]]
    - `goods_input_usu_logistics_add` = `8` → [[grey_usu/Товары/Логистические услуги|Логистические услуги]]
    - `goods_output_services_add` = `30` → [[vanilla/Товары/Услуги|Услуги]]
    - `goods_output_transportation_add` = `10` → [[grey_usu/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `200` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_clerks_add` = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `2`
    - `state_pollution_generation_add` = `25`
