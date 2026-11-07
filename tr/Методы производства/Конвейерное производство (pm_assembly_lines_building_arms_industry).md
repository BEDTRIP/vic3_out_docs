---
type: concept
description: "Метод производства «Конвейерное производство (pm_assembly_lines_building_arms_industry)» — T&R 1.13, `pm_assembly_lines_building_arms_industry`"
project: vic3
audience: agent
source: tr
aliases: ["Конвейерное производство (pm_assembly_lines_building_arms_industry)", "Assembly Lines", "pm_assembly_lines_building_arms_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_assembly_lines_building_arms_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_vanilla_production_methods.txt]
replaces: "[[vanilla/Методы производства/Конвейерное производство (pm_assembly_lines_building_arms_industry)]]"
---
# Конвейерное производство (pm_assembly_lines_building_arms_industry)

Метод производства · `pm_assembly_lines_building_arms_industry` · `common/production_methods/ztr_vanilla_production_methods.txt:2128` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/assembly_lines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[tr/Технологии/Конвейеры|Конвейеры]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_lubricant_add` = `6` → [[tr/Товары/Lubricants|Lubricants]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]
