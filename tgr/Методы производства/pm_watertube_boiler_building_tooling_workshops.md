---
type: concept
description: "Метод производства «pm_watertube_boiler_building_tooling_workshops» — TGR 1.13, `pm_watertube_boiler_building_tooling_workshops`"
project: vic3
source: tgr
aliases: ["pm_watertube_boiler_building_tooling_workshops"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_watertube_boiler_building_tooling_workshops
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
---
# pm_watertube_boiler_building_tooling_workshops

Метод производства · `pm_watertube_boiler_building_tooling_workshops` · `common/production_methods/TGR_TRADE_automation.txt:280`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/watertube_boiler.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[tgr/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **disallowing_laws**: [[tgr/Законы/Запрет промышленности|Запрет промышленности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `4` → [[tgr/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
