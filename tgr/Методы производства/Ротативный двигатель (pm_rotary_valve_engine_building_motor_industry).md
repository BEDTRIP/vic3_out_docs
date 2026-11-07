---
type: concept
description: "Метод производства «Ротативный двигатель (pm_rotary_valve_engine_building_motor_industry)» — TGR 1.13, `pm_rotary_valve_engine_building_motor_industry`"
project: vic3
source: tgr
aliases: ["Ротативный двигатель (pm_rotary_valve_engine_building_motor_industry)", "Rotary Valve Engine", "pm_rotary_valve_engine_building_motor_industry"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rotary_valve_engine_building_motor_industry
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
replaces: "[[vanilla/Методы производства/Ротативный двигатель (pm_rotary_valve_engine_building_motor_industry)]]"
---
# Ротативный двигатель (pm_rotary_valve_engine_building_motor_industry)

Метод производства · `pm_rotary_valve_engine_building_motor_industry` · `common/production_methods/TGR_TRADE_automation.txt:506`

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rotary_valve_engine.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Ротативный двигатель|Ротативный двигатель]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `3` → [[tgr/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `2` → [[tgr/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `-500` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_laborers_add` = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `-1000` → [[vanilla/Население/Типы/Механики|Механики]]
