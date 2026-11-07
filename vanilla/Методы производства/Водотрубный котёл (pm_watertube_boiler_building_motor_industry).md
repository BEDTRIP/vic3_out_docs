---
type: concept
description: "Метод производства «Водотрубный котёл (pm_watertube_boiler_building_motor_industry)» — ваниль 1.13, `pm_watertube_boiler_building_motor_industry`"
project: vic3
source: vanilla
aliases: ["Водотрубный котёл (pm_watertube_boiler_building_motor_industry)", "Water-tube Boiler", "pm_watertube_boiler_building_motor_industry"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_watertube_boiler_building_motor_industry
paths: [.vanillaVIC3/common/production_methods/01_industry.txt]
---
# Водотрубный котёл (pm_watertube_boiler_building_motor_industry)

Метод производства · `pm_watertube_boiler_building_motor_industry` · `common/production_methods/01_industry.txt:1797`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/watertube_boiler.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `5` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-500` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Автоматизация (pmg_automation_building_motor_industry)|Автоматизация (pmg_automation_building_motor_industry)]]
