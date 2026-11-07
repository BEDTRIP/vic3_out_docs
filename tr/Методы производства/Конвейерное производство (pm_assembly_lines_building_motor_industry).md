---
type: concept
description: "Метод производства «Конвейерное производство (pm_assembly_lines_building_motor_industry)» — T&R 1.13, `pm_assembly_lines_building_motor_industry`"
project: vic3
source: tr
aliases: ["Конвейерное производство (pm_assembly_lines_building_motor_industry)", "Assembly Lines", "pm_assembly_lines_building_motor_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_assembly_lines_building_motor_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_vanilla_production_methods.txt]
replaces: "[[vanilla/Методы производства/Конвейерное производство (pm_assembly_lines_building_motor_industry)]]"
---
# Конвейерное производство (pm_assembly_lines_building_motor_industry)

Метод производства · `pm_assembly_lines_building_motor_industry` · `common/production_methods/ztr_vanilla_production_methods.txt:1972` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **state_modifiers**: изменено
- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/assembly_lines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[tr/Технологии/Конвейеры|Конвейеры]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_lubricant_add` = `3` → [[tr/Товары/Lubricants|Lubricants]]
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `-500` → [[vanilla/Население/Типы/Механики|Механики]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]
