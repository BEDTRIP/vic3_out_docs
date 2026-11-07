---
type: concept
description: "Метод производства «Конвейерное производство (pm_assembly_lines_building_tooling_workshop)» — T&R 1.13, `pm_assembly_lines_building_tooling_workshop`"
project: vic3
source: tr
aliases: ["Конвейерное производство (pm_assembly_lines_building_tooling_workshop)", "Assembly Lines", "pm_assembly_lines_building_tooling_workshop"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_assembly_lines_building_tooling_workshop
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_vanilla_production_methods.txt]
replaces: "[[vanilla/Методы производства/Конвейерное производство (pm_assembly_lines_building_tooling_workshop)]]"
---
# Конвейерное производство (pm_assembly_lines_building_tooling_workshop)

Метод производства · `pm_assembly_lines_building_tooling_workshop` · `common/production_methods/ztr_vanilla_production_methods.txt:2097` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **state_modifiers**: изменено
- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/assembly_lines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[tr/Технологии/Конвейеры|Конвейеры]]
- **disallowing_laws**: [[tr/Законы/Запрет промышленности|Запрет промышленности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_lubricant_add` = `6` → [[tr/Товары/Lubricants|Lubricants]]
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]
