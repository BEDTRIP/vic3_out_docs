---
type: concept
description: "Метод производства «Конвейерное производство (pm_assembly_lines_building_furniture_manufactory)» — ваниль 1.13, `pm_assembly_lines_building_furniture_manufactory`"
project: vic3
source: vanilla
aliases: ["Конвейерное производство (pm_assembly_lines_building_furniture_manufactory)", "Assembly Lines", "pm_assembly_lines_building_furniture_manufactory"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_assembly_lines_building_furniture_manufactory
paths: [.vanillaVIC3/common/production_methods/01_industry.txt]
---
# Конвейерное производство (pm_assembly_lines_building_furniture_manufactory)

Метод производства · `pm_assembly_lines_building_furniture_manufactory` · `common/production_methods/01_industry.txt:688`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/assembly_lines.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Конвейеры|Конвейеры]]
- **disallowing_laws**: [[vanilla/Законы/Запрет промышленности|Запрет промышленности]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_oil_add` = `5` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Автоматизация (pmg_automation_building_furniture_manufactory)|Автоматизация (pmg_automation_building_furniture_manufactory)]]
