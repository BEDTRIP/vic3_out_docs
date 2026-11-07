---
type: concept
description: "Метод производства «Ротативный двигатель (pm_rotary_valve_engine_building_arms_industry)» — TGR 1.13, `pm_rotary_valve_engine_building_arms_industry`"
project: vic3
source: tgr
aliases: ["Ротативный двигатель (pm_rotary_valve_engine_building_arms_industry)", "Rotary Valve Engine", "pm_rotary_valve_engine_building_arms_industry"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rotary_valve_engine_building_arms_industry
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
replaces: "[[vanilla/Методы производства/Ротативный двигатель (pm_rotary_valve_engine_building_arms_industry)]]"
---
# Ротативный двигатель (pm_rotary_valve_engine_building_arms_industry)

Метод производства · `pm_rotary_valve_engine_building_arms_industry` · `common/production_methods/TGR_TRADE_automation.txt:593`

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
    - `goods_input_coal_add` = `5` → [[tgr/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
