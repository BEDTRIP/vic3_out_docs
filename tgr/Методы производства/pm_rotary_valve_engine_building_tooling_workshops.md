---
type: concept
description: "Метод производства «pm_rotary_valve_engine_building_tooling_workshops» — TGR 1.13, `pm_rotary_valve_engine_building_tooling_workshops`"
project: vic3
source: tgr
aliases: ["pm_rotary_valve_engine_building_tooling_workshops"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rotary_valve_engine_building_tooling_workshops
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
---
# pm_rotary_valve_engine_building_tooling_workshops

Метод производства · `pm_rotary_valve_engine_building_tooling_workshops` · `common/production_methods/TGR_TRADE_automation.txt:308`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rotary_valve_engine.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Ротативный двигатель|Ротативный двигатель]]
- **disallowing_laws**: [[tgr/Законы/Запрет промышленности|Запрет промышленности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `5` → [[tgr/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
