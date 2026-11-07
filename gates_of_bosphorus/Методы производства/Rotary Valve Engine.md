---
type: concept
description: "Метод производства «Rotary Valve Engine» — Gates of Bosphorus 1.13, `gbbf_rotary_valve_engine_building_esparto`"
project: vic3
source: gates_of_bosphorus
aliases: ["Rotary Valve Engine", "gbbf_rotary_valve_engine_building_esparto"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_rotary_valve_engine_building_esparto
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_04_plantation_methods.txt]
---
# Rotary Valve Engine

Метод производства · `gbbf_rotary_valve_engine_building_esparto` · `common/production_methods/gbbf_04_plantation_methods.txt:132`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rotary_valve_engine.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Ротативный двигатель|Ротативный двигатель]]
- **disallowing_laws**: [[vanilla/Законы/Запрет промышленности|Запрет промышленности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `10` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Automation|Automation]]
