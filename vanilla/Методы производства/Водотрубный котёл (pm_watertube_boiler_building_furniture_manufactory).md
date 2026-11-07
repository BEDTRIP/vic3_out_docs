---
type: concept
description: "Метод производства «Водотрубный котёл (pm_watertube_boiler_building_furniture_manufactory)» — ваниль 1.13, `pm_watertube_boiler_building_furniture_manufactory`"
project: vic3
source: vanilla
aliases: ["Водотрубный котёл (pm_watertube_boiler_building_furniture_manufactory)", "Water-tube Boiler", "pm_watertube_boiler_building_furniture_manufactory"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_watertube_boiler_building_furniture_manufactory
paths: [.vanillaVIC3/common/production_methods/01_industry.txt]
---
# Водотрубный котёл (pm_watertube_boiler_building_furniture_manufactory)

Метод производства · `pm_watertube_boiler_building_furniture_manufactory` · `common/production_methods/01_industry.txt:628`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/watertube_boiler.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **disallowing_laws**: [[vanilla/Законы/Запрет промышленности|Запрет промышленности]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `5` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Автоматизация (pmg_automation_building_furniture_manufactory)|Автоматизация (pmg_automation_building_furniture_manufactory)]]
