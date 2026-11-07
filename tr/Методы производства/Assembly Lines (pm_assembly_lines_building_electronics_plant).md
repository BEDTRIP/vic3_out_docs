---
type: concept
description: "Метод производства «Assembly Lines (pm_assembly_lines_building_electronics_plant)» — T&R 1.13, `pm_assembly_lines_building_electronics_plant`"
project: vic3
source: tr
aliases: ["Assembly Lines (pm_assembly_lines_building_electronics_plant)", "Assembly Lines", "pm_assembly_lines_building_electronics_plant"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_assembly_lines_building_electronics_plant
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Assembly Lines (pm_assembly_lines_building_electronics_plant)

Метод производства · `pm_assembly_lines_building_electronics_plant` · `common/production_methods/ztr_new_production_methods.txt:729`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/assembly_lines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[tr/Технологии/Конвейеры|Конвейеры]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_lubricant_add` = `3` → [[tr/Товары/Lubricants|Lubricants]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_battery_plant)|Automation (pmg_automation_building_battery_plant)]], [[tr/Группы методов/Automation (pmg_automation_building_electronics_plant)|Automation (pmg_automation_building_electronics_plant)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Electronic Grade Wire|Electronic Grade Wire]], [[tr/Методы производства/Embedded Control Circuit|Embedded Control Circuit]]
