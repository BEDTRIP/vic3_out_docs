---
type: concept
description: "Метод производства «pm_watertube_boiler_building_furniture_manufacturies» — TGR 1.13, `pm_watertube_boiler_building_furniture_manufacturies`"
project: vic3
source: tgr
aliases: ["pm_watertube_boiler_building_furniture_manufacturies"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_watertube_boiler_building_furniture_manufacturies
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
---
# pm_watertube_boiler_building_furniture_manufacturies

Метод производства · `pm_watertube_boiler_building_furniture_manufacturies` · `common/production_methods/TGR_TRADE_automation.txt:187`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/watertube_boiler.dds`
- **unlocking_technologies**: [[tgr/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **disallowing_laws**: [[tgr/Законы/Запрет промышленности|Запрет промышленности]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `3` → [[tgr/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `2` → [[tgr/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
