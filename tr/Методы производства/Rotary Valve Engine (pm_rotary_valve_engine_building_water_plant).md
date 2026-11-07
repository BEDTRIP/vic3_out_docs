---
type: concept
description: "Метод производства «Rotary Valve Engine (pm_rotary_valve_engine_building_water_plant)» — T&R 1.13, `pm_rotary_valve_engine_building_water_plant`"
project: vic3
audience: agent
source: tr
aliases: ["Rotary Valve Engine (pm_rotary_valve_engine_building_water_plant)", "Rotary Valve Engine", "pm_rotary_valve_engine_building_water_plant"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rotary_valve_engine_building_water_plant
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Rotary Valve Engine (pm_rotary_valve_engine_building_water_plant)

Метод производства · `pm_rotary_valve_engine_building_water_plant` · `common/production_methods/ztr_new_production_methods.txt:6556`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rotary_valve_engine.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Ротативный двигатель|Ротативный двигатель]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_copper_add` = `12` → [[tr/Товары/Copper|Copper]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `6` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `6` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-900` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_water_plant)|Automation (pmg_automation_building_water_plant)]]
