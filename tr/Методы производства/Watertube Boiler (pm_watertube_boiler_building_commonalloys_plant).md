---
type: concept
description: "Метод производства «Watertube Boiler (pm_watertube_boiler_building_commonalloys_plant)» — T&R 1.13, `pm_watertube_boiler_building_commonalloys_plant`"
project: vic3
source: tr
aliases: ["Watertube Boiler (pm_watertube_boiler_building_commonalloys_plant)", "Watertube Boiler", "pm_watertube_boiler_building_commonalloys_plant"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_watertube_boiler_building_commonalloys_plant
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Watertube Boiler (pm_watertube_boiler_building_commonalloys_plant)

Метод производства · `pm_watertube_boiler_building_commonalloys_plant` · `common/production_methods/ztr_new_production_methods.txt:5943`

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
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_commonalloys_plant)|Automation (pmg_automation_building_commonalloys_plant)]]
