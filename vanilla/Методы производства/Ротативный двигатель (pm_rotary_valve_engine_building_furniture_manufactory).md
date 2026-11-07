---
type: concept
description: "Метод производства «Ротативный двигатель (pm_rotary_valve_engine_building_furniture_manufactory)» — ваниль 1.13, `pm_rotary_valve_engine_building_furniture_manufactory`"
project: vic3
source: vanilla
aliases: ["Ротативный двигатель (pm_rotary_valve_engine_building_furniture_manufactory)", "Rotary Valve Engine", "pm_rotary_valve_engine_building_furniture_manufactory"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rotary_valve_engine_building_furniture_manufactory
paths: [.vanillaVIC3/common/production_methods/01_industry.txt]
---
# Ротативный двигатель (pm_rotary_valve_engine_building_furniture_manufactory)

Метод производства · `pm_rotary_valve_engine_building_furniture_manufactory` · `common/production_methods/01_industry.txt:658`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rotary_valve_engine.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Ротативный двигатель|Ротативный двигатель]]
- **disallowing_laws**: [[vanilla/Законы/Запрет промышленности|Запрет промышленности]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `10` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Автоматизация (pmg_automation_building_furniture_manufactory)|Автоматизация (pmg_automation_building_furniture_manufactory)]]
