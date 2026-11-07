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
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `3` → [[tgr/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `3` → [[tgr/Товары/ГСМ|ГСМ]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `2` → [[tgr/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[tgr/Товары/Электричество|Электричество]]
