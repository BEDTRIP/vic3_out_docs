---
type: concept
description: "Метод производства «Конвейерное производство (pm_assembly_lines_building_furniture_manufactory)» — T&R 1.13, `pm_assembly_lines_building_furniture_manufactory`"
project: vic3
audience: agent
source: tr
aliases: ["Конвейерное производство (pm_assembly_lines_building_furniture_manufactory)", "Assembly Lines", "pm_assembly_lines_building_furniture_manufactory"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_assembly_lines_building_furniture_manufactory
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_vanilla_production_methods.txt]
replaces: "[[vanilla/Методы производства/Конвейерное производство (pm_assembly_lines_building_furniture_manufactory)]]"
---
# Конвейерное производство (pm_assembly_lines_building_furniture_manufactory)

Метод производства · `pm_assembly_lines_building_furniture_manufactory` · `common/production_methods/ztr_vanilla_production_methods.txt:1939` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/assembly_lines.dds`
- **unlocking_technologies**: [[tr/Технологии/Конвейеры|Конвейеры]]
- **disallowing_laws**: [[tr/Законы/Запрет промышленности|Запрет промышленности]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_lubricant_add` = `3` → [[tr/Товары/Lubricants|Lubricants]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]
