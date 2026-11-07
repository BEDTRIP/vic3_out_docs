---
type: concept
description: "Метод производства «pm_assembly_lines_building_furniture_manufacturies» — TGR 1.13, `pm_assembly_lines_building_furniture_manufacturies`"
project: vic3
source: tgr
aliases: ["pm_assembly_lines_building_furniture_manufacturies"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_assembly_lines_building_furniture_manufacturies
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
---
# pm_assembly_lines_building_furniture_manufacturies

Метод производства · `pm_assembly_lines_building_furniture_manufacturies` · `common/production_methods/TGR_TRADE_automation.txt:247`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/assembly_lines.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Конвейеры|Конвейеры]]
- **disallowing_laws**: [[tgr/Законы/Запрет промышленности|Запрет промышленности]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `3` → [[tgr/Товары/Инструменты|Инструменты]]
    - `goods_input_oil_add` = `3` → [[tgr/Товары/ГСМ|ГСМ]]
    - `goods_input_electricity_add` = `2` → [[tgr/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[tgr/Товары/Электричество|Электричество]]
