---
type: concept
description: "Метод производства «Конвейерное производство (pm_assembly_lines_building_tooling_workshop)» — ваниль 1.15, `pm_assembly_lines_building_tooling_workshop`"
project: vic3
audience: agent
source: vanilla
aliases: ["Конвейерное производство (pm_assembly_lines_building_tooling_workshop)", "Assembly Lines", "pm_assembly_lines_building_tooling_workshop"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_assembly_lines_building_tooling_workshop
paths: [.vanillaVIC3/common/production_methods/01_industry.txt]
---
# Конвейерное производство (pm_assembly_lines_building_tooling_workshop)

Метод производства · `pm_assembly_lines_building_tooling_workshop` · `common/production_methods/01_industry.txt:1076`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/assembly_lines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Конвейеры|Конвейеры]]
- **disallowing_laws**: [[vanilla/Законы/Запрет промышленности|Запрет промышленности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `9` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_input_copper_add` = `1` → [[vanilla/Товары/Медь|Медь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Автоматизация (pmg_automation_building_tooling_workshop)|Автоматизация (pmg_automation_building_tooling_workshop)]]
