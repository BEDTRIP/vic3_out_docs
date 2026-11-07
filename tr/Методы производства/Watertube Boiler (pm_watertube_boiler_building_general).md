---
type: concept
description: "Метод производства «Watertube Boiler (pm_watertube_boiler_building_general)» — T&R 1.13, `pm_watertube_boiler_building_general`"
project: vic3
source: tr
aliases: ["Watertube Boiler (pm_watertube_boiler_building_general)", "Watertube Boiler", "pm_watertube_boiler_building_general"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_watertube_boiler_building_general
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Watertube Boiler (pm_watertube_boiler_building_general)

Метод производства · `pm_watertube_boiler_building_general` · `common/production_methods/ztr_new_production_methods.txt:5`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/watertube_boiler.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `5` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-600` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_general)|Automation (pmg_automation_building_general)]]
