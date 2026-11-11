---
type: concept
description: "Метод производства «pm_assembly_lines_building_tooling_workshops» — TGR 1.15, `pm_assembly_lines_building_tooling_workshops`"
project: vic3
audience: agent
source: tgr
aliases: ["pm_assembly_lines_building_tooling_workshops"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_assembly_lines_building_tooling_workshops
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
---
# pm_assembly_lines_building_tooling_workshops

Метод производства · `pm_assembly_lines_building_tooling_workshops` · `common/production_methods/TGR_TRADE_automation.txt:339`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/assembly_lines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Конвейеры|Конвейеры]]
- **disallowing_laws**: [[tgr/Законы/Запрет промышленности|Запрет промышленности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `4` → [[tgr/Товары/ГСМ|ГСМ]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `1` → [[tgr/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[tgr/Товары/Электричество|Электричество]]
