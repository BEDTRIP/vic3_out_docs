---
type: concept
description: "Метод производства «Rotary Valve Engine (pm_rotary_valve_engine_building_commonalloys_plant)» — T&R 1.13, `pm_rotary_valve_engine_building_commonalloys_plant`"
project: vic3
source: tr
aliases: ["Rotary Valve Engine (pm_rotary_valve_engine_building_commonalloys_plant)", "Rotary Valve Engine", "pm_rotary_valve_engine_building_commonalloys_plant"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rotary_valve_engine_building_commonalloys_plant
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Rotary Valve Engine (pm_rotary_valve_engine_building_commonalloys_plant)

Метод производства · `pm_rotary_valve_engine_building_commonalloys_plant` · `common/production_methods/ztr_new_production_methods.txt:5970`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rotary_valve_engine.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Ротативный двигатель|Ротативный двигатель]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `10` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_commonalloys_plant)|Automation (pmg_automation_building_commonalloys_plant)]]
