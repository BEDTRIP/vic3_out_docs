---
type: concept
description: "Метод производства «Ротативный двигатель (pm_rotary_valve_engine_building_steel_mill)» — ваниль 1.13, `pm_rotary_valve_engine_building_steel_mill`"
project: vic3
audience: agent
source: vanilla
aliases: ["Ротативный двигатель (pm_rotary_valve_engine_building_steel_mill)", "Rotary Valve Engine", "pm_rotary_valve_engine_building_steel_mill"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rotary_valve_engine_building_steel_mill
paths: [.vanillaVIC3/common/production_methods/01_industry.txt]
---
# Ротативный двигатель (pm_rotary_valve_engine_building_steel_mill)

Метод производства · `pm_rotary_valve_engine_building_steel_mill` · `common/production_methods/01_industry.txt:1680`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rotary_valve_engine.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Ротативный двигатель|Ротативный двигатель]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `10` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Автоматизация (pmg_automation_building_steel_mill)|Автоматизация (pmg_automation_building_steel_mill)]]
