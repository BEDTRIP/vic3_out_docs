---
type: concept
description: "Метод производства «Водотрубный котёл (pm_watertube_boiler_building_tooling_workshop)» — ваниль 1.13, `pm_watertube_boiler_building_tooling_workshop`"
project: vic3
source: vanilla
aliases: ["Водотрубный котёл (pm_watertube_boiler_building_tooling_workshop)", "Water-tube Boiler", "pm_watertube_boiler_building_tooling_workshop"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_watertube_boiler_building_tooling_workshop
paths: [.vanillaVIC3/common/production_methods/01_industry.txt]
---
# Водотрубный котёл (pm_watertube_boiler_building_tooling_workshop)

Метод производства · `pm_watertube_boiler_building_tooling_workshop` · `common/production_methods/01_industry.txt:1012`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/watertube_boiler.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **disallowing_laws**: [[vanilla/Законы/Запрет промышленности|Запрет промышленности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `10` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Автоматизация (pmg_automation_building_tooling_workshop)|Автоматизация (pmg_automation_building_tooling_workshop)]]
