---
type: concept
description: "Метод производства «Assembly Lines (pm_assembly_lines_building_consumer_electronics_industry)» — T&R 1.13, `pm_assembly_lines_building_consumer_electronics_industry`"
project: vic3
audience: agent
source: tr
aliases: ["Assembly Lines (pm_assembly_lines_building_consumer_electronics_industry)", "Assembly Lines", "pm_assembly_lines_building_consumer_electronics_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_assembly_lines_building_consumer_electronics_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Assembly Lines (pm_assembly_lines_building_consumer_electronics_industry)

Метод производства · `pm_assembly_lines_building_consumer_electronics_industry` · `common/production_methods/ztr_new_production_methods.txt:10421`

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
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_consumer_electronics_industry)|Automation (pmg_automation_building_consumer_electronics_industry)]]
