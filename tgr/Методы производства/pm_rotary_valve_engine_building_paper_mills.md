---
type: concept
description: "Метод производства «pm_rotary_valve_engine_building_paper_mills» — TGR 1.13, `pm_rotary_valve_engine_building_paper_mills`"
project: vic3
source: tgr
aliases: ["pm_rotary_valve_engine_building_paper_mills"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rotary_valve_engine_building_paper_mills
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
---
# pm_rotary_valve_engine_building_paper_mills

Метод производства · `pm_rotary_valve_engine_building_paper_mills` · `common/production_methods/TGR_TRADE_automation.txt:397`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rotary_valve_engine.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Ротативный двигатель|Ротативный двигатель]]
- **disallowing_laws**: [[tgr/Законы/Запрет промышленности|Запрет промышленности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `4` → [[tgr/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `1` → [[tgr/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
