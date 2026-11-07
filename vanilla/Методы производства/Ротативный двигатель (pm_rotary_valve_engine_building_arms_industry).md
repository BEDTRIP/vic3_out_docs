---
type: concept
description: "Метод производства «Ротативный двигатель (pm_rotary_valve_engine_building_arms_industry)» — ваниль 1.13, `pm_rotary_valve_engine_building_arms_industry`"
project: vic3
source: vanilla
aliases: ["Ротативный двигатель (pm_rotary_valve_engine_building_arms_industry)", "Rotary Valve Engine", "pm_rotary_valve_engine_building_arms_industry"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rotary_valve_engine_building_arms_industry
paths: [.vanillaVIC3/common/production_methods/01_industry.txt]
---
# Ротативный двигатель (pm_rotary_valve_engine_building_arms_industry)

Метод производства · `pm_rotary_valve_engine_building_arms_industry` · `common/production_methods/01_industry.txt:2528`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rotary_valve_engine.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Ротативный двигатель|Ротативный двигатель]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_coal_add` = `15` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Автоматизация (pmg_automation_building_arms_industry)|Автоматизация (pmg_automation_building_arms_industry)]]
